# PenetrationTest vs Fuzzing
介紹查找漏洞的方式以及相關的工具。

## **查找漏洞的方式有?**
最常使用的方法是***模糊測試Fuzzing***以及***滲透測試Penetration Test***。
	
## **什麼是模糊測試(Fuzzing)?**
隨機發送錯誤的數據(包含錯誤格式，亂數輸入等等)，觀察系統或是程式的行為及回應是否與預期相符。

## **什麼是滲透測試(Penetration Test)?**
對系統或應用程式做真實的攻擊，試圖找出可利用的漏洞和弱點。

## **模糊測試的類型**
* 應用程序模糊測試：例如桌面應用程序、Urls、表單、RPC 請求
* 網路傳輸協定模糊測試：例如HTTP、FTP

```
Tip：模糊測試的類型不只這兩個呦。
```

## **模糊測試流程圖**
![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/result/1.png)

## **有哪些常用的工具?**
* 模糊測試工具
	* [Ffuf](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/tree/main/Fuzzing/Web/Ffuf)
	* [Dirb](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/tree/main/Fuzzing/Web/Dirb)
	* [Gobuster](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/tree/main/Fuzzing/Web/Gobuster)
	* [WFuzz](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/tree/main/Fuzzing/Web/WFuzz)
	* [Dirsearch](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/tree/main/Fuzzing/Web/Dirsearch)
	* [Boofuzz](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/tree/main/Fuzzing/Network%20protocol/Boofuzz)
* 滲透測試工具
	* Nmap
	* Metasploit
	* Burp Suite

```
Tip：工具不只這些呦。
```

## **References**
* https://www.linkedin.com/advice/0/how-do-you-use-fuzzing-penetration-testing
* https://www.golinuxcloud.com/fuzzing-tools-for-web-application-pentesting/
* https://www.golinuxcloud.com/fuzzing-tools-for-web-application-pentesting/
* https://allabouttesting.org/top-12-fuzzing-tools-for-hackers/
* https://github.com/bkapsec/fuzzing
* https://github.com/cpuu/awesome-fuzzing
* https://github.com/secfigo/Awesome-Fuzzing
