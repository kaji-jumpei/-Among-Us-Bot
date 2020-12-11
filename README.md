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

### コマンド
| AutoMuteUs Command   | AutoMuteUs Alias | Ehemong_Us Command   | Ehemong_Us Alias | Arguments   | Description                                                                                                     | Example                            |
| -------------- | ------- |  -------------- | ------- |----------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| `.au help`     | `.au h` | `.au help`     | `.au h` | None        | Print help info and command usage                                                                               |                                    |
| `.au new`      | `.au n` | | | None        | Start a new game in the current text channel. Optionally accepts the room code and region                       | `.au n CODE eu`                    |
| `.au link`     | `.au l` | | | @name color | Manually link a discord user to their in-game color                                                             | `.au l @Soup cyan`                 |
| `.au refresh`  | `.au r` | | | None        | Remake the bot's status message entirely, in case it ends up too far up in the chat.                            |                                    |
| `.au end`      | `.au e` | | | None        | End the game entirely, and stop tracking players. Unmutes all and resets state                                  |                                    |
| `.au unlink`   | `.au u` | | | @name       | Manually unlink a player                                                                                        | `.au u @player`                    |
| `.au settings` | `.au s` | | |             | View and change settings for the bot, such as the command prefix or mute behavior                               |                                    |
| `.au pause`    | `.au p` | | | None        | Pause the bot, and don't let it automute anyone until unpaused. **will not un-mute muted players, be careful!** |                                    |
| `.au privacy`  |         | | |             | View privacy and data collection information about the bot                                                      |                                    |
| `.au info`     | `.au i` | | | None        | View general info about the Bot                                                                                 |                                    |
