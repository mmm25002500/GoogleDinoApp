# Google 小恐龍遊戲 GoogleDinoApp
這是一款使用Java寫的Android Game，這是人人知曉的Google小恐龍，移植到Android上，目前也正在維護中，也有在定時更新。<br>
目前功能:<br>
1.玩遊戲

[![Build Status](http://img.shields.io/travis/badges/badgerbadgerbadger.svg?style=flat-square)](https://travis-ci.org/badges/badgerbadgerbadger)

## 如何編譯 How to Compile
由於Android-Studio 或是其他IDE已將javac內含至此，所以只須執行就會自動編譯並執行。
### 編譯 Compile:

**Step 1.**``git clone https://github.com/mmm25002500/GoogleDinoApp``

**Step 2.** 打開Android-Studio

**Step 3.** 打開專案 Open Project

Step 4.Run

### 安裝 Install:

``adb install release.apk``

### 心得與建構思路:
這是我利用課餘時間，突發奇想將Google離線版Google小恐龍源碼給下載下來，使用「chrome://dino」可以進到小恐龍畫面內。<br><br>
我這次在遊戲根目錄內放置asset裡面就是遊戲的HTML、JavaScript、CSS源碼，然後在activity_main.xml中加入webview，由於這是HTML，所以使用Android內建的webView App框架就可以達成了，不需要自己另寫。在MainActivity.java中，我將URL網址設定成「file:///android_asset/index.html」，這麼一來，在打開APP時就會載入此HTML網頁。

## 關於我們 About Us

[Team Website](www.tershi.ml) <br>
[Team Facebook](https://www.facebook.com/shanling.team/) <br>
[XiaTerShi YouTube](https://www.youtube.com/channel/UCPdpFDFOp3sPbZhRkaQVaQA) <br>
[XiaTerShi FaceBook](https://www.facebook.com/Tershi25648) <br>
[Tershi MailServer](https://mail.tershi.ml) <br>
[Tershi Official WebSite](https://official.tershi.ml) <br>
[Tershi Gitbook](https://gitbook.tershi.ml) <br>
[Tershi Telegram](https://t.me/TershiXia) <br>
以上關於因為域名為免費域 因此隨時會網域更換！ <br>
Licence:© Tershi 2020 All right reversed 此程式除了「關於」頁面不可重製及發布之外，其餘頁面及功能可進行重製發布。
