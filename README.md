# <H/Fitness> 微健身小遊戲

<h2>附檔專題pdf需下載才能點開小遊戲Demo影片喔！</h2>

>專題發想：
>主要是因疫情所帶來的影響，大眾生活習慣在改變，盡量減少外出與群聚，遠距上班、遠距上課、居家運動、居家健身...等等的居家生活變得盛行，這也是我們製作「微健身小遊戲」平台的契機。

>目的： 
>希望藉由AI影像追蹤、影像辨識及肢體偵測技術的結合，製作出高互動的小遊戲，不需額外花錢購買遊戲控制器與健身器材，就能讓想運動又不便出門的人，隨時都能在家享受運動樂趣，達到他們的運動目標，並從中獲得>成就感。

功能介紹(目前僅開發2款小遊戲)：

遊戲1：I’m in
遊戲機制：一開始會請玩家站到指定的位置上，定位後才開始遊戲，這遊戲很簡單，只要玩家一直調整身體的位置，讓身體擠進畫面上的框框內，進入即可獲得分數。那我們是用OpenCV 搭配Mediapipe肢體偵測位置，將身體所有偵測到的點位選起來，與螢幕上的遊戲框來進行，大家可以看到畫面上藍框就是選取肢體的所有點位，而紅框為隨機產生的遊戲框。

遊戲2：Flash
遊戲機制：遊戲時間都為1分鐘，玩家必須一直閃躲天上掉下來的logo，閃過即可獲得分數、被擊中則會扣分，當你閃得越多，logo掉下來的速度也會越來越快。而實作的方法為比對每個時間點logo的ROI位置，與我們所有人體點位來判斷是否被擊中。

.
.
.
