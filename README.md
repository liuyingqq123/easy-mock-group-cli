
Easy Mock Group CLI
---
[![npm version](https://img.shields.io/npm/v/easy-mock-group-cli.svg?style=flat-square)](https://www.npmjs.com/package/easy-mock-group-cli)
Easy Mock Group CLI 是一个基于 [Easy Mock CLI](https://github.com/easy-mock/easy-mock-cli) 的修改, 按照文件夹分组生成 `API` 调用文件的命令行工具。
如果你正在使用 Easy Mock 伪造接口数据，那一定不要错过 Easy Mock CLI。
## 原链接和说明文档
- [Documentation](https://easy-mock.github.io/easy-mock-cli/)
## 安装
```bash
npm install -g easy-mock-group-cli
```
## 使用
1. 在package.json中的scripts区域, 加入:
```json
"easymock": "easymock init"
```

2. 原配置文件.easymockrc.json中, projects配置项中只需要配置easy-mock的项目id, 例如:
```json
"id": "5c650482ba54f57d008c0ce8"
```

3. 执行:
```cmd
easymock init
```