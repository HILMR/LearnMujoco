# 新版Mujoco学习笔记
## 目标
开源后的mujoco与开源前,尤其是`mujoco_py`,存在一定的差别,而目前的教程普遍都是开源前的教程,存在很强的误导性

本学习笔记持续更新...
## 新的变化
`MuJoCo`已经开源，可以直接通过pip安装
```
pip install mujoco
```
> 注意：mujoco安装方式的变化
- `mujoco_py`和`mjpro150`或者`mjpro210`啥的都成为历史了(参考:https://github.com/deepmind/mujoco/issues/347)
- 为了更方便使用`MuJoCo`可以安装`dm_control`，这也是官方教程中推荐的使用方式
```
pip install dm_control
```
### 如何学习
- 官方jupyter教程：
    - [mujoco原生python支持](https://github.com/deepmind/dm_control/blob/main/tutorial.ipynb)
    - [dm_control教程](https://github.com/deepmind/mujoco/blob/main/python/tutorial.ipynb)
- [官方文档](https://mujoco.readthedocs.io/en/latest/overview.html)
    - 重点参考1：[MJCF编写指南](https://mujoco.readthedocs.io/en/latest/XMLreference.html)
    - 重点参考2：[API文档](https://mujoco.readthedocs.io/en/latest/APIreference/index.html)(虽然是C版本的，但是命名方式和python类似，结合jupyter教程可以了解如何使用)
- Github仓库和issue (尤其留意issue，因为目前版本迭代非常快，很多新功能被逐步加入)
    - [mujoco](https://github.com/deepmind/mujoco)
    - [dm_control](https://github.com/deepmind/dm_control)
> 注意：一定要区分开源前的教程和开源后的教程！