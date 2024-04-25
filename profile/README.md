<p align="center">
    <img width="150" alt="Logo" src="https://raw.githubusercontent.com/japanese-law-analysis/.github/master/icon/icon.svg">
</p>

# japanese-law-analysis

日本の法律・判例などの法文書の解析を通して法文書の平易化を行うプロジェクトです。


# 配布データ

[data_setリポジトリ](https://github.com/japanese-law-analysis/data_set)でデータをCC0ライセンスのもとで配布しています。


# 作成しているソフトウェア

## ライブラリ

- [japanese_law_xml_schema](https://github.com/japanese-law-analysis/japanese_law_xml_schema)：法令標準XMLスキーマ(<https://elaws.e-gov.go.jp/file/XMLSchemaForJapaneseLaw_v3.xsd>)を取り扱うデータ構造と関数を提供する
- [jplaw_tools](https://github.com/japanese-law-analysis/jplaw_tools)：法律文書を解析する際に便利な関数を実装

## 解析ツール

- [analysis_yomikae](https://github.com/japanese-law-analysis/analysis_yomikae)：読替規定文を解析し、読み替えられる対象の語と読み替え後の文言を抽出する
- [analysis_ryakusyou](https://github.com/japanese-law-analysis/analysis_ryakusyou)：略称・定義規定の「～という。」・「～をいう。」文の解析し、文言を抽出する

## サポートツール

- [listup_law](https://github.com/japanese-law-analysis/listup_law)：[e-gov法令検索](https://elaws.e-gov.go.jp/)から一括ダウンロードしたXML法令データにどのような法令が含まれているのかをリストアップする
- [listup_precedent](https://github.com/japanese-law-analysis/listup_precedent)：[裁判所のホームページ](https://www.courts.go.jp/)で公開されている判例の情報を取得してリストアップする
- [parse_japanese_dependency](https://github.com/japanese-law-analysis/parse_japanese_dependency)：日本語の係り受け解析を行う
