```markdown
# 环境配置与运行说明

## 依赖库

需要安装以下 Python 库：

- `langchain`
- `langchain-deepseek`
- `langchain_tavily`

## 环境变量

在项目根目录下创建 `.env` 文件，并配置以下变量：

```env
DEEPSEEK_API_KEY=你的真实有效API密钥
TAVILY_API_KEY=任意字符串（可随便填写）
```

> **注意**：`DEEPSEEK_API_KEY` 必须是真实有效的密钥；`TAVILY_API_KEY` 无实际校验要求，可随意输入。

## 运行方式

运行 Notebook 时，**仅需执行第 1 个、第 3 个以及最后一个单元格**，其余单元格无需运行。
```
