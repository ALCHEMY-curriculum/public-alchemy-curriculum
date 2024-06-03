# html-css-js-curriculum

## 概要

<details>
  <summary>ダウンロードについて（Fork）</summary>

1. 「Fork」 を押す
   ![](https://github.com/ALCHEMY-curriculum/public-alchemy-curriculum/assets/55649762/902cb346-45b8-4d24-b21b-c57e7709a8ba)
2. 「Create Fork」を押す

3. Fork した自分のリポジトリを clone する

</details>

## 課題を実施する前に下記内容を確認する

- [ディレクトリが作成されているか](https://www.notion.so/alchemy-inc/d39c7c0e8dce4ddfa049a1ea99e1e29f)
- 各課題の Issue が作成されているか（リポジトリの Issue タブを確認）
- Milestone が作成されているか（リポジトリの Issue タブから Milestone を押下）

## 課題について

コンテンツは 3 プログラム構成で実施していきます。

- `HTML-CSS`：全ての基礎となるマークアップを身につけるプログラムです。

- `JavaScript`：現代では必須となった JavaScript を現場ライクな形で学び、動的な処理や外部機能を利用し実装力をつけるプログラムです。

詳細はこちら [エンジニア育成プログラム・ファストス](https://www.notion.so/1f5483e3a0f249629a2f5ece97e2e4d1)

## 開発

課題の進め方は[github flow](https://atmarkit.itmedia.co.jp/ait/articles/1708/01/news015.html)で進めてください。

<details>
  <summary>課題の進め方</summary>
  こちらの総合課題を例にして説明します。
  https://www.notion.so/alchemy-inc/586e3d4481e44b339ce2c2c83591f9d0

1. 指定されたブランチ名(`html-general`)を確認し、ローカル環境でそのブランチを作成し、今のブランチからそのブランチに移動します。
   `git switch -c html-general`とターミナルで打ち込むことでブランチを作成し、`html-general`ブランチに移動もできます.

2. 指定されたファイル(`html_learning/general.html`)を修正します。

3. 修正したファイルをステージングに追加します。
   `git add html_learning/general.html` とターミナルに打ち込み`Enter`を押します。

4. ステージングされたファイルをコミットします。
   `git commit -v` とターミナルに打ち込み`Enter`を押します。
   ※`-v`オプションをつけることで自分が修正した差分の確認もすることができます。

5. コミットメッセージを打ち込みます。
   コミットメッセージは以下のリンクを参考にしてください。
   https://qiita.com/konatsu_p/items/dfe199ebe3a7d2010b3e

今回の例では`feat:HTML総合課題の実装`としておきます。

6. リモートリポジトリに変更をプッシュします。
   `git push origin html-general`とターミナルに打ち込み`Enter`を押します。

7. リモートリポジトリで PR(プルリクエスト)を作成します。

- hoge ボタンを押します。
- ブランチが`html-general`ブランチから`main`に向いていることを確認します
- PR の内容を記述します。
  ※コミットメッセージは実務を想定して他者から見てもらうことを想定して書くと勉強になります。
  参考:https://dev.classmethod.jp/articles/pull-request-template/

- hoge ボタンを押します。

</details>

- master ブランチから新規ブランチを切る
- 新規ブランチで実装を進める
- git で適宜コミット
- github に push
- github 上で PR を作って、レビュー実施
  - PR の書き方は[こちら](https://hydrakecat.hatenablog.jp/entry/2018/06/30/%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC%E3%81%97%E3%81%A6%E3%82%82%E3%82%89%E3%81%84%E3%82%84%E3%81%99%E3%81%84PR%E3%81%AE%E6%9B%B8%E3%81%8D%E6%96%B9)を参考に
- **研修生**がマージ
- マージ後に、対応する課題の issue を**研修生**がクローズする
