# Outlook アドイン導入手順（kintone連携）

1. このフォルダ内の `manifest.xml` を Outlook Web にサイドロード
   → https://aka.ms/olksideload にアクセスして manifest.xml をアップロード

2. Outlook Web で「新規メール作成」を開くと、右側に taskpane.html のUIが表示されます

3. 案件を選んで「📎 メールに紐づける」ボタンを押すと、メールヘッダーに `X-KINTONE-ANKEN-ID` が保存されます

GitHub Pages URL:
https://movef-mina.github.io/outlook-anken/taskpane.html
