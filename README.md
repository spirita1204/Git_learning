# Git_learning  
設定快捷縮寫  
```
$ git config --global alias.co checkout  
$ git config --global alias.l "log --oneline --graph"  
```  
查詢目錄下狀態
```
$ git status
```
建立內容為hello之welcome.html檔  
```
$ echo "hello" >welcome.html  
```
讓git開始追蹤(加入到index暫存區)  
```
$ git add welcome.html  
$ git add *.html  
$ git add --all  
```  
將暫存內容提交儲存("做了什麼"),只會處理暫存區的內容  
```
$ git commit -m "init"  
```
檢視紀錄  
```
$ git log  
$ git log --oneline --graph #輸出更為精簡
```
