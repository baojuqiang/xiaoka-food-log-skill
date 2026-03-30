# calmate_food_log_skill
小卡健康饮食记录skill
# 小卡健康饮食记录 - OpenClaw Skill

用自然语言通过 [OpenClaw](https://openclaw.ai) 记录每日饮食，数据同步到小卡健康 App。

## 安装

\```bash
# 克隆到 OpenClaw skills 目录
git clone https://github.com/baojuqiang/xiaoka-food-log-skill \
  ~/.openclaw/workspace/skills/xiaoka-food-log
\```

## 使用前提

- 安装 [小卡健康 App](https://apps.apple.com/app/id你的appid)（用于绑定账号）
- 安装 [OpenClaw](https://openclaw.ai)
- 本地已有 `curl` 和 `jq`

## 使用方式

安装后直接对话，首次使用会自动引导绑定：

> 记录午餐，我吃了一碗米饭和两个鸡蛋

绑定只需操作一次，之后无需任何配置。

## 无需重启，无需配置环境变量
