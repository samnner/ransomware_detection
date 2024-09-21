大方向：
1.	之前是用byte data，但後面使用csv檔的dataset，覺得這個dataset是更適合的，但預處理在透過ViT的部分就需要挑出需要的欄目，就不能整個data直接轉換成圖片，後面再丟進模型進行判斷。
2.	目前在選擇哪幾個是需要的欄目，能拿來分析是否為ransomware 。
3.	還有挑選需要用哪個model來更改，進行偵測。
4.	後續是不是需要加入DDos的dataset之類的。

其他：
1.	model需要改哪些東西。
2.	目前整理下來的方法是將數個欄目挑出來進行圖表分析，能觀察出感染及未感染的軟體，為較適合的拿來分析的欄目。
3.	目前code的部分是之前拿來進行byte data的處理，所以跟處理csv檔會對不上，需要挑選適合欄目才能進行後面圖表分析及train model。
4.  train1是原始train的前一百筆資料
4.	覺得有錯或不好的地方再討論。

References:
1. https://www.kaggle.com/competitions/microsoft-malware-prediction/discussion/84069
2. https://github.com/janasayan/Detecting-Ransomware-using-ML-and-Deep-Learning-Techniques/tree/main