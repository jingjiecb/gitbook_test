# 设计原则和方法

#### 交互框架

作用：提供理解或定义某种事物的一种结构。帮助人们结构化设计过程。认识设计中的主要问题。有助于定义问题所涉及的领域。

**执行、评估活动周期EEC**：最有影响力的框架。定义了活动的四个组成部分：目标，执行，客观因素，评估。目标和意图的不同在于，单个目标可对应多个意图。

EEC共有7个阶段：1-4是执行阶段，5-7是评估阶段。EEC这几个阶段可以表示用户从想进行操作到进行操作再到确认操作是否产生了自己期待的影响。

1. 形成目标
2. 形成意图
3. 明确动作
4. 执行动作
5. 感知系统状态
6. 解释系统状态
7. 评估输出

EEC模型可以解释为什么有些界面的使用存在问题。执行隔阂：用户达到目标而想执行的动作和系统允许的动作之间的差别。评估隔阂：系统状态的实际表现与用户预期之间的差别。通过对这两种隔阂的分析，可以找到如何才能使用户轻松明确哪些活动是被允许的，找到如何确定系统是否处于期望的运行状态等问题。

扩展EEC模型。

**可用性目标**：可用性目标不仅涉及人与正在发生交互作用的系统，还包括系统对使用它的人所产生的作用。包括：

1. 易学性：用户可以在较短的时间内应用系统来完成某些任务。是最基本的可用性属性。10分钟法则
2. 高效率：当用户学会使用产品之后，用户应该具有更高的生产力水平。
3. 易记性：用户在学会使用软件后应当容易记忆，能迅速回想起它的使用方法。良好的组织，使用用户已有的经验可以帮助提高易记性。
4. 少出错：保证灾难性后果的错误发生频率最低，保证错误发生后可以迅速恢复到正常状态。
5. 主观满意度：用户对系统的主观喜爱程度。某些情况下，系统的娱乐价值更重要。

**用户体验目标**：

什么是用户体验：用户在与系统交互时的感觉（根据不同的用户群体重点不同，例如为儿童创建的网站应该有趣并且引人入胜，面向年轻人的网站应该注重时尚感和趣味性），较可用性目标更主观，可用性可能对用户体验带来阻碍。

**简易可用性工程**：提高可用性为目标的先进的产品开发方法论。强调以人为中心来进行交互式产品的设计研发。借鉴了许多不同领域的方法和技术。

**可用性度量**

常用方法是选择一些能够代表目标用户群体的测试用户。让这些用户使用系统执行一组预定的任务。比较任务的执行情况。针对多维属性。度量要针对特定用户和特定任务进行。测试前要明确一组具有代表性的测试任务。、

易学性度量：用户分类，分为新手用户、熟练用户、非频繁使用用户。对非频繁使用用户进行测试最能体现系统的易记性。度量方法：对在特定长时间没有使用系统的用户进行用户测试，对用户进行记忆测试。

错误率度量：错误指的是不能实现预定目标的操作。用户执行特定任务时通过统计这种操作的次数，可以在度量其他可用性属性的同时来度量。

满意度度量：满意度度量评价都是主观的，适合询问来度量。通常在用户测试完成之后进行。

**度量关键技术**：

* 用户和任务观察：了解产品的目标用户。
* 场景：简便易行的原型工具。水平原型：减少功能深度并获得界面的表层。垂直原型：减少功能的数量而对所选功能进行完整实现。
* 边做边说：最有价值的单个可用性工程方法
* 启发式评估：让多个不同专家来进行经验性评估。5名专家可以发现80%的可用性问题。

**黄金规则**：

1. 尽可能保持一致
2. 符合普遍可用性（不同类型用户普遍觉得好用）
3. 提供信息丰富的反馈
4. 设计说明对话框以生成结束信息
5. 预防并处理错误
6. 让操作容易撤销
7. 支持内部控制点（用户成为主动者而不是响应者）
8. 减轻短时记忆负担

**十项启发式规则**：

1. 系统状态可见性（提供信息反馈）
2. 系统与现实世界的吻合（提供合理选项，不合理选项disable）
3. 用户享有控制权和自主权（可自由导航、前进后退等）
4. 一致性和标准化（设计的一致性）
5. 避免出错（日历牌避免输错日期）
6. 依赖识别而非记忆（识别图标而不是记忆命令）
7. 使用的灵活性和高效性（同时给出图形按钮和快捷键）
8. 审美感和最小化设计（行距、空白等）
9. 帮助用户识别、诊断和恢复错误（友好的错误提示）
10. 帮助和文档（详细、准确）