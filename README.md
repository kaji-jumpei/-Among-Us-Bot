# How to えへへっ鯖 Among Us Bot 
## 必須
ホスト1名
- Windows PC
  - Steam Among Us
  - [Among Us capture (Windowsソフト) ](https://github.com/denverquane/amonguscapture/releases/latest)
- どちらかのBotへのコマンド送信，管理
  - AutoMuteUs
    - 起動：簡単
    - 時間帯によって混雑して使えません
  - Ehemong_Us
    - 起動：面倒
    - ホストが起動していれば，いつでも使用可能
 
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
| `.au link`     | `.au l` |`.ehe link`     | `.ehe l`| @name color | 手動でユーザをBotとリンク.色：Red, Blue, Green, Pink, Orange, Yellow, Black, White, Purple, Brown, Cyan, Lime                                                           | `.au l @Soup cyan`                 |
| `.au refresh`  | `.au r` | `.ehe refresh`  | `.ehe r` | None        | テキストチャンネルでBotの表示を一番下に作り直す                   |
| `.au end`      | `.au e` | `.ehe end`      | `.ehe e` | None        | ゲーム終了．全ユーザのミュートを解除．                  |
| `.au unlink`   | `.au u` |`.ehe unlink`   | `.ehe u`| @name       | 手動でユーザとBotのリンクを解除．                                                                                        | `.au u @player`                    |
| `.au settings` | `.au s` |`.ehe settings` | `.ehe s`|             | 設定表示                  |
| `.au pause`    | `.au p` | `.ehe pause`    | `.ehe p`| None        | Botを一時停止，解除するまで誰もミュートしないよ．**既にミュートされたユーザは解除されないので注意！**                       |
| `.au privacy`  |         |`.ehe privacy` | |             | Botのプライバシーとデータ収集情報を表示                                                 |                                    |
| `.au info`     | `.au i` | `.ehe info`     | `.ehe i`| None        | Botに関する一般情報を表示                                                                                 |                                    |
