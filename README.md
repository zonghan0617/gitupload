# HTML作業3 Github Pages 上線練習

---

## 作業練習檔案

請下載此Github Repository，到電腦內練習。

1. 於本頁面右手邊點選綠色按鈕【 Clone or Download 】
2. 點選 Download ZIP
3. 下載完成後解壓縮檔案練習

---

## 作業敘述

練習透過指令將這個網頁專案上架至你自己的Github Repository上，並且設定Github Pages將此靜態頁面架設。

---

## 提示

### 命令列工具
Window: git bash, cmd命令列工具 
macOS: terminal

### 使用命令列工具移動

#### 查詢現在所處位置有哪些檔案或資料夾
Windows在命令列工具輸入指令：`dir` 
macOS在命令列工具輸入指令：`ls` 

#### 進入資料夾
`cd 資料夾名稱`
EX：若要進入所處位置有的desktop資料夾
`cd desktop`

#### 退出目前所處資料夾
`cd ..`

### 電腦第一次安裝好git
若你是第一次在這台電腦安裝好git須執行以下指令設定，以避免後續執行上的困擾。
1. 開啟git的色彩設定
``` git config --global color.ui true ```

2. 讓git記住你的github帳號
``` git config --global user.name 你的github帳號 ```

3. 讓git記住你的github Email
``` git config --global user.email 你註冊github用的email ```

### 此專案第一次推上Github
1. 透過命令列工具移動並進入專案資料夾，分別輸入以下指令
2. ``` git init ```
3. ``` git add . ```
4. ``` git commit -m “你做了哪些改變” ```
5. ``` git remote add origin 你github repository的網址 ```
6. ``` git push origin master ```
7. 如果這台電腦是第一次push會要求輸入github帳號密碼(Mac輸入密碼時看不到文字)
8. 更新Repository頁面，如果有看到內容更新，即代表成功Push
9. 點選頁面上的【Settings】=> 點選在Github Pages Source下原本顯示為none的按鈕，設定為master branch。
![](https://i.imgur.com/5cZFDid.png)
10. 完成

### 專案已在github上我要更新程式碼

1. 透過命令列工具移動並進入專案資料夾，分別輸入以下指令
2. ``` git add . ```
3. ``` git commit -m “你做了哪些改變” ```
4. ``` git push origin master ```
5. 完成



