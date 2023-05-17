# Dirsearch
使用 Dirsearch 對 Web 應用程序進行Fuzzing。

## **環境&工具**
* 一台kali Linux
* 一台有DVWA服務的靶機

## **工具使用方法**
* step1：安裝工具
	> ```shell
    > pip3 install dirsearch
    > ```

## **典型的目錄發現**
* step2：執行程式
    > ```shell
    > dirsearch -w <wordlist File> -u <URL>
    > ```
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Web/Dirsearch/result/1.png)
* step3：結果
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Web/Dirsearch/result/2.png)

## **References**
* https://www.golinuxcloud.com/fuzzing-tools-for-web-application-pentesting/

