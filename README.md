# How to えへへっ鯖 Among Us Bot 
## 必須
ホスト1名
- Windows PC
  - Steam Among Us
  - [Among Us capture (Windowsソフト) ](https://github.com/denverquane/amonguscapture/releases/latest)
- どちらかのBotへのコマンド送信，管理
  - AutoMuteUs 
  - Ehemong_Us
 
## How to AutoMuteUs
1. Among Us capture起動(初回のみ)
2. `.au new` `.au n`のどちらかのコマンドを任意のテキストチャンネルへ送信
3. AutoMuteUsからDMでメッセージが送信される  
![AutoMuteUs DM](images/AutoMuteUs01.jpg "AutoMuteUs")

4. a.) **Click the following link to link your capture:** をクリック  
b.) メッセージ下部の **URL, Code** を手動で AmongUsCapture へ入力  
![AmongUsCapture link](images/linkus.jpg "LinkUs")  
![AmongUsCapture link](images/linkus2.jpg "LinkUs")  

5. テキストチャンネル内のAutoMuteUs Botの表示がグリーンになれば準備完了
![AmongUsCapture link](images/AutoMuteUsChanged.jpg "LinkUs")  
6. 各プレイヤーが Discord 上で，**自分の色と同じリアクションの絵文字**をクリック

## How to Ehemong_Us
1. [automuteus_windows(v2.4.2)](https://github.com/denverquane/automuteus/releases/tag/2.4.3) ダウンロード → 解凍後 automuteus_windows.exe 起動
2. automuteus_windows.exe同フォルダ内に**config.txt**ができており，中身の`DISCORD_BOT_TOKEN=`にトークンコードを貼り付
3. 改めて automuteus_windows.exe を起動
4. Among Us capture起動(初回のみ)
5. `.ehe new` `.ehe n`のどちらかのコマンドを任意のテキストチャンネルへ送信
6. Ehemong_UsからDMでメッセージが送信される  
7. [How to AutoMuteUs](#how-to-automuteus)の4.以降参照

## コマンド
| AutoMuteUs Command   | AutoMuteUs Alias | Ehemong_Us Command   | Ehemong_Us Alias | Arguments   | Description                                                                                                     | Example                            |
| -------------- | ------- |  -------------- | ------- |----------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| `.au help`     | `.au h` | `.ehe help`     | `.ehe h` | None        | ヘルプ表示                                                                               |                                    |
| `.au new`      | `.au n` |`.ehe new`      | `.ehe n`| None        | 現在のテキストチャンネルで新規ゲーム開始．オプションで部屋コード，地域を設定可能(なしで大丈夫)                      | `.au n CODE eu`                    |
| `.au link`     | `.au l` |`.ehe link`     | `.ehe l`| @name color | Manually link a discord user to their in-game color                                                             | `.au l @Soup cyan`                 |
| `.au refresh`  | `.au r` | `.ehe refresh`  | `.ehe r` | None        | Remake the bot's status message entirely, in case it ends up too far up in the chat.                            |                                    |
| `.au end`      | `.au e` | `.ehe end`      | `.ehe e` | None        | End the game entirely, and stop tracking players. Unmutes all and resets state                                  |                                    |
| `.au unlink`   | `.au u` |`.ehe unlink`   | `.ehe u`| @name       | Manually unlink a player                                                                                        | `.au u @player`                    |
| `.au settings` | `.au s` |`.ehe settings` | `.ehe s`|             | View and change settings for the bot, such as the command prefix or mute behavior                               |                                    |
| `.au pause`    | `.au p` | `.ehe pause`    | `.ehe p`| None        | Pause the bot, and don't let it automute anyone until unpaused. **will not un-mute muted players, be careful!** |                                    |
| `.au privacy`  |         |`.ehe privacy` | |             | View privacy and data collection information about the bot                                                      |                                    |
| `.au info`     | `.au i` | `.ehe info`     | `.ehe i`| None        | View general info about the Bot                                                                                 |                                    |
