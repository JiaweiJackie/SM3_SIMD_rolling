# SM3_SIMD_rolling

个人完成。

# 实现原理

循环展开以及多线程加速。

分别对单线程、四线程以及八线程进行测试，最终发现四线程加速效果相对较好，当线程数量过多时，可能存在线程切换的开销以及一些其他的性能瓶颈等原因进而使得运行时间非但不下降反而升高。

四线程代码如下：

![image](https://user-images.githubusercontent.com/105580300/181923454-cba6296b-36be-4e9f-8737-02eda3d4b134.png)


# 执行结果

点击直接运行即可：

![image](https://user-images.githubusercontent.com/105580300/181923428-2cb7dd71-5c44-4a79-a408-e3f0f270b741.png)


![image](https://user-images.githubusercontent.com/105580300/181922346-4646dd1b-d2db-43b3-a933-cc5615e8a571.png)

执行成功！
