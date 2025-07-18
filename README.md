## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Thu Mar  6 01:34:47 UTC 2025
- Auto Sign-in run successful on Thu Mar  6 03:01:05 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 02:42:23 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 03:01:50 UTC 2025
- Auto Sign-in run successful on Sat Mar  8 02:18:06 UTC 2025
- Auto Sign-in run successful on Sun Mar  9 02:23:40 UTC 2025
- Auto Sign-in run successful on Mon Mar 10 02:25:36 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 03:02:14 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 03:01:04 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 03:02:59 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 03:01:01 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 02:58:19 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 03:06:56 UTC 2025
- Auto Sign-in run successful on Mon Mar 17 03:06:20 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 03:05:20 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 03:04:15 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 03:02:30 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 03:05:32 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 03:02:53 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 03:10:25 UTC 2025
- Auto Sign-in run successful on Mon Mar 24 03:11:25 UTC 2025
- Auto Sign-in run successful on Tue Mar 25 03:07:01 UTC 2025
- Auto Sign-in run successful on Wed Mar 26 03:05:22 UTC 2025
- Auto Sign-in run successful on Thu Mar 27 03:06:53 UTC 2025
- Auto Sign-in run successful on Fri Mar 28 03:08:12 UTC 2025
- Auto Sign-in run successful on Sat Mar 29 03:04:31 UTC 2025
- Auto Sign-in run successful on Sun Mar 30 03:14:39 UTC 2025
- Auto Sign-in run successful on Mon Mar 31 03:14:01 UTC 2025
- Auto Sign-in run successful on Tue Apr  1 03:31:31 UTC 2025
- Auto Sign-in run successful on Wed Apr  2 03:08:53 UTC 2025
- Auto Sign-in run successful on Thu Apr  3 03:07:43 UTC 2025
- Auto Sign-in run successful on Fri Apr  4 03:07:22 UTC 2025
- Auto Sign-in run successful on Sat Apr  5 03:05:06 UTC 2025
- Auto Sign-in run successful on Sun Apr  6 01:25:40 UTC 2025
- Auto Sign-in run successful on Mon Apr  7 01:23:22 UTC 2025
- Auto Sign-in run successful on Tue Apr  8 01:21:11 UTC 2025
- Auto Sign-in run successful on Wed Apr  9 01:21:40 UTC 2025
- Auto Sign-in run successful on Thu Apr 10 01:21:10 UTC 2025
- Auto Sign-in run successful on Fri Apr 11 01:21:38 UTC 2025
- Auto Sign-in run successful on Sat Apr 12 01:20:06 UTC 2025
- Auto Sign-in run successful on Sun Apr 13 02:49:23 UTC 2025
- Auto Sign-in run successful on Mon Apr 14 01:24:38 UTC 2025
- Auto Sign-in run successful on Tue Apr 15 01:23:59 UTC 2025
- Auto Sign-in run successful on Wed Apr 16 01:23:23 UTC 2025
- Auto Sign-in run successful on Thu Apr 17 01:22:20 UTC 2025
- Auto Sign-in run successful on Fri Apr 18 01:21:34 UTC 2025
- Auto Sign-in run successful on Sat Apr 19 01:19:24 UTC 2025
- Auto Sign-in run successful on Sun Apr 20 01:27:57 UTC 2025
- Auto Sign-in run successful on Mon Apr 21 01:26:16 UTC 2025
- Auto Sign-in run successful on Tue Apr 22 01:22:49 UTC 2025
- Auto Sign-in run successful on Wed Apr 23 01:23:14 UTC 2025
- Auto Sign-in run successful on Thu Apr 24 01:23:11 UTC 2025
- Auto Sign-in run successful on Fri Apr 25 01:24:01 UTC 2025
- Auto Sign-in run successful on Sat Apr 26 01:20:53 UTC 2025
- Auto Sign-in run successful on Sun Apr 27 01:28:18 UTC 2025
- Auto Sign-in run successful on Mon Apr 28 01:25:47 UTC 2025
- Auto Sign-in run successful on Tue Apr 29 01:23:56 UTC 2025
- Auto Sign-in run successful on Wed Apr 30 01:24:00 UTC 2025
- Auto Sign-in run successful on Thu May  1 01:39:41 UTC 2025
- Auto Sign-in run successful on Fri May  2 01:24:21 UTC 2025
- Auto Sign-in run successful on Sat May  3 01:22:25 UTC 2025
- Auto Sign-in run successful on Sun May  4 01:39:57 UTC 2025
- Auto Sign-in run successful on Mon May  5 01:27:38 UTC 2025
- Auto Sign-in run successful on Tue May  6 01:24:55 UTC 2025
- Auto Sign-in run successful on Wed May  7 01:25:44 UTC 2025
- Auto Sign-in run successful on Thu May  8 01:25:47 UTC 2025
- Auto Sign-in run successful on Fri May  9 01:25:22 UTC 2025
- Auto Sign-in run successful on Sat May 10 01:22:32 UTC 2025
- Auto Sign-in run successful on Sun May 11 01:38:05 UTC 2025
- Auto Sign-in run successful on Mon May 12 01:28:28 UTC 2025
- Auto Sign-in run successful on Tue May 13 01:26:37 UTC 2025
- Auto Sign-in run successful on Wed May 14 01:25:21 UTC 2025
- Auto Sign-in run successful on Thu May 15 01:23:33 UTC 2025
- Auto Sign-in run successful on Fri May 16 01:26:31 UTC 2025
- Auto Sign-in run successful on Sat May 17 01:24:29 UTC 2025
- Auto Sign-in run successful on Sun May 18 01:39:26 UTC 2025
- Auto Sign-in run successful on Mon May 19 01:38:43 UTC 2025
- Auto Sign-in run successful on Tue May 20 01:27:24 UTC 2025
- Auto Sign-in run successful on Wed May 21 01:27:02 UTC 2025
- Auto Sign-in run successful on Thu May 22 01:26:13 UTC 2025
- Auto Sign-in run successful on Fri May 23 01:26:21 UTC 2025
- Auto Sign-in run successful on Sat May 24 01:23:26 UTC 2025
- Auto Sign-in run successful on Sun May 25 01:41:39 UTC 2025
- Auto Sign-in run successful on Mon May 26 01:37:19 UTC 2025
- Auto Sign-in run successful on Tue May 27 01:25:36 UTC 2025
- Auto Sign-in run successful on Wed May 28 01:27:04 UTC 2025
- Auto Sign-in run successful on Thu May 29 01:26:55 UTC 2025
- Auto Sign-in run successful on Fri May 30 01:24:51 UTC 2025
- Auto Sign-in run successful on Sat May 31 01:25:03 UTC 2025
- Auto Sign-in run successful on Sun Jun  1 01:50:53 UTC 2025
- Auto Sign-in run successful on Mon Jun  2 01:39:43 UTC 2025
- Auto Sign-in run successful on Tue Jun  3 01:28:21 UTC 2025
- Auto Sign-in run successful on Wed Jun  4 01:36:55 UTC 2025
- Auto Sign-in run successful on Thu Jun  5 01:27:15 UTC 2025
- Auto Sign-in run successful on Fri Jun  6 01:27:06 UTC 2025
- Auto Sign-in run successful on Sat Jun  7 01:26:48 UTC 2025
- Auto Sign-in run successful on Sun Jun  8 01:43:33 UTC 2025
- Auto Sign-in run successful on Mon Jun  9 01:41:29 UTC 2025
- Auto Sign-in run successful on Tue Jun 10 01:37:48 UTC 2025
- Auto Sign-in run successful on Wed Jun 11 01:37:25 UTC 2025
- Auto Sign-in run successful on Thu Jun 12 01:27:31 UTC 2025
- Auto Sign-in run successful on Fri Jun 13 01:37:09 UTC 2025
- Auto Sign-in run successful on Sat Jun 14 01:25:53 UTC 2025
- Auto Sign-in run successful on Sun Jun 15 01:45:16 UTC 2025
- Auto Sign-in run successful on Mon Jun 16 01:40:31 UTC 2025
- Auto Sign-in run successful on Tue Jun 17 01:37:40 UTC 2025
- Auto Sign-in run successful on Wed Jun 18 01:28:09 UTC 2025
- Auto Sign-in run successful on Thu Jun 19 01:37:54 UTC 2025
- Auto Sign-in run successful on Fri Jun 20 01:27:59 UTC 2025
- Auto Sign-in run successful on Sat Jun 21 01:27:25 UTC 2025
- Auto Sign-in run successful on Sun Jun 22 01:44:43 UTC 2025
- Auto Sign-in run successful on Mon Jun 23 01:43:14 UTC 2025
- Auto Sign-in run successful on Tue Jun 24 01:38:06 UTC 2025
- Auto Sign-in run successful on Wed Jun 25 01:38:26 UTC 2025
- Auto Sign-in run successful on Thu Jun 26 01:37:14 UTC 2025
- Auto Sign-in run successful on Fri Jun 27 01:38:34 UTC 2025
- Auto Sign-in run successful on Sat Jun 28 01:26:36 UTC 2025
- Auto Sign-in run successful on Sun Jun 29 01:46:37 UTC 2025
- Auto Sign-in run successful on Mon Jun 30 01:42:48 UTC 2025
- Auto Sign-in run successful on Tue Jul  1 01:48:01 UTC 2025
- Auto Sign-in run successful on Wed Jul  2 01:37:57 UTC 2025
- Auto Sign-in run successful on Thu Jul  3 01:38:13 UTC 2025
- Auto Sign-in run successful on Sat Jul  5 01:26:19 UTC 2025
- Auto Sign-in run successful on Sun Jul  6 01:45:17 UTC 2025
- Auto Sign-in run successful on Mon Jul  7 01:43:08 UTC 2025
