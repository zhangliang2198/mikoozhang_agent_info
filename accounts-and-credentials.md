# Accounts And Credentials

## 用途

保存账号、密码、Token、API Key、私钥、证书、恢复码、二次验证方式和登录说明。这里是个人管理 Agent 查找凭据信息的主入口。

## 账号记录模板

```md
## 服务或系统名称

- 创建日期：YYYY-MM-DD
- 最后更新：YYYY-MM-DD
- 类型：网站 / App / 服务器 / 数据库 / 云服务 / 开发工具 / 其他
- 账号：
- 用户名：
- 邮箱：
- 手机号：
- 密码：
- 二次验证：
- 恢复码：
- 登录地址：
- 绑定设备：
- 用途：
- 关联项目或任务：
- 失效时间：
- 轮换规则：
- 备注：
```

## Token / Key 记录模板

```md
## Token 或 Key 名称

- 创建日期：YYYY-MM-DD
- 最后更新：YYYY-MM-DD
- 所属系统：
- 类型：Token / API Key / Secret / 私钥 / 证书 / Cookie / 其他
- 内容：
- 权限范围：
- 使用位置：
- 失效时间：
- 轮换规则：
- 关联项目：
- 备注：
```

## 使用规则

- 有过期时间的凭据同步记录到 `reminders-and-automations.md`。
- 和项目相关的凭据在 `projects.md` 中添加索引，不重复大量内容。
- 更新密码、Token 或 Key 后，必须更新“最后更新”和“轮换规则”。
