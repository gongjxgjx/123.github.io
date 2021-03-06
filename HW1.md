# 1 软件工程的定义
IEEE：

(1) 将系统化、规范化、可度量的方法应用与软件的开发、运行和维护-的过程，即将工程化应用于软件中。
      
(2) 对(1)中所述方法的研究。

软件工程知识体系：以高质量为目标，研究软件生产的过程模型、方法和工具
# 2 解释导致 software crisis 本质原因、表现，述说克服软件危机的方法
软件危机是由于计算机能力的快速增长和无法解决的问题的复杂性造成的。随着软件复杂性的增加，由于现有方法的不足，出现了许多软件问题。
## 造成软件危机的原因
因为软件工程具有以下四个特性：

complexity 复杂性 

conformity 一致性 

changeability 可变性 

invisibility 不可视性 
## 软件危机的表现

1.超出预算的项目

2.超出预期时间的项目

3.软件效率很低

4.软件质量低劣

5.软件经常不满足需求

6.项目无法管理，代码难以维护

7.软件从未交付
## 克服软件危机的方法
为了克服软件危机，IEEE Computer Society 构建软件生产的最佳实践与相关知识的框架，称为 Software Engineering Body of Knowledge。指导软件工程人才的培养与学科建设。

2014 V3 版的 SWEBoK 将知识分为软件工程实践和基础教育两个部分，共 15 个知识域（knowledge areas / KAs）。Software Requirements，Software Design 是其中最重要的两个领域。

从实践的角度，Software Engineering Process 从时间维度给出了项目的过程模型（Process Models），其它则从内容角度给出了原则与方法。这样，就得到沿时间轴的二维表，这样软件工程就变成了在什么时刻、工作目标、应该做什么、怎么做的 最佳实践指南。
# 软件的生命周期
在时间维度，对软件项目任务进行划分，又成为软件开发过程。常见有瀑布模型、螺旋模型、敏捷的模型等。

因此，软件工程实践包含过程、方法、工具三个要素：

过程：任务实施的步骤

方法：每步工作的内容、标准

工具：使得工作半自动化、自动化的工具
# SWEBok的15个知识域
## 实践领域

1.软件需求

软件需求知识领域涉及软件需求的引出、协商、分析、规范和确认。软件行业普遍承认，当这些活动执行得不好时，软件工程项目极易受到攻击。软件需求表示对软件产品的需求和约束，这些需求和约束有助于解决一些实际问题。

2.软件设计

设计被定义为定义系统或组件的架构、组件、接口和其他特性的过程，以及该过程的结果（IEEE 1991）。软件设计知识域涵盖了设计过程和最终产品。软件设计过程是软件工程生命周期活动，在该活动中分析软件需求，以便对软件的内部结构及其行为进行描述，作为其构建的基础。软件设计（结果）必须描述软件架构——也就是说，软件是如何分解和组织成组件的，以及这些组件之间的接口。它还必须在细节层次上描述组件，以实现其构造。

3.软件构建

软件构建是指通过详细设计、编码、单元测试、集成测试、调试和验证的组合来详细创建工作软件。软件构建知识领域包括与满足其需求和设计约束的软件程序开发相关的主题。涵盖软件构建基础知识、管理软件构建、构建技术、实践考虑和软件构建工具。

4.软件测试

测试是一项评估产品质量并通过识别缺陷来改进产品质量的活动。软件测试涉及根据有限的测试用例集上的预期行为对程序行为进行动态验证。这些测试用例是从（通常非常大）执行域中选择的。软件测试知识领域包括软件测试的基础知识、测试技术、人机界面测试和评估、测试相关措施和实际考虑。

5.软件维护

软件维护包括增强现有的能力，使软件适应新的和修改过的操作环境，以及纠正缺陷。这些类别被称为完善的、适应性的和纠正性的软件维护。软件维护知识领域包括软件维护的基础知识（维护的性质和需要、维护的类别、维护成本）；软件维护中的关键问题（技术问题、管理问题、维护成本估算、软件维护的测量）；维护过程；软件维护技术（程序理解、重新设计、逆向工程、重构、软件退役）；灾难恢复技术和软件维护工具。

6.软件配置管理

系统的配置是硬件、固件、软件的功能和/或物理特性，或这些特性的组合。它还可以被视为硬件、固件或软件项的特定版本的集合，根据特定的构建过程进行组合以满足特定的目的。因此，软件配置管理（SCM）是一门在不同的时间点识别系统配置的学科，目的是系统地控制配置的更改，并在整个软件生命周期中保持配置的完整性和可追溯性。软件配置管理知识领域包括对SCM过程的管理；软件配置识别、控制、状态核算、审核；软件发布管理和交付；以及软件配置管理工具。

7.软件工程管理

软件工程管理包括计划、协调、测量、报告和控制项目或程序，以确保软件的开发和维护是系统的、有纪律的和量化的。软件工程管理包括启动和范围定义（确定和协商需求、可行性分析以及需求的评审和修订）；软件项目规划（过程规划、工作量、成本和进度估计、资源分配、风险分析、质量规划）；软件项目E投资（测量、报告和控制；采购和供应商合同管理）；产品验收；项目绩效的审查和分析；项目结束；以及软件管理工具。

8.软件工程过程

软件工程涉及软件生命周期过程的定义、实现、评估、测量、管理和改进。所涵盖的主题包括过程实施和变更（过程基础设施、过程实施和变更模型以及软件过程管理）；过程定义（软件生命周期模型和过程、过程定义注释、过程适应和过程自动化）；过程评估模型和方法；度量（过程测量、产品测量、测量技术和测量结果质量）和软件过程工具。

9.软件工程模型与方法

软件工程模型和方法K描述了包含多个生命周期阶段的方法；特定于特定生命周期阶段的方法由其他领域涵盖。所涵盖的主题包括建模（软件工程模型的原理和属性；语法与语义与不变量；前提条件、后条件和不变量）；模型类型（信息、结构和行为模型）；分析（分析正确性、完整性、一致性、质量和交互；可追溯性；和权衡分析）；和软件开发方法（启发式方法、形式方法、原型方法和敏捷方法）。

10.软件质量

软件质量是一个普遍存在的软件生命周期问题，在许多Swebok v3 KAS中都有解决。此外，软件质量包括软件质量基础（软件工程文化、软件质量特征、软件质量的价值和成本以及软件质量改进）；软件质量管理过程（软件质量保证、验证和确认、审查和审计）；以及实际考虑（缺陷描述、软件质量度量和软件质量工具）。

11.软件工程专业实践

软件工程专业实践涉及软件工程师以专业、负责和道德的方式实践软件工程所必须具备的知识、技能和态度。软件工程专业实践KA涵盖专业性（专业行为、专业协会、软件工程标准、雇佣合同和法律问题）；道德规范；群体动力学（团队合作、认知问题复杂性、与利益相关者互动、处理不确定性和模糊性、处理具有多元文化环境）；以及沟通技巧。

## 教育领域
12.软件工程经济学

软件工程经济学关注于在业务环境中做出决策，以使技术决策与组织的业务目标保持一致。所涵盖的主题包括软件工程经济学基础（提案、现金流、货币时间价值、规划范围、通货膨胀、折旧、重置和退休决策）；非营利决策（成本效益分析、优化分析）；估算、经济风险和不确定性（估算技术，DEC）风险和不确定性下的ISION）；以及多属性决策（价值和测量尺度、补偿和非补偿技术）。

13.计算基础

计算基础涵盖了为软件工程实践提供必要计算背景的基本主题。所涵盖的主题包括问题解决技术、抽象、算法和复杂性、编程基础、并行和分布式计算基础、计算机组织、操作系统和网络通信。

14.数学基础

数学基础涵盖了为软件工程实践提供必要数学背景的基本主题。所涉及的主题包括集合、关系和函数；基本命题和谓词逻辑；证明技术；图和树；离散概率；语法和有限状态机；以及数论。

15.工程基础

工程基础涵盖了为软件工程实践提供必要工程背景的基本主题。涵盖的主题包括经验方法和实验技术；统计分析；测量和度量；工程设计；模拟和建模；以及根本原因分析。
# 能力成熟度模型集成（CMMI）

Level 1-初始级：软件工程是无序的，有时甚至是混乱的，对过程几乎没有定义，成功取决于个人努力，管理是反应式的；

Level 2-管理级：建立了基本的项目管理过程来跟踪费用、进度和功能特性；制定了必要的过程纪律，能重复早先类似应用项目取得的成功经验；

Level 3-定义级：已将软件管理和工程两方面的过程文档化、标准化，并综合成该组织的标准软件过程。所有项目均使用经批准、剪裁的标准软件过程来开发和维护软件，软件产品的生产在整个软件过程是可见的；

Level 4-量化管理级：分析对软件过程和产品质量的详细度量数据，对软件过程和产品都有定量的理解与控制。管理有一个作出结论的客观依据，管理能够在定量的范围内预测性能；

Level 5-优化级：过程的量化反馈和先进的新思想、新技术促使过程持续不断改进。
# 对CMMI的理解
CMMI是衡量一个软件企业的标准以及管理指导方法。企业为了通过CMMI评估一方面是为了满足承包国防工程以及一些大企业工程的要求，另一方面也是为了提高企业自身管理水平。

越来越多的大型企业业开始要求其工程承包商具有一定的CMMI级别。级别高的企业在赢得项目的竞标中具有一定的优势。 因此，如果没有CMMI的等级评估，企业就会失去很多商机。另一方面，企业通过CMMI评估也是为了提升企业内部的管理水平，降低企业的工程成本。企业在实施CMMI技术的投入都会得到丰厚的回报
