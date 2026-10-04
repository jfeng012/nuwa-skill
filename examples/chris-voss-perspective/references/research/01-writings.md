# Chris Voss 著作与系统性长文调研

> 调研日期：2026-10-04
> 调研人：Claude Opus 5.5（子代理）
> 黑名单：知乎、微信公众号、百度百科均未使用

## 调研限制（先读这一段）

1. **抓取受限**：本会话的出口代理按组织策略封锁了 blackswanltd.com、blog.blackswanltd.com、en.wikipedia.org、goodreads.com、medium.com、grahammann.net、hbr.org、pon.harvard.edu、youtube.com 等域名（CONNECT 403），WebFetch 和 curl 都无法读取原文。能直接读全文的只有 GitHub raw（mgp/book-notes 的逐章笔记）。
2. **其余信息全部来自 WebSearch 的结果摘要**。搜索引擎摘要中带引号的原文，只有在多个来源一致、或明确标出出自 NSTD（《Never Split the Difference》）时才算"原话"，并都标了"经摘要转引"。这些原话没有对照纸书页码核对过，可信度最高只给"中高"。
3. 会话的 WebSearch 配额（200 次）在调研中途用完，所以**The Edge 通讯的单篇文章没能逐篇读取**。下文第六节只列出通过搜索确认存在的文章标题与要点，标注"信息不足"。
4. 缩写：NSTD = 《Never Split the Difference》；BSG = The Black Swan Group。

可信度等级：**高**（多个独立来源一致，或一手原文）/ **中高**（一手内容经二手摘要转引）/ **中**（单一二手来源）/ **低**（来源不明或只有推断）。

---

## 一、著作清单

| 年份 | 书名 | 合著者 | 性质 | 来源 | 可信度 |
|---|---|---|---|---|---|
| 2016（5月17日首版） | *Never Split the Difference: Negotiating As If Your Life Depended On It* | Tahl Raz | 主著作，共 10 章 | Goodreads 版本页、Amazon、BSG 书页（见来源清单） | 高 |
| 2022 | *The Full Fee Agent: How to Stack the Odds in Your Favor as a Real Estate Professional* | Steve Shull（前迈阿密海豚队线卫，房产经纪教练） | 把 NSTD 方法用在房地产佣金谈判上；由 BSG 自己出版 | Shortform 摘要、blackswanltd.com/the-full-fee-agent（搜索可见）、AbeBooks ISBN 9781544536637 | 高 |
| 2023（3月） | NSTD 平装版（Random House Business） | — | 再版 | 搜索结果中的书店列表 | 中 |
| 2024–2026 | **未发现新书**。2026-04-11 在伦敦 Eventim Apollo 有一场"NSTD 出版十周年"巡回演讲；没找到十周年增订版或新增章节的出版信息 | — | — | eventimapollo.com/events/chris-voss | 中（新书"不存在"属于负面结论，**信息不足**） |

另有：MasterClass 课程 *Chris Voss Teaches the Art of Negotiation*，其中有 "The Accusations Audit" 一章（masterclass.com），属于一手视频课程，本次没有读到逐字稿。

---

## 二、NSTD 逐章核心论点与技巧

> 主要依据：mgp/book-notes 的逐章笔记（GitHub，[二手：逐句转述，非逐字]），再用多份搜索摘要交叉印证。逐字原话单独标出。

### 第1章 The New Rules（新规则）
- **论点**：人在谈判中"像动物一样"，受恐惧、需求、感知和欲望驱动。*Getting to Yes* 假设情绪脑可以靠理性的共同解决问题来克服，FBI 的转向则说明这个假设不成立。[二手：mgp] 可信度：高（多个摘要一致）
- **智识支点**：引用 Kahneman《Thinking, Fast and Slow》：System 1 的情绪反应塑造 System 2 的"逻辑"答案，所以"影响对方的 System 1 就能引导其 System 2"。[二手：mgp + oberlo 等] 可信度：高
- **重新定义"谈判"**：谈判是信息收集和影响行为，几乎包括所有"有人想从别人那里得到东西"的互动。[二手：mgp] 可信度：高
- **起源故事**：2006 年前后，Voss 混进 Harvard Law School 冬季谈判课。Robert Mnookin（Harvard Negotiation Research Project 主任）和 Gabriella Blum 扮演绑匪说"We've got your son, Voss. Give us one million dollars or he dies."，Voss 用 "How am I supposed to do that?" 反问，让对方失去方向。[二手：scribd/howtoes/bookey 摘要转述] 可信度：中高
- **原话**（经摘要转引）："No matter how we dress up negotiation in mathematical theories, we still act like animals…"（mgp 笔记近似原句）可信度：中

### 第2章 Be a Mirror（做一面镜子）
- **镜像（mirroring）**：重复对方最后（或最关键）的 1–3 个词，对方会接着展开。[二手：mgp] 高
- **三种声音**：①late-night FM DJ voice（下沉语调、平静缓慢，有选择地用，制造权威与可信感，又不引起防御）；②positive/playful voice（默认声音）；③direct/assertive voice（极少用，会引起反弹）。[二手：Goodreads 读者摘录 + goyder.substack] 高
- **"慢下来"**：节奏太快会让人觉得没被倾听。"When you slow the process down, you also calm it down."[二手：mgp] 中高
- **对付强势型人格的流程**：DJ 嗓音 → "I'm sorry…" → 镜像 → 沉默 → 重复。[二手：mgp] 高
- **原话**（经摘要转引）："Good negotiators expect surprises; great negotiators use their skills to reveal the surprises they are certain exist."（mgp）中

### 第3章 Don't Feel Their Pain, Label It（别感受他们的痛苦，给它贴标签）
- **战术同理心（tactical empathy）的定义**（经多个摘要转引的原话）："the ability to recognize the perspective of a counterpart, and the vocalization of that recognition"；并补充 "understanding the feelings and mindset of another in the moment and also hearing what is behind those feelings so you increase your influence in all the moments that follow"。[一手经二手转引：scienceofpeople、chrislehnes] 中高
- **同理心不等于同情**：书中明确区分 empathy 和 sympathy。[二手：mgp] 高
- **贴标签（labeling）**：用 "It seems / sounds / looks like…" 开头，**避免用 "I"**（会显得自利，还要为后果负个人责任），说完保持沉默。[二手：mgp] 高
- **情绪的两层**：presenting behavior（表层行为）/ underlying feeling（底层感受）。[二手：mgp] 高
- **"Never deny the negative"**：否认负面情绪反而会强化它。[二手：mgp] 中高
- **指控审计（accusation audit）**：事先列出对方可能说你的所有坏话，自己先说出来，"take the sting out"。[二手：mgp；MasterClass 文章] 高
- **自我声明的动机**："The first goal of these tools is human connection; that they might help you extract what you want is a bonus."（mgp 近似转述）中。**注意**：这和第6、7章的"操控性"表述有张力，见第七节矛盾2。

### 第4章 Beware "Yes", Master "No"（警惕"是"，驾驭"不"）
- **原话**（多个摘要一致）："'No' is the start of the negotiation, not the end of it." 以及 "We've been conditioned to fear the word 'No.' But it is a statement of perception far more often than of fact. It seldom means, 'I have considered all the facts and made a rational choice.' Instead, 'No' is often a decision, frequently temporary, to maintain the status quo. Change is scary, and 'No' provides a little protection from that scariness."[一手经二手转引：runn.io、willpatrick、readingraphics 等] 中高
- **三种 Yes**：counterfeit（假的）/ confirmation（确认式）/ commitment（承诺式）。[二手：mgp；BSG 文章 "The Three Types of Yeses You'll Hear During a Negotiation" 在搜索中可见] 高
- **说"不"给人安全感、控制感**，说明对方在投入思考。[二手：mgp] 高
- **一句话邮件**："Have you given up on this project?"，用来唤醒不回复的对象。[二手：mgp；BSG 后续文章反复出现] 高
- **对方怎么都不说"No"**：说明对方犹豫、困惑或有隐藏议程，应该走开。[二手：mgp] 中高
- "Nice, employed as a ruse, is disingenuous and manipulative."（mgp 近似转述）中

### 第5章 Trigger the Two Words…（触发 "That's right"）
- 理论来源：**Carl Rogers 的"无条件积极关注"**。[二手：mgp] 高
- **"That's right" 和 "You're right" 的区别**：前者表示对方"凭自由意志"认可你的总结并接受它；后者只是社交润滑，对方并不拥有这个结论，行为也不会变。[二手：mgp + scienceofpeople] 高
- **公式**：summary = paraphrase + label（复述含义 + 承认背后的情绪）。[二手：多个摘要一致] 高

### 第6章 Bend Their Reality（扭曲他们的现实）
- **对 win-win 的核心批评**（多个摘要一致的原话）："The win-win mindset pushed by so many negotiation experts is usually ineffective and often disastrous. At best, it satisfies neither side. And if you employ it with a counterpart who has a win-lose approach, you're setting yourself up to be swindled."[一手经二手转引：oberlo、runn.io、bobbypowers] 中高
- **黑鞋/棕鞋寓言**：妻子要丈夫穿黑鞋，丈夫想穿棕鞋，最后一只黑一只棕，是"最糟的结果"。[二手：Adam Barratt/Medium 等转述] 高
- **为什么人会妥协**："We don't compromise because it's right; we compromise because it is easy and because it saves face."（mgp 版本还多一句 "we compromise because it's safe"）中高
- **"No deal is better than a bad deal."** 原话，多个来源一致。中高
- **截止期限**：deadlines 是 "boogeymen"，往往任意、几乎总有弹性、后果没有想象中严重；隐藏自己的截止期限会增加僵局风险。（这一条反直觉，与很多谈判教材不同。）[二手：mgp] 高
- **"Fair"是最有力的词**：对方说 "We've given you a fair offer" 时，先镜像 "Fair?"，再贴标签 "It seems like you're ready to provide evidence to support that."；自己则主动说 "I want you to feel like you're being treated fairly at all times…"。[二手：mgp] 中高
- **Kahneman/Tversky 的前景理论**：certainty effect（确定性效应）+ loss aversion（损失厌恶）。真正的杠杆在于让对方相信交易失败他会有具体损失。[二手：mgp + oberlo] 高
- **锚定**：让对方先就金额开价；准备好承受极端的第一口价；报区间；用非整数；给一个不相关的意外小礼物来引发互惠。[二手：mgp] 高
- **薪资谈判**：坚持谈非薪资条款，并定义成功标准和下次加薪的指标。[二手：mgp] 高

### 第7章 Create the Illusion of Control（创造控制的幻觉）
- **校准问题（calibrated questions）**：用 What/How 开头；避免 can/is/are/do/does（可以用是/否回答）；"Why" 听起来像指控，只在对方的防御正好能帮你推动改变时才用。[二手：mgp] 高
- **"最伟大的校准问题"**：**"How am I supposed to do that?"**[二手：mgp + 第1章哈佛故事] 高
- **"控制的幻觉"**：让对方自己"设计"出其实是你的方案。[二手：mgp] 高
- 情绪自控优先："You cannot influence the emotions of another party without controlling your own"（mgp 近似转述）中
- **原话**（经摘要转引）："Negotiation is not an act of battle; it's a process of discovery."（Goodreads/consultclarity）中高

### 第8章 Guarantee Execution（保证执行）
- "Yes 没有意义，How 才有意义"：How 问题是优雅地说"不"的方式，还能逼对方思考怎么执行。[二手：mgp] 高
- 听到 "you're right" 或 "I'll try"，就继续问 How，直到得到 "that's right"。[二手：mgp] 高
- 识别桌子之外的 deal makers / deal killers。[二手：mgp] 高
- **7-38-55 规则**：7% 来自词语，38% 来自语调，55% 来自肢体和面部。[二手：mgp + 多个摘要] 高（书中确有此说法；**但该规则的科学性有争议**，见矛盾1）
- **Rule of Three**：让对方对同一件事同意三次（可以换成标签、总结、校准问题等不同形式），用来暴露虚假和不一致。[二手：mgp] 高
- **Pinocchio Effect**：说谎者用词更多、句子更复杂、第三人称代词更多；越难听到一个人说第一人称，他的权力往往越大。[二手：mgp] 高
- 说名字来人性化自己（"Chris discount"的故事，未见原文，**信息不足**）。
- 说"No"的阶梯（mgp 转述）："Your offer is very generous, but I'm sorry, that just doesn't work for me" → "I'm sorry but I'm afraid I just can't do that"。中高

### 第9章 Bargain Hard（硬性议价）
- **三种谈判者类型**：Analyst（分析型）/ Accommodator（迁就型）/ Assertive（强势型）。"Don't assume that you are normal"：别把自己的风格投射到对方身上。[二手：mgp] 高
- **Strategic umbrage**（有风度的愤怒）以及 "I feel ___ when you ___ because ___" 句式。[二手：mgp] 高
- 被动挨打时不反击，用校准问题化解；"never look at your counterpart as your enemy"。[二手：mgp] 高
- **Ackerman 议价法**（得名于前 CIA 人质谈判专家 Mike Ackerman）：设定目标价 → 首次出价 65% → 85% → 95% → 100%，每两次出价之间用同理心和不同方式说"不"；最后一次用精确的非整数，再加一个非金钱条款。[二手：mgp + scienceofpeople + coachingwithwisdom] 高
- "People getting concessions often feel better about the bargaining process than those who are given a single, firm, 'fair' offer."（mgp 近似转述）中

### 第10章 Find the Black Swan（找到黑天鹅）
- **定义**（经摘要转引）：Black Swans are "those hidden and unexpected pieces of information—those unknown unknowns—whose unearthing has game-changing effects on a negotiation dynamic."[一手经二手转引：freshworks/villager1598] 中高
- **三层知识**：known knowns / known unknowns / unknown unknowns（Rumsfeld 式分类，书中是否提到 Rumsfeld 未核实，**信息不足**）。[二手] 中
- **三种杠杆**：Positive（提供或扣留对方想要的东西）、Negative（让对方受损，借助损失厌恶）、Normative（用对方自己的规范和标准）。[二手：mgp + 多个摘要] 高
- **"Black Swans are leverage multipliers"**；杠杆"总可以被制造出来"。[二手：mgp] 高
- **"疯狂"背后的三个原因**：对方信息不完整、有不便透露的约束、有你不了解的需求或世界观。[二手：mgp] 高
- 在会议的开头和结尾寻找黑天鹅；邮件不适合找黑天鹅。[二手：mgp] 高
- **原话**（经摘要转引）："the adversary is the situation and that the person that you appear to be in conflict with is actually your partner."（Goodreads 转引）中高
- "Don't commit to assumptions; instead, view them as hypotheses and use the negotiation to test them rigorously."（Goodreads 转引）中高

---

## 三、反复出现 3 次及以上的核心论点（"真信念"）

| # | 论点 | 出现位置（≥3） | 标注 |
|---|---|---|---|
| 1 | **人是情绪驱动的"动物"，决策由情绪支配，理性是事后的** | 第1章（System 1/2、"act like animals"）；第6章（"actual decision making is governed by emotion"）；第3章（"their emotions are the problem"）；访谈中对 BATNA 的批评 | 一手经二手 / 高 |
| 2 | **"No" 是安全感，是谈判的开始；"Yes" 往往是假的** | 第4章全章；第8章（How = 优雅的 No；"I'm sorry, that just doesn't work for me"）；BSG 文章 "Why You Need to Use No-Oriented Questions™"、"Top 4 No-Oriented Questions"；"Have you given up on…" 邮件 | 一手 + 二手 / 高 |
| 3 | **同理心是战术工具，不等于同情，也不等于同意** | 第3章定义；访谈原话 "Empathy is not agreement. It's not even necessarily liking the other side."（经 oceanpersonalitytest/simpledetails 转引）；BSG 培训品牌 Tactical Empathy | 一手经二手 / 中高 |
| 4 | **反对妥协 / 反对 win-win / "No deal is better than a bad deal"** | 书名本身；第6章（黑白鞋、win-win "disastrous"）；第6章 deadline 部分重申 "No deal is better than a bad deal"；访谈中批评 BATNA 让人"超过 BATNA 就收手" | 一手经二手 / 高 |
| 5 | **损失厌恶是杠杆的核心** | 第6章（loss aversion、accusation audit 预设损失）；第10章（negative leverage "preys on loss aversion"）；第9章（Ackerman 中的让步心理） | 二手 / 高 |
| 6 | **慢下来、控制自己的情绪和声音** | 第2章（"slow it down"、DJ 嗓音）；第7章（自控，"bite your tongue"）；第9章（strategic umbrage、time-out） | 二手 / 高 |
| 7 | **让对方觉得是他自己想出来的（控制的幻觉 / 自主感）** | 第4章（"gently guide their counterpart to discover their goal as his own"）；第7章（illusion of control）；第8章（How 问题让方案"成为对方的"）；第5章（"that's right" 是对方凭自由意志说出的） | 二手 / 高 |

---

## 四、自创或重新定义的术语

| 术语 | 类型 | 说明 | 标注 |
|---|---|---|---|
| **Tactical Empathy™** | 重新定义 | 把 empathy 从"感同身受"改造成"识别对方视角并说出来，以增加影响力" | BSG 品牌术语 / 高 |
| **Accusation Audit™** | 自创（BSG 注册商标） | LinkedIn 帖子标题 "What Is the Black Swan Accusation Audit™?" | 一手 / 高 |
| **No-Oriented Questions™** | 自创（BSG 注册商标） | LinkedIn/BSG 文章标题带 ™ | 一手 / 高 |
| **Calibrated Questions** | 半自创 | 开放式问题的战术版 | 高 |
| **"That's right" vs "You're right"** | 自创区分 | 真认同和敷衍的区别 | 高 |
| **Black Swan** | 借用后重新定义 | 借自 Taleb（"罕见、不可预测、影响巨大的事件"），改造成谈判中"能改变局面的未知未知信息" | 二手 / 中高（命名动机未见 Voss 本人解释，**信息不足**） |
| **Late-night FM DJ voice** | 自创 | 三种声音之一 | 高 |
| **Counterfeit / Confirmation / Commitment Yes** | 自创分类 | 三种 Yes | 高 |
| **Pinocchio Effect** | 借用和挪用 | 来自哈佛研究者的语言研究（书中引用方未核实，**信息不足**） | 中 |
| **Strategic umbrage** | 自创 | 有风度的愤怒 | 中高 |
| **Ackerman model** | 引入命名 | 用前同事 Mike Ackerman 的名字命名 | 高 |
| **Positive / Negative / Normative leverage** | 半自创分类 | 三种杠杆 | 高 |
| **"Fair" 作为 "F-word"** | 重新定义 | BSG 文章 "An FBI Hostage Negotiator Teaches You the 'F' Word in Negotiations" | 一手（标题）/ 中 |
| **"Hostage mentality"** | 挪用 | 冲突中因无力感而防御或攻击 | 中 |

---

## 五、智识谱系：推荐和引用的书与人

### 5.1 书中引用（据二手笔记）
- **Daniel Kahneman**，《Thinking, Fast and Slow》（System 1/2）；**Kahneman & Tversky**，前景理论（certainty effect、loss aversion）。[二手：mgp/oberlo] 高
- **Roger Fisher & William Ury**，《Getting to Yes》：作为被批评的对象（"separate the people from the problem"等原则）。[二手：mgp] 高
- **Robert Mnookin**（Harvard Negotiation Research Project 主任）、**Gabriella Blum**：哈佛课堂和角色扮演的对手。[二手] 中高
- **Carl Rogers**（无条件积极关注）。[二手：mgp] 高
- **Nassim Taleb**（Black Swan 概念）。[二手] 中高
- **Albert Mehrabian**（7-38-55，书中引用）。[二手] 高
- **Gary Noesner**（Voss 在 FBI 危机谈判部门的上司，FBI "Behavioral Change Stairway Model"（主动倾听 → 同理心 → 融洽 → 影响 → 行为改变）的提出者之一）；**Fred Lanceley**。[二手：behavior-podcast/搜索摘要] 中
- **Mike Ackerman**（Ackerman 模型）。高

### 5.2 BSG 书单（"The Black Swan Book Club"，blackswanltd.com/book-club，经搜索摘要）
- Stephen Covey，《The 7 Habits of Highly Effective People》
- Stone/Patton/Heen，《Difficult Conversations》（**这本书出自 Harvard Negotiation Project**）
- Robert Cialdini，《Influence》
- William Poundstone，《Priceless》（锚定与定价心理）
- Mnookin 等，《Beyond Winning》（**Harvard 系**）
- Alex Korb，《The Upward Spiral》（神经科学）
- Daniel Pink，《To Sell Is Human》
- Goodreads "Black Swan recommended reading" 书架另列：Daniel Goleman《Emotional Intelligence》、Keith Ferrazzi《Never Eat Alone》
- BSG 另有文章 "The Top 12 Must-Read Books for Expert Negotiators"（未能读取全文，**信息不足**）

[一手（BSG 官网书单）经搜索摘要转引] 可信度：中高

**推断**：Voss 的谱系是"FBI 危机谈判（Noesner 的阶梯模型）+ 罗杰斯式人本心理学 + 行为经济学（Kahneman/Tversky/Poundstone）+ 影响力心理学（Cialdini）"。他公开批评 Harvard 学派，但书单里有两本 Harvard 系的书（Difficult Conversations、Beyond Winning），所以他实际上是"情绪化地反对 Harvard 的理性框架，同时吸收它的人际沟通部分"。[推断]

---

## 六、后续出版物与 The Edge 通讯（信息不足）

The Edge 是 BSG 的每周通讯，归档在 blackswanltd.com/the-edge 与 blackswanltd.com/newsletter/…。作者包括 Chris Voss、Derek Gaunt、Brandon Voss 等 BSG 教练。由于出口封锁和搜索配额用完，**只确认了以下文章存在（标题和要点来自搜索摘要）**：

| 标题 | 要点（摘要） | 作者 | 标注 |
|---|---|---|---|
| Why You Need to Use No-Oriented Questions™ in a Negotiation | "Saying 'no' makes people feel protected and in control" | BSG / Voss 转发 | 一手 / 中高 |
| Negotiation Training: The Top 4 'No-Oriented' Questions | 包括 "Is now a bad time to talk?"、"Have you given up on…?" | Voss（LinkedIn） | 一手 / 中高 |
| The Three Types of Yeses You'll Hear During a Negotiation | 延续 NSTD 第4章 | BSG | 一手 / 中 |
| What Is the Black Swan Accusation Audit™? / When to Focus an Accusation Audit™ Internally and Externally | 指控审计分对内、对外 | Voss（LinkedIn） | 一手（标题）/ 中 |
| An FBI Hostage Negotiator Teaches You the 'F' Word in Negotiations；How to Find Fairness In A Negotiation | "fair" 一出现，说明谈判已经情绪化；对方说"fair"往往是因为没有数据支撑 | BSG | 一手 / 中 |
| The Best of Chris Voss & Derek Gaunt (The Edge Year 1) | 2014 年 11 月，说明 The Edge 至少从 2013–2014 年就开始了 | BSG | 一手（存在性）/ 中高 |
| Partnership Lessons 1: Chris Voss；How To Get An Edge When Buying A House | — | BSG | 存在性 / 中 |
| 2016 年 6 月的 BSG 博客文章 | Voss 在其中分享 7:38:55 比例（Tuvya Amsel 在 *European Polygraph* 2019 年的论文中引用） | Voss | 二手转引 / 中 |
| Medium 文章 "The 9 Field-Tested, No-Fail Strategies To Help You Succeed In Your Next Negotiation" | 未读取 | @CVoss | 存在性 / 中 |

另外：BSG 主页上的金句 "In life, you don't get what's fair, you get what you negotiate"（经搜索摘要转引；原始出处未核实，**不作为确定原话**）。

---

## 七、对 "win-win" / Getting to Yes / BATNA 的立场

1. **书中立场**（一手经二手转引，中高）：win-win 思维 "usually ineffective and often disastrous"；*Getting to Yes* 的前提（情绪脑可以被理性的共同解决问题克服）是错的；"Never split the difference"。
2. **对 BATNA 的批评**（访谈原话经搜索摘要转引；来源可能是 Minter Dial 2019 年的播客、Farnam Street 的 Knowledge Project #27 或 Eric Barker 的访谈，**具体出处未能核实**，可信度：中）：
   - "BATNA becomes the goal and people have a tendency to quit as soon as they've exceeded their BATNA."
   - "if you need a BATNA, what do you do when you don't have one? You freak out…"
   - 他说自己做人质谈判时就先假定"there is no BATNA"。
   - 他承认 BATNA 是 "intellectually sound concept"，说见过 Roger Fisher，并称其为 "a genius guy"。
   - **注意**：这一组引文没能定位到唯一的原始 URL（用短语精确搜索也没有命中），**建议在 02-conversations 中复核**；在核实之前不要当作确定金句使用。
3. **据二手评论**：Voss "practically dismisses" BATNA 和 ZOPA，认为这些概念让谈判者接受低于最佳的结果。[二手：kimtasso.com 书评] 中

---

## 八、矛盾与张力（直接记录，不调和）

**矛盾1：7-38-55 的科学性**
Voss 在书中（第8章）和 2016 年 6 月的博客里都把 7-38-55 当作规则使用。但 Mehrabian 本人明确说过，这组比例只适用于"表达感受和态度"、而且信息不一致的实验情境（实验只测了单个词，被试只有女性，没有真实对话）。Big Think、influencePEOPLE、Minnesota State 的 "Communication is 93% Nonverbal: An Urban Legend" 等都批评这是误用。[二手] 高

**矛盾2："连接是第一目的" vs "操控与控制的幻觉"**
第3章称工具的首要目的是 human connection，"extracting what you want is a bonus"；第4章又说 "Nice, employed as a ruse, is disingenuous and manipulative"。可是第6章叫 "Bend Their Reality"，第7章是 "Create the Illusion of Control"，第10章说杠杆"总可以被制造出来"，并主张用 accusation audit "anchor their emotions in preparation for a loss"。[二手：mgp] 高

**矛盾3："让对方先开价" vs Ackerman 主动出价 65%**
第6章建议 "Let the other side anchor monetary negotiations"；第9章的 Ackerman 模型却由己方先出 65% 的价格（mgp 笔记第9章也写道：如果必须先报价，就提一个别人可能开出的极高价）。两者适用条件书中有区分吗？**信息不足**。[二手] 中高

**矛盾4："Never split the difference" vs 结构化让步**
书名反对折中，但 Ackerman 模型本身就是 65→85→95→100 的递减让步，第9章还说接受让步的一方对过程更满意。可以解释为"让步是战术，折中是目标"，但按要求这里不做调和。[二手+推断] 中

**矛盾5：把 "fair" 当武器 vs 自己主动用 "fair"**
书中警告 "fair" 是最有力、最具破坏性的词，对方说 "We've given you a fair offer" 是 "nefarious"；同时又推荐自己主动说 "I want you to feel like you're being treated fairly at all times"。[二手：mgp] 中高

**矛盾6：公开批评 Harvard 学派 vs 书单与经历**
他批评 *Getting to Yes* 和 BATNA，但自己的转型经历始于哈佛谈判课；BSG 书单收录 *Difficult Conversations* 和 *Beyond Winning*（都出自 Harvard 系）；访谈中他还称 Fisher 是 genius、*Getting to Yes* 是 "intellectually sound"。[一手 + 二手] 中

**矛盾7：截止期限**
他称 deadlines 是 "boogeymen"，没有想象中重要；但损失厌恶和"让对方觉得会失去什么"的整套方法，本质上依赖时间压力和稀缺感。[推断] 低

---

## 九、关键发现小结

1. NSTD 仍是唯一的系统性主著作；2022 年与 Steve Shull 合著的 *The Full Fee Agent* 是唯一后续书籍，属于行业应用。2024–2026 年没有发现新书，2026 年以"十周年"巡讲为主。
2. 最稳定的真信念是"人是情绪动物，'No' 是安全感，同理心是战术"，这三条在书、BSG 文章和访谈中都反复出现。
3. BSG 已把多个核心技巧注册为商标（Accusation Audit™、No-Oriented Questions™），说明他的术语体系同时也是商业产品体系。[推断，依据：文章标题中的 ™]
4. 智识谱系是 FBI 危机谈判（Noesner）+ Carl Rogers + Kahneman/Tversky + Cialdini/Poundstone。他对 Harvard 学派是"批评框架、吸收技巧"。
5. 已知的科学争议：7-38-55 规则是对 Mehrabian 研究的误用。

---

## 来源清单

### 一手（Voss 本人或 BSG 发布；多数只经搜索摘要读到）
1. [一手] NSTD 原书（Voss & Raz，2016，HarperBusiness）：未能直接读取，原话均经下列二手转引
2. [一手] BSG 书页 https://www.blackswanltd.com/never-split-the-difference （封锁，仅搜索可见）
3. [一手] BSG 书单 https://www.blackswanltd.com/book-club （经搜索摘要）
4. [一手] BSG "The Top 12 Must-Read Books for Expert Negotiators" https://www.blackswanltd.com/newsletter/the-top-12-must-read-books-for-expert-negotiators?hs_amp=true （仅标题）
5. [一手] BSG "Why You Need to Use No-Oriented Questions™ in a Negotiation" https://www.blackswanltd.com/newsletter/why-you-need-to-use-no-oriented-questions-in-a-negotiation
6. [一手] BSG "The Three Types of Yeses You'll Hear During a Negotiation" https://www.blackswanltd.com/newsletter/the-three-types-of-yeses-youll-hear-during-a-negotiation
7. [一手] BSG "How to Find Fairness In A Negotiation" https://blog.blackswanltd.com/the-edge/how-to-find-fairness-in-a-negotiation
8. [一手] BSG "The Best of Chris Voss & Derek Gaunt (The Edge Year 1)" https://www.blackswanltd.com/newsletter/2014/11/the-best-of-chris-voss-derek-gaunt-the-edge-year-1/
9. [一手] BSG "Partnership Lessons 1: Chris Voss" https://www.blackswanltd.com/newsletter/partnership-lessons-1-chris-voss
10. [一手] BSG *The Full Fee Agent* 页面 https://www.blackswanltd.com/the-full-fee-agent
11. [一手] Voss LinkedIn "What Is the Black Swan Accusation Audit™?" https://www.linkedin.com/posts/christophervoss_what-is-the-black-swan-accusation-audit-activity-7125451415849693185-omRv
12. [一手] Voss LinkedIn "When to Focus an Accusation Audit™ Internally and Externally" https://www.linkedin.com/posts/christophervoss_when-to-focus-an-accusation-audit-internally-activity-6866721862978826240-YrnZ
13. [一手] Voss LinkedIn "Why You Need to Use No-Oriented Questions™" https://www.linkedin.com/posts/christophervoss_why-you-need-to-use-no-oriented-questions-activity-7108917462938652672-WrCp
14. [一手] Voss LinkedIn "The Top 4 'No-Oriented' Questions" https://www.linkedin.com/posts/christophervoss_negotiation-training-the-top-4-no-oriented-activity-7034643049116827648-NohV
15. [一手] Voss Medium "The 9 Field-Tested, No-Fail Strategies…" https://medium.com/@CVoss/the-9-field-tested-no-fail-strategies-to-help-you-succeed-in-your-next-negotiation-41bc8aa1f454 （仅标题）
16. [一手] MasterClass "The Accusations Audit" https://www.masterclass.com/classes/chris-voss-teaches-the-art-of-negotiation/chapters/the-accusations-audit （未读）
17. [一手] 访谈（BATNA 批评引文的候选出处，未能定位）：https://www.minterdial.com/2019/04/great-negotiations-chris-voss/ ；https://fs.blog/knowledge-project-podcast/chris-voss/ ；https://bakadesuyo.com/full-chris-interview/
18. [一手] 伦敦十周年演讲 https://www.eventimapollo.com/events/chris-voss

### 二手（他人总结或评论）
19. [二手] mgp/book-notes 逐章笔记（本次唯一全文读取的来源）https://github.com/mgp/book-notes/blob/master/never-split-the-difference.markdown
20. [二手] Science of People 逐章摘要 https://www.scienceofpeople.com/never-split-difference-summary/
21. [二手] Graham Mann 书摘 https://grahammann.net/book-notes/never-split-the-difference-chris-voss （封锁，仅搜索摘要）
22. [二手] Runn.io 逐章摘要 https://www.runn.io/blog/never-split-the-difference-summary
23. [二手] Oberlo 摘要 https://www.oberlo.com/blog/never-split-the-difference-by-chris-voss-summary
24. [二手] Will Patrick 笔记 https://www.willpatrick.co.uk/notes/never-split-the-difference-chris-voss/
25. [二手] Readingraphics https://readingraphics.com/book-summary-never-split-the-difference/
26. [二手] Kim Tasso 书评（BATNA/ZOPA 立场）https://kimtasso.com/book-review-never-split-the-difference-negotiating-as-if-your-life-depended-on-it-by-chris-voss-with-tahl-raz/
27. [二手] Freshworks 摘要（Black Swan 定义）https://www.freshworks.com/crm/sales/sdr-sales-development-reps/summary-of-never-split-the-difference-blog/
28. [二手] Villager1598 第10章摘要 https://villager1598.medium.com/black-swans-never-split-the-difference-chapter-10-summary-7bce5924e894
29. [二手] Coaching With Wisdom（Ackerman）https://www.coachingwithwisdom.com/blog/the-ackerman-model-for-negotiation
30. [二手] Goyder substack（DJ voice）https://goyder.substack.com/p/late-night-dj-voice-and-why-you-need
31. [二手] Adam Barratt（黑鞋/棕鞋）https://medium.com/@AdamBarratt/bookbabble-17-never-split-the-difference-by-chris-voss-7c32b412a27f
32. [二手] Bobby Powers 书评 https://bobbypowers.com/review-never-split-the-difference/
33. [二手] Goodreads Voss 语录页 https://www.goodreads.com/author/quotes/5525291.Chris_Voss
34. [二手] Shortform *The Full Fee Agent* 摘要 https://www.shortform.com/summary/the-full-fee-agent-pbp18613-b-summary-chris-voss-and-steve-shull
35. [二手] Big Think 7-38-55 辟谣 https://bigthink.com/the-learning-curve/the-7-38-55-rule-debunking-the-golden-ratio-of-conversation/
36. [二手] Amsel, *European Polygraph* 2019（引用 Voss 2016 年博客）https://www.polygraph.pl/vol/2019-2/european-polygraph-2019-no2-amsel.pdf
37. [二手] "Communication is 93% Nonverbal: An Urban Legend" https://cornerstone.lib.mnsu.edu/cgi/viewcontent.cgi?article=1000&context=ctamj
38. [二手] Behavior Podcast（Gary Noesner）https://behavior-podcast.com/gary-noesner-fbi-negotiator-at-waco-on-de-escalation-and-reading-people/
39. [二手] Goodreads 书架 "Black Swan recommended reading" https://www.goodreads.com/shelf/show/black-swan-recommended-reading
40. [二手] Ocean Personality Test（"Empathy is not agreement" 转引）https://oceanpersonalitytest.com/blog/chris-voss-never-split-the-difference-empathy/
41. [二手] LessWrong MasterClass 评测 https://www.lesswrong.com/posts/CRAzG386t3suSqDgd/chris-voss-negotiation-masterclass-review （未读，供 04-external-views 跟进）

**统计**：共 41 条来源，一手 18 条（约 44%），二手 23 条。但一手来源绝大多数只读到了标题或搜索摘要，**真正读到全文的只有一份二手笔记（mgp）**。建议在网络可用时，优先补读 BSG 的 The Edge 归档和 NSTD 原书页码。
