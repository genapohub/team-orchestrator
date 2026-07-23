# Team Orchestrator — 虚拟科技公司调度指挥官

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)

一个面向 AI 编程助手的 **调度指挥官 Skill**，管理 13 个专业 AI 角色组成的虚拟研发团队。自动分析用户意图、按需调度角色、串联上下文、追踪项目进度——一句话即可驱动全流程。

## 能力

- **智能路由**：根据用户输入自动匹配需要的角色，不必要的一个不多调
- **三种模式**：全流程跑通 / 按需组合 / 增量补充
- **上下文串联**：角色产出自动传递，无需重复交代项目背景
- **进度追踪**：记忆系统记录项目阶段和关键决策

## 管理的 13 个角色

| 角色 | Skill | 典型产出 |
|------|-------|---------|
| 产品经理 | product-plan-guide | PRD/BRD/MRD |
| 技术负责人 | tech-lead-guide | 架构设计/ADR |
| 项目管理 | project-mgmt-guide | WBS/里程碑/风险 |
| UI/UX设计师 | ux-design-guide | 交互设计/设计系统 |
| 平面设计师 | graphic-design-guide | 品牌VI/视觉资产 |
| 前端开发 | frontend-dev-guide | 组件方案/前端架构 |
| 后端开发 | backend-dev-guide | API设计/数据库 |
| 测试/QA | qa-testing-guide | 测试策略/自动化 |
| DevOps/运维 | devops-guide | CI/CD/K8s |
| 数据分析 | data-analyst-guide | 指标体系/BI看板 |
| 增长负责人 | growth-guide | 增长模型/获客矩阵 |
| 商业化负责人 | monetization-guide | 定价/销售漏斗 |
| 运营经理 | operations-guide | 用户生命周期/内容 |

## 触发热词

从0到上线、全流程、完整方案、端到端、调度、团队协作、整个项目、研发团队、虚拟团队

---

## 安装

本 Skill 遵循 **Open Agent Skills 标准**（SKILL.md 格式），兼容以下工具：

### WorkBuddy / CodeBuddy

**方式一：克隆到 skills 目录**
```bash
git clone https://github.com/genapohub/team-orchestrator.git ~/.workbuddy/skills/team-orchestrator
```

**方式二：ZIP导入**
```bash
git clone https://github.com/genapohub/team-orchestrator.git
zip -r team-orchestrator.zip team-orchestrator/
```
然后在 WorkBuddy 桌面端 → **技能市场** → **添加技能/上传技能** → **点击"跳过检测，直接安装"**。

### Trae

**ZIP 导入**
```bash
git clone https://github.com/genapohub/team-orchestrator.git
```
然后在 Trae → **设置** → **Rules & Skills** → **创建** → 上传 `team-orchestrator.zip`。

### Codex

```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/team-orchestrator.git ~/.codex/skills/team-orchestrator

# 或使用 cc switch (推荐)
git clone https://github.com/genapohub/team-orchestrator.git ~/.cc-switch/skills/team-orchestrator
```

重启 CC Switch客户端/Codex客户端 后自动发现。也可以在对话中输入 `$team-orchestrator` 手动调用。

### Cursor
```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/team-orchestrator.git ~/.cursor/skills-cursor/team-orchestrator
```

重启 Cursor客户端 后自动发现。也可以在对话中输入 `$team-orchestrator` 手动调用。

---

## 使用

```
从0到上线做一个宠物托运小程序
用户流失严重，出增长+运营+数据分析的组合方案
上次PRD基础上补个埋点和技术选型方案
给我的SaaS产品做完整的商业化方案
```

Skill 会自动分析意图，匹配需要的角色，按依赖关系编排执行。

## 许可

[MIT](LICENSE) © zhangmengbo
