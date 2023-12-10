# Unity3D
Unity3D（IslandSurvival）案例开发



博客介绍页：

- [Unity3D_IslandSurvival 案例开发 | Jermain Liu (jermainn.github.io)](https://jermainn.github.io/p/7cfb.html) 
- [Unity3D_IslandSurvival 案例开发 | Jermain Liu (gitee.io)](https://jermainn.gitee.io/p/7cfb.html) 

GitHub发布页：[jermainn/Unity3D: Unity3D案例开发 (github.com)](https://github.com/jermainn/Unity3D) 

下载页：

- GitHub：[Release 测试 · jermainn/Unity3D (github.com)](https://github.com/jermainn/Unity3D/releases/tag/Unity3D) 
- 百度网盘：https://pan.baidu.com/s/16e0VTI-ueueOr3JRBx_sbw?pwd=6iij 提取码：6iij



> 当前案例尚存在较多问题，需要接下来对其进行进一步修整优化



**介绍** 

案例界面采用了旧港口的场景

![OldSeaPort_Scene](https://cdn.jsdelivr.net/gh/jermainn/cdn@master/images/temp/OldSeaPort_Scene.webp)



针对主角主视角，主要设计有相机视角跟随、鼠标控制视角运动、按键控制主角移动、简单的攻击效果和攻击音效。配置界面UI，分别显示生命值、得分值和子弹数量。

![player_view_mark](https://cdn.jsdelivr.net/gh/jermainn/cdn@master/images/temp/player_view_mark.webp)



子弹攻击效果和主角游戏结束分别如下：

<img src="https://cdn.jsdelivr.net/gh/jermainn/cdn@master/images/temp/attack_view1.webp" alt="attack_view1" style="zoom:80%;" />

<img src="https://cdn.jsdelivr.net/gh/jermainn/cdn@master/images/temp/GAMEOVER_view.webp" alt="GAMEOVER_view" style="zoom:80%;" />



主角生命为0后，游戏结束。画面中释放了鼠标，中间部分显示“GAME OVER”，并提供“TRY AGAIN”按键重新开始。
针对敌人，实现了自动寻路，始终向着主角运动，并通过状态控制，在追踪、攻击、死亡等状态进行切换。下面展示简单游戏动图。

![GamePlay](https://cdn.jsdelivr.net/gh/jermainn/cdn@master/images/temp/GamePlay.gif)

