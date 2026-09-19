G検定 模擬試験 配置手順（GitHub Pages）
==========================================

このフォルダの6ファイルをそのままアップロードすれば動作します。
  index.html      本体
  manifest.json   アプリ情報（名前・アイコン）
  sw.js           オフライン動作用
  icon-180.png / icon-192.png / icon-512.png   アイコン

１．リポジトリを作る
  (1) https://github.com/new を開く
  (2) Repository name に「gkentei」など任意の名前を入力
  (3) Public を選択（GitHub Pagesの無料利用に必要）
  (4) 「Create repository」を押す

２．ファイルをアップロードする
  (1) 作成したリポジトリの画面で「uploading an existing file」のリンクを押す
      （すでにファイルがある場合は「Add file」→「Upload files」）
  (2) 上記6ファイルをまとめてドラッグ＆ドロップ
  (3) 下の「Commit changes」を押す

３．GitHub Pagesを有効にする
  (1) リポジトリの「Settings」タブ →左メニュー「Pages」
  (2) Build and deployment の Source で「Deploy from a branch」
  (3) Branch を「main」、フォルダを「/ (root)」にして「Save」
  (4) 1〜2分待つと同じ画面の上部にURLが表示される
      例： https://＜ユーザー名＞.github.io/gkentei/

４．配布
  上記URLを相手に送る。iPhoneではSafariで開き、共有ボタン→「ホーム画面に追加」で
  アプリのように使える。一度開けば以後はオフラインでも動作する。

５．更新するとき
  新しい index.html を受け取ったら、リポジトリで index.html を開き「…」→「Delete file」
  してから「Add file」→「Upload files」で新しいものを上げる（または上書きアップロード）。
  数分で全員の端末に反映される（アプリを開き直すと更新される）。

注意
  ・解答の進捗と誤答記録は各人の端末内に保存され、他の人とは共有されない。
  ・Safariとホーム画面のアプリはデータ領域が別なので、どちらか一方で使い続けること。
