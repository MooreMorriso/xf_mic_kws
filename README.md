# 讯飞二代麦克风阵列ROSPY简易SDK
## 开发原因
最初的想法是用二代麦克风阵列的ROS SDK识别关键词以后就开始5s的录音，但看了半天没搞明白，便去翻用户手册，然后就有了这个东西。
## 怎么使用？
事实上目前这个DEMO跟平常任意一个rospy脚本一样，随便扔个pkg然后rosrun这个.py就可以，后期我会优化一下成一个pkg
## 参数呢
目前还得去python文件里去改，关于参数的部分在里边都有注释
## 依赖
    1. 安装pyaudio  pip3 install pyaudio
    2. 安装pyserial  pip3 install pyserial
    3. 安装wave  pip3 install wave
In one go: pip3 install pyaudio pyserial wave
## Enjoy?
