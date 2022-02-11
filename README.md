# RM_Sentry

## 功能介绍

2020RM 哨兵 webots 模型，能实现轨道上自动追击目标。

>其它功能例如自动巡逻等可在其基础上添加。

## 效果展示

**运动效果图：**

<center class="half">
    <img src="https://s2.loli.net/2022/02/11/qhTUvQdzn1YAGKW.gif">
</center>

## 依赖工具及软件环境

`工具:`Webots

`软件环境:`Windows10

## 文件层次

- controllers（控制器本体）:

    文件名|内容
    -|-
    Logic_Detection|自动追击
    my_controller|只控制底盘运动
    RN_Sentry_VS|只控制云台运动

- worlds（哨兵工程）

## 使用方法

- 使用 Logic_Detection 控制器：

    拖动正方体方块模拟装甲板运动。

- 使用 my_controller 控制器：

    按键|运动
    -|-
    D|底盘左移
    A|底盘右移

- 使用 RN_Sentry_VS 控制器：

    按键|运动
    -|-
    D|云台左旋
    A|云台右旋

## 写在最后

在我的[博客 webots 篇](https://lapzjfit.site/post/Webots%2Flist%2FWebots%E5%BA%8F%E7%AB%A0)有相关资料描述。