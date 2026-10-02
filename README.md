# MONOQLO PTランキング

ページ: https://monoqlo-league.github.io/ranking/

MONOQLO麻雀部 PTランキングのページ本体(`index.html`)を置くリポジトリ。管理者だけが更新する。

- 集計元のデータ(月ごとの対局記録CSVと `ban.csv`)は、別リポジトリ **monoqlo-data** に置く。CSVの更新手順や集計のルールは、そちらの README を参照。
- ページは開くたびに monoqlo-data のファイルを読み込んで集計する。
- データ用リポジトリの名前を変えた場合は、`index.html` の `const DATA_REPO="monoqlo-data";` も同じ名前に書き換える。

## ファイル

- `index.html` … ランキングのページ本体
