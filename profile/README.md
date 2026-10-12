# 🎮 AI H5 Game

使用 AI 辅助设计与开发 H5 小游戏，探索解谜、消除、益智、策略与经营玩法。

我们以独立游戏项目积累实践，在统一的开发手册中沉淀玩法设计、交互规范、工程方法和验证要求，形成从灵感到可玩作品的完整流程。

## 游戏项目

按核心玩法组织项目，每款游戏独立维护源码、资源与运行说明。

### 解谜与益智

| 游戏 | 核心玩法 | 项目仓库 |
| --- | --- | --- |
| 全都吃光光！ · Eat ’Em All! | 多蛇线路规划，通过换头、吃果增长与伙伴让路清空水果 | `eat-em-all`（本地项目，仓库待发布） |
| 绝对准度 · Exact Fire | 有限弹数的角度射击，利用镜面、分裂镜与黑洞规划弹道 | [exact-fire](https://github.com/ai-h5-game/exact-fire) |
| 喵饮时光 · Purr & Pour | 旋转水管方块，绕过障碍，把清泉送到猫咪水碗 | [purr-and-pour](https://github.com/ai-h5-game/purr-and-pour) |
| 喵然入梦 | 在拼布区域内移动小猫，消除行列冲突，让它们安稳入睡 | [sleep-cat](https://github.com/ai-h5-game/sleep-cat) |
| 水之涌动 · Aqua Surge | 连接同色端点，在路径之间分配空间并填满棋盘 | [aqua-surge](https://github.com/ai-h5-game/aqua-surge) |
| 24 · Twenty Four | 组合数字与四则运算，推演得到 24 的解法 | [twenty-four](https://github.com/ai-h5-game/twenty-four) |

### 消除与图案连接

| 游戏 | 核心玩法 | 项目仓库 |
| --- | --- | --- |
| 下一个在哪？ · Where’s the Next One? | 连连看与图案收集，判断连接路径并解锁主题 | [next-one](https://github.com/ai-h5-game/next-one) |
| 迷宫消消乐：破壁者 | 将墙体与空间关系融入三消，逐步打开可操作区域 | [Wall-Breaker](https://github.com/ai-h5-game/Wall-Breaker) |

### 休闲、策略与经营

| 游戏 | 核心玩法 | 项目仓库 |
| --- | --- | --- |
| 这箱归喵！ · Purr & Pick | 在开箱与交换提议之间做取舍，完成成就并收集猫咪 | [purr-and-pick](https://github.com/ai-h5-game/purr-and-pick) |
| 水果小丑牌 | 在水果矩阵中框选区域，组合分数与倍率达到目标 | [fruit-game](https://github.com/ai-h5-game/fruit-game) |
| 森林便利店 | 从货架寻找食材，合成商品并完成动物订单 | [feeding-animals](https://github.com/ai-h5-game/feeding-animals) |

游戏源码、资源与项目文档目前为私有资料，需要对应仓库的访问权限。组织首页不列出单款游戏的试玩地址。

## 开发体系

开发遵循五个阶段，已有确认材料的项目从相应阶段开始：

**玩法设计 → 立项与主题设计 → 交互与视觉设计 → 开发 → 验收**

| 阶段 | 核心任务 | 主要交付物 |
| --- | --- | --- |
| 玩法设计 | 明确玩家动作、决策空间、核心循环与规则边界 | 玩法方案、单局推演、代表场景 |
| 立项与主题设计 | 将玩法映射到主题，确定目标设备、范围与成功标准 | 项目简报、验收目标 |
| 交互与视觉设计 | 明确页面状态、操作反馈、返回路径与素材要求 | 交互与视觉设计说明 |
| 开发 | 实现可玩的核心流程，逐步完善功能与体验 | 可玩版本、验证记录 |
| 验收 | 按需求核对实际结果，记录证据与尚未验证的内容 | 验收报告 |

### 开发资料

开发规范正文统一维护在 `ai-h5-game-hub/docs/game-dev-playbook/`，组织首页提供导航。

| 资料 | 用途 | 入口 |
| --- | --- | --- |
| 开发手册 | 查阅流程、玩法、界面、工程与验证原则 | [手册总目录](https://github.com/ai-h5-game/ai-h5-game-hub/blob/main/docs/game-dev-playbook/README.md) |
| 新游戏启动提示词 | 从灵感或已有方案进入当前阶段 | [开始一个游戏](https://github.com/ai-h5-game/ai-h5-game-hub/blob/main/docs/game-dev-playbook/START_HERE.md) |
| 提示词与模板 | 执行阶段任务并记录交付物 | [提示词](https://github.com/ai-h5-game/ai-h5-game-hub/tree/main/docs/game-dev-playbook/prompts) · [模板](https://github.com/ai-h5-game/ai-h5-game-hub/tree/main/docs/game-dev-playbook/templates) |
| 工具与技术 | 按任务选择技能，查阅适用技术栈要求 | [Skill 指南](https://github.com/ai-h5-game/ai-h5-game-hub/blob/main/docs/game-dev-playbook/skills/README.md) · [Phaser / Vite 专项](https://github.com/ai-h5-game/ai-h5-game-hub/blob/main/docs/game-dev-playbook/profiles/phaser-vite.md) |
| 游戏案例 | 查看实际项目中的设计取舍与验证证据 | [案例目录](https://github.com/ai-h5-game/ai-h5-game-hub/blob/main/docs/game-dev-playbook/examples/README.md) |
| 规范维护 | 将实践中的问题与经验整理为可验证的规则 | [维护说明](https://github.com/ai-h5-game/ai-h5-game-hub/blob/main/docs/game-dev-playbook/MAINTAINING.md) |

以上资料需要目标仓库的访问权限。案例整理进度以目录记录为准，案例内容不代表对应游戏已完成全部验收。

## 仓库分工

| 仓库 | 职责 |
| --- | --- |
| 各独立游戏仓库 | 维护游戏源码、素材、项目说明与游戏自身的验证记录 |
| [ai-h5-game-hub](https://github.com/ai-h5-game/ai-h5-game-hub) | 统一维护游戏目录、设计档案、开发手册及工作台网站 |
| [.github](https://github.com/ai-h5-game/.github) | 展示组织公共首页 |
| [.github-private](https://github.com/ai-h5-game/.github-private) | 展示组织成员首页，增加成员工作台入口 |

游戏功能问题在对应游戏仓库处理；开发规范与工作台问题在 `ai-h5-game-hub` 处理。

## 协作与授权

运行或开发已有游戏时，先查看对应仓库的 README 与项目规则。开始新游戏时，从启动提示词进入开发流程，并明确本轮范围和验收目标。

有仓库访问权限的成员可通过对应项目的 Issues 反馈问题或提出建议。问题反馈请附上设备、浏览器、复现步骤、预期结果与实际表现。

各项目源码、素材和文档的使用范围，以对应仓库的 LICENSE 或明确授权说明为准。
