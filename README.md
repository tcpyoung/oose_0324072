# oose_0324072

資管3A 0324079 姚玟伶
---------------------
資管3B 0324028 游珮萱
---------------------
資管3A 0324504 邱冠霖
---------------------
資管3B 0324072 蔡豐仰(組長)
---------------------

## 摘要
　　「Medical Go」可以即時看到醫療箱的藥品是否過期、出門在外看到不足的，需要再買來補充。讓處理居家的臨時小問題時能夠更方便而有效，也透過演示步驟，來教導大家怎麼正確地處理傷口，並防止不必要的後遺症，並結合了搜尋附近診所評價系統，以及推薦和分類該去哪家急診掛號，讓使用者對於醫療更有不一樣的便捷。


![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/1.jpg "git圖示")
![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/2.jpg "git圖示")
![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/3.jpg "git圖示")
![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/4.jpg "git圖示")
![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/5.jpg "git圖示")
![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/6.jpg "git圖示")
![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/7.jpg "git圖示")

### Use case條件描述：

#### 使用者個案名稱：會員登入
行為者：使用者
目標：讓使用者可以使用該app
前提：使用者需要先註冊為會員
一系列事件：
正常程序：
1.使用者透過帳號密碼登入系統
2.使用者登入成功
例外狀況：帳號密碼錯誤，登入失敗
#### 使用者個案名稱：OCR
行為者：使用者
目標：讓使用者可以透過拍照的方式記錄藥品，省去打字的麻煩
前提：所拍藥品上的文字要夠清楚
結束狀態：取得資料，回到主畫面
一系列事件：
正常程序：
1.特徵值與已經建立好的文字模型進行比對
2.成功取得文字內容
例外狀況：比對錯誤無法取得文字內容
#### 使用者個案名稱：急救系統
行為者：使用者
目標：讓使用者在面臨狀況時有正確的處理步驟
前提：使用者要選到正確的部位還有症狀
結束狀態：查詢完所需的處理步驟，回到主畫面
一系列事件：
正常程序：1.使用者選取正確部位及症狀
2.取得正確處理步驟
例外狀況：資料庫中沒有所遇到的症狀
#### 使用者個案名稱：急救資料庫
行為者：開發者
目標：提供使用者急救的正確處理步驟
前提：開發者的急救知識要正確
一系列事件：
正常程序：1.開發者將正確的步驟放進資料庫
2.讓使用者可以取得正確資訊
例外狀況：誤把錯誤資訊放進資料庫
#### 使用者個案名稱：語音系統
行為者：使用者
目標：讓使用者在緊急時可以不用慢慢點受傷部位及症狀就可以查詢
前提：使用者說話不可模糊不清
結束狀態：成功取得急救步驟，並回到主畫面
一系列事件：
正常程序：1.使用者說出要查詢的症狀
2.成功取得正確資訊
例外狀況：使用者沒有將症狀說清楚，系統找不到資料
#### 使用者個案名稱：虛擬醫療箱
行為者：使用者
目標：讓使用者可以拉取物件，擁有客製化的醫療箱
前提：使用者要知道自己的醫療箱裡面有哪些物品
一系列事件：
正常程序：使用者擁有一個專屬的醫療箱
例外狀況：使用者想要拉取的物品有app沒提供的物件
#### 使用者個案名稱：提醒系統
行為者：使用者
目標：提醒使用者吃藥換藥時間及回診日期
前提：使用這必須先輸入提醒的時間
結束狀態：依照使用者設定的時間提醒，使用者接收到提醒後並關閉
一系列事件：
正常程序：
1.使用者設定一個提醒時間
2.時間到，系統對使用者發出提醒
3.使用者確實接收到訊息並關閉提醒
例外狀況：使用者將系統發出的提醒略過

![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/11.png "git圖示")

## 活動圖：

![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/8.png "git圖示")

## 強韌圖：

![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/9.jpg "git圖示")
![GITHUB](https://github.com/tcpyoung/oose_0324072/blob/master/10.jpg "git圖示")
