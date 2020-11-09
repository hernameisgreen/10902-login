# 簡易會員系統製作

### 功能項目
1. 有登入畫面
2. 有註冊功能
3. 有忘記密碼找回功能
4. 登入後可依身份別到不同的會員中心畫面
    * 一般會員中心
    * VIP會員中心
5. 有登出功能
6. 有管理員帳號
7. 管理員登入後有管理中心畫面
8. 管理中心可以顯示會員列表
9. 管理中心可以修改會員資料
10. 管理中心可以刪除會員

### 頁面規劃
* 首頁(HTML+FORM)
* 註冊頁(HTML+FORM)
* 忘記密碼頁(HTML+FORM)
* 檢查帳號頁(PHP)
* 錯誤訊息頁(HTML+PHP)
* 成功訊息回傳頁(HTML+PHP)
* 一般會員中心頁(HTML+PHP)
* 白金會員中心頁(HTML+PHP)
* 管理中心頁(HTML+PHP)
* 編輯會員資料頁(HTML+PHP)    

### 資料庫規劃
##### 登入功能
- login
    * id(id)
    * 帳號(acc)
    * 密碼(password)
    * email(email)
    * 註冊時間(create_time)
##### 會員功能
- member
    * id(id)
    * 姓名(name)
    * 出生年月日(birthday)
    * 角色(含管理員)(role)
    * 居住地(addr)
    * 學歷(education)

