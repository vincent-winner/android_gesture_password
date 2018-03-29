# python_android_gesture_password
用python2.x破解android的锁屏手势密码
android手机屏幕的手势密码：
系统将手势以一串数字(以十六进制的方式)进行SHA1加密，存储在了手机里的/data/system/gesture.key 文件中。

把手机root，把gesture.key文件取出来放在和gesture_passswd_*.py同一个文件夹下，运行gesture_passwd_*.py进行解密，解密之前最好保证gesture.key有读取权限

####解密开始：
#####加密后的密码为：63f6171ce48733d6fca74f0c76c78a9ef2e3c430
#####解锁密码为： 00-01-02-04-06-03-05-08-07
#####共耗时： 4.7755961418151855 秒

#####安卓图案锁屏对应位置如下
              00  01  02
              03  04  05
              06  07  08







