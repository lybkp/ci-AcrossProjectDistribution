#### 插件功能
跨项目上传构件至其他项目自定义仓库

#### 插件参数
1. 待分发构件可以是本次归档的构件也可以是自定义仓库的构件（相对路径支持*通配符）
2. 目标项目选择想要上传的项目
3. 自定义仓库的仓库路径：
    - 可不填,默认会在目标项目自定义仓库下
4. 构件列表取消显示: 分发本次已归档构件到当前项目自定义仓库时，勾选此项后流水线构件列表中不会显示分发的构件。避免重复显示 