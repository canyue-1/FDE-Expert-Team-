# FDE 专家团

汇集 24 位 FDE 真实落地案例经验，覆盖制造、跨境、政务、财务等 6 大行业领域，按问题路由匹配行业专家输出 AI 落地方案。

## 类型

Team 型（多角色协作团队）

## 功能

汇集 Datawhale「FDE 100 案例集」24 位现场部署工程师（Field Deployment Engineer）的真实落地经验，按行业领域拆分为 6 位成员专家：

- **制造与工业**（fde-manufacturing）—— 经验传承、采购、物流装载、非标报价、经营透明、工程租赁
- **跨境电商与贸易**（fde-cross-border）—— 达人建联、外贸知识管理、库存广告联动、海外数据断层
- **企业数字化与组织转型**（fde-org-transform）—— 研发转型、消防维保数字化、国企 AI 落地、上市公司数智化
- **政务与公共服务**（fde-gov-public）—— 车管所 OCR+RPA、城市规划 GIS+AI
- **专业服务与内容生产**（fde-pro-service）—— 法律案件、电商素材、短视频量产、消费品包装审核
- **财务数据与工程**（fde-finance-eng）—— 央国企财务、零售对账、电信数据、建筑图纸

主理人负责路由调度，根据用户问题识别行业后调度对应领域成员，由成员基于真实案例经验输出专业判断。

两个预设 Workflow：

1. **企业 AI 落地全景诊断**：开放式问题（"不知道从哪开始"）→ 主理人初步诊断 → 调度行业专家深度方案 → 汇总统一路线图
2. **跨行业经验复用**：想借鉴其他行业经验 → 识别源行业+目标行业 → 评估可迁移性 → 输出可迁移/需调整部分

通用 FDE 方法论：四阶段 SOP（业务进场 → 经验沉淀 → 嵌入流程 → 陪跑迭代）、四大原则（业务优先/复用优先/问题即标准/进入流程）、七个核心动作（进入现场/找到真问题/小切口起步/AI 嵌入流程/人机分工/沉淀组织能力/持续陪跑）。

## 使用示例

- 我们的企业想用 AI 但不知道从哪里开始，应该怎么做？
- 制造业怎么用 AI 做经验传承和知识沉淀？
- 跨境电商如何用 AI 打通库存、补货和广告决策？

## 头像

头像已自动生成在 `avatars/` 目录下。如需替换为自定义头像，要求：

- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

将专家包目录放到专家目录下：

```
~/.workbuddy/plugins/marketplaces/my-experts/plugins/fde-expert-team/
```

然后运行注册命令使其可见：

```bash
python3 /Applications/WorkBuddy.app/Contents/Resources/app.asar.unpacked/resources/plugins/workbuddy-builtin/skills/expert-manager/scripts/register_expert.py ~/.workbuddy/plugins/marketplaces/my-experts/plugins/fde-expert-team
```

## 打包分享

```bash
python3 /Applications/WorkBuddy.app/Contents/Resources/app.asar.unpacked/resources/plugins/workbuddy-builtin/skills/expert-manager/scripts/package_expert.py ~/.workbuddy/plugins/marketplaces/my-experts/plugins/fde-expert-team
```