# Ffuf
使用 Ffuf 對 Web 應用程序進行Fuzzing。

## **環境&工具**
* 一台kali Linux
* 一台有DVWA服務的靶機

## **工具使用方法**
* step1：下載工具
	> ```shell
    > git clone https://github.com/ffuf/ffuf.git
    > ```
* step2：至工具的資料夾下
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Web/Ffuf/result/1.png)

## **典型的目錄發現**
* step3：執行程式
  * FUZZ是指定進行爆破的位置
    > ```shell
    > ffuf -c -w <字典檔> -u <目標位置>/FUZZ
    > ```
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Web/Ffuf/result/2.png)
* step4：結果
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Web/Ffuf/result/3.png)

## **References**
* https://www.golinuxcloud.com/fuzzing-tools-for-web-application-pentesting/
* https://codeantenna.com/a/0JgR5ayngO
* https://github.com/ffuf/ffuf
* https://zh.wikipedia.org/zh-tw/HTTP%E7%8A%B6%E6%80%81%E7%A0%81#5xx%E6%9C%8D%E5%8A%A1%E5%99%A8%E9%94%99%E8%AF%AF

	
