# 目录结构以下是根据(Sage)人格推荐项目目录结构

本项目遵循以下目录结构：

## 目录结构

```
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
    │           ├── views\        # 视图页面
    │           │     └── model\   # 视图模型类
    │           └── converters\   # 数据转换器
    ├── services\                 # 存放自动提示相关代码(nlp)和自然语言处理相关代码(prompter)
    └── tests\                    # 存放测试相关代码
```

## 或演进

`演进或参考的建议性文件结构`

```
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
    │     │     ├── queries\     # 查询类
    │     │     ├── data\        # 存储训练数据相关代码
    │     │     ├── models\      # 模型存储相关代码
    │     │     ├── dialog\      # 对话管理相关代码
    │     │     ├── summarization\  # 自动总结相关代码
    │     │     ├── creative_writing\ # 自动创作相关代码
    │     │     ├── behavior_control\ # 行为控制相关代码
    │     │     └── services\    # 应用层服务类
    │     └── presentation\      # 表现层
    │           ├── views\        # 视图页面
    │           │     └── model\   # 视图模型类
    │           └── converters\   # 数据转换器
    ├── services\                 # 存放自动提示相关代码(nlp)和自然语言处理相关代码(prompter)
    │     ├── nlp\               # 自然语言处理相关代码
    │     └── prompter\          # 自动提示相关代码
    └── tests\                    # 存放测试相关代码
```

## 可能启发

`演进或参考的建议性文件结构`

```
project/
├── data/                                # 数据目录
│   ├── raw/                             # 原始数据目录
│   ├── processed/                       # 预处理后的数据目录
│   ├── embeddings/                      # 词向量模型目录
│   └── ...
├── models/                              # 模型目录
│   ├── neural_networks/                 # 深度学习模型目录
│   ├── traditional_ml/                  # 传统机器学习模型目录
│   └── ...
├── utils/                               # 工具目录
│   ├── preprocessing/                   # 预处理工具目录
│   ├── evaluation/                      # 评估工具目录
│   ├── visualization/                   # 可视化工具目录
│   ├── cache/                           # 缓存工具目录
│   └── ...
├── api/                                 # API目录
│   ├── controllers/                     # 控制器目录
│   ├── services/                        # 服务目录
│   ├── models/                          # API模型目录
│   ├── middleware/                      # 中间件目录
│   ├── routes/                          # 路由目录
│   └── ...
├── frontend/                            # 前端目录
│   ├── components/                      # 组件目录
│   ├── pages/                           # 页面目录
│   ├── assets/                          # 静态文件目录
│   ├── styles/                          # 样式目录
│   └── ...
├── tests/                               # 测试目录
│   ├── unit/                            # 单元测试目录
│   ├── integration/                     # 集成测试目录
│   ├── performance/                     # 性能测试目录
│   └── ...
├── docs/                                # 文档目录
│   ├── api/                             # API文档目录
│   ├── user/                            # 用户文档目录
│   ├── developer/                       # 开发者文档目录
│   └── ...
├── config/                              # 配置文件目录
│   ├── settings/                        # 应用程序设置目录
│   ├── database/                        # 数据库配置目录
│   ├── logging/                         # 日志配置目录
│   ├── cache/                           # 缓存配置目录
│   └── ...
└── main.py                              # 应用程序主入口
```

