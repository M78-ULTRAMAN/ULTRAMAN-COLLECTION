# CONVERGE MOTION iPhoneアプリ版

## 最短の公開方法（Netlify Drop）
1. このZIPを解凍します。
2. PCまたはiPhoneのSafariで `app.netlify.com/drop` を開きます。
3. 解凍した `CONVERGE_MOTION_PWA` フォルダをアップロードします。
4. 表示されたURLをiPhoneのSafariで開きます。
5. 共有ボタン → 「ホーム画面に追加」→「追加」。

## 保存について
- 所持状況・メモは同じURLのSafari内に自動保存されます。
- SafariのWebサイトデータ削除やURL変更で消える可能性があります。
- 「管理」→「バックアップを保存」でiCloud Driveへ定期保存してください。
- 別端末への移行は「バックアップから復元」を使います。

## ファイル構成
- index.html: アプリ本体
- manifest.webmanifest: ホーム画面アプリ設定
- sw.js: オフラインキャッシュ
- icon-*.png: アプリアイコン
