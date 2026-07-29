# Horizon

个人新闻聚合工具，fork 自 [Thysrael/Horizon](https://github.com/Thysrael/Horizon)。

原项目是一个 AI 驱动的新闻雷达，从多信息源抓取内容，用 AI 打分过滤，生成日报。此分支为个人使用定制。

## 定制内容

- AI 提供商：GLM（智谱AI）
- 个人信息源配置
- 其他个人调整

## 使用

```bash
# 安装依赖
uv sync

# 配置
cp .env.example .env
# 编辑 .env 填入 API Key
cp data/config.example.json data/config.json
# 编辑 data/config.json 配置信息源

# 运行
uv run horizon
```

## 上游

原项目：[Thysrael/Horizon](https://github.com/Thysrael/Horizon)  
所有功劳归属原作者。
