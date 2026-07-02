5日間のふりかえりアンケート

このフォルダをGitHub Pagesなどにアップロードして使います。

構成
index.html
assets/pets/*.png

使い方
1. publicフォルダの中身をリポジトリにアップロードします。
2. index.htmlを公開します。
3. Google Apps Scriptに送信する場合は、index.html内の CONFIG.GAS_ENDPOINT にURLを入れます。

ゲーム側から渡せる主なURLパラメータ
research_id
condition_id
character_id
language
day
partner_id または pet_id

お世話プロフィール用に渡せるURLパラメータ例
profile_watch
profile_response
profile_affection
profile_regularity
profile_observation
profile_interaction
profile_balance
profile_continuity

上記がない場合は、アンケート回答から仮のプロフィールを表示します。
