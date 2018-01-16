# RestfulAPI
根据萤石开放平台的开发文档，使用Java实现接口的封装。https://open.ys7.com/doc/zh/book/index/device_option.html


初步完成了萤石摄像头的一些接口的封装，后面还会陆续更新，

本节包含设备相关的接口，按功能分为设备操作、设备查询、设备升级、云台控制、报警消息查询、探测器相关操作、客流统计相关、开关状态控制等。

接口列表如下：

1	添加设备	添加设备到账号下

2	删除设备	删除账号下指定设备

3	修改设备名称	修改设备名称

4	设备抓拍图片	抓拍设备的当前画面

5	NVR设备关联IPC	NVR设备关联IPC

6	NVR设备删除IPC	NVR设备删除IPC

7	获取设备列表	获取用户下的设备列表

8	获取单个设备信息	获取指定设备的信息

9	获取摄像头列表	获取用户下的摄像头列表

10	根据UUID查询抓拍图片	设备互联互通根据UUID查询抓拍的图片

11	获取设备版本信息	获取设备的版本信息

12	设备升级固件	升级设备固件

13	获取设备升级状态	获取设备升级状态，包含升级进度、状态等

14	开始云台控制	开始云台转动

15	停止云台控制	停止云台转动

16	镜像翻转	镜像翻转

17	添加预置点	添加预置点

18	调用预置点	调用预置点

19	清除预置点	清除预置点

20	获取所有报警信息列表	查询用户下的所有报警消息列表

21	按照设备获取报警消息列表	查询指定设备的报警消息列表

22	订阅C用户报警消息	B模式管理员账号订阅C端用户设备的报警消息

23	取消订阅C用户报警消息	B模式管理员账号取消订阅C端用户设备的报警消息

24	获取探测器列表	查询指定A1系列设备关联的探测器列表

25	设置探测器状态	设置探测器的布撤防状态

26	删除探测器	删除A1系列设备关联的探测器

27	获取可关联的IPC列表	获取A1系列设备可关联的IPC设备列表

28	获取已关联的IPC列表	获取A1系列设备已关联的IPC设备列表

29	设置探测器与IPC的关联关系	设置A1系列设备关联的探测器与IPC设备的关联关系

30	获取客流统计开关状态	查询指定设备客流统计开关状态

31	设置客流统计开关	设置设备客流统计开关状态

32	查询设备某一天的统计客流数据	查询设备某一天总的客流数据

33	查询设备某一天每小时的客流数据	查询设备某一天每小时的客流数据

34	配置客流统计信息	配置客流统计信息

35	获取客流统计配置信息	获取客流统计配置信息

36	设备布撤防	设置设备活动检测开关状态

37	关闭设备视频加密	关闭设备视频加密开关

38	开启设备视频加密	打开设备视频加密开关

39	获取wifi配置提示音开关状态	获取wifi配置或者设备重启提示音开关状态

40	设置wifi配置提示音开关	设置wifi配置或者设备重启提示音开关状态

41	获取镜头遮蔽开关状态	获取镜头遮蔽开关状态

42	设置镜头遮蔽开关	设置镜头遮蔽开关

43	获取声源定位开关状态	获取声源定位开关状态

44	设置声源定位开关	设置声源定位开关

45	获取设备布撤防时间计划	获取设备布撤防（活动检测）时间计划

46	设置布撤防时间计划	设置布撤防（活动检测）时间计划

47	修改探测器名称	修改探测器的名称

48	设备一键消警	设备远程消除警报功能

49	获取摄像机指示灯开关状态	获取摄像机指示灯开关状态

50	设置摄像机指示灯开关	设置摄像机指示灯开关

51	获取全天录像开关状态	获取全天录像开关状态

52	设置全天录像开关	设置全天录像开关