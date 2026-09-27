# RMtask
everyweektask
# RMtask
everyweektask

## 任务文件存放格式

各任务按 `taskN` 编号建立一级目录，任务内部的代码、配置等内容按类型归入子目录。不同 task 统一提交到同一分支，无需单独建立 branch。

```
.
├── task1
│   └── environment      # 配置环境
├── task2
│   ├── cpp
│   │   ├── 1            # 入门一
│   │   ├── 2            # 入门二
│   │   └── ros          # 分支结构
└── README.md
```

### 说明

- `task1/`、`task2/` …… 按任务编号建立一级目录。
- 每个 task 目录下按内容类型建子目录，例如 `environment/`（配置环境）、`cpp/`（C++ 代码）等。
- `cpp/` 下的 `1`、`2`、`ros` 分别对应「入门一」「入门二」「分支结构」三部分内容。
- 新增任务时按同样规则追加 `taskN/` 目录，并同步更新上方树状结构。
