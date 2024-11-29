# SML
就是脑子一热，我假设社会是可编程的，然后我向GPT灌了点基础知识看看能不能整点活，没想到居然还有模有样的。。
我就一什么都不懂的高中生，没受过相关专业的教育，也就业余嘛，你看我Markdown都写不来的。

下面是一个适用于GitHub仓库的`README.md`模板，它以第一人称方式写成，介绍了你创建的社会建模语言（SML）及其使用方法。

# 文件说明：
- **msg-1-1**：原来的对话（这些对话里的技术性信息与我本人没什么关联，因为我用的是公共账号）
- **msg-1-2**: 发现有误尝试挽救无果
- **msg-3-1**：松鼠花生的试探性分析
- **cocilang.txt**:用于训练大模型的文本
- **默认既定规则.txt**:自己瞎摸索出来的并不完整，并不完备的定律

欢迎路过的道友拷打我。

---

# 社会建模语言（SML）

欢迎来到**社会建模语言（SML）**的仓库！  
SML是一种用于描述社会现象和行为逻辑的结构化语言，旨在通过关键字和规则，帮助用户将复杂的社会问题拆解为可编程的规则和可执行的路径。该语言适用于社会工程、心理模拟、目标建模等多种应用场景。

## 项目简介

SML（社会建模语言）旨在通过引入一系列的核心关键字和结构化规则，帮助用户描述并模拟社会现象和行为的动态变化。通过这些规则，我们可以创建能够自动推演的社会模型，以便探索人类行为和社会结构的复杂交互。

这个仓库包含了SML的核心语言定义、使用示例、以及如何在不同场景下应用该语言的详细说明。

## 语言特点

- **动态性**：社会现象具有动态变化的特性，所定义的规则可能在揭示后失效。我们通过`RULE`和`SELF_REFLECT`等关键字处理规则的动态性。
- **目标导向**：行为和论述是以目标为导向的，行为主体通过`GOAL`来驱动行为的方向和实施路径。
- **认知限制**：人类的认知能力有限，只有在特定条件满足时，才能实现更深层次的认知或行动。这一概念通过`COGNITIVE_LIMIT`和`TRIGGER`等关键字来建模。
- **相对真理**：对于社会现象的理解没有绝对的对错，只有相对的真理和解释，体现了不同社会背景下的多元观点（`RELATIVE_TRUTH`）。
- **生存优先**：在所有行为决策中，生存是最高优先级，人类行为受生存需求和情感偏向的影响（`SURVIVAL_PRIORITY`、`EMOTIONAL_BIAS`）。
- **经济基础**：社会结构和行为逻辑受经济基础的影响（`ECONOMIC_BASE`、`SUPERSTRUCTURE`）。
- **行为骨架与复杂化**：欲望和行为有简单的骨架结构，但在实际执行过程中会变得复杂，体现在`DESIRE`和`ACTION_SKELETON`中。
- **认知与存在的交互**：认知与存在的关系是动态的、相互作用的（`COGNITION`、`EXISTENCE`）。

## 核心关键字

SML的核心在于一组关键词，它们帮助定义社会行为、规则、目标和互动方式。以下是主要关键字及其简要说明：

- **ACTOR**：行为主体，指在模型中执行动作的个体或群体。
- **DISCOURSE**：论述或讨论，描述行为者的目标和行为方向。
- **GOAL**：目标，指行为主体期望通过行动实现的结果。
- **RULE**：规则，描述行为或社会现象的普遍规律。
- **SELF_REFLECT**：自我反思，指在规则暴露或应用后的效应反馈。
- **COGNITIVE_LIMIT**：认知限制，指人类在特定条件下对信息的理解或处理的局限性。
- **TRIGGER**：触发条件，描述某一事件或行为的触发因素或前提条件。
- **RELATIVE_TRUTH**：相对真理，强调不同背景下的多元真理观。
- **SURVIVAL_PRIORITY**：生存优先，表示行为主体在所有决策中优先考虑生存的基本原则。
- **EMOTIONAL_BIAS**：情感偏向，指人类行为受到情感驱动或偏向的影响。
- **THEORY_DEPENDENCY**：理论依赖，指知识和理论的建立依赖于现有的认知体系。
- **ECONOMIC_BASE**：经济基础，指社会或行为模式的经济因素和结构。
- **SUPERSTRUCTURE**：上层建筑，指由经济基础决定的社会结构、文化、政治等上层系统。
- **PHILOSOPHICAL_MODEL**：哲学模型，作为理解世界的工具或框架，帮助解释复杂的现象。
- **DESIRE**：欲望，指驱动个体行为的基本动机或需求。
- **ACTION_SKELETON**：行为骨架，指基于欲望的行为框架或简单模型，后续会被复杂化。
- **COGNITION**：认知，指个体或群体的认知过程，如何感知、处理和理解信息。
- **EXISTENCE**：存在，指个体或群体的实际存在状态，以及存在与认知的互动。
- **PUSH**：制造事件，指人为地推动一个事件的发生，以实现特定的社会反应或目标。
- **MARK**：标记某个人，指将某个个体或群体指定为特定角色或符号，以在后续事件中提高其地位或影响力。

## 示例

以下是一个简单的SML代码示例，展示如何使用这些关键字：

```plaintext
ACTOR: "Donald Trump"
DISCOURSE: "Promote transparency in government"
GOAL: "Increase public trust"
RULE: "Public policies gain trust through transparency"
SELF_REFLECT: IF RULE_DISCLOSED THEN RULE_EFFECTIVENESS -= 50%

PUSH: "Campaign rally to address government accountability"
GOAL: "Shift public discourse to transparency"
TRIGGER: IF PUBLIC_OUTRAGE > THRESHOLD THEN ACTION: "Announce transparency initiative"
```

## 安装与使用

1. 克隆此仓库：

```bash
git clone https://github.com/yourusername/sml.git
```

2. 在项目目录中使用语言定义，创建模型或进行模拟。

3. 你可以根据自己的需求自定义关键字或规则。

## 贡献

我们欢迎所有的贡献！如果你有任何建议、修复或新特性，欢迎提交`pull request`。具体的贡献指南请参考`CONTRIBUTING.md`文件。

## 授权

随便整的，不想招摇。

---

感谢你对SML的兴趣！
