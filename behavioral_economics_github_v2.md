# 行为经济学期中复习笔记

Behavioral Economics: Open-Book Exam Reference

五份课件整合｜中文讲解·英文定义·公式推导·考题检索

 **使用方式。** 先用下方“课程脉络”确定题目属于哪一种机制，再从目录或英文索引定位。各章按“标准基准—行为偏离—模型—推导—证据—答题”展开；附录给出公式速查、英文命题动词、练习与答案。关键定义后的英文句子可直接作为答题骨架，但需结合题目条件改写。

 **资料范围。** 依据潘宇航老师2026年秋季的五份课件整理，总计294个PDF页面。下文采用 L/P/R/S/B 五个简称，页码均指 **PDF实际页面** ，包含封面和分隔页，避免与课件右下角的幻灯片编号混淆。课程安排、联系方式与提交日期不作为知识重点；课件提到但尚未系统展开的后续专题，仅保留其在整体框架中的位置。

| 简称 | 原文件与主题                                        | PDF页数 |
|:-----|:----------------------------------------------------|:--------|
| L    | `BehavioralEcon_1_Logistics.pdf`：导论与应用        | 68      |
| P    | `BehavioralEcon_1_1_NSP_Present_Bias.pdf`：当下偏误 | 59      |
| R    | `BehavioralEcon_1_2_NSP_Ref_Dep(1).pdf`：参照依赖   | 56      |
| S    | `BehavioralEcon_1_3_NSP_SP(1).pdf`：社会偏好        | 59      |
| B    | `BehavioralEcon_2_NB.pdf`：非标准信念               | 52      |

<a id="course-map"></a>

## 课程脉络：从“人如何选择”到“为什么偏离”

1.   **总框架：** 选择由偏好、信念、约束和决策过程共同决定。标准模型给出基准；行为模型提供可检验的心理机制。

2.   **非标准偏好（Non-standard preferences）：** 时间维度看当下偏误；评价基准看参照依赖；人与人之间看社会偏好。

3.   **非标准信念（Non-standard beliefs）：** 高估能力、低估风险、误解小样本，以及错误预测未来偏好。

4.   **政策与证据：** 默认选项、提醒与承诺分别作用于不同障碍；用实验和数据区分机制，并检验福利影响。

 **来源与补充的边界。** 核心模型、研究案例来自课件；为自学补充的定义、证明、政策评价与练习均标为“补充”“推导”或“自拟”。课件的简化公式会说明适用条件。文献结果统一按“课件报告”呈现；本文没有将课件的所有文献与图表另作外部文献核验，也不把单项实验写成普遍定律。

## 目录导引

- [1 导论：标准基准、行为机制与证据](#chapter-1)
  - [1.1 行为经济学研究什么？](#section-1-1)
  - [1.2 标准模型的常见假设及三类偏离](#section-1-2)
  - [1.3 为什么学习和市场不一定消除偏误？](#section-1-3)
  - [1.4 复利增长偏误与退休储蓄](#section-1-4)
  - [1.5 LED、选择过载、默认与提醒](#section-1-5)
  - [1.6 如何读实验、事件研究与AI学习案例？](#section-1-6)
  - [1.7 与博弈论、政策分析的关系](#section-1-7)
- [2 当下偏误：跨期选择与自我控制](#chapter-2)
  - [2.1 指数贴现的定义、假设与时间一致性](#section-2-1)
  - [2.2 递减不耐心与准双曲贴现](#section-2-2)
  - [2.3 计划反转：投资品与享乐品的阈值](#section-2-3)
  - [2.4 天真型、成熟型与倒推](#section-2-4)
  - [2.5 参数识别与承诺工具](#section-2-5)
  - [2.6 肥料应用与政策识别](#section-2-6)
- [3 参照依赖：风险决策与前景理论](#chapter-3)
  - [3.1 彩票、期望效用及理性选择基准](#section-3-1)
  - [3.2 风险态度、Jensen不等式与初始财富](#section-3-2)
  - [3.3 确定性等价、风险溢价与保险](#section-3-3)
  - [3.4 独立性公理、确定性效应与复合彩票](#section-3-4)
  - [3.5 前景理论的四项改变](#section-3-5)
  - [3.6 价值函数：损失厌恶与敏感性递减](#section-3-6)
  - [3.7 概率加权与四重风险态度](#section-3-7)
  - [3.8 反射效应、隔离效应与禀赋效应](#section-3-8)
  - [3.9 目标收入与出租车劳动供给](#section-3-9)
- [4 社会偏好：结果、形象与意图](#chapter-4)
  - [4.1 三类社会偏好及识别思路](#section-4-1)
  - [4.2 Fehr--Schmidt：两人不平等厌恶](#section-4-2)
  - [4.3 无差异曲线与独裁者转移推导](#section-4-3)
  - [4.4 多人不平等厌恶：先比较，再平均](#section-4-4)
  - [4.5 Charness--Rabin：最差者与总收益](#section-4-5)
  - [4.6 形象效用：为什么公开会改变行为？](#section-4-6)
  - [4.7 奖励挤出：平均形象与边际激励不同](#section-4-7)
  - [4.8 意图、善意指标与互惠效用](#section-4-8)
  - [4.9 最后通牒博弈：两套阈值与识别](#section-4-9)
  - [4.10 公平均衡与白羽毛运动](#section-4-10)
- [5 非标准信念：能力、风险与未来偏好的误判](#chapter-5)
  - [5.1 理性信念、乐观与偏好信念](#section-5-1)
  - [5.2 三种过度自信：不要混淆对象](#section-5-2)
  - [5.3 过高估计：投资阈值与真实福利](#section-5-3)
  - [5.4 过度投资的比较静态与课件选择题边界](#section-5-4)
  - [5.5 过高定位：能力与比赛进入](#section-5-5)
  - [5.6 过度精确与二阶Taylor近似](#section-5-6)
  - [5.7 小数定律、代表性与赌徒谬误](#section-5-7)
  - [5.8 投射偏误：把当前状态投射到未来](#section-5-8)
  - [5.9 投射与赌徒谬误的实证案例](#section-5-9)
- [6 跨章节辨析、证据与政策的整合](#chapter-6)
  - [6.1 容易混淆的概念对照](#section-6-1)
  - [6.2 五类应用如何对应机制？](#section-6-2)
  - [6.3 一个统一的答题流程](#section-6-3)
  - [6.4 课件表述的集中校正清单](#section-6-4)
- [7 开卷速查：公式、英文术语与答题表达](#chapter-7)
  - [7.1 核心公式及调用条件](#section-7-1)
  - [7.2 符号防混淆表](#section-7-2)
  - [7.3 英文关键词索引（按字母检索）](#section-7-3)
  - [7.4 英文命题动词与答题粒度](#section-7-4)
  - [7.5 可直接改写的英文答题骨架](#section-7-5)
- [8 英文练习题与解答：计算、辨析及实验设计](#chapter-8)
  - [8.1 题1：复利、时点与增长偏误](#section-8-1)
  - [8.2 题2：三期作业、天真型与成熟型](#section-8-2)
  - [8.3 题3：当下偏误的参数识别](#section-8-3)
  - [8.4 题4：CE、风险溢价与保险](#section-8-4)
  - [8.5 题5：独立性公理](#section-8-5)
  - [8.6 题6：参照点改变与混合彩票](#section-8-6)
  - [8.7 题7：不平等厌恶与转移](#section-8-7)
  - [8.8 题8：最后通牒阈值及离散报价](#section-8-8)
  - [8.9 题9：形象模型与奖励](#section-8-9)
  - [8.10 题10：错误投资与比较静态](#section-8-10)
  - [8.11 题11：过度精确与区间覆盖](#section-8-11)
  - [8.12 题12：小样本与赌徒谬误](#section-8-12)
  - [8.13 题13：投射强度与购买阈值](#section-8-13)
  - [8.14 题14：综合机制识别与实验设计](#section-8-14)
  - [8.15 教师视角：如何把题目出得有区分度？](#section-8-15)
- [9 课件定位与文献线索](#chapter-9)
  - [9.1 五份课件的阅读回查路线](#section-9-1)
  - [9.2 文献与机制的对应（按课件引述）](#section-9-2)
  - [9.3 GitHub阅读与使用](#section-9-3)

<a id="chapter-1"></a>

## 1 导论：标准基准、行为机制与证据

<a id="section-1-1"></a>

### 1.1 行为经济学研究什么？

 **行为经济学（Behavioral economics）** 将心理学上更现实的假设纳入经济学，以改善对行为的解释、预测和福利分析。

*Behavioral economics incorporates psychologically realistic assumptions into economics to improve positive and normative analysis.*

 **实证分析（Positive analysis）** 回答“人实际上怎样行动、某项变化带来什么影响”； **规范分析（Normative analysis）** 回答“什么结果更好、应怎样设计政策”。二者不能混同：某种默认选项提高参与率，是行为结果；它是否改善福利，还要看个人利益、成本与自主性。

行为经济学仍使用最优化、效用函数、概率与均衡。区别在于模型假设如何设定。若将声誉放入效用函数，关心声誉的人仍可能是在最大化效用；若将主观概率代入预期利润，错误投资也可能是基于偏误信念的最优选择。

<a id="section-1-2"></a>

### 1.2 标准模型的常见假设及三类偏离

| 基准假设                                             | 含义                                 | 本课程对应的偏离                 |
|:-----------------------------------------------------|:-------------------------------------|:---------------------------------|
| 稳定且清晰的偏好（Stable, well-defined preferences） | 能对选项形成一致排序                 | 参照点、状态、社会环境会影响评价 |
| 指数贴现（Exponential discounting）                  | 相邻时期贴现比例恒定                 | 当下偏误、时间不一致             |
| 最终财富评价（Final-wealth evaluation）              | 根据最终财富评估得失                 | 参照依赖、损失厌恶               |
| 狭义自利（Narrow self-interest）                     | 只关心自己的物质收益                 | 公平、利他、互惠、形象           |
| 贝叶斯信息处理（Bayesian updating）                  | 用先验与信息似然一致更新信念         | 过度自信、小样本误判             |
| 充分优化（Full optimization）                        | 信息处理、注意力与执行不构成重要障碍 | 选择过载、有限注意、自控问题     |

这些是课件用于对照的常见基准，不是所有传统经济模型都必须同时采用的公理。理性本身不等于自利，风险厌恶也不等于不理性。

 **偏好（Preferences）** 描述想要什么； **信念（Beliefs）** 描述认为将发生什么； **约束（Constraints）** 描述能做什么； **决策过程（Decision process）** 描述如何处理信息和执行选择。同样的低储蓄，可以来自收入低、短期耐心不足、误判复利或忘记办理。

 **英文答题表达：** *The same observed choice may be consistent with different preferences, beliefs, or constraints. Additional variation is needed to identify the mechanism.*

 **偏好排序的基本性质（补充定义，用于展开课件“可以排序、选择一致”的含义）。**   **完备性（Completeness）** 要求任意两选项 $`A,B`$ ，至少有 $`A\succeq B`$ 或 $`B\succeq A`$ ；允许无差异。 **传递性（Transitivity）** 要求 $`A\succeq B`$ 且 $`B\succeq C`$ 时有 $`A\succeq C`$ 。

*Completeness means that any two alternatives can be compared. Transitivity means that rankings are internally consistent across comparisons.*

稳定偏好不等于所有状态下都选同一选项，条件或信息改变时排序可以合理变化。这里不将连续性等更完整的效用表示条件当作课件已展开证明的内容。

<a id="section-1-3"></a>

### 1.3 为什么学习和市场不一定消除偏误？

人更容易在高频、有明确反馈、代价较低的任务中学习。退休、婚姻、职业等选择低频且结果延迟，难以重复试错；即使知道正确答案，也可能受自控和执行障碍影响。专家懂知识，不代表没有当下偏误或注意力限制。

市场也可能迎合偏误。例如，企业可通过复杂收费或突出短期利益获利，而不一定主动纠正消费者的误判。要分析竞争是否改善结果，需要说明消费者能否识别错误、是否有纠错激励，以及企业能否利用偏误。

<a id="section-1-4"></a>

### 1.4 复利增长偏误与退休储蓄

 **指数增长偏误（Exponential growth bias）** 指低估指数或复利增长，常把乘法积累近似为线性增长。

*Exponential growth bias is the tendency to underestimate exponential growth, often by treating compound growth as approximately linear.*

单笔本金  $`PV`$ 、每期回报率  $`r`$ 、期限  $`n`$ ：

**公式（1）**

```math
FV=PV(1+r)^n.
```

 线性近似  $`PV(1+rn)`$  忽略利息产生的利息，期限长时误差显著。课件例子：

```math
100000(1.07)^{30}\approx761226,
\qquad100000(1+0.07\times30)=310000.
```

 低估约451226，即约为真实终值的59.3%。别把“低估比例”与“实际比预测高多少”的分母混淆。

每期末存入  $`C`$ ，连续  $`n`$  期的 **普通年金终值（Future value of an ordinary annuity）** 为：

**公式（2）**

```math
FV=C\sum_{k=0}^{n-1}(1+r)^k=C\frac{(1+r)^n-1}{r}.
```

 每期初存入时再乘  $`(1+r)`$ ；存款时点必须先确定。停止存款后还持有  $`m`$  期，则将已累计余额再乘  $`(1+r)^m`$ 。

课件A在25至35岁存款10年、B在35至65岁存款30年，均每年5000、年回报5%，按课件的期末存款约定：

```math
FV_A=5000\frac{1.05^{10}-1}{0.05}1.05^{30}\approx271805,
\quad FV_B=5000\frac{1.05^{30}-1}{0.05}\approx332194.
```

 A本金只有50000，B本金150000，A仍接近B，但 **本例B的终值更高** 。它说明早存有显著积累优势，不能推出“早存一定胜过晚存更多”。

<a id="section-1-5"></a>

### 1.5 LED、选择过载、默认与提醒

 **全生命周期成本（Life-cycle cost）** 同时计入购买成本与未来使用成本。LED价格较高但使用成本可能较低；只看购价可能忽视未来节约。补充计算式：

```math
NPV=-\Delta K+\sum_{t=1}^{T}\frac{\Delta S_t}{(1+r)^t}.
```

  $`\Delta K`$  为额外购置成本， $`\Delta S_t`$  为节约费用。若  $`NPV\gt 0`$  仍不购买，需要继续检查资金约束、不确定性、租住期限、注意力和当下偏误。不能看到低采用就直接判定非理性。

 **选择过载（Choice overload）** 指选项增加可能提升认知或搜索负担，从而降低购买、延迟决定或降低满意度。

*Choice overload occurs when a larger choice set creates enough cognitive or search costs to impair decision-making.*

课件的果酱实验对照24种与6种：较大菜单可能吸引更多观看者，但购买转化较低。 **关注度（Attention）与购买率（Purchase rate）是不同结果变量。** 结论不是选项越少永远越好，而是菜单收益与复杂性成本之间有权衡。

 **默认效应（Default effect）** 指未主动选择时自动执行的选项影响最终选择。 **主动加入（Opt-in）** 默认不参加，需行动才参加； **主动退出（Opt-out）** 默认参加，需行动才退出。惰性、交易成本、默认传递的推荐信号和现状参照点都可能产生默认效应。

课件器官捐赠图比较不同制度下的有效同意比例，支持默认的重要性；跨国比较本身仍可能混有文化与制度差异。不要把“同意比例”直接当作“实际捐赠率”。

 **提醒（Reminder）** 使既有意图更容易被想起； **承诺装置（Commitment device）** 约束未来选择或改变违约激励； **助推（Nudge）** 通过选择架构影响行为，同时保留选择自由且不显著改变经济激励（此处为补充定义）。自动加入但可退出常属于助推，强制储蓄并非仅仅一个默认选项。

<a id="section-1-6"></a>

### 1.6 如何读实验、事件研究与AI学习案例？

 **随机对照试验（Randomized controlled trial, RCT）** 通过随机分配处理，使各组在期望意义上可比。处理组与对照组的结果差异可用于估计干预效果，前提还包括执行、流失与溢出等方面满足要求。

课堂设备实验（L，25–26页）对照禁止设备、有限平板使用、自由使用三类政策。课件报告允许设备组考试成绩下降约0.18个标准差。 **标准差单位（Standard-deviation units）不等于GPA原始分数** ；换算必须知道对应成绩的标准差。随机的是课堂政策，首先识别政策效应，不自动等于每个实际使用者的因果效应。附近同学受干扰属于 **负外部性（Negative externality）** 。

AI案例（L，27–31页）将作业得分、完成时间与考试得分并置：课件展示作业表现提高、完成更快，同时后续考试表现下降的模式。需要区分 **任务生产率（Task productivity）** 与 **学习积累（Learning）** 。事件时间图横轴为相对首次使用AI的月份，读图需检查处理前趋势、处理后路径、置信区间与尺度。除非题目提供足够识别信息，不应仅凭图断言所有AI使用都会损害学习。

 **可重复性与复现（Reproducibility and replication）** 要求审视结论是否可在原数据重分析或新数据中重现。L第12–14页关于截止日期研究的讨论，适合作为“经典结果仍需检验”的例子；具体撤稿或文献状态按课件叙述理解，不在这里当作已独立核验的外部事实。

 **辨析与适用条件：** L第56页图源与参考文献的对应关系并不清晰，且第11页部分时间存在跨年表述问题；这些不影响核心模型，但不应作为背诵知识。L第48页的“经济学原理翻译”带有课堂幽默性质，不是正式定理。

<a id="section-1-7"></a>

### 1.7 与博弈论、政策分析的关系

博弈论（Game theory）关注策略相互依赖；行为经济学关注心理机制。二者可结合成 **行为博弈论（Behavioral game theory）** ：将公平、互惠、有限推理放入策略互动中，最后通牒博弈就是例子。

分析政策建议时遵循： **行为事实—竞争解释—识别设计—针对性干预—结果与福利** 。提高参与率不一定提高福利，降低行动成本与限制个人自由也不是同一种政策。

 **英文答题表达：** *A policy should target the diagnosed friction. Higher take-up alone does not establish a welfare improvement.*

<a id="chapter-2"></a>

## 2 当下偏误：跨期选择与自我控制

<a id="section-2-1"></a>

### 2.1 指数贴现的定义、假设与时间一致性

 **跨期选择（Intertemporal choice）** 是在不同时点发生的成本与收益之间权衡。基准模型：

<a id="equation-3"></a>

**公式（3）**

```math
U_t=\sum_{k=0}^{\infty}\delta^ku_{t+k},\qquad0\lt \delta\leq1.
```

  $`u_{t+k}`$  是该期即时效用（Instantaneous utility）， $`\delta`$  是每期贴现因子（Discount factor）。若采用离散贴现率  $`r`$ ， $`\delta=1/(1+r)`$ 。贴现因子越小，未来权重越低；贴现率越大，未来权重越低。

课件假设包括跨期可分、即时效用规则稳定、贴现不随消费本身变化及相邻期贴现比例恒定。其中跨期可分（Intertemporal separability）表示本期效用不直接依赖其他期消费，排除了模型中未另行建模的习惯和跨期互补；即时效用平稳（Stationary instantaneous utility）表示相同消费按相同规则转为即时效用；贴现独立于消费（Consumption-independent discounting）表示 $`\delta`$ 不随具体消费路径变化。 **时间一致性（Time consistency）** 指没有新信息、偏好或约束变化时，事前计划与后续最优选择一致。

*Preferences are time-consistent if the ranking of fixed future alternatives does not reverse solely because time passes.*

 **推导。** 在  $`t\lt T`$  时比较  $`T`$  获得  $`A`$  与  $`T+1`$  获得  $`B`$ ：

```math
\delta^{T-t}u(A)\gtreqless\delta^{T+1-t}u(B)
\iff u(A)\gtreqless\delta u(B).
```

 到  $`T`$  时比较仍相同。因而低  $`\delta`$  可表示不耐心，但不必引起计划反转。

课件Amy例子：当前写作业成本1， $`k`$ 天后休闲收益  $`4/3`$ ， $`\delta=0.9`$ ：

```math
\Delta U=-1+\frac{4}{3}\delta^k.
```

  $`k=1,2,3`$ 时分别为0.2、0.08、 $`-0.028`$ 。这说明收益越远越不愿付当前成本， **不是对同一固定未来安排的时间不一致证明** 。

<a id="section-2-2"></a>

### 2.2 递减不耐心与准双曲贴现

 **递减不耐心（Decreasing impatience）** 指将两个选择同时推迟后，人对额外等待往往更有耐心。Thaler的课件例子报告短期隐含年贴现率高于长期；注意跨期限比较应先统一年化口径。

 **当下偏误（Present bias）** 是赋予立即发生的成本和收益额外权重，相对于它们全部发生于未来时的评价。

*Present bias is the disproportionate weight placed on immediate costs and benefits relative to future outcomes.*

 **准双曲贴现（Quasi-hyperbolic discounting）** ：

<a id="equation-4"></a>

**公式（4）**

```math
U_t=u_t+\beta\sum_{k=1}^{\infty}\delta^ku_{t+k},
\quad0\lt \beta\leq1,\ 0\lt \delta\leq1.
```

| 时期       | 今天 |     明天      |      后天       |     三期后      |
|:-----------|:----:|:-------------:|:---------------:|:---------------:|
| 指数权重   |  1   |    $`\delta`$     |    $`\delta^2`$     |    $`\delta^3`$     |
| 准双曲权重 |  1   |  $`\beta\delta`$  |  $`\beta\delta^2`$  |  $`\beta\delta^3`$  |

 $`\beta`$ 表示现在与全部未来的额外折扣； $`\delta`$ 控制未来各期之间的耐心。 $`\beta`$ 只乘一次，两期后权重不等于  $`(\beta\delta)^2`$ 。当 $`\beta=1`$ 时回到指数贴现。

<a id="section-2-3"></a>

### 2.3 计划反转：投资品与享乐品的阈值

 **投资品（Investment good）** ：成本在实施当期、收益在下一期，例如学习、锻炼。成本 $`C`$ 、收益 $`B`$ 。在提前一期开计划时：

```math
-\beta\delta C+\beta\delta^2B\geq0
\iff C\leq\delta B.
```

 到实施日：

```math
-C+\beta\delta B\geq0
\iff C\leq\beta\delta B.
```

 所以“计划做、当天不做”的区间是：

<a id="equation-5"></a>

**公式（5）**

```math
\beta\delta B\lt C\leq\delta B.
```

 若 $`C=2,B=3,\beta=1/2,\delta=1`$ ，提前净效用为 $`1/2`$ ，当天为 $`-1/2`$ 。

 **享乐品（Leisure/temptation good）** ：当前收益 $`B`$ ，下一期成本 $`C`$ 。提前评价 $`\beta\delta(B-\delta C)`$ ，当天评价 $`B-\beta\delta C`$ 。计划不消费、当天消费可在 $`\beta\delta C\leq B\lt \delta C`$ 出现（边界取决于无差异规则）。课件冰淇淋 $`B=2,C=3,\beta=1/2,\delta=1`$ ：提前 $`-1/2`$ ，当天 $`+1/2`$ 。

 **辨析与适用条件：** “消费过多／不足”需指明比较基准，通常是长期计划或事前评价。一次不健身也可能由健康或约束改变引起，不能直接识别当下偏误。

 **英文答题表达：** *The reversal occurs because the immediate effort cost loses the extra future discount when the implementation date arrives.*

<a id="section-2-4"></a>

### 2.4 天真型、成熟型与倒推

 $`\widehat{\beta}`$ 是对未来自己 $`\beta`$ 的预测。 **成熟型（Sophisticated agent）** 正确预见未来自我控制问题； **天真型（Naïve agent）** 低估未来的当下偏误。

```math
\begin{array}{ll}
\widehat{\beta}=\beta\lt 1 &: \text{Sophisticated},\\
\beta\lt \widehat{\beta}=1 &: \text{Fully naive},\\
\beta\lt \widehat{\beta}\lt 1 &: \text{Partially naive}.
\end{array}
```

**分类对照：** Sophisticated＝成熟型；Fully naive＝完全天真型；Partially naive＝部分天真型。

*A sophisticated agent correctly anticipates future present bias, whereas a naïve agent underestimates it.*

成熟型仍有偏误，不保证完全执行长期最优计划。每期自我最优化形成一个跨期策略问题；成熟型用 **逆向归纳（Backward induction）** 求解。

 **完整例子（课件Amy，并补充成熟型求解）。**  $`t=0,1,2`$ 必须择一期完成，成本 $`1,1.5,2.5`$ ， $`\beta=0.5,\delta=1`$ 。无其他收益差异。

1.  第0期有承诺：比较 $`-1,-0.75,-1.25`$ ，锁定第1期。

2.  无承诺，第1期：立即 $`-1.5`$ ，等到第2期 $`-1.25`$ ，故拖延。

3.  完全天真型第0期预期未来自己会选第1期，故等待，实际最终第2期完成。

4.  成熟型预见等待会导致第2期，因此第0期比较 $`-1`$ 与 $`-1.25`$ ，选择立即做。

 **承诺价值补充。** 对成熟型，第0期锁定第1期比无承诺立即做提高效用 $`0.25`$ 。若承诺费用 $`k`$ 在第0期支付，且货币效用线性，则最高愿付 $`k=0.25`$ ；若费用未来支付，须再乘相应贴现权重。

<a id="section-2-5"></a>

### 2.5 参数识别与承诺工具

选择“300天后的1块巧克力／301天后的2块”主要约束长期耐心；选择“今天1块／明天2块”还含当下偏误。需要多次选择、效用或奖励尺度假设，才能识别参数； **一个二元选择通常只给不等式或区间，不直接精确估出 $`\beta,\delta`$ ** 。预测未来选择再与实际比较，才涉及 $`\widehat{\beta}`$ 。

承诺可通过提前锁定行动、限制撤回或改变违约成本起作用。公开目标还可能同时引入社会形象；提醒主要解决遗忘；普通奖励虽改变激励，但不必自动构成自愿承诺。

<a id="section-2-6"></a>

### 2.6 肥料应用与政策识别

课件Duflo等（2011）案例：肯尼亚肥料回报较高但采用低。当前购买的出行或心理固定成本虽小，仍可能诱发拖延。SAFI在收获后有现金时提供按正常价格预购、未来免费配送。

实验对照包括收获后免费配送、可事前选择时机、较晚免费配送、较晚50%补贴与对照组。结果变量是 **实际使用率（Fertilizer use/adoption）** ，不是只看购买。课件柱图依次约为对照28%、基本SAFI 38%、可选时机SAFI 47%、晚配送33%、晚补贴41%；应按图中处理标签理解，而非认为一切免费配送都等效。课件模型校准约69%存在当下偏误， **这是模型依赖的估计，不是直接观察到的个人属性比例** 。

政策要点是时机与微小行动成本可能重要；补贴、承诺、现金管理与交易便利等机制须结合设计区分。

 **英文答题表达：** *A small, well-timed intervention can be effective when procrastination or transaction costs prevent intended purchases. This does not rule out liquidity constraints.*

<a id="chapter-3"></a>

## 3 参照依赖：风险决策与前景理论

<a id="section-3-1"></a>

### 3.1 彩票、期望效用及理性选择基准

 **彩票或风险前景（Lottery / risky prospect）** 由可能结果及其概率组成： $`L=(x_1,p_1;\ldots;x_n,p_n)`$ ， $`p_i\geq0`$ 且 $`\sum_i p_i=1`$ 。期望收益 $`\mathbb{E}[X]=\sum_i p_ix_i`$ 是货币平均值； **期望效用理论（Expected utility theory, EUT）** 按效用的概率加权平均排序：

<a id="equation-6"></a>

**公式（6）**

```math
\mathrm{EU}(L;w_0)=\sum_i p_i u(w_0+x_i).
```

*Expected utility theory evaluates a lottery by the probability-weighted average of utility over final outcomes.*

 $`w_0`$ 是初始财富。考试先判断 $`x_i`$ 是净变化还是最终财富；若已给最终财富，不能再加一次 $`w_0`$ 。 **只有线性效用时，期望货币收益的排序才等于期望效用排序。**

<a id="section-3-2"></a>

### 3.2 风险态度、Jensen不等式与初始财富

 **风险厌恶（Risk aversion）** 表示偏好确定的期望财富而非同均值彩票： $`u(\mathbb{E}[W])\geq\mathbb{E}[u(W)]`$ 。EUT下、在相关定义域上凹效用对应风险厌恶；严格凹且非退化风险时通常严格不等。

*A risk-averse individual weakly prefers a certain payoff equal to the lottery’s expected value to the lottery itself.*

 **Jensen不等式（Jensen’s inequality）** ：凹函数 $`u`$ 满足 $`\mathbb{E}[u(W)]\leq u(\mathbb{E}[W])`$ 。凸函数不等号相反。

| 曲率    | 风险态度                   | 例子与定义域                         |
|:--------|:---------------------------|:-------------------------------------|
|  $`u''\lt 0`$  | Risk averse                |  $`\sqrt{W}`$ ， $`W\gt 0`$                      |
|  $`u''=0`$  | Risk neutral               |  $`u(W)=W`$                              |
|  $`u''\gt 0`$  | Risk loving / risk seeking |  $`u(W)=W^2`$ ，通常取 $`W\geq0`$ 以保持递增 |

初始财富改变相关区间上的曲率与风险承受，不代表富人必定更爱风险。补充的 **绝对风险厌恶（Absolute risk aversion）** 指标：

```math
A(W)=-\frac{u''(W)}{u'(W)}.
```

 平方根效用有 $`A(W)=1/(2W)`$ ，财富上升时下降。这能解释本课例子，但不是所有效用函数都具有同样财富效应。不同人的效用数值不能未经归一化直接比较幸福大小。

<a id="section-3-3"></a>

### 3.3 确定性等价、风险溢价与保险

 **确定性等价（Certainty equivalent, CE）** 是使个人与彩票无差异的确定净收益：

<a id="equation-7"></a>

**公式（7）**

```math
u(w_0+\mathrm{CE})=\mathrm{EU}(L;w_0).
```

*The certainty equivalent is the sure payoff that makes the decision-maker indifferent between receiving it and facing the lottery.*

 **风险溢价（Risk premium）** 为期望收益与确定性等价之差：

<a id="equation-8"></a>

**公式（8）**

```math
\mathrm{RP}=\mathbb{E}[X]-\mathrm{CE}.
```

 风险厌恶者 $`\mathrm{RP}\geq0`$ ，风险中性为0，风险偏好者可小于0。

课件例子： $`w_0=0`$ ，等概率得100或0， $`u(x)=\sqrt{x}`$ 。 $`\mathrm{EU}=5`$ ， $`\mathrm{CE}=25`$ ， $`\mathrm{RP}=25`$ 。不是“EU=5元”，EU是效用单位。

 **保险补充推导。** 初始财富 $`W`$ ，损失 $`D`$ 以概率 $`p`$ 发生，完全保险费 $`P`$ 。最高愿付保险费满足：

```math
u(W-P_{\max})=(1-p)u(W)+pu(W-D).
```

 令未保险最终财富的确定性等价为 $`W_{CE}`$ ，则 $`P_{\max}=W-W_{CE}=pD+\mathrm{RP}`$ 。因此最高保费通常包含期望损失与风险溢价，不能把总保费直接称作风险溢价。

<a id="section-3-4"></a>

### 3.4 独立性公理、确定性效应与复合彩票

 **独立性公理（Independence axiom）** ：给两种彩票加入相同概率的共同彩票，不改变原排序。若 $`A\succeq B`$ ，则对 $`0\lt q\lt 1`$ ：

```math
qA+(1-q)C\succeq qB+(1-q)C.
```

*Mixing two lotteries with the same third lottery in the same proportion should preserve their preference ranking.*

EUT证明：两边期望效用之差等于 $`q[\mathrm{EU}(A)-\mathrm{EU}(B)]`$ ，符号不变。

 **课件数字推导。** 设 $`u(0)=0`$ 。在 $`80\%`$ 得4000与确定3000中选后者，意味着 $`u(3000)\gt 0.8u(4000)`$ ；在 $`20\%`$ 得4000与 $`25\%`$ 得3000中选前者，意味着 $`0.8u(4000)\gt u(3000)`$ 。严格偏好同时成立与EUT不相容。

 **确定性效应（Certainty effect）** 是从“很可能”到“确定”的变化受到特别重视。

*The certainty effect is the disproportionate influence of certainty relative to merely probable outcomes.*

单独偏好确定3000并不违背EUT；与另一组选择合起来才能给出矛盾。

 **复合彩票约简（Reduction of compound lotteries）** 把多阶段随机过程按最终概率合并。例如25%进入第二阶段，第二阶段80%得4000，最终得4000概率20%。若在第二阶段选择确定3000，最终得3000概率25%。EUT依赖最终分布，故相同最终分布应等价。

 **辨析与适用条件：** 约简原则与独立性公理在标准EUT中共同起作用，但不是无条件同义词。两阶段呈现导致不同选择还涉及隔离效应、框架和约简违反，不宜全都只称为“小概率高估”。

<a id="section-3-5"></a>

### 3.5 前景理论的四项改变

 **前景理论（Prospect theory, PT）** 以参照点附近的得失价值与决策权重刻画风险选择。课件四项特征为参照依赖、损失厌恶、敏感性递减、概率加权。

<a id="equation-9"></a>

**公式（9）**

```math
\Delta_i=w_0+x_i-r,\qquad
V(L)=\sum_i w(p_i)v(\Delta_i)\quad\text{(simplified model)}.
```

  **参照依赖（Reference dependence）** ：同一最终结果，因参照点 $`r`$ 不同，被编码成不同的收益或损失。

*Reference dependence means that outcomes are evaluated as gains or losses relative to a reference point rather than solely as final wealth.*

 $`r`$ 可由现状、预期或目标形成。最终得100，原预期0时为收益100，原预期200时为损失100；先算 $`\Delta`$ ，再选分支。

<a id="section-3-6"></a>

### 3.6 价值函数：损失厌恶与敏感性递减

课件分段幂函数：

<a id="equation-10"></a>

**公式（10）**

```math
v(\Delta)=\begin{cases}
\Delta^{\alpha},&\Delta\geq0,\\
-\lambda(-\Delta)^{\beta},&\Delta\lt 0,
\end{cases}\quad0\lt \alpha,\beta\leq1,\ \lambda\gt 1.
```

  **损失厌恶（Loss aversion）** ：可比规模损失的负面影响大于收益的正面影响。

*Loss aversion means that losses loom larger than comparable gains relative to a reference point.*

若两侧指数相同为 $`a`$ ， $`\vert v(-x)\vert /v(x)=\lambda`$ ；若不同，该比值是 $`\lambda x^{\beta-\alpha}`$ ，不宜把任意金额下的比率都说成 $`\lambda`$ 。

 **敏感性递减（Diminishing sensitivity）** ：离参照点越远，相同增量的价值变化通常越小。

*Diminishing sensitivity means that a fixed change has a smaller impact as outcomes move farther from the reference point.*

收益侧 $`0\lt \alpha\lt 1`$ 时： $`v'=\alpha\Delta^{\alpha-1}\gt 0`$ ， $`v''=\alpha(\alpha-1)\Delta^{\alpha-2}\lt 0`$ 。 损失侧 $`0\lt \beta\lt 1`$ 时：

```math
v'=\lambda\beta(-\Delta)^{\beta-1}\gt 0,\quad
v''=\lambda\beta(1-\beta)(-\Delta)^{\beta-2}\gt 0.
```

 所以收益侧凹、损失侧凸；指数为1时对应部分线性。风险态度还受概率权重影响，不能由曲率一项决定全部彩票排序。

 **混合彩票例题。** 收益侧 $`v(x)=x`$ ，损失侧 $`v(x)=2x`$ （ $`x\lt 0`$ ）， $`w(p)=p`$ 。等概率赢100或输100的价值为 $`50-100=-50`$ ，不接受。若赢 $`G`$ 、输100，接受要求 $`0.5G-100\geq0`$ ，所以 $`G\geq200`$ 。

<a id="section-3-7"></a>

### 3.7 概率加权与四重风险态度

 **小概率过度加权（Overweighting small probabilities）** ：小概率事件的决策权重高于客观概率， $`w(p)\gt p`$ 。这可以发生在个人准确知道客观概率时。

*Overweighting small probabilities means assigning small-probability outcomes more decision weight than their objective probabilities warrant.*

典型逆S形（Inverse-S-shaped）权重在较大但非1的概率区间低于45度线，且 $`w(0)=0,w(1)=1`$ 。课件函数：

```math
w(p)=\frac{p^{\gamma}}{\left[p^{\gamma}+(1-p)^{\gamma}\right]^{1/\gamma}},
\quad\gamma^+\approx0.61,\quad\gamma^-\approx0.69.
```

 参数为课件所引估计，不是每个人共同常数。一般 $`w(p)+w(1-p)\neq1`$ ；它不必构成一个新的主观概率分布。

|                            | 收益（Gains）        | 损失（Losses）           |
|:---------------------------|:---------------------|:-------------------------|
| 高概率（High probability） | 风险厌恶：锁定收益   | 风险偏好：赌一把逃避损失 |
| 小概率（Low probability）  | 风险偏好：彩票吸引力 | 风险厌恶：为灾难风险投保 |

这是 **四重风险态度（Fourfold pattern of risk attitudes）** 的典型模式，不是逐人逐题必然成立的定理。保险的关键解释是 **小概率损失被过度加权** ，不宜笼统归为“高概率低估”。

 **辨析与适用条件：** 完整累积前景理论（Cumulative prospect theory）使用排序后的累积概率构造权重；多结果彩票不能总是将每个概率独立替换为 $`w(p_i)`$ 。考试按题目明确给定的简化模型计算。PT并非只要 $`\lambda=1,w(p)=p,r=w_0`$ 就自动等同任意最终财富EUT；还要使价值函数与最终财富效用的表达相容。线性价值函数是不含这一困难的特殊情况。

<a id="section-3-8"></a>

### 3.8 反射效应、隔离效应与禀赋效应

 **反射效应（Reflection effect）** 指把收益彩票换成对应损失后，典型风险偏好方向反转。例如确定得500优于等概率得1000或0，但等概率损失1000或0优于确定损失500。

*The reflection effect is a reversal of risk preferences when gains are replaced by corresponding losses.*

它不同于损失厌恶：前者比较风险选择，后者比较同等收益与损失的价值强度。

 **隔离效应（Isolation effect）** ：评价选项时忽略共同部分，只关注差异部分，从而使等价描述改变选择（补充术语，用于理解R第38–40页）。若题目要求只用课件术语，可围绕两阶段呈现与确定性效应解释。

 **禀赋效应（Endowment effect）** 指拥有物品后，放弃物品所需补偿通常高于尚未拥有时的支付意愿。 **支付意愿（Willingness to pay, WTP）** 与 **接受补偿意愿（Willingness to accept, WTA）** 分别对应取得与放弃。

*The endowment effect is the tendency to value a good more highly when one owns it, often reflected in WTA exceeding WTP.*

所有权可能改变参照点，使放弃编码为损失。但课件将 $`v_{gain}(p)`$ 与 $`\vert v_{loss}(p)\vert`$ 直接当成货币支付意愿、推断 $`WTA/WTP\approx\lambda`$ ，只提供直觉。严格求WTP/WTA需建立物品与货币的联合效用并解无差异条件；效用数值不直接等于元数。

<a id="section-3-9"></a>

### 3.9 目标收入与出租车劳动供给

课件Camerer等（1997）案例：部分司机高时薪时早收工，低时薪时多工作。 **目标收入（Income targeting）** 把日收入目标作为参照点。最简单规则 $`wh=\bar{Y}`$ ，推得：

```math
h=\bar{Y}/w,\qquad\frac{dh}{dw}=-\bar{Y}/w^2\lt 0.
```

 该规则是解释性简化，并非完整最优化模型。标准劳动供给中替代效应促使多工作，收入效应可能减少工时，净效应不必总为正；时薪若由收入除以工时构造也可能存在机械相关。因此负相关支持研究动机，但不足以单独证明参照依赖。

 **英文答题表达：** *An income target can act as a reference point: higher hourly earnings allow the target to be reached sooner. However, a negative wage-hours correlation alone does not identify reference dependence.*

<a id="chapter-4"></a>

## 4 社会偏好：结果、形象与意图

<a id="section-4-1"></a>

### 4.1 三类社会偏好及识别思路

 **社会偏好（Social preferences）** 指效用受他人结果、社会评价或互动意图影响。

*Social preferences make choices depend on others’ payoffs, social image, or perceived intentions in addition to own material outcomes.*

| 类型                      | 核心评价对象             | 实验识别方向               |
|:--------------------------|:-------------------------|:---------------------------|
| 结果型（Outcome-based）   | 最终收益、差距、总福利   | 改变收益分配               |
| 形象型（Image-based）     | 别人或自己如何评价行为   | 改变可见性、匿名性与归因   |
| 意图型（Intention-based） | 对方为何选择这样对待自己 | 相同结果、改变对方替代选项 |

单次捐款或拒绝报价不能唯一识别动机。 **利他（Altruism）** 关心他人福利； **温暖光辉（Warm glow）** 是行动本身带来的内在满足； **自我形象（Self-image）** 维护自己的身份判断； **社会形象（Social image）** 在意他人评价。四者可同时存在。

<a id="section-4-2"></a>

### 4.2 Fehr–Schmidt：两人不平等厌恶

 **不平等厌恶（Inequality aversion）** 是对自己与他人的收益差距感到不适，区分劣势与优势。

*Inequality aversion is a dislike of payoff differences, with potentially different weights on disadvantageous and advantageous inequality.*

<a id="equation-11"></a>

**公式（11）**

```math
U_i=\pi_i-\alpha_i\max\{\pi_j-\pi_i,0\}
-\beta_i\max\{\pi_i-\pi_j,0\}.
```

  $`\alpha_i\geq0`$ ， $`0\leq\beta_i\lt 1`$ ，通常 $`\alpha_i\geq\beta_i`$ 。 $`\alpha`$ 为 **劣势不平等厌恶（Disadvantageous inequality aversion）** ； $`\beta`$ 为 **优势不平等厌恶（Advantageous inequality aversion）** 。两人一次比较中两种正差距不会同时大于0。

```math
U_i=\begin{cases}
(1+\alpha_i)\pi_i-\alpha_i\pi_j,&\pi_i\lt \pi_j,\\
(1-\beta_i)\pi_i+\beta_i\pi_j,&\pi_i\geq\pi_j.
\end{cases}
```

 固定自己收益，自己落后时对方增加1使效用下降 $`\alpha`$ ；自己领先时对方增加1使效用上升 $`\beta`$ （未跨越平等点）。 $`\beta\lt 1`$ 使领先时 $`\partial U_i/\partial\pi_i=1-\beta\gt 0`$ ，防止只为减少优势差距而偏好直接销毁自己的钱。

例：自己8、他人10， $`\alpha=0.5`$ ， $`U=7`$ ；自己10、他人8， $`\beta=0.2`$ ， $`U=9.6`$ ；同得9， $`U=9`$ 。后者未必更喜欢平分，因为自己的物质收益也变化了。

<a id="section-4-3"></a>

### 4.3 无差异曲线与独裁者转移推导

横轴 $`\pi_i`$ 、纵轴 $`\pi_j`$ 。落后区 $`\pi_j\gt \pi_i`$ 中：

```math
\left.\frac{d\pi_j}{d\pi_i}\right\vert _{U}=\frac{1+\alpha}{\alpha}\gt 0.
```

 领先区 $`\pi_j\lt \pi_i`$ 中：

```math
\left.\frac{d\pi_j}{d\pi_i}\right\vert _{U}=-\frac{1-\beta}{\beta}\lt 0.
```

 参数为0时相应部分垂直。纯自利曲线垂直；一般利他曲线向右下；恶意／嫉妒曲线可向右上。曲线方向必须结合坐标定义解释。

 **补充推导：独裁者博弈（Dictator game）。** 自己有 $`M`$ ，给他人 $`t`$ 且1:1转移。在 $`t\leq M/2`$ ：

```math
U_i=M-t-\beta(M-2t)=M(1-\beta)+(2\beta-1)t.
```

 在 $`t\geq M/2`$ ： $`U_i=M(1+\alpha)-(1+2\alpha)t`$ ，严格递减。所以 $`\beta\lt 1/2`$ 时给0； $`\beta\gt 1/2`$ 时给 $`M/2`$ ； $`\beta=1/2`$ 时 $`[0,M/2]`$ 无差异。 **不平等厌恶不等于一定平分。**

<a id="section-4-4"></a>

### 4.4 多人不平等厌恶：先比较，再平均

<a id="equation-12"></a>

**公式（12）**

```math
\begin{aligned}
U_i=\pi_i&-\frac{\bar{\alpha}_i}{n-1}\sum_{j\neq i}\max\{\pi_j-\pi_i,0\}\\
&-\frac{\bar{\beta}_i}{n-1}\sum_{j\neq i}\max\{\pi_i-\pi_j,0\}.
\end{aligned}
```

 不能先将他人收入平均，再与自己比较。课件 $`(10,15,20)`$ 、 $`\bar{\alpha}=0.6,\bar{\beta}=0.2`$ ：

```math
U_1=10-0.6(15/2)=5.5,\quad
U_2=15-0.6(5/2)-0.2(5/2)=13,
```

```math
U_3=20-0.2(15/2)=18.5.
```

 中间者同时落后于一人、领先于另一人，两种成本可同时存在，即使他人平均收入与自己相同。

<a id="section-4-5"></a>

### 4.5 Charness–Rabin：最差者与总收益

课件简化的 **社会福利偏好（Social-welfare preferences）** ：

<a id="equation-13"></a>

**公式（13）**

```math
U_i=(1-\lambda_i)\pi_i+\lambda_i\left[\delta_i\min_j\pi_j+(1-\delta_i)\Pi\right],
\quad\Pi=\sum_j\pi_j.
```

 通常 $`\lambda,\delta\in[0,1]`$ 。 $`\lambda`$ 为社会福利相对自己收益的权重， $`\delta`$ 为社会福利内部最差者相对总收益的权重。

*The model trades off own payoff, the payoff of the least well-off, and total surplus.*

 $`\lambda=0`$ 为自利； $`\lambda=1,\delta=1`$ 只看最低收益； $`\lambda=1,\delta=0`$ 只看总收益。总收益包含自己，不能把 $`\lambda`$ 直接等同“只关心别人”的比例。

课件 $`\lambda=0.4,\delta=0.5`$ ，对玩家1比较 $`A=(10,10)`$ 与 $`B=(11,5)`$ ：

```math
U_1(A)=0.6(10)+0.4[0.5(10)+0.5(20)]=12,
```

```math
U_1(B)=0.6(11)+0.4[0.5(5)+0.5(16)]=10.8.
```

 因此牺牲自己1，换来最差者与总收益的改善。

 **辨析与适用条件：** 在参数非负下，固定自己收益而提高他人收益不会降低此简化模型效用；FS模型在自己落后时可能降低效用。这是区分效率关切与差距厌恶的重要思路。完整Charness–Rabin模型还含互惠成分。

<a id="section-4-6"></a>

### 4.6 形象效用：为什么公开会改变行为？

简单式 $`U_i=\pi_i+\theta S(a_i)`$ ， $`S`$ 为行动形成的声誉。详细式：

<a id="equation-14"></a>

**公式（14）**

```math
U_i(a;\tau)=b(a)+r(\tau)a+ya-c(a)+q\theta S(\mu(a,y)).
```

  $`b`$ 、 $`c`$ 是直接收益与成本； $`r(\tau)`$ 是类型决定的内在动机（Intrinsic motivation）； $`ya`$ 为外部金钱激励（Extrinsic monetary incentive）； $`q`$ 是可见概率； $`\theta`$ 是形象权重； $`\mu(a,y)`$ 是观察者对类型的推断。

*Social-image utility depends on what an action reveals about the actor, not only on the action itself.*

同做两小时志愿服务，无偿与有报酬可能传递不同信号，所以用 $`S(\mu(a,y))`$ 而非只用 $`S(a)`$ 。匿名 $`q=0`$ 消除外部观察项，但内在满足、自我形象不必消失。

若存在内部最优，求导得到：

```math
U_a=b'(a)+r(\tau)+y-c'(a)+q\theta S'(\mu)\mu_a=0.
```

 在 $`U_{aa}\lt 0`$ 且 $`S'\mu_a\gt 0`$ 时，隐函数法给出：

```math
\frac{da^*}{dq}=-\frac{\theta S'\mu_a}{U_{aa}}\gt 0.
```

 同理增加 $`\theta`$ 可提高行动。若行动带来负面评价、信号规则内生变化或出现边界解，则不能直接套结论。

<a id="section-4-7"></a>

### 4.7 奖励挤出：平均形象与边际激励不同

 **外部激励挤出（Crowding out by extrinsic incentives）** 指奖励削弱其他动机，可能部分或完全抵消其直接激励。

*Extrinsic rewards may crowd out prosocial behavior when they weaken the reputational or intrinsic incentive to act.*

课件渠道为动机归因： $`y`$ 提高物质收益，但可能使给定行动更像逐利。令 $`G(a,y)=S(\mu(a,y))`$ ，则：

```math
\frac{da^*}{dy}=-\frac{1+q\theta G_{ay}}{U_{aa}}.
```

 在凹性下，若 $`1+q\theta G_{ay}\lt 0`$ ，奖励反而降低行动。 **仅有 $`G_y\lt 0`$ 不够** ：如果奖励让所有行动的声誉同减一个常数，不改变行动间差异，最优行动可不变。

离散例：行动成本5，内在收益2，无奖励时形象收益4，净收益1；加1元奖励后形象收益降至1，净收益 $`2+1+1-5=-1`$ ，行为停止。这里默认不行动的效用基准不变。 课件献血例子同时给出部分人群被挤出与现场奖励增加献血的研究，故不能背成“给钱必然有害”。

<a id="section-4-8"></a>

### 4.8 意图、善意指标与互惠效用

 **互惠（Reciprocity）** ：根据对方表现出的善意或恶意，回报或惩罚对方。

*Reciprocity is the tendency to reward perceived kindness and punish perceived unkindness.*

课件的简化模型：

<a id="equation-15"></a>

**公式（15）**

```math
U_i(a_i,a_j)=\pi_i(a_i,a_j)+f_i(a_j)\pi_j(a_i,a_j).
```

 此处 $`f_i`$ 表示 $`i`$ 感受到 $`j`$ 的善意，不是 $`i`$ 给 $`j`$ 的善意。给定 $`f_i`$ ，对方收益的边际权重即 $`f_i`$ 。

<a id="equation-16"></a>

**公式（16）**

```math
f_i=\frac{\pi_i-\frac{1}{2}(\pi_i^{\max}+\pi_i^{\min})}{\pi_i^{\max}-\pi_i^{\min}}.
```

 最高、最低收益表示对方本可给予自己的待遇，平均数是课件简化公平基准。当分母正、实际收益在区间内时， $`f_i\in[-1/2,1/2]`$ 。无可选差异时不能除以0，须另设约定。

同给2：若可给0到10，则 $`f=(2-5)/10=-0.3`$ ；若可给0到2，则 $`f=(2-1)/2=0.5`$ 。 **同一收益，不同选择空间，代表不同意图。**

 $`f=-0.3`$ 时，花 $`c`$ 使对方损失 $`D`$ 的效用变化 $`-c+0.3D`$ ；愿惩罚条件 $`\vert f\vert D\geq c`$ 。正 $`f`$ 时花 $`c`$ 使对方增收 $`D`$ ，条件 $`fD\geq c`$ 。假设该反应不重新改变对先前行动的善意评价。

<a id="section-4-9"></a>

### 4.9 最后通牒博弈：两套阈值与识别

 **最后通牒博弈（Ultimatum game）** ：提议者分总额 $`M`$ ，回应者接受则执行、拒绝则双方0。纯自利回应者接受任意正报价，零报价无差异。

课件 $`M=10`$ 、给回应者 $`x`$ ， $`f_2=(x-5)/10`$ 。接受效用：

```math
U_2^{acc}=x+\frac{x-5}{10}(10-x)=-\frac{x^2}{10}+\frac{5}{2}x-5,
\quad U_2^{rej}=0.
```

 解 $`U^{acc}\geq0`$ ：

```math
x^2-25x+50\leq0,\quad x=\frac{25\pm5\sqrt{17}}{2}.
```

 结合 $`0\leq x\leq10`$ ：

<a id="equation-17"></a>

**公式（17）**

```math
x\geq(25-5\sqrt{17})/2\approx2.192.
```

  $`x=2`$ 时 $`U=-0.4`$ ，拒绝； $`x=7`$ 时 $`U=7.6`$ ，接受。无差异处需约定接受；离散报价时按最小报价单位向上取整。

 **FS回应者。**  $`x\leq M/2`$ 时 $`U^{acc}=x-\alpha(M-2x)`$ ，得到：

<a id="equation-18"></a>

**公式（18）**

```math
x\geq\frac{M\alpha}{1+2\alpha}.
```

  $`x\geq M/2`$ 部分因 $`\beta\lt 1`$ 也会接受。 $`M=10,\alpha=0.5`$ 门槛2.5。由此， **拒绝低报价本身不能区分不平等厌恶和互惠** 。

 **迷你最后通牒（Mini-ultimatum）。** 课件Falk等（2003）保持实际分配 $`(8,2)`$ 相同，只改变另一可选方案，拒绝率： $`(5,5)`$ 为44.4%、 $`(2,8)`$ 为26.7%、无不同选择 $`(8,2)`$ 为18.0%、 $`(10,0)`$ 为8.9%。固定参数、仅看最终分配的模型无法直接解释这一系统差异。

 **英文答题表达：** *Holding the realized allocation fixed while varying the proposer’s alternatives isolates the role of perceived intentions more clearly than the standard ultimatum game.*

<a id="section-4-10"></a>

### 4.10 公平均衡与白羽毛运动

 **公平均衡（Fairness equilibrium）** 是一种心理博弈均衡，策略为最优回应，且关于行动的一阶信念与关于他人信念的二阶信念相互一致。

*A fairness equilibrium combines best responses with mutually consistent beliefs about strategies and perceived kindness.*

相互友善与相互敌视都可能成立；“公平”不表示结果必然平等或福利高。

课件另列Rabin原式 $`U_i=\pi_i+\widetilde{f}_j(1+f_i)`$ ，这里 $`f_i`$ 又指自己对他人的善意，记号与式[（15）](#equation-15)不同；不能不加说明混用。原式与课件简化式也不具有相同尺度性质。双方收益同乘 $`k`$ 且 $`f`$ 不变，简化式整体同乘 $`k`$ ，排序不变，故不能仅由简化式推出“小赌注下公平更重要”。

白羽毛运动（White Feather Campaign）通过公开羞辱未参军男子，提高不参军的社会形象成本。课件Becker案例的事件为报纸首次提及当地活动。课件报告事件后10天相对前10天参军提高36.6%，绝对约0.06个百分点，外推约33000人。相对百分比、百分点与外推人数必须分开，事件前平稳有助识别，但不单独证明全部因果条件成立。

<a id="chapter-5"></a>

## 5 非标准信念：能力、风险与未来偏好的误判

<a id="section-5-1"></a>

### 5.1 理性信念、乐观与偏好信念

 **信念（Beliefs）** 是对不确定事件的主观概率。 **理性预期（Rational expectations）** 在课件中指信念与真实分布一致、不存在可预测的系统错误；它不意味着每一次预测都正确。

*Rational expectations allow forecast errors, but these errors are not systematically predictable given the available information.*

 **非标准信念（Non-standard beliefs）** 表示系统性而非仅随机的误判。

个人可能从相信自己健康或有能力中得到心理满足，形成 **信念效用（Utility from beliefs）** 或动机性乐观。信念带来即时安慰与错误行动的成本可以同时存在；不能因为错误信念让人开心，就断定它提高总体福利。

 **补充：贝叶斯基准。** 先验 $`P(H)`$ ，新证据 $`E`$ ，更新为：

```math
P(H\mid E)=\frac{P(E\mid H)P(H)}{P(E\mid H)P(H)+P(E\mid\neg H)P(\neg H)}.
```

 此公式用于理解“Bayesian information processor”的基准，五份课件没有把完整贝叶斯计算作为独立章节系统展开。

<a id="section-5-2"></a>

### 5.2 三种过度自信：不要混淆对象

 **过度自信（Overconfidence）** 包括绝对表现、相对排名、不确定性三种不同偏差。

| 术语                       | 定义与英文句式                                                                             | 例子                               |
|:---------------------------|:-------------------------------------------------------------------------------------------|:-----------------------------------|
| 过高估计（Overestimation） | Overestimating one’s absolute ability, performance, or probability of success.             | 实际预期70分，却自信能得90分       |
| 过高定位（Overplacement）  | Believing that one ranks higher relative to others than one actually does.                 | 实际中游，却自认前10%              |
| 过度精确（Overprecision）  | Being excessively certain about beliefs, often reflected in intervals that are too narrow. | 均值预测正确，却把波动范围设得过窄 |

只说“很自信”不足以分类，要指出信念错在均值、排名还是方差。

<a id="section-5-3"></a>

### 5.3 过高估计：投资阈值与真实福利

按课件实际期望利润式解释：投资时无论结果均支付成本 $`C`$ ，成功以概率 $`p`$ 获得总收入 $`R`$ ，失败收入0；不投收益0。主观概率 $`\widetilde{p}=p+\delta`$ ， $`\delta\gt 0`$ 且概率须不超过1。

```math
\Pi^{true}=pR-C,\qquad\Pi^{belief}=(p+\delta)R-C.
```

 理性投资要求 $`p\geq C/R`$ ，偏误者投资要求 $`p+\delta\geq C/R`$ 。

<a id="equation-19"></a>

**公式（19）**

```math
p \lt \frac{C}{R} \leq p+\delta
```

 是 **过度投资区间（Overinvestment region）** 。错误投资的期望福利损失为 $`L=C-pR\gt 0`$ ，不是每次实际损失都恰好等于 $`L`$ 。

 **英文答题表达：** *The agent invests because perceived expected profit is non-negative, even though true expected profit is negative.*

课件 $`R=100,C=30,p=0.25,\delta=0.1`$ ：门槛0.3，主观概率0.35，主观利润5，真实利润 $`-5`$ ，期望损失5。

 **收益口径陷阱。** 若题目改为成功“净赚 $`R`$ ”、失败“净亏 $`C`$ ”，利润为 $`pR-(1-p)C`$ ，门槛变成 $`C/(R+C)`$ 。先写状态收益表，再求期望，不能机械套用 $`C/R`$ 。

<a id="section-5-4"></a>

### 5.4 过度投资的比较静态与课件选择题边界

固定 $`p,R`$ ，错误投资的成本区间为：

```math
pR\lt C\leq(p+\delta)R.
```

 偏差 $`\delta`$ 增加会扩大区间上界；成本上升或 $`R`$ 下降则可能使个体进入该区间，也可能越过上界退出投资，不能一概断言“提高成本一定更容易过度投资”。

|  $`p=0.25,\widetilde{p}=0.35,R=100`$  |  $`C=20`$  |  $`C=30`$  |  $`C=40`$  |
|:---------------------------------|:-------|:-------|:-------|
| 真实最优                         | 投资   | 不投   | 不投   |
| 偏误选择                         | 投资   | 投资   | 不投   |
| 错误投资                         | 否     | 是     | 否     |

B第17页把更高偏差、更高成本、更低回报都列为增加风险，属于缺少条件的简化。考试若要求解释，写出区间，说明何时进入、何时退出。连续总体中的错误投资比例还取决于 $`p`$ 与成本的分布。

<a id="section-5-5"></a>

### 5.5 过高定位：能力与比赛进入

表现 $`y_i=a_i+\varepsilon`$ ， $`\varepsilon\sim N(0,\sigma_\varepsilon^2)`$ ，达到 $`t`$ 成功。在给定个人真实能力 $`a_i`$ 时：

<a id="equation-20"></a>

**公式（20）**

```math
p_i=1-\Phi\left(\frac{t-a_i}{\sigma_\varepsilon}\right).
```

  $`\Phi(z)`$ 为标准正态累积分布， $`1-\Phi(z)`$ 为右尾概率。若自认能力 $`a_i+\eta`$ ， $`\eta\gt 0`$ ：

```math
\widetilde{p}_i=1-\Phi\left(\frac{t-a_i-\eta}{\sigma_\varepsilon}\right)\gt p_i.
```

 进入成本 $`C`$ 、成功总奖 $`V`$ ，按 $`\widetilde{p}_iV-C\geq0`$ 进入。

课件 $`a_i=0,t=1,\sigma_\varepsilon=1,\eta=0.5`$ ：

```math
p_i=1-\Phi(1)=0.1587,\quad\widetilde{p}_i=1-\Phi(0.5)=0.3085.
```

  $`C=30,V=100`$ ，真实最优不进入，主观选择进入，真实利润约 $`-14.13`$ 。

 **辨析与适用条件：** 给定 $`a_i`$ 时概率计算只用表现噪声标准差 $`\sigma_\varepsilon`$ ，不能再无条件把能力方差加进去。若题目询问随机抽取未知能力者的总体成功率，才需要对能力分布积分。课件正态对称分布下半数高于均值；任意偏态分布中，“多数高于均值”并非逻辑上不可能，不能脱离分布假设使用平均以上效应的论证。

<a id="section-5-6"></a>

### 5.6 过度精确与二阶Taylor近似

真实 $`X\sim N(\mu,\sigma^2)`$ ，主观方差 $`\widetilde{\sigma}^2\lt \sigma^2`$ ，即使均值相同也会误判风险。对风险厌恶者：

<a id="equation-21"></a>

**公式（21）**

```math
\mathbb{E}[u(W_0+X)]\approx u(W_0+\mu)+\frac{1}{2}u''(W_0+\mu)\mathrm{Var}(X).
```

  **推导。** 以 $`m=W_0+\mu`$ 展开：

```math
u(W_0+X)\approx u(m)+u'(m)(X-\mu)+\frac{1}{2}u''(m)(X-\mu)^2.
```

 取期望，一阶项为0，二阶项变成方差项。因 $`u''\lt 0`$ ，方差增加降低近似EU；低估方差使EU偏高。

课件 $`u(W)=\sqrt{W},W_0=100,\mu=0.2,\sigma=10,\widetilde{\sigma}=5`$ ：

```math
u(100)=10,\quad u(100.2)\approx10.009995,
\quad u''(100.2)=-\frac{1}{4(100.2)^{3/2}}.
```

 真实方差100， $`\mathrm{EU}^{true}\approx9.9975\lt 10`$ ；主观方差25， $`\mathrm{EU}^{belief}\approx10.0069\gt 10`$ ，因此错误接受项目。

 **置信范围补充。** 正态分布95%主观范围若写成 $`[\mu-1.96\widetilde{\sigma},\mu+1.96\widetilde{\sigma}]`$ ，真实覆盖率为 $`2\Phi(1.96\widetilde{\sigma}/\sigma)-1`$ ；若主观标准差为真实一半，覆盖率约67.3%，而非95%。

 **辨析与适用条件：** Taylor式为局部近似。正态分布有无界负尾，平方根效用仅在非负财富定义；课件例子应按小风险近似理解，不能视为对整个正态分布的精确期望积分。

<a id="section-5-7"></a>

### 5.7 小数定律、代表性与赌徒谬误

 **小数定律信念（Belief in the law of small numbers）** 是误以为小样本也应高度代表总体。

*The law-of-small-numbers bias is the mistaken belief that even small samples should closely resemble the population from which they are drawn.*

对独立伯努利变量 $`X_i`$ ， $`\widehat{p}=n^{-1}\sum X_i`$ ：

```math
\mathbb{E}[\widehat{p}]=p,\quad\mathrm{Var}(\widehat{p})=\frac{p(1-p)}{n}.
```

 小样本不必有偏，但波动更大。医院每天15人与45人出生的例子，小医院更容易出现极端男孩比例。若问严格超过60%，事件应写成 $`K\gt 0.6n`$ 并按整数处理：15人时 $`K\geq10`$ ，45人时 $`K\geq28`$ 。

 **代表性启发式（Representativeness heuristic）** 根据“看上去像不像总体”判断概率，可能忽略基率、样本量或独立性。 **锚定（Anchoring）** 指判断向初始数值靠拢； **可得性（Availability）** 依据记忆中例子的易得程度评估事件（B第32页提及的补充解释）。

 **赌徒谬误（Gambler’s fallacy）** 是错误相信独立随机结果存在短期补偿性负相关。

*The gambler’s fallacy is the mistaken belief that independent random outcomes are self-correcting, so a run of one outcome makes the opposite outcome more likely next.*

公平独立硬币： $`P(T_6\mid HHHHH)=1/2`$ 。 **大数定律（Law of large numbers）** 仅说明样本均值随样本增大趋近总体均值，不要求未来反向补偿过去。

 **序列与事件类。** 特定序列HTHHTT和HHHTTT均为 $`2^{-6}`$ ；“恰好三正三反”包含 $`\binom63`$ 条序列，概率 $`\binom63 2^{-6}=20/64`$ 。不能将一条序列与一组序列当成相同层级比较。

 **辨析与适用条件：** 如果真实成功概率未知，连续结果可能理性地提供信息；若确有能力或环境持续性，也可能出现正相关。辨认赌徒谬误时必须先确认题目是否设定独立、已知概率。

<a id="section-5-8"></a>

### 5.8 投射偏误：把当前状态投射到未来

 **投射偏误（Projection bias）** 是预测未来偏好时过度使用当前状态。

*Projection bias is the tendency to exaggerate how much future tastes or utility will resemble current tastes or utility.*

课件当前状态 $`s'`$ 、未来状态 $`s`$ ：

<a id="equation-22"></a>

**公式（22）**

```math
\widehat{u}(c,s)=(1-\alpha)u(c,s)+\alpha u(c,s'),\qquad0\leq\alpha\leq1.
```

  $`\alpha=0`$ 正确预测； $`\alpha=1`$ 完全投射。预测误差：

**公式（23）**

```math
\widehat{u}(c,s)-u(c,s)=\alpha[u(c,s')-u(c,s)].
```

 因此投射可高估也可低估，取决于当前与未来效用的差；不总是过度消费。

例：当前饥饿效用10，未来饱腹效用4， $`\alpha=0.5`$ ，预测为7，误差3。若价格6且货币效用线性，预测净收益1而实际未来净收益 $`-2`$ ，发生错误购买。一般购买条件 $`4+6\alpha\geq6`$ ，即 $`\alpha\geq1/3`$ （无差异时购买）。

 **与当下偏误区别。** 当下偏误改变不同时点效用的权重，可能正确知道未来收益；投射偏误改变预测的未来效用本身。即使时间贴现完全一致，也可能投射错误；两种偏误可共同出现。

<a id="section-5-9"></a>

### 5.9 投射与赌徒谬误的实证案例

课件Conlin等（2007）将户外服装订单与当地购买、退货时温度匹配。当前冷可能使未来保暖效用被高估，后续暖时退货。课件预测：其他条件给定时，购买日温度更低对应更高退货概率，退货日温度更高也对应更高退货概率。

 **识别要点：** 冷天买外套本身可完全理性。需检查后续天气、购买者选择、产品与季节等控制。课件“理性情形退货与两日温度无关”的表述是在特定模型与控制条件下的基准，不能当作现实无条件规律。

课件Chen等（2016）涉及庇护法官、信贷人员与棒球裁判；本课重点展示法官。若案件随机分配且彼此独立，控制案件特征后，前次批准不应机械降低本次批准率。负序列相关支持赌徒谬误解释，但还要排除案件排序、配额、疲劳与真实质量相关。B第48页为机制示意，不应把曲线点位当作回归估计数据。

 **英文答题表达：** *Serial dependence in decisions is informative only after accounting for serial dependence in case quality and other institutional explanations.*

<a id="chapter-6"></a>

## 6 跨章节辨析、证据与政策的整合

<a id="section-6-1"></a>

### 6.1 容易混淆的概念对照

| 概念对                 | 区别与英文答题关键词                                                                 |
|:-----------------------|:-------------------------------------------------------------------------------------|
| 不耐心／当下偏误       | Impatience可由低 $`\delta`$ 产生；Present bias是现在的额外权重 $`\beta\lt 1`$ 。                |
| 时间不一致／随机改主意 | Time inconsistency要求固定未来比较因时间本身发生排序反转；新信息下改变计划不必违反。 |
| 成熟型／无偏误         | Sophistication是预测未来自己正确，不是 $`\beta=1`$ 。                                    |
| 风险厌恶／损失厌恶     | Risk aversion比较风险与同均值确定结果；Loss aversion比较参照点两侧得失影响。         |
| 概率加权／错误信念     | Probability weighting改变决策影响；Biased beliefs改变对客观发生概率的判断。          |
| 不平等厌恶／利他       | Inequality aversion下别人增收可能扩大劣势；Altruism通常欢迎他人改善。                |
| 互惠／无条件利他       | Reciprocity随对方意图改变，Unconditional altruism不依赖此前善意。                    |
| 内在满足／社会形象     | Intrinsic motivation可在匿名时存在；Social image依赖外部评价。                       |
| 过高估计／过高定位     | Overestimation是绝对表现；Overplacement是相对排名。                                  |
| 过度精确／过高估计     | Overprecision低估方差；Overestimation可高估均值或成功率。                            |
| 投射偏误／当下偏误     | Projection bias预测错未来效用；Present bias对已知效用进行特殊跨期赋权。              |
| 默认／强制             | Default允许退出；Mandate强制执行，福利与自由成本不同。                               |
| 显著行为效应／福利改善 | Statistical effect不等于Welfare gain；还须界定福利基准与干预成本。                   |

<a id="section-6-2"></a>

### 6.2 五类应用如何对应机制？

| 现象         | 可能机制                           | 检验或工具                           |
|:-------------|:-----------------------------------|:-------------------------------------|
| 退休储蓄不足 | 当下偏误、复利误判、惰性、低收入   | 承诺、复利信息、默认加入；分别识别   |
| LED采用低    | 未来节约不显著、资金约束、当下偏误 | 生命周期成本信息、融资、即时便利     |
| 公开捐款增加 | 形象、未来人际回报                 | 匿名／公开随机对照，控制其他回报     |
| 市场进入过多 | 过高估计、过高定位、非金钱收益     | 测量主观概率与真实表现               |
| 买后退货     | 投射、信息变化、质量问题           | 比较当前状态与未来状态并控制产品信息 |

<a id="section-6-3"></a>

### 6.3 一个统一的答题流程

1.   **定义对象：** 行动、时点、各状态收益、概率与约束；谁是决策者？

2.   **给基准：** 指数贴现、EUT、自利模型或正确概率下预测什么？

3.   **引入机制：** 改变哪个参数或评价环节，不要只贴偏误标签。

4.   **列出选择差：**  $`\Delta U=U(\text{act})-U(\text{do not act})`$ ，解 $`\Delta U\geq0`$ 。

5.   **检查边界：** 概率、报价、定义域、无差异、离散金额、是否为近似。

6.   **解释证据：** 其他模型能否给出同样行为？需要什么对照？

7.   **评价政策：** 直接效应、其他渠道、成本与福利基准。

 **英文答题表达：** *Under the benchmark model, the individual would …. Introducing … changes the choice condition to …. The mechanism is …. However, the observed behavior alone does not rule out ….*

<a id="section-6-4"></a>

### 6.4 课件表述的集中校正清单

1.  R第32–44页多处把货币期望值作为“EUT预测”：应加线性效用／风险中性条件。组合选择违反独立性的论证不依赖这种线性假设。

2.  R第28页图注的指数与所列公式指数不同，复习用题目给定参数，不据图注推断统一估计。

3.  R第29页“回到EUT”须额外说明价值函数与最终财富效用兼容；R第47页WTA/WTP为直觉性简化。

4.  S第31–32页公开增加亲社会行为依赖正面边际信号及稳定最优条件；第35页形象水平下降本身不充分证明行为挤出。

5.  S第42页“小赌注公平更重要”不可仅由 $`U_i=\pi_i+f_i\pi_j`$ 推得。

6.  B第13页投资收益的文字与利润式口径需统一；采用无论成败均付 $`C`$ 时才有 $`pR-C`$ 。

7.  B第17页成本与奖金额的比较静态不无条件成立；B第18页平均以上的逻辑依赖分布假设。

8.  L第26页标准差与GPA单位不能直接等同；默认同意率不等于实际器官捐赠率。

这些边界用于把答案写严谨，不要求答题时长篇批评课件。常用一句话：*This conclusion holds under the stated assumptions; it is not unconditional.*

<a id="chapter-7"></a>

## 7 开卷速查：公式、英文术语与答题表达

<a id="section-7-1"></a>

### 7.1 核心公式及调用条件

| 任务                         | 公式                                                 | 条件／章节定位                        |
|:-----------------------------|:-----------------------------------------------------|:--------------------------------------|
| 复利（Compounding）          |  $`FV=PV(1+r)^n`$                                        | 每期利率一致；[第1.4节](#section-1-4) |
| 期末年金（Ordinary annuity） |  $`FV=C[(1+r)^n-1]/r`$                                   | 期初款另乘 $`1+r`$                        |
| 指数贴现                     |  $`U_t=\sum_{k\geq0}\delta^ku_{t+k}`$                    | [第2节](#chapter-2)                   |
| 准双曲贴现                   |  $`U_t=u_t+\beta\sum_{k\geq1}\delta^ku_{t+k}`$           |  $`\beta`$ 只乘一次                       |
| 计划学但当天不学             |  $`\beta\delta B\lt C\leq\delta B`$                         | 成本当前、收益下一期                  |
| 风险期望效用                 |  $`\mathrm{EU}=\sum p_i u(w_0+x_i)`$               | 用最终财富；[第3节](#chapter-3)       |
| 确定性等价                   |  $`\mathrm{CE}=u^{-1}(\mathrm{EU})-w_0`$     |  $`u`$ 可逆且递增                         |
| 风险溢价                     |  $`\mathrm{RP}=\mathbb{E}[X]-\mathrm{CE}`$    | 与净收益口径一致                      |
| 前景相对得失                 |  $`\Delta=w_0+x-r`$                                      | 先确定参照点                          |
| 价值函数                     |  $`v(\Delta)=\Delta^\alpha`$ 或 $`-\lambda(-\Delta)^\beta`$  | 先判断正负                            |
| FS两人效用                   | 式[（11）](#equation-11)的两个正差距                 | [第4.2节](#section-4-2)               |
| CR福利效用                   | 式[（13）](#equation-13)                             | 最差者、总收益、自己                  |
| 互惠效用                     |  $`U_i=\pi_i+f_i\pi_j`$                                  | [第4.8节](#section-4-8)               |
| 互惠报价门槛                 |  $`(25-5\sqrt{17})/2\approx2.192`$                       | 仅课件10元简化模型                    |
| FS报价门槛                   |  $`x\geq M\alpha/(1+2\alpha)`$                           | [第4.9节](#section-4-9)               |
| 投资门槛                     |  $`p\geq C/R`$                                           | 无论成败均付 $`C`$                        |
| 错误投资区间                 |  $`p \lt \frac{C}{R} \leq p+\delta`$                                  | [第5.3节](#section-5-3)               |
| 表现达到门槛                 |  $`1-\Phi((t-a_i)/\sigma_\varepsilon)`$                  | 给定能力；[公式（20）](#equation-20)  |
| 小风险EU近似                 |  $`u(W_0+\mu)+\tfrac{1}{2}u''(W_0+\mu)\sigma^2`$             | [第5.6节](#section-5-6)               |
| 样本比例方差                 |  $`p(1-p)/n`$                                            | 独立同分布；[第5.7节](#section-5-7)   |
| 未来偏好预测                 |  $`(1-\alpha)u(c,s)+\alpha u(c,s')`$                     | [第5.8节](#section-5-8)               |

<a id="section-7-2"></a>

### 7.2 符号防混淆表

| 符号      | 当下偏误               | 参照／社会偏好            | 信念               |
|:----------|:-----------------------|:--------------------------|:-------------------|
|  $`\alpha`$   | 无统一固定用途         | 收益曲率；FS劣势厌恶      | 投射强度           |
|  $`\beta`$    | 当下偏误参数           | 损失曲率；FS优势厌恶      | 按题目另定义       |
|  $`\delta`$   | 长期贴现因子           | CR最差者福利权重          | 过高估计的概率偏差 |
|  $`\lambda`$  | 无统一固定用途         | 损失厌恶；CR社会福利权重  | 按题目另定义       |
|  $`r`$        | 利率（若题目如此设定） | 参照点； $`r(\tau)`$ 内在动机 | 不得自动套别章含义 |

同字母跨模型不共享数值或经济含义。答题第一步可写：*Here,  $`\beta`$  denotes ….*

<a id="section-7-3"></a>

### 7.3 英文关键词索引（按字母检索）

| English keyword                     | 中文及检索方向           | 章节链接                   |
|:------------------------------------|:-------------------------|:---------------------------|
| Absolute risk aversion              | 绝对风险厌恶， $`-u''/u'`$   | [第3.2节](#section-3-2)    |
| Advantageous inequality aversion    | 优势不平等厌恶， $`\beta`$   | [第4.2节](#section-4-2)    |
| Altruism / warm glow                | 利他／行动内在满足       | [第4节](#chapter-4)        |
| Anchoring / availability            | 锚定／可得性             | [第5.7节](#section-5-7)    |
| Backward induction                  | 逆向归纳，成熟型求解     | [第2.4节](#section-2-4)    |
| Bayesian updating                   | 贝叶斯更新基准           | [第5节](#chapter-5)        |
| Beliefs / rational expectations     | 信念／理性预期           | [第5节](#chapter-5)        |
| Certainty effect                    | 确定性效应               | [第3.4节](#section-3-4)    |
| Certainty equivalent                | 确定性等价               | [公式（7）](#equation-7)   |
| Choice architecture                 | 选择架构、默认与助推     | [第1.5节](#section-1-5)    |
| Choice overload                     | 选择过载、菜单复杂性     | [第1.5节](#section-1-5)    |
| Commitment device                   | 承诺装置                 | [第2.4节](#section-2-4)    |
| Compounding                         | 复利增长                 | [第1.4节](#section-1-4)    |
| Crowding out                        | 外部激励挤出             | [第4.7节](#section-4-7)    |
| Default / opt-in / opt-out          | 默认／主动加入／主动退出 | [第1.5节](#section-1-5)    |
| Decreasing impatience               | 递减不耐心               | [公式（4）](#equation-4)   |
| Diminishing sensitivity             | 敏感性递减               | [公式（10）](#equation-10) |
| Disadvantageous inequality aversion | 劣势不平等厌恶， $`\alpha`$  | [第4.2节](#section-4-2)    |
| Endowment effect                    | 禀赋效应，WTA与WTP       | [第3.8节](#section-3-8)    |
| Expected utility theory (EUT)       | 期望效用理论             | [公式（6）](#equation-6)   |
| Exponential discounting             | 指数贴现                 | [公式（3）](#equation-3)   |
| Exponential growth bias             | 指数增长偏误             | [第1.4节](#section-1-4)    |
| Fairness equilibrium                | 公平均衡与信念一致       | [第4.10节](#section-4-10)  |
| Fourfold pattern                    | 四重风险态度             | [第3.7节](#section-3-7)    |
| Gambler’s fallacy                   | 赌徒谬误                 | [第5.7节](#section-5-7)    |
| Income targeting                    | 目标收入                 | [第3.9节](#section-3-9)    |
| Independence axiom                  | 独立性公理               | [第3.4节](#section-3-4)    |
| Indifference curve                  | 无差异曲线               | [第4.2节](#section-4-2)    |
| Intrinsic / extrinsic motivation    | 内在／外部动机           | [公式（14）](#equation-14) |
| Jensen’s inequality                 | Jensen不等式             | [第3.2节](#section-3-2)    |
| Kindness / reciprocity              | 善意／互惠               | [第4.8节](#section-4-8)    |
| Law of large / small numbers        | 大数定律／小数定律信念   | [第5.7节](#section-5-7)    |
| Loss aversion                       | 损失厌恶                 | [公式（10）](#equation-10) |
| Naïveté / sophistication            | 天真／成熟               | [第2.4节](#section-2-4)    |
| Negative externality                | 负外部性、同学分心       | [第1.6节](#section-1-6)    |
| Nudge / reminder                    | 助推／提醒               | [第1.5节](#section-1-5)    |
| Overconfidence                      | 三种过度自信             | [第5.2节](#section-5-2)    |
| Overestimation                      | 过高估计、投资门槛       | [第5.3节](#section-5-3)    |
| Overplacement                       | 过高定位、比赛进入       | [公式（20）](#equation-20) |
| Overprecision                       | 过度精确、低估方差       | [第5.6节](#section-5-6)    |
| Overweighting small probabilities   | 小概率过度加权           | [第3.7节](#section-3-7)    |
| Positive / normative analysis       | 实证／规范分析           | [第1节](#chapter-1)        |
| Present bias                        | 当下偏误                 | [第2节](#chapter-2)        |
| Projection bias                     | 投射偏误                 | [第5.8节](#section-5-8)    |
| Prospect theory                     | 前景理论                 | [公式（9）](#equation-9)   |
| Quasi-hyperbolic discounting        | 准双曲贴现               | [公式（4）](#equation-4)   |
| Randomized controlled trial         | 随机对照试验             | [第1.6节](#section-1-6)    |
| Reference dependence / point        | 参照依赖／参照点         | [公式（9）](#equation-9)   |
| Reflection effect                   | 反射效应                 | [第3.8节](#section-3-8)    |
| Representativeness heuristic        | 代表性启发式             | [第5.7节](#section-5-7)    |
| Risk aversion / risk premium        | 风险厌恶／风险溢价       | [公式（8）](#equation-8)   |
| Self-image / social image           | 自我形象／社会形象       | [公式（14）](#equation-14) |
| Social-welfare preferences          | 社会福利偏好             | [公式（13）](#equation-13) |
| Time inconsistency                  | 时间不一致               | [第2节](#chapter-2)        |
| Ultimatum game                      | 最后通牒博弈             | [第4.9节](#section-4-9)    |
| Willingness to pay / accept         | 支付／接受补偿意愿       | [第3.8节](#section-3-8)    |

<a id="section-7-4"></a>

### 7.4 英文命题动词与答题粒度

| 指令                  | 应完成的工作                       | 常见不足             |
|:----------------------|:-----------------------------------|:---------------------|
| Define                | 给准确概念、对象与限定             | 只举例而不定义       |
| Explain / interpret   | 解释机制及符号经济含义             | 只翻译题干或重写公式 |
| Derive / show         | 从条件逐步推导结论                 | 直接抄最后门槛       |
| Calculate / compute   | 写公式、代数、数值与单位           | 把EU写成货币金额     |
| Compare / distinguish | 指出共同点与关键差异               | 只分别列定义         |
| Discuss / evaluate    | 给条件、支持理由与竞争解释         | 一概断言政策好或坏   |
| Design an experiment  | 明确处理、对照、随机化、结果与识别 | 只说“问参与者动机”   |
| Predict               | 给方向与依赖条件                   | 只报偏误名称         |

<a id="section-7-5"></a>

### 7.5 可直接改写的英文答题骨架

1.  *Present bias gives immediate outcomes extra weight. As the cost becomes immediate, its relative weight increases, causing a reversal of the earlier plan.*

2.  *Risk aversion concerns attitudes toward uncertainty, whereas loss aversion concerns the asymmetry between gains and losses relative to a reference point.*

3.  *The individual may know the objective probability but assign it a disproportionate decision weight. This differs from holding an incorrect probability belief.*

4.  *A sophisticated agent anticipates future self-control problems and may therefore demand commitment. Sophistication does not eliminate present bias.*

5.  *The same allocation can induce different responses when the alternatives available to the proposer differ. This points to an intention-based mechanism.*

6.  *The reward increases the material return but may weaken the reputational signal. The net effect depends on the change in marginal incentives.*

7.  *The agent underestimates uncertainty rather than overestimating the mean. For a risk-averse decision-maker, this raises perceived expected utility.*

8.  *The small sample is more variable, not necessarily more biased. Independence implies that past outcomes do not change the probability of the next draw.*

9.  *Current preferences contaminate the forecast of future utility. The prediction error depends on both the projection parameter and the difference between current and future tastes.*

10. *The treatment changes behavior, but a welfare conclusion additionally requires a benchmark for well-being and an assessment of intervention costs.*

<a id="chapter-8"></a>

## 8 英文练习题与解答：计算、辨析及实验设计

以下均为 **自拟练习** ，不是实际试题或确定预测。先独立写英文答案，再核对。题型覆盖目录中的主要模型，方便考前查漏。

<a id="section-8-1"></a>

### 8.1 题1：复利、时点与增长偏误

*A person invests 10,000 at an annual return of 7% for 30 years. Compute the future value under compounding and under a linear approximation. Explain the behavioral bias behind the latter.*

 **解答。**  $`FV=10000(1.07)^{30}\approx76122.55`$ ；线性预测 $`10000(1+0.07\times30)=31000`$ 。差额约45122.55，低估约59.3%。

 **英文答题表达：** *The linear approximation ignores interest earned on past interest. It illustrates exponential growth bias.*

 **变式。** 如果每年末存10000，必须用年金式，不能把一次性本金式乘30。题目若改为年初存款，年金终值另乘1.07。

<a id="section-8-2"></a>

### 8.2 题2：三期作业、天真型与成熟型

*A student must complete a task in period 0, 1, or 2. The costs are 2, 3, and 5. Let  $`\beta=0.5`$  and  $`\delta=1`$ . Find the completion time with commitment, without commitment for a fully naïve agent, and without commitment for a sophisticated agent. What is the sophisticated agent’s maximum immediate utility cost of commitment?*

 **解答。** 第0期锁定时间： $`-2,-1.5,-2.5`$ ，选第1期。第1期实际比较 $`-3`$ 与 $`-2.5`$ ，拖到第2期。天真型先等待，最终第2期完成；成熟型倒推，立即第0期完成优于等待到第2期。承诺带来 $`-1.5-(-2)=0.5`$ 效用改善，故最高即时费用0.5。

 **英文答题表达：** *Commitment implements period 1. The naïve agent ends up in period 2, while the sophisticated agent completes in period 0 to avoid future procrastination. The maximum immediate commitment cost is 0.5 utility units.*

<a id="section-8-3"></a>

### 8.3 题3：当下偏误的参数识别

*Assume linear utility. A person is indifferent between 100 in 30 days and 110 in 31 days, and between 100 today and 120 tomorrow. Under quasi-hyperbolic discounting, identify  $`\delta`$  and  $`\beta`$ .*

 **解答。** 两个未来日期中 $`\beta`$ 约去： $`100\beta\delta^{30}=110\beta\delta^{31}`$ ， $`\delta=10/11`$ 。当前比较 $`100=120\beta\delta`$ ，所以 $`\beta=11/12\approx0.9167`$ 。  **解释。** 题目明确给无差异与线性效用，才能算点值；若只知道选择其中一项，只能得到不等式。每日 $`\delta`$ 不可直接当成年贴现因子。

<a id="section-8-4"></a>

### 8.4 题4：CE、风险溢价与保险

*Let  $`u(W)=\sqrt{W}`$  and initial wealth be 100. A loss of 36 occurs with probability 0.5. Find expected final wealth, expected utility, the certainty equivalent of final wealth, the risk premium, and the maximum premium for full insurance.*

 **解答。** 最终财富100或64，期望82； $`\mathrm{EU}=0.5(10)+0.5(8)=9`$ ；最终财富CE为81；风险溢价 $`82-81=1`$ ；最高完全保险费 $`100-81=19`$ ，其中期望损失18、风险溢价1。

 **英文答题表达：** *The maximum insurance premium is 19, equal to the expected loss of 18 plus a risk premium of 1. The expected utility of 9 is not a monetary payoff.*

<a id="section-8-5"></a>

### 8.5 题5：独立性公理

*An individual prefers a sure 3,000 to an 80% chance of 4,000, but prefers a 20% chance of 4,000 to a 25% chance of 3,000. Show why these strict preferences violate EUT. Assume all other outcomes are zero.*

 **解答。** 归一化 $`u(0)=0`$ ，前者要求 $`u(3000)\gt 0.8u(4000)`$ ，后者要求 $`0.2u(4000)\gt 0.25u(3000)`$ ，即 $`0.8u(4000)\gt u(3000)`$ ，矛盾。无需假设 $`u`$ 线性。

 **英文答题表达：** *The two inequalities contradict each other. The violation concerns the joint pattern of choices, not the preference for a sure outcome in isolation.*

<a id="section-8-6"></a>

### 8.6 题6：参照点改变与混合彩票

*An outcome yields final wealth 120. Evaluate it under  $`v(\Delta)=\Delta`$  for gains and  $`v(\Delta)=2\Delta`$  for losses when the reference point is 100 and when it is 150. Explain the difference.*

 **解答。**  $`r=100`$ 时 $`\Delta=20,v=20`$ ； $`r=150`$ 时 $`\Delta=-30,v=-60`$ 。

 **英文答题表达：** *The same final wealth is coded as a gain or a loss depending on the reference point. Loss aversion then amplifies the negative valuation in the second case.*

 **变式。** 若价值函数为平方根分段，使用 $`\sqrt{20}`$ 或 $`-2\sqrt{30}`$ ，不可给负数直接开平方。

<a id="section-8-7"></a>

### 8.7 题7：不平等厌恶与转移

*In a dictator game, player 1 has 10 and player 2 has 0. Player 1 may transfer  $`t\in[0,10]`$ . Derive the optimal transfer under Fehr–Schmidt preferences. Discuss the cases  $`\beta\lt 1/2`$ ,  $`\beta=1/2`$ , and  $`\beta\gt 1/2`$ .*

 **解答。** 当 $`t\leq5`$ ， $`U=10(1-\beta)+(2\beta-1)t`$ ；当 $`t\geq5`$ ， $`U=10(1+\alpha)-(1+2\alpha)t`$ 严格递减。因此三种情况依次为 $`t^*=0`$ 、 $`t^*\in[0,5]`$ 、 $`t^*=5`$ 。

 **英文答题表达：** *Giving reduces own income but also reduces advantageous inequality. Equal sharing is optimal only when the weight on advantageous inequality is sufficiently high.*

<a id="section-8-8"></a>

### 8.8 题8：最后通牒阈值及离散报价

*In a 10-unit ultimatum game, the responder has Fehr–Schmidt preferences with  $`\alpha=0.75`$ . Derive the minimum acceptable offer. If offers must be integers and indifference leads to acceptance, what is the smallest accepted integer? Can rejection alone establish intention-based reciprocity?*

 **解答。**  $`x\geq10(0.75)/(1+1.5)=3`$ ，最小整数3。拒绝不能唯一识别互惠，因为不平等厌恶本身预测拒绝。可改用相同分配、不同替代选项的迷你最后通牒设计。

 **英文答题表达：** *Rejection is also consistent with distributional preferences. Varying the proposer’s alternatives while holding the realized allocation fixed provides a sharper test of intentions.*

<a id="section-8-9"></a>

### 8.9 题9：形象模型与奖励

*Suppose  $`U(a)=(r+y)a-a^2/2+q\theta a`$  with  $`a\geq 0`$  and non-negative parameters. Find  $`a^*`$  and its response to  $`q`$  and  $`y`$ . Does this model generate crowding out?*

 **解答。** 一阶条件 $`r+y-a+q\theta=0`$ ，二阶导 $`-1\lt 0`$ ， $`a^*=r+y+q\theta`$ 。 $`da^*/dq=\theta\geq0`$ ， $`da^*/dy=1\gt 0`$ 。该例 **不产生奖励挤出** ，因为声誉对行动的边际回报未随奖励下降。要产生挤出，需加入足够负的 $`G_{ay}`$ 等机制。

 **英文答题表达：** *This specification cannot generate crowding out: monetary incentives enter additively and do not weaken the marginal image return.*

<a id="section-8-10"></a>

### 8.10 题10：错误投资与比较静态

*Let  $`p=0.25`$ ,  $`\widetilde{p}=0.35`$ , and  $`R=100`$ . The entry cost is paid in both states. Characterize the cost interval in which a biased agent invests but a correctly informed agent does not. Does a higher cost always increase overinvestment?*

 **解答。**  $`25\lt C\leq35`$ 。成本20时两者均投，30时错误进入，40时均不投，故不单调。正确识别期望损失 $`C-25`$ 。

 **英文答题表达：** *A higher cost can move the agent into or out of the overinvestment region. The effect is not unconditionally monotonic.*

<a id="section-8-11"></a>

### 8.11 题11：过度精确与区间覆盖

*An uncertain outcome is normally distributed with mean 0 and true standard deviation 10. An agent believes the standard deviation is 5 and reports a 95% range centered at zero. What range does the agent report, and what is its true coverage?*

 **解答。** 报告 $`[-9.8,9.8]`$ ，真实覆盖 $`P(\vert Z\vert \leq0.98)=2\Phi(0.98)-1\approx0.673`$ 。过度精确表现为声称95%但实际覆盖较低，而非均值错误。

 **英文答题表达：** *The forecast is overprecise: its center is correct, but uncertainty is understated, so the reported range covers only about 67.3% of the true distribution.*

<a id="section-8-12"></a>

### 8.12 题12：小样本与赌徒谬误

*A fair coin has landed heads five times. What is the probability of tails next? Is HTHHTT more likely than HHHTTT? Explain how the law of large numbers differs from the gambler’s fallacy.*

 **解答。** 下一次反面0.5；两条特定序列均 $`1/64`$ 。大数定律描述长期频率收敛，赌徒谬误额外假定短期负相关；独立性不允许该额外推断。

 **英文答题表达：** *Long-run convergence does not require future outcomes to compensate for past realizations. The existing imbalance becomes small relative to a growing sample.*

<a id="section-8-13"></a>

### 8.13 题13：投射强度与购买阈值

*Current utility from food is 10, but future utility when satiated will be 4. The price is 6 and utility is quasi-linear in money. Under projection bias, find the range of  $`\alpha`$  that induces purchase. Is purchase justified by true future utility?*

 **解答。** 预测 $`4+6\alpha`$ ，购买条件 $`4+6\alpha-6\geq0`$ ，即 $`\alpha\geq1/3`$ ；真实未来净效用 $`-2`$ ，不值得购买。需注明无差异购买约定。

 **英文答题表达：** *Projection bias raises predicted future utility above its true value. A sufficiently large projection parameter therefore induces a purchase that the future self does not value enough to justify its price.*

<a id="section-8-14"></a>

### 8.14 题14：综合机制识别与实验设计

*A university wants to increase gym attendance. Propose an experiment that distinguishes limited attention, present bias, and social-image concerns. Specify treatments, outcomes, and identification limitations.*

 **解答思路。** 采用随机分组并保持价格和设施可用性一致：对照、私人提醒、自愿承诺工具、公开目标／出勤展示；可做析因设计（Factorial design）以估计交互作用。结果变量包括报名、真实刷卡出勤、持续出勤、退出与满意度。提醒有效可支持注意力渠道，承诺需求与执行改善支持自控机制，公开相对匿名差异支持社会形象。

局限：提醒也可改变显著性，公开也可产生同伴监督，承诺自愿采用者存在选择性；“提供承诺”的随机效应与“实际采用承诺”的效果应区分。还应测量事前计划和对未来行为的预测，以识别天真程度。福利评价需包含运动收益、罚金成本与自主性。

 **英文答题表达：** *Randomize the offer of each tool, measure actual attendance rather than sign-up alone, and state which additional channels each treatment may affect. Treatment effects need not uniquely identify a single psychological mechanism.*

<a id="section-8-15"></a>

### 8.15 教师视角：如何把题目出得有区分度？

1.   **概念题：** 给新例子，要求定义并分类；如同一人高估成绩但低估排名，能否区分三类过度自信？

2.   **计算题：** 改变收益口径、成本支付时点或报价单位，检查学生是否真正理解模型。

3.   **推导题：** 求参数区间、比较静态与边界，而非只计算课件原数值。

4.   **辨析题：** 给“更高成本总增加过度投资”“公开必增捐款”等命题，要求给条件或反例。

5.   **识别题：** 保持结果不变改变意图，或保持物质回报不变改变匿名性，考察实验控制。

6.   **政策题：** 同一现象给多种机制，要求先诊断再建议工具，并区分行为和福利。

考试准备不应只背研究作者、年份或示意图数值；应能复现模型的比较条件。若题目明确询问课件案例，回答“研究问题—设计—发现—机制—局限”五项。

<a id="chapter-9"></a>

## 9 课件定位与文献线索

<a id="section-9-1"></a>

### 9.1 五份课件的阅读回查路线

| 课件 | PDF页面      | 对应知识                                 |
|:-----|:-------------|:-----------------------------------------|
| L    | 8、20、33–45 | 行为经济学目标、AI研究、标准模型与局限   |
| L    | 24–31        | 电子设备RCT、AI作业生产率与学习结果      |
| L    | 49–57        | 退休储蓄、复利增长偏误、政策工具         |
| L    | 58–66        | LED、选择过载、默认、提醒、与博弈论关系  |
| P    | 10–21、27–33 | 指数贴现、递减不耐心、准双曲、投资与享乐 |
| P    | 34–42        | Amy例子、天真与成熟、参数识别            |
| P    | 45–56        | 承诺、肥料实验、政策渠道                 |
| R    | 7–21         | 彩票、EUT、风险态度、CE、初始财富        |
| R    | 24–31        | 前景理论、参照点、价值函数、概率加权     |
| R    | 32–44        | 确定性、独立性、复合彩票、反射效应       |
| R    | 45–52        | 禀赋效应与目标收入                       |
| S    | 12–22        | FS两人／多人、无差异曲线、CR模型         |
| S    | 24–35        | 动机类别、形象模型、可见性、奖励挤出     |
| S    | 37–48        | 互惠、善意、公平均衡、接受门槛、迷你博弈 |
| S    | 50–55        | 公开羞辱、白羽毛运动与事件研究           |
| B    | 4–8、10–26   | 信念、乐观、三类过度自信与计算           |
| B    | 28–32        | 小数定律、医院、代表性、赌徒谬误         |
| B    | 34–42、44–48 | 投射模型、服装退货、法官决策             |

<a id="section-9-2"></a>

### 9.2 文献与机制的对应（按课件引述）

以下是定位线索而非扩展文献综述。具体实证结果以课件与题目材料为准。

| 文献                                                   | 复习用途                     |
|:-------------------------------------------------------|:-----------------------------|
| Samuelson (1937)                                       | 指数贴现基准                 |
| Thaler (1981)                                          | 跨期限隐含贴现率、递减不耐心 |
| Read, Loewenstein & Kalyanaraman (1999)                | 未来与即时选择反转           |
| O’Donoghue & Rabin (1999, 2001)                        | 当下偏误、天真与成熟、拖延   |
| Duflo, Kremer & Robinson (2011)                        | 肥料采用、SAFI与时机         |
| Kahneman & Tversky (1979)                              | 前景理论、确定性与反射效应   |
| Tversky & Kahneman (1992)                              | 累积前景理论与权重函数       |
| Kahneman, Knetsch & Thaler (1990)                      | 禀赋效应、WTA与WTP           |
| Camerer et al. (1997)                                  | 出租车司机目标收入           |
| Fehr & Schmidt (1999)                                  | 不平等厌恶                   |
| Charness & Rabin (2002)                                | 福利、最差者与效率           |
| Bénabou & Tirole (2006)                                | 内外动机、声誉与奖励挤出     |
| Rabin (1993)                                           | 意图互惠与公平均衡           |
| Falk, Fehr & Fischbacher (2003)                        | 迷你最后通牒、区分结果与意图 |
| Mellström & Johannesson (2008); Lacetera et al. (2012) | 献血奖励的不同实证结果       |
| Becker (2022，课件所列工作论文)                        | 白羽毛运动、社会形象与参军   |
| Weinstein (1980)                                       | 相对乐观信念                 |
| Tversky & Kahneman (1971, 1974)                        | 小数定律与启发式             |
| Loewenstein, O’Donoghue & Rabin (2003)                 | 投射偏误模型                 |
| Conlin, O’Donoghue & Vogelsang (2007)                  | 天气与服装订单／退货         |
| Chen, Moskowitz & Shue (2016)                          | 专业决策中的赌徒谬误         |
| Benartzi & Thaler (2007)                               | 退休储蓄行为                 |
| Carter, Greenberg & Walker (2017)                      | 课堂设备随机实验             |
| Iyengar & Lepper (2000)                                | 选择过载                     |
| Johnson & Goldstein (2003)                             | 默认与器官捐赠同意           |
| Strömberg, Lei & Wu (2026，课件所引)                   | AI作业表现与后续考试结果     |

<a id="section-9-3"></a>

### 9.3 GitHub阅读与使用

本文件采用UTF-8编码，可作为独立Markdown文件上传到GitHub。公式使用GitHub的行内数学分隔符与独立math公式块；目录、英文关键词和公式速查均使用站内章节链接。原课件页码仍指PDF实际页面，Markdown 本身不保留打印页码。中英文定义、模型推导、案例、辨析和14道练习均保留。

本文件可直接上传为 `behavioral_economics_open_book.md`；若希望它成为仓库首页，可将其重命名为 `README.md`。在GitHub中打开文件并选择渲染预览阅读，不要只看原始源码。下载后也可使用支持数学公式的Markdown编辑器阅读。与原LaTeX笔记相同，所附练习不代表实际考卷。
