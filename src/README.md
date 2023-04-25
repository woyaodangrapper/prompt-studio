src\
    ├── core\
    │     ├── domain\            # 领域层
    │     │     ├── aggregates\ # 聚合根类
    │     │     ├── entities\   # 实体类
    │     │     ├── value_objects\ # 值对象
    │     │     └── services\   # 针对领域层的应用服务类
    │     ├── infrastructure\   # 基础设施层
    │     │     ├── repositories\ # 数据库访问相关代码
    │     │     ├── event_handlers\ # 事件处理相关代码
    │     │     ├── messaging\     # 消息流通相关代码
    │     │     ├── caching\       # 缓存相关代码
    │     │     └── utilities\     # 工具类
    │     ├── application\       # 应用层
    │     │     ├── commands\    # 命令类
    │     │     └── queries\     # 查询类
    │     └── presentation\      # 表现层
    │           ├── viewmodels\   # 视图模型类
    │           ├── views\        # 视图页面
    │           └── converters\   # 数据转换器
    ├── services\
    │     ├── prompter\          # 存放自动提示相关代码
    │     └── nlp\               # 存放自然语言处理相关代码
    │
    └── tests\                    # 测试相关代码
