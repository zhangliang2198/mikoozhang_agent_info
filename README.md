# mikoozhang agent info

这个仓库用于保存 Mikoo Zhang 的个人长期信息、个人管理 Agent 规则和 AI 操作指导。它的目标是让 AI 在后续协作中能快速理解用户、生活事务、任务、日程、提醒、项目、环境、偏好和已验证经验。

入口文件是 `AGENTS.md`。AI 进入这个仓库时应先读取 `AGENTS.md`，再根据任务类型查找对应主题文件。

## 文件索引

- `AGENTS.md`：总入口，说明这个记忆库的用途、写入规则和查找规则。
- `profile.md`：用户基础信息、长期稳定偏好和个人工作习惯。
- `personal-profile.md`：偏个人管理的基础信息、生活画像和长期约束。
- `ai-collaboration.md`：AI 协作方式、默认执行策略和记忆写入判断。
- `tasks.md`：个人待办、任务队列、下一步动作和任务管理规则。
- `reminders-and-automations.md`：提醒、定时任务、周期任务和自动化记录。
- `calendar-and-schedule.md`：日程、可用时间、时间偏好和安排规则。
- `goals.md`：年度、季度、月度和阶段性个人目标。
- `routines-and-habits.md`：生活习惯、固定流程和日常节奏。
- `people-and-relationships.md`：重要联系人关系和沟通偏好。
- `health-and-wellbeing.md`：健康、运动、作息、饮食等非诊疗管理信息。
- `household-and-assets.md`：家庭事务、设备资产、保修维护和证件续期提醒。
- `finance-and-subscriptions.md`：预算、账单、订阅、发票和报销提醒。
- `learning-and-growth.md`：学习计划、技能成长、阅读和课程记录。
- `environment.md`：本机环境、常用路径、工具链和系统配置。
- `projects.md`：长期维护的项目索引、技术栈、入口文件和命令。
- `coding-standards.md`：跨项目通用代码标准、测试要求和工程质量规则。
- `workflows.md`：常用工作流，例如 review、修复、构建、发布、汇报。
- `commands.md`：可复用命令集合，按用途和项目分类。
- `tools.md`：开发工具、软件、账号体系和工具偏好。
- `preferences.md`：UI、文案、沟通、交付等偏好。
- `troubleshooting.md`：已验证的问题排查记录和解决方案。
- `decisions.md`：长期技术决策记录。
- `security.md`：敏感信息处理规则和提交前安全检查。
- `private-notes.md`：个人但非高敏感的私有说明。

## 使用方式

1. 先读 `AGENTS.md`。
2. 根据任务主题读取对应 `.md` 文件。
3. 如果对话中产生了长期有用的新信息，写入对应文件。
4. 如果新增了主题文件，同时更新 `AGENTS.md` 和本文件的索引。
5. 不把密码、Token、私钥、身份证号、银行卡号、完整住址、医疗报告等高敏感内容明文提交到仓库。
