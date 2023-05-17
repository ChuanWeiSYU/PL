## 111-2 師大科技系程式語言
授課教師：蔡芸琤</p>
姓名：許傳偉</p>
系級：科技碩三年級</p>
Email：<chuanwei.syu@gmail.com></p>
### 課程筆記區
### 作業連結區
#### 作業一&作業二：美國大學學費有多貴？[點我觀看](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_1/HW1_60971032H.ipynb)
使用一個包含3548筆數據，橫跨西元2013至2021年的美國公私立大專院校的數據集，回答一些簡單的問題，如「在美國讀大學公私立學費差異？」等等。
其中由於美元換算不便，所以有特別透過爬蟲爬取即時銀行數據，來實現金額轉換，最後透過視覺化圖表以地圖呈現區位差異。</p>
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_1/plot1.png)
可以看出，美國大學學費一年比一年貴，雖然有通貨膨脹的因素存在，但依然慘烈。</p>
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_1/plot2.png)
美國中西部地區是一個洗洋學歷的好去處……反正台灣的傻逼人資看到英文畢業證書就高潮。</p>
備註：該圖片可能要多Run幾次才會出得來。
#### 作業三：學士、碩士、博士和教授們作息時間有何差異：以PPT發文時間進行統計！[點我觀看](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_3/HW3_60971032H.ipynb)
透過爬取PTT的四個版的發文時間，各取最新的169篇(事實上可以更多，但受限於執行時間和電腦機能)文章的時間戳記，來分別以長條圖代表學士、碩士、博士與博士畢業後可能的生活習慣。</p>
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_3/%E5%AD%B8%E5%A3%AB%E6%AC%A1%E6%95%B8%E5%88%86%E9%85%8D.png)</p>
這張圖是大學生的發文時間，我們大概可以發現，發文划手機的時間集中在下午4:00左右，基本上這是個整天課上到累了的時間；另外，這爬蟲數據以網拍版(e-shopping)的發文時間作為基礎，主要原因是因為大學並沒有專版，事實上我有考慮過LoL和韓劇版(KoreaDrama)來分別抓取男女大學生，但後面想想太麻煩了所以作罷。</p>
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_3/%E7%A2%A9%E5%A3%AB%E6%AC%A1%E6%95%B8%E5%88%86%E9%85%8D.png)</p>
這張圖是碩士生的發文時間，相對之下，我們可以發現發文的時間規律得多，可以想像沒發文的時間在Meeting、寫論文和療傷。</p>
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_3/%E5%8D%9A%E5%A3%AB%E6%AC%A1%E6%95%B8%E5%88%86%E9%85%8D.png)</p>
這張圖是博士生的發文時間，基本上沒有什麼規律，一種解釋是該版的人不只有台灣土博，還有來自各地的台灣留學生，可能有「國際化」問題，但也可能是博士生的壓力已經大到作息徹底紊亂了，同時，在凌晨1:00至2:00發文的狀況也所在多有……</p>
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_3/%E5%8D%9A%E5%A3%AB%E5%BE%8C%E6%AC%A1%E6%95%B8%E5%88%86%E9%85%8D.png)</p>
無論是當了教授、或者當研究員等博士後研究，都可以發現教授們願意划手機發文的時間驚人的一致，中午吃飯(11:00至12:00)前後和睡覺前(約23:00)，實在令人羨慕。</p>
#### 作業四：博恩為什麼會紅？透過Youtube字幕檔案作為分析焦點，進行視覺化分析~[點我觀看](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_4/HW4_60971032H.ipynb)
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_4/%E8%BC%B8%E5%87%BA%E6%AA%94%E6%A1%88.png)</p>
以上分析是根據四篇「欸！」的專題，來跑出的文字雲，可見博恩在說話時，非常常使用你、我、他、我們、大家這類「人稱代名詞」或者「群體名詞」，同時口條中夾雜大量語助詞，如怎麼、什麼、這個。
其實可以了解，一個生動的知識性演講，絕非通篇都是足以讓人暈厥的資訊量，而是善用比喻、透過實例讓大家理解才是正確的做法！</p>
[點我看文章](https://www.linkedin.com/pulse/%E6%96%87%E5%AD%97%E6%8E%A2%E5%8B%98%E6%9C%80%E6%98%93%E8%B7%A8%E5%9F%9F%E7%9A%84%E8%B3%87%E6%96%99%E7%A7%91%E5%AD%B8%E6%96%B9%E6%B3%95-%E5%82%B3%E5%81%89-%E8%A8%B1)←這篇文章解釋了我對於文字探勘和文字雲的理解，老實說，我不寫是因為我不想讓我的個人平台有兩篇差不多的文章，不然好像我在水字數，沒拿到分數我其實可接受~
#### 作業五：博恩四個「欸！」系列的主題分析~[點我觀看](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_5/HW5_60971032H.ipynb)
![image](https://github.com/ChuanWeiSYU/PL/blob/main/HomeWork_5/HW5_output.png)</p>
我們發現，我們所用來分析的四個欸主題中「苗栗國、宗教團體與恐龍法官」所使用的用詞是相對較為接近的，其中尤其是宗教團體與苗栗國，幾乎可以說是完全重疊，唯一比較脫離群體的主題是：「死刑執行」，我想應該是因為討論到這個容易被炎上的主題，稿子必須「字斟句酌」一點，絕對不能用他平常的口條來脫稿演出，因此我相信這個分析結果是有道理的。
### 專題連結區
