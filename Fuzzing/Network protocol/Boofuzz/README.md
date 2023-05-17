# Boofuzz
使用 Boofuzz 對網路傳輸協定進行Fuzzing。

## **環境&工具**
* 一台kali Linux
* 一台有FTP服務的靶機
	
## **工具使用方法**
* step1：安裝工具
    > ```shell
    > pip install boofuzz
    > git clone https://github.com/jtpereyda/boofuzz.git
    > ```

## **FTP**
* step2：查看靶機的FTP服務有哪些功能
    > ```shell
    > nc -nv <IP>
    > help
    > ```
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Network%20protocol/Boofuzz/result/1.png)
* step3：至boofuzz\examples底下，將ftp_simple.py的IP做修改
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Network%20protocol/Boofuzz/result/2.png)
* step4：執行程式，這裡有將原是檔案複製一份出來因此檔名與上一部不同
    > ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Network%20protocol/Boofuzz/result/3.png)
* step5：UI視窗觀察
	* port number 為 26000
		> ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Network%20protocol/Boofuzz/result/4.png)
	* 若沒有限制多少筆資料，沒有出錯的話就會一直執行下去
		> ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Network%20protocol/Boofuzz/result/5.png)
* step6：test case data
	* 在目錄底下會產生”boofuzz-results”的資料夾存放結果
		> ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Network%20protocol/Boofuzz/result/6.png)
	* 可用SQLite開啟查看
		> ![image](https://github.com/WanShannn/PenetrationTest-vs-Fuzzing/blob/main/Fuzzing/Network%20protocol/Boofuzz/result/7.png)
	
## **References**
* https://github.com/jtpereyda/boofuzz
* https://boofuzz.readthedocs.io/en/stable/
* https://www.kitploit.com/2021/11/boofuzz-network-protocol-fuzzing-for.html




