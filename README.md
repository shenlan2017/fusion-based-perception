# 深蓝学院后融合练习

lidar、camera后融合算法，输入数据来自apollo检测算法

## 使用方法

使用catkin_make编译代码并source所在的工作空间

使用以下命令启动可视化

```shell
$ roslaunch kit_perception rviz.launch
```

提供了两个数据集供测试使用，分别为单物体数据集和多物体数据集

使用以下命令使用单物体数据集启动程序

```shell
$ roslaunch kit_perception single_obj_fusion.launch
```

使用以下命令使用多物体数据集启动程序

```shell
$ roslaunch kit_perception mutil_obj_fusion.launch
```

### 可视化说明

在rviz内蓝色物体为融合结果，白色物体为雷达观测
