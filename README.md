# Slack勤怠通知ボタン

Slackへ勤怠開始・休憩・勤怠終了の通知する際に
複数ワークスペース・複数チャンネルに投稿するスクリプト

わりと自分に最低限な機能しか無い

![preview](images/preview.png | width=300)

![results](images/results.png | width=300)


## Installation

- Clone or Download this repository.
- Copy `config.js.dist` to `config.js`.
- Change parameters in `config.js` as described in the comments.
  - *Highly Recommend* : First, test on your personal test channel. 

Details

- Get `Bot API Token` from Slack.
  - Open https://slack.com/apps/A0F7YS25R-bots
  - push "Add to Slack" button
  - copy `API Token`

- Get thread_ts from message.
  - ![スレッドにコメントを行い、そのスレッドコメントの](images/thread_ts_1.png | width=100)
  - ![URLを取得する](images/thread_ts_2.png | width=100)
  - Get `thread_ts` parameter value from query string.


## Usage

1. Open index.html. (Recommended to put in "Favorites" or create an alias on your desktop)
2. Press the button!
