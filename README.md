这是一个根据UE官方文档针对 AI_EQS 系统进行学习的实践Demo.

这个Demo使用引擎版本：UE4.26

此项目实践过程与官方文档存在的一些差异：

1-必要项目设置：

没有在 **编辑器首选项（Editor Preferences）> 试验性（Experimental）> AI** 部分，找到并启用 **场景查询系统（Environment Querying System）**。【暂时未找到相关参考博客】

6-行为树：战斗设置

BT_Enemy（行为树）-> Attack序列节点的 **黑板** 类型的 **装饰器** 设置中

- **观察者中止（Observer aborts）** 设为 **低优先级（Lower Priority）** 【无 Lower Priority 选项】

修改：暂时将 **观察者中止（Observer aborts）** 设置为 **空（None）** 

