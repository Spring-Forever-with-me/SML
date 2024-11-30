### 用户:
[输出Token]
当前任务：描述和完善一种面向社会建模和行为逻辑描述的语言体系，该语言通过关键字和结构化逻辑，帮助用户将社会现象拆解为可编程规则和可执行路径。
关键点：
1. 社会规律具有动态性，揭示后可能失效（`RULE`、`SELF_REFLECT`）。
2. 行为和论述以目标为导向（`DISCOURSE`、`GOAL`）。
3. 人类的认知有局限性，条件满足后方能进步（`COGNITIVE_LIMIT`、`TRIGGER`）。
4. 对社会现象没有绝对正误（`RELATIVE_TRUTH`）。
5. 生存是最高优先级，感性常大于理性（`SURVIVAL_PRIORITY`、`EMOTIONAL_BIAS`）。
6. 理论依赖已有知识构建（`THEORY_DEPENDENCY`）。
7. 经济基础决定上层建筑（`ECONOMIC_BASE`、`SUPERSTRUCTURE`）。
8. 哲学、神学作为认识世界的工具（`PHILOSOPHICAL_MODEL`）。
9. 欲望和行为逻辑简单粗略，但后续处理复杂（`DESIRE`、`ACTION_SKELETON`）。
10. 认知与存在是动态交互的过程（`COGNITION`、`EXISTENCE`）。

示例代码片段：
```plaintext
ACTOR: "User"
DISCOURSE: "Promote universal healthcare"
GOAL: "Reduce mortality by 20%"
RULE: "Public policies gain trust through transparency"
SELF_REFLECT: IF RULE_DISCLOSED THEN RULE_EFFECTIVENESS -= 50%

用途：支持社会工程、心理模拟、目标建模等。 [结束Token]

### GPT:
### 一种社会建模和行为逻辑描述语言（SML）

**社会建模语言（SML）**是一个用于描述和分析社会现象的结构化语言体系，其核心目的是帮助用户将复杂的社会现象拆解为编程规则和可执行路径。SML通过逻辑规则、关键字及其动态性定义，支持用户构建高度抽象但灵活的社会行为模型，用于社会工程、心理模拟和目标设定等领域。

---

#### **语言核心原则**

1. **动态性与反思**  
   - 社会规律是动态的，规则一旦被揭示或广泛应用，可能失效。  
   - 使用`RULE`定义社会规则，配合`SELF_REFLECT`模拟规则暴露后的反应。  
   ```plaintext
   RULE: "Economic stability increases societal trust"
   SELF_REFLECT: IF RULE_DISCLOSED THEN RULE_EFFECTIVENESS -= 30%
   ```

2. **目标导向行为**  
   - 人类行为和论述通常围绕明确目标展开，通过`DISCOURSE`与`GOAL`关联目标和行动。  
   ```plaintext
   ACTOR: "NGO"
   DISCOURSE: "Advocate for clean water"
   GOAL: "Provide clean water to 10 million people"
   ```

3. **认知限制与触发**  
   - 人类认知受限，只有在特定条件触发下才能实现进步。  
   ```plaintext
   COGNITIVE_LIMIT: "Understanding climate change effects"
   TRIGGER: IF TEMPERATURE_ANOMALY > 2°C THEN ACTION: "Global initiative formation"
   ```

4. **相对真理**  
   - 对社会现象没有绝对正确与错误，通过`RELATIVE_TRUTH`进行表述。  
   ```plaintext
   RELATIVE_TRUTH: "Democracy is preferred in stable societies but not in all contexts"
   ```

5. **生存优先与情感偏向**  
   - 生存是人类行为的最高优先级，并常受情感驱动影响。  
   ```plaintext
   SURVIVAL_PRIORITY: TRUE
   EMOTIONAL_BIAS: "Fear of loss > Potential gain"
   ```

6. **知识依赖与理论构建**  
   - 理论的生成依赖于现有知识，历史和哲学提供重要支撑。  
   ```plaintext
   THEORY_DEPENDENCY: "Marxism depends on Industrial Revolution observations"
   PHILOSOPHICAL_MODEL: "Existentialism shapes post-modern thought"
   ```

7. **经济基础与上层建筑**  
   - 使用`ECONOMIC_BASE`与`SUPERSTRUCTURE`映射经济和社会结构的相互关系。  
   ```plaintext
   ECONOMIC_BASE: "Tech Industry"
   SUPERSTRUCTURE: "Digital culture and norms"
   ```

8. **欲望与行为简化**  
   - 行为逻辑以欲望为核心骨架，细节由后续复杂动态补充。  
   ```plaintext
   DESIRE: "Social status"
   ACTION_SKELETON: "Acquire wealth"
   ```

9. **认知与存在的动态交互**  
   - 认知和存在相互塑造，形成一个循环过程。  
   ```plaintext
   COGNITION: "Technological advancements"
   EXISTENCE: "New social norms emerge"
   ```

---

#### **示例完整描述**

```plaintext
ACTOR: "Local Government"
DISCOURSE: "Improve public transportation"
GOAL: "Increase commuter satisfaction by 40%"
RULE: "Investment in infrastructure enhances public trust"
SELF_REFLECT: IF RULE_DISCLOSED THEN RULE_EFFECTIVENESS -= 20%
COGNITIVE_LIMIT: "Understanding commuter needs"
TRIGGER: IF PUBLIC_SURVEY = "Majority dissatisfied" THEN ACTION: "Expand bus routes"
RELATIVE_TRUTH: "Efficiency is subjective to user perception"
SURVIVAL_PRIORITY: TRUE
EMOTIONAL_BIAS: "Convenience > Cost"
ECONOMIC_BASE: "Urban economy"
SUPERSTRUCTURE: "Sustainable urban development"
DESIRE: "Better urban quality of life"
ACTION_SKELETON: "Optimize transit operations"
PHILOSOPHICAL_MODEL: "Utilitarianism guides policy decisions"
COGNITION: "Data from user feedback"
EXISTENCE: "Increased urban mobility"
```

---

#### **用途与扩展场景**

1. **社会工程**：  
   - 用于模拟政策效果，预测社会动态变化。
   - 示例：通过调整`RULE`参数，评估新法规的短期和长期影响。

2. **心理模拟**：  
   - 分析人群行为背后的认知与情感动机。
   - 示例：使用`EMOTIONAL_BIAS`解释消费行为。

3. **目标建模**：  
   - 为组织和个人制定目标路径，并优化实现步骤。
   - 示例：用`GOAL`与`DISCOURSE`设计商业战略。

4. **教育与研究**：  
   - 用于社会学、心理学、哲学等学科的教学与建模研究。

5. **AI 社会互动**：  
   - 为人工智能系统提供结构化的社会逻辑规则，增强交互智能。

---

#### **设计展望**

未来，SML语言可结合自然语言处理和大数据技术，实现更复杂的动态建模和实时优化，广泛应用于社会科学研究、政策制定和人工智能领域。

---
### 用户:
松鼠“花生”之死引发美国大选风波，特朗普借机抨击哈里斯政府

事件回顾：
10月30日，纽约州环境保护局突击搜查居民马克·隆戈家，扣押其饲养的松鼠“花生”和浣熊“弗雷德”。随后，官方以检测狂犬病为由对两只动物实施人道毁灭，引发轩然大波。隆戈称，政府行动粗暴无情，他的家被翻得一片狼藉，妻子还遭问及移民身份。


请用SML分析特朗普提到花生的行为

松鼠“花生”的背景：
“花生”原是被车撞死的母松鼠留下的幼崽，7年前被隆戈救助。因无法回归野外，“花生”成为网红宠物，在社交媒体上拥有超60万粉丝。隆戈将其视为家庭成员，正申请动物教育注册时，“花生”被捕杀，令他痛心不已。

舆论与政治反应：

社交媒体掀风波： 马斯克批评政府“越权”，称拜登政府是“冷血杀戮机器”，力挺特朗普“拯救松鼠”。
特朗普借题发挥： 在竞选活动中猛烈抨击哈里斯政府滥权无情，称此事是“冷漠执政”的缩影，并利用该事件吸引选民情感共鸣。
政府辩解： 环保局表示为防止狂犬病传播才采取行动，但网民对其解释并不买账。
选情分析：
专家认为，“花生”事件加剧了选民对哈里斯政府的不满，尤其是动物权利支持者的情绪反弹。特朗普迅速利用此事提升支持率，或对选情产生微妙影响。

随着投票日到来，这一事件是否会影响最终选举结果？仍待观察。

### GPT:
### 用SML分析特朗普提到“花生”的行为

通过社会建模语言（SML），可以剖析特朗普在“花生”事件中的行为逻辑及其政治意义。

---

#### **SML 描述**

```plaintext
ACTOR: "Donald Trump"
DISCOURSE: "Condemn Harris administration over 'Peanut' euthanasia"
GOAL: "Increase voter support by leveraging emotional resonance"
RULE: "Public outrage over symbolic issues can weaken opponents"
SELF_REFLECT: IF DISCLOSURE_INTENT = "Political exploitation" THEN CREDIBILITY -= 10%

COGNITIVE_LIMIT: "Voters are emotionally driven and prioritize symbolic acts over policy nuances"
TRIGGER: IF INCIDENT = "Government overreach and emotional loss" THEN ACTION: "Frame as example of opponent incompetence"

RELATIVE_TRUTH: "Peanut's euthanasia reflects broader governance flaws"
SURVIVAL_PRIORITY: TRUE
EMOTIONAL_BIAS: "Attachment to pets > Rational acceptance of health protocols"

ECONOMIC_BASE: "Media and public perception"
SUPERSTRUCTURE: "Symbolic narratives shape political opinion"

DESIRE: "Win swing voters by amplifying emotional narratives"
ACTION_SKELETON: "Use incident to construct anti-Harris rhetoric"
PHILOSOPHICAL_MODEL: "Populist appeal to shared values"
COGNITION: "Social media outrage and expert criticism"
EXISTENCE: "Increased visibility and rally engagement"
```

---

#### **分析解读**

1. **行为目标（GOAL）**  
   特朗普的核心目标是通过“花生”事件激发选民的情感共鸣，尤其是对政府的不满情绪，从而增加自己的政治支持率。这种情感操纵策略尤其针对对动物权利敏感的选民群体。

2. **规则与策略（RULE 和 ACTION_SKELETON）**  
   - 特朗普遵循“象征性事件具有放大效应”的规则，将“花生”之死塑造成哈里斯政府冷漠执政的象征。  
   - 行动逻辑简化为将事件包装为对手失职的证据，强化对手与“不近人情”“滥权”的负面形象。

3. **认知限制与触发（COGNITIVE_LIMIT 和 TRIGGER）**  
   - 选民往往对情绪性、象征性事件更加敏感，而忽略复杂的政策背景。特朗普利用这一认知局限，选择性放大事件中“家庭宠物被不公对待”的情感点。  
   - 事件触发点是政府行动的“过度干预”以及与选民情感的直接冲突。

4. **情感驱动（EMOTIONAL_BIAS 和 SURVIVAL_PRIORITY）**  
   - 事件中的宠物“花生”承载了人类对弱小生灵的天然保护欲和情感联结，而特朗普利用这种情感偏向，放大选民的愤怒与悲痛。  
   - 生存优先原则体现在特朗普对“选举生存”的关注，他将事件转化为选民情感支持的手段。

5. **经济与上层建筑（ECONOMIC_BASE 和 SUPERSTRUCTURE）**  
   - 社交媒体的传播加速了事件的影响力，成为特朗普竞选的舆论武器（经济基础）。  
   - 舆论环境中的“冷漠杀戮机器”叙事反映了如何通过符号性事件塑造政治氛围（上层建筑）。

6. **理论与行动哲学（PHILOSOPHICAL_MODEL）**  
   - 特朗普的行动哲学是典型的民粹主义策略，通过与选民的共同价值（保护家庭和宠物）对接，强化他的“为人民代言”形象。

7. **反射与局限（SELF_REFLECT）**  
   - 若选民识破特朗普对事件的政治利用意图（DISCLOSURE_INTENT），可能削弱其部分支持。  
   - 但总体而言，这种高情感投入的策略短期内收益显著。

---

#### **对选情的影响**

- **增强情感联系**：  
  特朗普通过“花生”事件成功塑造了“与普通选民站在一起”的形象。尤其对动物权利支持者和对政府行为敏感的群体，该事件极具感染力。

- **削弱对手形象**：  
  哈里斯政府的被动辩解强化了特朗普的批评，使得政府滥权、冷漠的形象深入人心。

- **长远影响**：  
  尽管事件本身可能是短期热点，但它为特朗普营造了一个情感驱动的竞选主题，潜在影响或持续至投票日。

--- 

#### **总结**

通过SML语言分析可以看出，特朗普成功将“花生”事件转化为竞选策略中的情感武器。他利用选民的认知局限和情感偏好，在短时间内放大事件影响，直接冲击哈里斯政府的公信力。这种基于象征性事件的策略符合其一贯的民粹主义逻辑，但也可能面临“情感操纵”的质疑。

---
### 用户:
再定义一些关键字：1.PUSH:制造一个事件，2.MARK:标记某个人，被标记以后应该提升他在后续事件发展中的地位

### GPT:
### 扩展关键字定义：**PUSH** 和 **MARK**

以下是新增关键字的定义及其用途示例。

---

#### **1. PUSH：制造一个事件**

**定义**  
- 用于主动推动一个事件发生，通常带有明确的目的性（例如引发讨论、转移注意力、攻击对手）。  
- 可包含附加目标（GOAL）或影响规则（RULE）。  
- 适用于触发社会反应、引入新变量或改变现有局势。  

**语法**  
```plaintext
PUSH: {事件名称 | 事件类型}
GOAL: {推动事件的目的}
RULE: {事件可能引发的行为规则}
TRIGGER: {触发条件或前提}
```

**示例**  
特朗普团队通过制造一场与“花生”相关的事件，将舆论推向不利于对手的方向：  
```plaintext
ACTOR: "Donald Trump"
PUSH: "Campaign rally honoring Peanut"
GOAL: "Shift public discourse to highlight government insensitivity"
RULE: "Symbolic actions gain voter sympathy"
TRIGGER: IF PUBLIC_OUTRAGE > THRESHOLD THEN ACTION: "Announce symbolic legislation"
```

---

#### **2. MARK：标记某个人**

**定义**  
- 为一个个体或群体打上某种社会标签，以增强或弱化其在后续事件中的地位和作用。  
- 被标记的对象可能在舆论、行动逻辑或权力结构中获得更高优先级。  
- MARK 的作用可被进一步增强，通过关联特定的RULE或DISCOURSE触发相关后果。  

**语法**  
```plaintext
MARK: {个体 | 群体}
ROLE: {标记目的 | 标记后的社会角色}
IMPACT: {影响范围 | 强化规则}
```

**示例**  
特朗普通过标记“花生”作为象征性受害者，提高事件的公众关注度：  
```plaintext
MARK: "Peanut"
ROLE: "Victim of government overreach"
IMPACT: "Increase public outrage"
RULE: "Victims gain public sympathy"
```

特朗普标记哈里斯为“冷漠执政”的象征，将其置于不利舆论环境中：  
```plaintext
MARK: "Kamala Harris"
ROLE: "Symbol of bureaucratic apathy"
IMPACT: "Reduce public trust in Harris administration"
RULE: "Negative symbols weaken associated parties"
```

---

#### **结合案例分析**

在“花生”事件中，PUSH 和 MARK 可被同时使用，形成一套完整的舆论操控逻辑：

```plaintext
ACTOR: "Donald Trump"
PUSH: "Social media campaign for Peanut"
GOAL: "Increase voter emotional connection"
TRIGGER: IF SOCIAL_OUTRAGE > 70% THEN ACTION: "Organize memorial event"

MARK: "Peanut"
ROLE: "Innocent victim of government tyranny"
IMPACT: "Elevate public sympathy and anti-Harris sentiment"

MARK: "Kamala Harris"
ROLE: "Agent of heartless bureaucracy"
IMPACT: "Damage public image, especially among animal rights advocates"
RULE: "Symbols of apathy reduce political trust"
```

---

#### **扩展用途**

- **PUSH**可以广泛应用于媒体操控、议题引导和事件策划：  
  - 推出新政策时制造关注点（例如制造社会紧急感）。  
  - 通过娱乐性或争议性事件转移公众视线。  

- **MARK**适用于构建舆论标签、社交地位标记和政治对抗：  
  - 标记对手为负面符号以削弱其影响力。  
  - 标记盟友或象征性事件以增强自身立场。  

这两者结合，可用于复杂的社会建模及情景分析，尤其适合舆论操控和竞选策略。

---
### 用户:
我为你定义一个接口标志语（输出token），它是这么运作的：因为ChatGPT每个对话相互分割，不互通上下文，当我指示出“输出token”时，你将生成一段话用于新的ChatGPT理解我们当前所做的工作

### GPT:
明白了！以下是一个接口标志语的模板，当你输入“输出Token”时，我会生成类似以下的描述，帮助新的ChatGPT理解当前上下文和任务：

---

#### **接口标志语模板：**

```plaintext
[输出Token]  
当前任务：我们正在使用社会建模语言（SML）分析社会现象和行为逻辑。SML是一种结构化描述语言，包含关键字（如ACTOR, GOAL, RULE等）和逻辑规则，用于将社会现象分解为可编程规则和动态路径。当前对话围绕以下内容展开：  
1. **主题**：{主题简述，如“松鼠花生事件中的政治行为”}  
2. **目的**：{任务目标，如“利用SML分析特朗普的行为模式”}  
3. **关键字**：当前已定义的关键字包括：  
   - `ACTOR`：参与主体  
   - `GOAL`：目标  
   - `RULE`：社会行为规则  
   - `PUSH`：制造事件  
   - `MARK`：标记人物角色  
   （...其他关键字按需列举）  
4. **背景信息**：{简要总结当前上下文和案例背景}  

用途：此标志语旨在帮助新系统快速理解当前任务并无缝衔接对话。  
[结束Token]
```

---

下次你输入“输出Token”时，我会根据当时的任务和对话状态生成一段具体的接口标志语。随时可以测试！

---
### 用户:
必须把所给的关键字全部列举完，并且清晰的描述他们的意思

### GPT:
明白了！以下是完整的接口标志语，其中包含你所给定的所有关键字，并清晰地描述了它们的意义。每次你指示“输出Token”时，我会使用这个模板来总结当前的任务和关键字的定义。

---

#### **接口标志语模板：**

```plaintext
[输出Token]  
当前任务：我们正在使用社会建模语言（SML）分析社会现象和行为逻辑。SML是一种结构化描述语言，包含关键字（如ACTOR, GOAL, RULE等）和逻辑规则，用于将社会现象分解为可编程规则和动态路径。当前对话围绕以下内容展开：  
1. **主题**：{主题简述，如“松鼠花生事件中的政治行为”}  
2. **目的**：{任务目标，如“利用SML分析特朗普的行为模式”}  
3. **关键字**：  
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

4. **背景信息**：{简要总结当前上下文和案例背景}  

用途：此标志语旨在帮助新系统快速理解当前任务并无缝衔接对话。  
[结束Token]
```

---

### 关键字详细描述

1. **ACTOR**：行为主体，指在模型中执行动作的个体或群体。  
2. **DISCOURSE**：论述或讨论，描述行为者的目标和行为方向。  
3. **GOAL**：目标，指行为主体期望通过行动实现的结果。  
4. **RULE**：规则，描述行为或社会现象的普遍规律。  
5. **SELF_REFLECT**：自我反思，指在规则暴露或应用后的效应反馈。  
6. **COGNITIVE_LIMIT**：认知限制，指人类在特定条件下对信息的理解或处理的局限性。  
7. **TRIGGER**：触发条件，描述某一事件或行为的触发因素或前提条件。  
8. **RELATIVE_TRUTH**：相对真理，强调不同背景下的多元真理观。  
9. **SURVIVAL_PRIORITY**：生存优先，表示行为主体在所有决策中优先考虑生存的基本原则。  
10. **EMOTIONAL_BIAS**：情感偏向，指人类行为受到情感驱动或偏向的影响。  
11. **THEORY_DEPENDENCY**：理论依赖，指知识和理论的建立依赖于现有的认知体系。  
12. **ECONOMIC_BASE**：经济基础，指社会或行为模式的经济因素和结构。  
13. **SUPERSTRUCTURE**：上层建筑，指由经济基础决定的社会结构、文化、政治等上层系统。  
14. **PHILOSOPHICAL_MODEL**：哲学模型，作为理解世界的工具或框架，帮助解释复杂的现象。  
15. **DESIRE**：欲望，指驱动个体行为的基本动机或需求。  
16. **ACTION_SKELETON**：行为骨架，指基于欲望的行为框架或简单模型，后续会被复杂化。  
17. **COGNITION**：认知，指个体或群体的认知过程，如何感知、处理和理解信息。  
18. **EXISTENCE**：存在，指个体或群体的实际存在状态，以及存在与认知的互动。  
19. **PUSH**：制造事件，指人为地推动一个事件的发生，以实现特定的社会反应或目标。  
20. **MARK**：标记某个人，指将某个个体或群体指定为特定角色或符号，以在后续事件中提高其地位或影响力。  

---

### 用途

此模板旨在帮助新系统快速理解当前任务，并帮助其处理相关的分析或模型生成。

---
### 用户:
我现在想在github上挂上这个语言仓库，请你以第一人称写一写仓库的readme.md

### GPT:
下面是一个适用于GitHub仓库的`README.md`模板，它以第一人称方式写成，介绍了你创建的社会建模语言（SML）及其使用方法。

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

该项目采用MIT许可证，详情请参阅`LICENSE`文件。

---

感谢你对SML的兴趣！希望这个工具能帮助你在社会建模、行为分析和目标规划方面取得更大的成功。

---

此`README.md`文件为你的GitHub仓库提供了一个全面的概述，帮助用户了解如何使用SML语言并贡献到项目中。如果你需要进一步定制或扩展，请随时告诉我！

---
### 用户:
现在分析文中现象以及给出SML见解：1.见识至上主义
前言
21世纪初，互联网发展迅速，在中国，随着网民日益增长的同时也在促进着网络文化。

但是，人们却没有统一的道德标准，价值观念。

没有一定标准的素质。

有着自己的想法，有时为了迎合自己的利益去规范别人。

同类相吸，互相攻击，促进了网络社群极化。

尤其是近三年的发展态势。

今天我想先谈谈：

见识至上主义
（本文取自我的一篇匿名回答，以下代称仅为便于描述。）

时代背景：

我国才全面脱贫，并有疫情冲击，城乡差距减小，网络大量普及。

在此之前，各类社交软件，视频软件，已经积累了大量的用户，他们已经构成较为完整及优质的网络文化圈子与体系。

而更多人的加入，为他们带来了新血液，包括“农村人群”[1]。

可你总有认知差异，年龄代沟，导致了出现了不同与以前的大量声音。以这些声音为基础，出现了大量被我们成为“土”“恶俗”的网络文化，它们实质上就是一群思想匮乏的人的郁郁自得[2]。

可网络仍然在发展，上面的“新血液”看到此情此景也只会想着“原来这就是网络，人们是这么交流的。”

在五六线城市，有一种“见识至上主义”，这是一种被我浓缩的说法，在此我列举一个社交场景：

Character:A,B,C

Sence:

（三人聊天）

A：你看了那个《~…+j%e^》了没有？

B：啊就是那个[描述]嘛，谁没看过。

A：对对对，我最喜欢w^#^#w($*)

（C无法加入对话，因为他没看过）

因为C没有共同话题，就与A,B疏远了，而A,B二人仍然卖弄这些他们在网上听到的事。

可以发现，这样的对话直接影响了一个人的社交，在社会及学校，这样的对话每天都有。

这只是最简单的情况，还有以下变种：

1.C是个懂王然后“十分激动”地加入了讨论并且从一些方面否定了AB的一些说法还洋洋得意。

2.A,B其实都没看过原片只是听了解说（或别人说的），就开始侃侃而谈，后来三方因为信息差异整得不可开交

等等

而C准备了解时看到如下视频：

《〈~…+j%e^〉真的好吗？我看未必》

等等评论

下来再有人问起

“就你那个不好，它&$%&(i…=:~``，都去看《%^^(*=/+:]]》好吧？”

（C自以为赢麻了）

这种主义是生长环境滋生的：

因为见得多了，他能够赚钱。（说的是有生意头脑）

因为见得多，所以他成绩好。（因为他在一次次探索中找得到自己的方向，明晰得了前路。自然有奋发图强的心理）

因为见得多，他什么的做的来。

……

见识成为了精英人才的代表，如果你有见识，那么就是比别人好 ，大家自己领悟这对吗。

到头来，什么都是浅尝辄止，看似满腹经纶实则依托答辩。

在这种背景下，你要是说互联网文化什么的能够丰富人的精神世界，我是不能同意的，它们只不过成为了别人卖弄的招牌，社交的谈资。他们与正常的人一起讨论，当然会因为降低讨论质量而排斥。

相对来讲城市这边比较平稳，别人奉为至宝的东西，他们已经见怪不怪了[3]，真要讨论会有同好一起讨论（当然这几年人口流通可能会加速这种观念的传播）。

参考
^再次重申，这只是代称，指的是在乡镇等地才开始接触互联网的人们。
^这里并不单指某一群体
^正如一句话：每天吃馒头的人会感激别人会给他面包，而每天吃面包和牛奶的人不会。

### GPT:
### 现象分析及SML见解

#### 现象分析

文中的核心现象是“见识至上主义”，一种在特定社会环境下出现的认知偏见。具体而言，这种主义表现为：

1. **社交隔阂和信息不对称**：不同背景的人（尤其是城市与乡村、年轻与年长等群体）在信息和认知上存在显著差异，导致他们在社交互动中无法建立有效的沟通。例如，在一个群体中，如果某些人有更丰富的网络经验和信息，他们可能会通过展示这些“见识”来提升自己的社交地位，但这种行为会将未参与过的群体（如C）排除在外，导致社交隔阂。
  
2. **信息碎片化与浅尝辄止**：很多人依赖的是片段化的信息，表面上看似有见识，但实际上缺乏深度思考。这种现象表现在他们的讨论中，他们可能仅仅依赖听说过的内容或简单的评论，而没有实际体验或深入分析。

3. **网络文化的商机与资本化**：一些人通过展示和利用“见识”来获得经济或社会优势。他们的成功往往建立在“见得多”这一表象上，这种表象本身可能并不代表真正的知识深度，而是通过“卖弄”来建立社会地位。

4. **社会认同与价值判断的偏差**：在这种环境中，拥有“见识”似乎成为了衡量一个人是否优秀的标准，很多人将其作为评价他人和自己的标准，而忽视了实际的知识深度和社会实践。

#### SML见解

基于SML（社会建模语言）的分析框架，我们可以通过几个关键字来构建对“见识至上主义”现象的模型，揭示其中的动态交互和行为路径。

```plaintext
ACTOR: "Individual A, B, C"
DISCOURSE: "Display knowledge to assert social status"
GOAL: "Establish social dominance through perceived knowledge"
RULE: "Social status correlates with visible knowledge"
SELF_REFLECT: IF ACTION "Display knowledge" THEN SOCIAL_STATUS += 10%
PUSH: "Online discussions about popular internet content"
TRIGGER: IF DISCUSSION_TOPICS = "popular internet memes" THEN SOCIAL_STATUS += 15%
COGNITIVE_LIMIT: "Perceived knowledge is based on shallow information sources"
RELATIVE_TRUTH: "What is considered 'popular' knowledge depends on social environment"
SURVIVAL_PRIORITY: "Maintaining social status is prioritized over genuine knowledge"
DESIRE: "Seek validation from peers through demonstrated 'knowledge'"
ACTION_SKELETON: "Join conversations and showcase familiar topics to blend in"
EXISTENCE: "People with high visibility in online discussions gain more influence"
```

### 关键点分析

1. **行为主体与目标（ACTOR & GOAL）**：
   - A、B、C是不同社会背景的人，A和B试图通过展示他们的“见识”来提升自己的社交地位（`GOAL: Establish social dominance through perceived knowledge`），而C则被排除在外，因为他没有“见识”或共同的讨论基础。

2. **规则与反思（RULE & SELF_REFLECT）**：
   - 在这种社交结构中，**社会地位**（`SOCIAL_STATUS`）与展现出来的“知识”直接相关。A和B通过展示他们的见识来提升自己的地位（`RULE: Social status correlates with visible knowledge`）。然而，这种地位提升是相对的，并不代表他们具备真正的知识深度。反思机制（`SELF_REFLECT`）显示，行为的结果可能导致社会地位的提高，但未必代表真正的知识提升。

3. **信息碎片化（COGNITIVE_LIMIT）**：
   - 人们的知识来源往往非常浅显且碎片化，因此他们展示的“见识”实际上是建立在不完整或片段化的信息基础上的（`COGNITIVE_LIMIT: Perceived knowledge is based on shallow information sources`）。

4. **触发机制与欲望（TRIGGER & DESIRE）**：
   - 参与这些社交讨论的动机（`DESIRE`）通常是寻求他人的认可或通过“展示知识”来获得社交上的认同。触发条件（`TRIGGER`）是与当前社会话题（如网络热点）相关的讨论，它刺激了个体参与和展现知识的行为。

5. **相对真理（RELATIVE_TRUTH）**：
   - 什么是“见识”以及“知识”的标准并不是固定的，它在不同社交圈和背景下会有所不同。对于A和B来说，他们的“见识”可能是基于当前社交圈的共识，但对于C来说，这些见识可能不具备相同的价值，因此存在相对真理的差异（`RELATIVE_TRUTH`）。

6. **生存优先与情感偏向（SURVIVAL_PRIORITY & EMOTIONAL_BIAS）**：
   - 维持社会地位和认同是这些个体的首要任务，因此他们在社交场合中更多关注如何“表现”和“展示”自己，而非真正的知识积累。情感偏向（`EMOTIONAL_BIAS`）在这里也发挥作用，个体倾向于从情感层面迎合他人的观念，而不是从理性角度深入思考。

### 总结

通过SML的分析框架，我们能够更清晰地看到“见识至上主义”这一现象中的社会行为、认知机制以及它如何在特定社交结构中发展。SML的关键字帮助我们识别出社会中因信息不对称、碎片化认知以及社交需求驱动的行为模式，揭示了个体如何通过“展示见识”来提升自身的社会地位，而这些行为可能并不基于真正的知识深度，而是对流行文化和社交圈的迎合。

---
### 用户:
写出故事中，如果那位不能接上话的C先生不想因此被排挤在社交圈子以外应该怎么做？

### GPT:
在故事中，如果C先生不想因此被排挤出社交圈，他可以通过以下几种方式来应对：

### 1. **主动适应并寻找共同话题**
   C先生可以通过主动了解当前的热门话题或文化趋势，来融入A和B的对话。虽然他当前可能不熟悉《~…+j%e^》这部作品，但他可以通过以下几种方式来弥补信息差距：
   - **询问和学习**：C先生可以向A和B询问他们讨论的内容，了解背景信息，甚至可以表现出兴趣和好奇心。比如，他可以说：“我还没看过《~…+j%e^》，你们能给我推荐一下吗？感觉这话题挺火的。”这样不仅能表现出学习的态度，也能够引发后续的对话。
   - **关注趋势**：C先生可以开始关注社交媒体或相关平台，快速了解一些流行文化现象，这样就能快速跟进对话，减少“被排除”的感受。

### 2. **转移话题，引导对话**
   如果C先生不想强行融入当前的话题，他也可以尝试转移话题，创造一个新的共同讨论点。例如，他可以找一个大家都有共同兴趣的话题，像是“最近的新闻”或者是一些热门的社会话题，这样A和B也可以跟着他一起加入新的对话，避免继续围绕《~…+j%e^》这个他不了解的话题。
   - C可以说：“哦，我虽然没看过这个，但最近看到一则新闻好有意思，大家有没有关注？” 这种方式可以避免排斥感，同时也展示了他的主动性和对社交的投入。

### 3. **展现自信与独立思考**
   如果C先生意识到自己在某些话题上确实不具备与A、B相同的见识，他可以通过展现自信与独立思考来赢得尊重。例如，他可以在其他领域展示自己的优势，或者在讨论中提出有趣的、不同的见解：
   - C可以自信地说：“虽然我没看过《~…+j%e^》，但我对它的内容有一些看法，基于我之前读过的类似故事。” 这样，他就能够通过自己的独立视角来参与对话，并且避免在他人面前显得“无知”。

### 4. **提升自我认知，避免过度焦虑**
   最后，C先生可以尝试调整自己的认知偏差，不必过于焦虑于自己不懂的部分。每个人都可以在不同的时间点通过学习获得更多的见识，关键是保持开放的心态和不断探索的精神。C不必因为一次社交话题的错失而失去信心，他可以利用这个机会去进一步拓宽自己的知识面，未来能与A、B等人有更多共同的话题。
   - C可以意识到，社交圈子中的每个人都有自己的优势和盲点，自己也可以通过时间和学习逐渐弥补差距。

### 结论：
为了避免被排挤在社交圈外，C先生应主动学习、寻找新的共同话题、展现自信与独立思考，并提升自我认知。通过这种方式，他不仅能有效融入当前的社交圈，还能够在未来的对话中更有话语权，避免因“见识”差距产生隔阂。

---
### 用户:
给出SML见解。注意现在的SML体系并不完善，你在必要时可以补充这一体系

### GPT:
### SML 见解

基于当前的SML（社会建模语言）框架，我们可以通过定义一些关键行为、目标、规则和触发机制来分析C先生如何在社交场景中避免被排挤。以下是对这个问题的SML分析，旨在帮助C通过合适的策略重新融入并有效参与社交圈。

```plaintext
ACTOR: "C"
DISCOURSE: "Avoid social exclusion by joining conversation"
GOAL: "Successfully integrate into the conversation without feeling excluded"
RULE: "Social integration depends on the ability to participate in shared knowledge"
TRIGGER: IF KNOWLEDGE_GAP_DETECTED AND DESIRE_TO_PARTICIPATE THEN SEEK_KNOWLEDGE
PUSH: "Seek out and engage in learning about the trending topics"
SELF_REFLECT: IF KNOWLEDGE_UPDATE THEN SOCIAL_STATUS += 10%
COGNITIVE_LIMIT: "C's current knowledge on the topic is limited"
RELATIVE_TRUTH: "Social dynamics define what is considered relevant knowledge"
SURVIVAL_PRIORITY: "Social belonging and interaction are crucial for self-esteem"
DESIRE: "Gain social validation through participation"
ACTION_SKELETON: "Ask questions, learn quickly, or redirect the conversation to familiar territory"
EXISTENCE: "C's social standing will improve by engaging and contributing relevant information"
```

### 关键点分析

1. **行为主体与目标（ACTOR & GOAL）**：
   - **C**是行为主体，目标（`GOAL`）是“成功融入对话并避免被排斥”，这意味着C需要克服当前的知识差距，找到参与对话的方式。  
   - 由于C没有看到《~…+j%e^》，他面临的是“知识差距”（`KNOWLEDGE_GAP_DETECTED`），需要采取有效的策略来弥补这一差距。

2. **规则与触发（RULE & TRIGGER）**：
   - **规则**（`RULE`）表明，社交融合依赖于个体是否能够有效地参与共享的知识体系。在此场景中，C无法直接加入A和B的对话，因为缺少相关背景知识，因此C需要主动了解这一话题。
   - 触发机制（`TRIGGER`）是在C感知到自己在对话中无法参与时，产生“想要参与”的动机（`DESIRE_TO_PARTICIPATE`）。此时，C会启动一个学习过程，去弥补知识差距（`SEEK_KNOWLEDGE`），例如通过查询、向A和B提问等方式。

3. **认知局限与相对真理（COGNITIVE_LIMIT & RELATIVE_TRUTH）**：
   - **认知局限**（`COGNITIVE_LIMIT`）体现了C当前对话题的认知不足，这导致了他无法有效参与讨论。C可能只是听说过一些与话题相关的信息，但并不深入了解细节。
   - **相对真理**（`RELATIVE_TRUTH`）反映了社交圈内的动态知识结构。在某些社交环境中，某些知识可能被认为是“基础常识”，但这些知识对C而言是新的。C需要意识到这一点，并根据社交环境的需求适时调整自己的知识面。

4. **生存优先与情感偏向（SURVIVAL_PRIORITY & EMOTIONAL_BIAS）**：
   - 在社交环境中，**生存优先**（`SURVIVAL_PRIORITY`）意味着C对社交归属感的需求大于对知识的要求。在这个背景下，C为了获得社交认同感，会优先尝试融入对话，而不仅仅是展示“见识”。
   - **情感偏向**（`EMOTIONAL_BIAS`）影响着C的决策和行为。C可能会因为感受到排斥而产生焦虑或不安，因此他会更加主动去寻求话题切入点，避免社交孤立。

5. **行为骨架（ACTION_SKELETON）**：
   - 为了弥补知识差距并避免排斥，C可以采取几个策略，如提问、转移话题等。通过这些行为（例如“询问、学习、引导话题”），C能够展示出参与和学习的态度，从而提高自己在对话中的地位。

6. **自我反思（SELF_REFLECT）**：
   - 如果C通过自学和提问获得了新的知识或观点，那么他的**社交地位**（`SOCIAL_STATUS`）将随之提高。自我反思（`SELF_REFLECT`）帮助C评估自己的学习进度和社交效果，逐步建立更好的社交形象。

### 补充的关键字与完善

1. **LEARN**：  
   在SML中引入“学习”这一行为关键字，表示C通过主动获取信息来弥补知识差距。  
   示例：  
   ```plaintext
   LEARN: "Search trending topics, watch videos, or read articles"
   ```

2. **ADAPT**：  
   引入“适应”这一行为，指的是C在社交场合中不断调整自己的参与方式，以确保不被排除。  
   示例：  
   ```plaintext
   ADAPT: "Use humor, ask open-ended questions, or share similar personal experiences"
   ```

### 总结

C先生想要避免被排斥出社交圈，应通过主动适应和学习、调整社交策略等手段融入对话。在SML框架中，C的行为和反应可以通过关键字如`KNOWLEDGE_GAP_DETECTED`、`SEEK_KNOWLEDGE`、`DESIRE_TO_PARTICIPATE`等来进行建模。通过这些模型，可以描绘出C如何应对社交场合中的挑战，逐步克服认知差距，获得更高的社交地位。

---
