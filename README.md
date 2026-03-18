# OpenClaw Mission Control

这是给 OpenClaw 用的 Mission Control 任务看板仓库。

## 目录说明

- `index.html`: GitHub Pages 上的任务看板页面
- `data/tasks.json`: 任务数据源
- `scripts/mc-update.sh`: 本地更新任务状态的辅助脚本

## 使用方式

1. 打开 GitHub Pages 页面
2. 点击 `Connect GitHub`
3. 输入具有 `repo` 权限的 GitHub Token
4. 开始在看板上管理任务

## 说明

这个仓库不存放密钥。Webhook secret 和 OpenClaw 配置在本机 `~/.openclaw` 下。
