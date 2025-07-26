## 上马自动签到 [![Run Auto Sign](https://github.com/angyyang/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/angyyang/shangma_auto_sign/actions/workflows/auto-sign.yaml)

## 上马2025年6月改版后原有代码无法自动签到了，重新分析新的签到接口后对代码做了改动，需要重新配置系统参数来签到，此代码可运行。具体使用方式待更新。 20250707

## 具体使用方式已更新。 20250708

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. //在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret
3. 在Repo的Setting页面，Secrets and Variables添加如下actions变量：登陆信息`SM_LOGIN`和上马用户id：`SM_USER_ID`
    登陆信息获取方式：登陆上马网： https://static.shang-ma.com/web/login/index.html 找到login的请求，把request payload整个复制出来放入SM_LOGIN
   ![image](https://github.com/user-attachments/assets/537f5ed0-f6ba-48fb-972a-2a3d19ded875)
   找到一个纯数字的请求，把这个数字复制出来放入SM_USER_ID
   ![image](https://github.com/user-attachments/assets/463f04e8-f6e6-419d-876a-de9211ee594d)




5. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Wed Jul 23 03:58:02 UTC 2025
- Auto Sign-in run successful on Thu Jul 24 01:18:33 UTC 2025
- Auto Sign-in run successful on Fri Jul 25 01:18:11 UTC 2025
- Auto Sign-in run successful on Sat Jul 26 01:16:28 UTC 2025
