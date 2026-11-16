---
name: hermes-agent-repo
version: 1.0.0
description: Hermes Agent ☤
trigger_conditions:
  - 需要理解、修改或排障 hermes-agent 的代码
  - 在 hermes-agent 里定位入口、数据表、对外契约或构建方式
---

# hermes-agent 仓库技能

> 由仓库实际内容生成的骨架（README/目录/模型定义/契约/构建脚本逐项取证）。新增判断与坑位请直接在下面对应小节补充。

## 定位

**Hermes Agent ☤**

<img src="assets/banner.png" alt="Hermes Agent" width="100%"> </p> <p align="center"> <a href="https://hermes-agent.nousresearch.com/">Hermes Agent</a> | <a href="https://hermes-agent.nousresearch.com/">Hermes Desktop</a> </p> <p align="center"> <a href="https://hermes-agent.nousresearch.com/docs/">

- 远端：`https://github.com/yumoqing/hermes-agent.git`
- 默认分支：`main`（共 45353 个提交）
- 最近提交：2026-09-27 `27062c3474` fix: install cua-driver and the Browser Use CLI by default again
- 规模：16524 个文件；Python 7854，TypeScript 2776，YAML 534

## 目录结构

- `tests/` — 测试（5582 个文件）
- `apps/` — 3545 个文件
- `contributors/` — 1640 个文件
- `website/` — 826 个文件
- `optional-skills/` — 790 个文件
- `hermes_cli/` — 607 个文件
- `ui-tui/` — 497 个文件
- `plugins/` — 379 个文件
- `tools/` — 344 个文件
- `plugin-catalog/` — 339 个文件
- `skills/` — 331 个文件
- `agent/` — 310 个文件
- 根文件：`.coderabbit.yaml`、`.dockerignore`、`.env.example`、`.envrc`、`.gitattributes`、`.gitignore`、`.hadolint.yaml`、`.mailmap`、`.npmrc`、`.nvmrc`

## 构建与运行

- `pyproject.toml`：`hermes-agent` v0.0.0，依赖 5 项
- `setup.py`：`?` v?，依赖 0 项
- `package.json`：`hermes-agent` v1.0.0，scripts=postinstall/install:root/install:web/install:tui/install:desktop/audit:root
- `Dockerfile`
- `docker-compose.yml`

## README 要点与注意（摘自 `README.es.md`）

- 章节：Instalación rápida、Primeros pasos、Evita la colección de claves API — Nous Portal、Referencia rápida: CLI vs Mensajería、Documentación、Migración desde OpenClaw、Contribuir、Comunidad、Licencia

## 建议阅读顺序

1. `README.es.md`

