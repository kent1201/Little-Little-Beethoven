# 小小貝多芬 Little-Little-Beethoven
##發想緣起
  小小貝多芬是發想於南投埔里的一間小房間裡，由小鄭、小王、小黃共同發想實作。<br> 
  2015年的平安夜，小鄭、小王、小黃漫步於淡水時突然聽見一聲嘆氣，轉頭一看，原來是一個阿罵。 <br>
  阿罵嘆氣著說，孫子想要有一台鋼琴可是年末將近，阿罵沒有十八趴領，沒有足夠的金錢買鋼琴。 <br>
  小鄭、小王、小黃靈機一動想到了一個解決方法可以用低成本的材料，讓有音樂夢想的小朋友，可以學習音樂。 <br>
  小小貝多芬這個想法就誕生了！<br>
##所需材料<br>
    1. Raspberry pi *1 NT1100 
    2. Keyboard *1 NT150 
    3. Speaker *1 NT299
    4. Microphone *1 NT100
##使用軟體<br>
    1. Java 開發 
    2. Jline 
    3. TargetDataLine 
    4. sun.audio 
    5. PulseAudio 
    
##實作過程<br>
###功能： 
    1. 彈奏鋼琴功能 
    2. 錄音功能 
    3. 播放錄音功能 
###實作過程： 
    1. 設定raspberry pi環境 
    2. 設定外接裝置(鍵盤、喇叭、麥克風) 
    3. 功能細節調整 
###實作遇到的困難： 
    1. 按鍵的延遲(要把音訊檔存進ram以解決) 
    2. 外接裝置的code 
##實際產出： 
    - 按按鍵會有do,re,mi,fa,so的聲音 
    - 可以錄音,邊彈邊唱,播放錄音 
    
##教學文件：
###編譯程式碼
  ```sh
    javac -classpath .:jline-1.0.jar Close.java
  ```
###執行程式碼
  ```sh
    java -classpath .:jline-1.0.jar Close
  ```
