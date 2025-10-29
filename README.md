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
- Auto Sign-in run successful on Sun Jul 27 01:25:22 UTC 2025
- Auto Sign-in run successful on Mon Jul 28 01:23:43 UTC 2025
- Auto Sign-in run successful on Tue Jul 29 01:27:34 UTC 2025
- Auto Sign-in run successful on Wed Jul 30 01:20:09 UTC 2025
- Auto Sign-in run successful on Thu Jul 31 01:19:37 UTC 2025
- Auto Sign-in run successful on Fri Aug  1 01:27:23 UTC 2025
- Auto Sign-in run successful on Sat Aug  2 01:16:17 UTC 2025
- Auto Sign-in run successful on Sun Aug  3 01:26:28 UTC 2025
- Auto Sign-in run successful on Mon Aug  4 01:25:32 UTC 2025
- Auto Sign-in run successful on Tue Aug  5 01:21:40 UTC 2025
- Auto Sign-in run successful on Wed Aug  6 01:20:04 UTC 2025
- Auto Sign-in run successful on Thu Aug  7 01:20:44 UTC 2025
- Auto Sign-in run successful on Fri Aug  8 01:20:16 UTC 2025
- Auto Sign-in run successful on Sat Aug  9 01:14:03 UTC 2025
- Auto Sign-in run successful on Sun Aug 10 01:24:16 UTC 2025
- Auto Sign-in run successful on Mon Aug 11 01:21:01 UTC 2025
- Auto Sign-in run successful on Tue Aug 12 01:13:14 UTC 2025
- Auto Sign-in run successful on Wed Aug 13 01:14:40 UTC 2025
- Auto Sign-in run successful on Thu Aug 14 01:15:01 UTC 2025
- Auto Sign-in run successful on Fri Aug 15 01:15:19 UTC 2025
- Auto Sign-in run successful on Sat Aug 16 01:11:43 UTC 2025
- Auto Sign-in run successful on Sun Aug 17 01:20:02 UTC 2025
- Auto Sign-in run successful on Mon Aug 18 01:19:22 UTC 2025
- Auto Sign-in run successful on Tue Aug 19 01:11:55 UTC 2025
- Auto Sign-in run successful on Wed Aug 20 01:09:41 UTC 2025
- Auto Sign-in run successful on Thu Aug 21 01:08:51 UTC 2025
- Auto Sign-in run successful on Fri Aug 22 01:09:52 UTC 2025
- Auto Sign-in run successful on Sat Aug 23 01:07:15 UTC 2025
- Auto Sign-in run successful on Sun Aug 24 01:17:19 UTC 2025
- Auto Sign-in run successful on Mon Aug 25 01:12:45 UTC 2025
- Auto Sign-in run successful on Tue Aug 26 01:10:56 UTC 2025
- Auto Sign-in run successful on Wed Aug 27 01:08:29 UTC 2025
- Auto Sign-in run successful on Thu Aug 28 01:07:44 UTC 2025
- Auto Sign-in run successful on Fri Aug 29 01:07:58 UTC 2025
- Auto Sign-in run successful on Sat Aug 30 01:04:40 UTC 2025
- Auto Sign-in run successful on Sun Aug 31 01:12:29 UTC 2025
- Auto Sign-in run successful on Mon Sep  1 01:19:10 UTC 2025
- Auto Sign-in run successful on Tue Sep  2 01:09:14 UTC 2025
- Auto Sign-in run successful on Wed Sep  3 01:04:44 UTC 2025
- Auto Sign-in run successful on Thu Sep  4 01:04:29 UTC 2025
- Auto Sign-in run successful on Fri Sep  5 01:06:16 UTC 2025
- Auto Sign-in run successful on Sat Sep  6 01:04:35 UTC 2025
- Auto Sign-in run successful on Sun Sep  7 01:11:29 UTC 2025
- Auto Sign-in run successful on Mon Sep  8 01:10:14 UTC 2025
- Auto Sign-in run successful on Tue Sep  9 01:07:12 UTC 2025
- Auto Sign-in run successful on Wed Sep 10 01:05:31 UTC 2025
- Auto Sign-in run successful on Thu Sep 11 01:06:59 UTC 2025
- Auto Sign-in run successful on Fri Sep 12 01:04:19 UTC 2025
- Auto Sign-in run successful on Sat Sep 13 01:01:41 UTC 2025
- Auto Sign-in run successful on Sun Sep 14 01:10:51 UTC 2025
- Auto Sign-in run successful on Mon Sep 15 01:11:15 UTC 2025
- Auto Sign-in run successful on Tue Sep 16 01:05:30 UTC 2025
- Auto Sign-in run successful on Wed Sep 17 01:05:18 UTC 2025
- Auto Sign-in run successful on Thu Sep 18 01:04:58 UTC 2025
- Auto Sign-in run successful on Fri Sep 19 01:07:14 UTC 2025
- Auto Sign-in run successful on Sat Sep 20 01:04:01 UTC 2025
- Auto Sign-in run successful on Sun Sep 21 01:12:38 UTC 2025
- Auto Sign-in run successful on Mon Sep 22 01:11:54 UTC 2025
- Auto Sign-in run successful on Tue Sep 23 01:05:19 UTC 2025
- Auto Sign-in run successful on Wed Sep 24 01:06:29 UTC 2025
- Auto Sign-in run successful on Thu Sep 25 01:06:55 UTC 2025
- Auto Sign-in run successful on Fri Sep 26 01:06:40 UTC 2025
- Auto Sign-in run successful on Sat Sep 27 01:03:53 UTC 2025
- Auto Sign-in run successful on Sun Sep 28 01:13:24 UTC 2025
- Auto Sign-in run successful on Mon Sep 29 01:08:40 UTC 2025
- Auto Sign-in run successful on Tue Sep 30 01:07:44 UTC 2025
- Auto Sign-in run successful on Wed Oct  1 01:14:49 UTC 2025
- Auto Sign-in run successful on Thu Oct  2 01:05:19 UTC 2025
- Auto Sign-in run successful on Fri Oct  3 01:05:14 UTC 2025
- Auto Sign-in run successful on Sat Oct  4 01:02:50 UTC 2025
- Auto Sign-in run successful on Sun Oct  5 01:12:55 UTC 2025
- Auto Sign-in run successful on Mon Oct  6 01:07:33 UTC 2025
- Auto Sign-in run successful on Tue Oct  7 01:06:14 UTC 2025
- Auto Sign-in run successful on Wed Oct  8 01:05:53 UTC 2025
- Auto Sign-in run successful on Thu Oct  9 01:06:52 UTC 2025
- Auto Sign-in run successful on Fri Oct 10 01:06:44 UTC 2025
- Auto Sign-in run successful on Sat Oct 11 01:03:59 UTC 2025
- Auto Sign-in run successful on Sun Oct 12 01:10:03 UTC 2025
- Auto Sign-in run successful on Mon Oct 13 01:11:40 UTC 2025
- Auto Sign-in run successful on Tue Oct 14 01:06:45 UTC 2025
- Auto Sign-in run successful on Wed Oct 15 01:08:51 UTC 2025
- Auto Sign-in run successful on Thu Oct 16 01:08:22 UTC 2025
- Auto Sign-in run successful on Fri Oct 17 01:07:45 UTC 2025
- Auto Sign-in run successful on Sat Oct 18 01:04:37 UTC 2025
- Auto Sign-in run successful on Sun Oct 19 01:15:59 UTC 2025
- Auto Sign-in run successful on Mon Oct 20 01:13:21 UTC 2025
- Auto Sign-in run successful on Tue Oct 21 01:10:32 UTC 2025
- Auto Sign-in run successful on Wed Oct 22 01:11:13 UTC 2025
- Auto Sign-in run successful on Thu Oct 23 01:09:23 UTC 2025
- Auto Sign-in run successful on Fri Oct 24 01:05:59 UTC 2025
- Auto Sign-in run successful on Sat Oct 25 01:07:11 UTC 2025
- Auto Sign-in run successful on Sun Oct 26 01:14:18 UTC 2025
- Auto Sign-in run successful on Mon Oct 27 01:15:25 UTC 2025
- Auto Sign-in run successful on Tue Oct 28 01:08:01 UTC 2025
- Auto Sign-in run successful on Wed Oct 29 01:13:25 UTC 2025
