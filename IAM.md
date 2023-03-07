# Introduction to AWS IAM

# 實施步驟

![image](https://user-images.githubusercontent.com/103306835/223349266-01800dfe-6905-4e13-9155-01c70223f89b.png)


# 實作


1.搜尋IAM服務(或是點選下方AWS Service IAM)

![image](https://user-images.githubusercontent.com/103306835/223350237-2eba2189-69b4-4511-9c6a-112a8caadeae.png)

2.新增S3-Support群組(Groups)

![image](https://user-images.githubusercontent.com/103306835/223350387-c398ed07-89b8-4352-b4cb-3bc769c71ae1.png)

3.將user-1添加到S3-Support組 (點選S3-Support)

![image](https://user-images.githubusercontent.com/103306835/223350614-8001cf42-4333-45c8-bbc0-c67493699882.png)

4.將user-1添加到S3-Support組 (點選Add Users to Group)

![image](https://user-images.githubusercontent.com/103306835/223350657-d18179c7-7c24-451b-8d90-7b333b42526b.png)

5.勾選user-1,按Add Users

![image](https://user-images.githubusercontent.com/103306835/223351114-58e19613-146c-4e8a-9638-c83c4322cc90.png)

6.在Users選項裡,就可以看到user-1 已加進到該群組

![image](https://user-images.githubusercontent.com/103306835/223351206-1f45d9d6-c20c-4a87-a72f-d930a24dfeb0.png)

7.登入並測試用戶權限點選左側欄Dashborad，複製網址

![image](https://user-images.githubusercontent.com/103306835/223351351-d6ef5fe8-6e31-421b-9625-9b39a9729ed8.png)

8.開啟無痕模式(Ctrl+shift+N)，貼上網址輸入帳號密碼

![image](https://user-images.githubusercontent.com/103306835/223351465-f6a97249-59f6-4bbc-a248-b47b051dec2e.png)

9.點選Service的S3

![image](https://user-images.githubusercontent.com/103306835/223351558-4b49519d-e302-4034-8540-89f5f1598700.png)

10.點選Service的EC2，點選Instances

![image](https://user-images.githubusercontent.com/103306835/223351616-3aeec711-1c6c-4156-b1b9-8bce09c587be.png)

11.現在以user-2 的身份登錄

點選user-1裡的Sign out!

![image](https://user-images.githubusercontent.com/103306835/223351821-b4ef0500-fad3-48e1-9e6f-feff76793f56.png)

12.再次將IAM的登入網址貼上，輸入帳號密碼

![image](https://user-images.githubusercontent.com/103306835/223351910-d1f1cd68-dcc0-41ab-8597-111731a7d091.png)

13.進入EC2，點選Instances

![image](https://user-images.githubusercontent.com/103306835/223352011-954257ff-0fba-4790-af1f-58f96b863e3d.png)

14.Instance State->Stop

![image](https://user-images.githubusercontent.com/103306835/223352157-fc1baad2-eef1-4e36-98b1-b265c497c992.png)

15.檢查 user-2 是否可以訪問 Amazon S3在搜尋列搜尋S3。

![image](https://user-images.githubusercontent.com/103306835/223352340-a84f5c01-fad4-4972-834d-b0082875af3e.png)

16.以user-3的身份登錄，您僱用該用戶作為您的Amazon EC2管理員。重複Sign out，貼上IAM網址，進行登入。

![image](https://user-images.githubusercontent.com/103306835/223352426-ba6d2a8b-5eb6-4af4-aa91-8860718e3f75.png)

17.進入EC2->Instances->Instance State->Stop

![image](https://user-images.githubusercontent.com/103306835/223352546-0b7bae06-45e9-4c78-804d-44da0c772d5d.png)

18.返回Lab點選End Lab

![image](https://user-images.githubusercontent.com/103306835/223352630-1f78ab9a-26d7-4844-b01a-d4fdd7d655a0.png)
