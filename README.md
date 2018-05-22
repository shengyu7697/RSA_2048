# RSA 2048

### RSA 非對稱加密演算法介紹
[RSA加密法遇上量子電腦](https://case.ntu.edu.tw/blog/?p=29107)  

使用rsa_solver.py練習 (來源 [dfarrell07/rsa_walkthrough](https://github.com/dfarrell07/rsa_walkthrough))  

使用公鑰(n=143, e=7)加密體重「72」公斤  
加密：c = 72^7%143 = 19  
傳送訊息：19  

使用私鑰(n=143, d=103)解密19  
解密：m = 19^103%143 = 72  
得到原始訊息：72  
