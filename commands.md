# Commands

## 用途

保存可复用命令。每条命令都应说明适用范围，避免在错误项目或错误环境中执行。

## Git

```powershell
git status --short --branch
git remote -v
git log --oneline -5
```

## PowerShell

```powershell
Get-ChildItem -Force
Get-Content -Raw -LiteralPath "path\to\file.md"
```

## 命令记录模板

````md
## 命令名称

- 日期：YYYY-MM-DD
- 适用范围：
- 命令：

```powershell
命令内容
```

- 作用：
- 风险：
- 验证方式：
````

## 注意事项

- 删除、覆盖、发布、推送类命令必须标注风险。
- 项目命令应优先记录在 `projects.md` 的对应项目下；通用命令记录在这里。
- 命令输出如果只是临时日志，不需要长期保存。
