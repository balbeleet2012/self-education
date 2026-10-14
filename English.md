# 从英语的角度讲英语语法

> 按英语语法自身的体系（而非中文教学语法的术语）讲解。
> 阅读路线（零基础）：一~三 认积木 + 简单句骨架 → 四 谓语与及物性 → 五 动词链（全文重心，可先读"三对正交参数"建立开关模型）→ 六 名词短语 → 七 一致 → 八 复合句 → 九 总图回收。

## 一、英语语法的核心思想

英语语法只解决一件事：**怎么把词合法地拼成句子**。它围绕三条主线：

1. **Syntagmatic（线性组合）**：词 → 短语 → 分句 → 句子，一层套一层
2. **Paradigmatic（词形变化/selection）**：每个位置允许填什么词、用什么形态（morphology + selection rules）
3. **Function（功能）**：每个成分在句中扮演什么角色（subject, predicator, object, complement, adjunct）

英语语法的底层公理：**词和词搭上关系，必须写出来**。要么变形（时态、复数），要么加功能词（介词、助动词、连词），要么靠排队（固定词序）——不能像中文那样把词一摆让人意会。这是理解一切英语规则的钥匙。

## 二、词类（Word Classes / Parts of Speech）

英语词类（传统"8 大词类" + determiner 单列），按**能不能自己变形**分两大阵营：

| | 类别 | 变形能力 | 例 |
|---|---|---|---|
| **开放类**（内容词） | noun, verb, adjective, adverb | 有：dogs/running/bigger/loudly | 词汇意义主体 |
| **封闭类**（功能词） | determiner, pronoun, preposition, conjunction, auxiliary | 基本没有 | 纯语法胶水 |

关键洞察：**英语句子 = 内容词负责语义 + 功能词负责语法**。`The dogs have been chasing cats` 里 `the / have / been` 全是功能词，它们承载了限定性、完成体、进行体等全部语法信息。

一句话拆开看词类全景——内容词填槽，功能词粘接：

```
The quick brown fox jumps over the  lazy dog  and  it   finally catches it.
det  adj   adj   N    V     prep det  adj  N    conj pron adv     V       pron
（那只敏捷的棕色狐狸跳过懒狗，并且它最终抓住了它。）
```

### 开放类（open class）= 实词，封闭类（closed class）= 虚词

在中文语境的英语语法教学里，**closed class words** 最常对应"虚词"（也叫功能词/结构词/语法词），与它对立的是**实词**（content words，即 open class 开放类词）。

| 英文术语 | 中文常见译名 | 成员 |
|---|---|---|
| open class（开放类） | 实词 / 实义词 / 内容词 | 名词、动词（实义）、形容词、副词 |
| closed class（封闭类） | 虚词 / 功能词 / 结构词 | 介词、连词、冠词、代词、助动词/情态动词、限定词、感叹词（有的体系算入） |

**"封闭"的含义**：这个类几乎不接纳新成员——

- 英语随时能生造新名词、新动词（google → to google），所以实词是开放类
- 但你不可能新造一个介词或冠词进入英语——of、the、and 这些集合几百年来基本固定，所以叫封闭类

**注意点**：

- 中文教材有时会直接用音译概念"封闭词类"，但讲语法功能时通常就说"虚词"
- 中国传统语法里的"虚词"（之乎者也）和英语的 closed class 概念基本对应，但不完全重合：英语的代词一般归入封闭类，而它在汉语里算实词还是虚词各家有争议
- 判断标准除了"不增新成员"，还有一条：**虚词主要承担语法功能而非词汇意义，且通常不重读**（of、the 在句中弱读）

一句话：**closed class = 封闭类词 = 虚词（功能词）**，成员是介词、连词、冠词、代词、助动词这一小撮"搭架子"的词。

## 三、句子结构（Clause Structure）

### 5 大核心槽位

英语语法用 5 个功能标签描写分句：

- **S** Subject（主语）：管着谓语动词的那个成分——用主格，动词的单复数跟着它走
- **V** Predicator/Verb（谓语动词核心）：全句唯一"扛时间"的词
- **O** Object（宾语）：动作的承受者，分 direct/indirect
- **C** Complement（补足语）：给主语或宾语"下定义"（不可删）
- **A** Adjunct（状语）：时间/地点/方式等外围信息（可删）

#### 5 大句型（complementation）

动词类型决定槽位组合，即 5 大句型：

```
SV:   Time flies.                          时间飞逝。（主+谓）
SVO:  She opened the door.                 她打开了门。（主+谓+宾）
SVOO: He gave me a gift.                   他给了我一份礼物。（主+谓+间宾+直宾）
SVOC: They painted the wall red.           他们把墙刷成了红色。（主+谓+宾+宾补）
SVC:  He is tall. / He became a doctor.    他很高。/ 他成了医生。（主+系+表）
```

英语视角下，**句型错误的本质 = 动词和它后面跟的东西不配套**（complementation 不匹配）：suggest 不接"宾+to do"这种框架，所以 `*He suggested me to go` 是错的，得换 `He suggested that I go`。

每个动词能接什么 frame 是词典属性，中式英语的高频踩坑都在这：

```
*I want that you go.        → I want you to go.          （want 不接 that 从句）
*She explained me it.       → She explained it to me.    （explain 不接双宾）
*He suggested me to go.     → He suggested that I go.    （suggest 不接宾+to do）
*We discussed about it.     → We discussed it.           （discuss 是 vt.）
*He married with her.       → He married her.            （marry 是 vt.）
```

### 4 大分句类型（按语用功能）

| Clause type | 词序特征 | 例 |
|---|---|---|
| **Declarative** 陈述 | S + V | `You are late.` |
| **Interrogative** 疑问 | **operator 提前**：V(operator) + S | `Are you late?` / `When did you arrive?` |
| **Imperative** 祈使 | 无 S，动词原形 | `Sit down.` |
| **Exclamative** 感叹 | what/how 前置，V 不提前 | `What a day it is!` |

**operator（操作词）**是英语语法独有概念：be/have/do/情态动词中排第一个的词。疑问倒装、否定加 `n't`、附加问句全由它执行。没有 operator？`do`-support 救场（`Did he go?`）——这是英语独有的机制。

operator 的全套任务——同一句话的四种变换都由它执行：

```
He can swim.                  陈述
Can he swim?                  疑问：operator 提前
He can't swim.                否定：operator + n't
He can swim, can't he?        附加问句：operator 回指

He goes. → Does he go? / He doesn't go. / He goes, doesn't he?
没有 operator（goes 是裸实义动词）→ do-support 补位，且三单 -s 转移到 do 上（does）
```

## 四、谓语与及物/不及物动词

### 谓语（Predicate）

英语句子先劈两半：`句子 = Subject + Predicate`（主语 + 谓语）。Predicate 不只是那个动词，而是**动词带着宾语、补足语、状语凑成的整个"说了主语什么"的部分**；动词是其中的核心（predicator）。

- 谓语动词必须**限定（finite）**：身上带时态——它负责把主语"钉"在某个时间点上，没它这句话就没有"什么时候"（什么叫限定、为什么全句只能有一个，见第五章「限定 vs 非限定」）
- 英语不允许"光杆主语"：`She beautiful.` ❌ → `She **is** beautiful.`——没动词就没谓语，也就不成句子

按结构谓语分两型：

- **简单谓语（simple predicate）**：单个实义动词（或动词短语）独立承担——`He slept.` / `She opened the door.`
- **复合谓语（compound predicate）**：辅助成分 + 动词/表语拼成，再分两小类——
  - **动词性复合谓语** = 助动词/情态动词 + 实义动词：`She can swim.` / `He has finished.`
  - **名词性复合谓语（系表）** = 连系动词 + 表语：`She is a teacher.` / `He became angry.`

### 及物动词（vt.）与不及物动词（vi.）

- **vt.（transitive）**：动作必须跨越到一个宾语上才语义完整。`She opened the door.`——宾语是动作承受者
- **vi.（intransitive）**：动作自我完结，不接宾语。`He slept.`——接对象必须绕介词：`listen **to** music`

#### 判别 vt./vi. 的三条方法

1. **能否被动化**：vt. 能（`The door was opened.`），vi. 不能 → 金标准
2. **疑问方式**：vt. 问"什么/谁"，vi. 问"怎么样"
3. **vi. 想接对象必须走介词**（介词短语是状语不是宾语）

坑点：同一词可两用（`The door opened.` / `She opened the door.`）；汉英及物性不对应（汉语"听音乐"直挂宾语，英语 `listen` 是 vi.）——vt./vi. 是每个动词的词典属性，不能按汉语语感推。

汉英及物性不对应的高频清单（vi. 的介词别丢，vt. 的介词别加）：

```
vi. 必须带介词：listen to / look at / wait for / depend on /
                arrive at / insist on / apologize to sb. for
vt. 不许加介词：*marry with → marry sb. / *discuss about → discuss sth.
               *enter into a room → enter a room / *reach to → reach sp.
```

#### 两个进阶点

- **交替动词（ergative/labile pairs）**：同一动词两格切换且语义有规律——`She opened the door`（vt.，施事+受事）/ `The door opened`（vi.，受事当主语）。`open/break/boil/burn/move` 一族都玩这个魔术：vi. 用法其实是"没有交代施事的被动变体"

  ```
  She boiled the water.  /  The water boiled.      她烧开了水 / 水开了
  He moved the car.      /  The car moved.         他挪了车 / 车动了
  He closed the door.    /  The door closed.       他关了门 / 门关上了
  Someone broke the vase. / The vase broke.        有人打碎了花瓶 / 花瓶碎了
  ```
- **连系动词清单**：be + 感官系（look/sound/taste/feel/smell）+ 变化系（become/get/turn/grow/go）+ 保持系（remain/stay/keep）。判别法：能换成 `be` 且句义基本不变 → 系动词 → 后面接形容词不接副词（`The soup tastes good`，不是 `*well`）

## 五、动词系统（英语语法最重的部分）

**Lexical verb = 实义动词**（也叫主动词 main verb）——动词短语里携带实际词汇意义、且**永远排在助动词链最后**的那一个动词。英语动词系统负担最重，是因为**时、体、态、式四套语法信息全压在动词链这一个位置上**——名词只要标个复数，形容词只要标个比较级，动词却要同时交代"何时发生、怎么看待、主动被动、真实与否"。

### 动词的两层分工

| 类别 | 中文 | 成员 | 功能 |
|---|---|---|---|
| **lexical verb**（开放类） | 实义动词 / 主动词 | run, eat, think, give… | 带词典意义，说明主语"做什么/是什么" |
| **auxiliary verb**（封闭类） | 助动词 / 辅助动词 | 基本助动词 be/do/have + 情态 can, will, must… | 不带完整词汇意义，只出语法力：构成时体态、否定、疑问、强调 |

一句话：**助动词出语法，实义动词出意思**——这条线是整个动词系统的骨架。

#### 动词的功能五分法

两层分工再细一档，按句中功能分五类：

| 类别 | 作用 | 例 |
|---|---|---|
| **实义动词**（lexical） | 表动作/状态，谓语核心 | run, walk, swim（动作）；eat, drink, write（行为）；know, believe, love（心理）；give, take, make, put（及物）；sleep, arrive, die（不及物） |
| **连系动词**（copular/linking） | 连接主语与表语 | be；感官系 look, sound, taste, feel, smell；变化系 become, get, turn, grow, go, fall；保持系 remain, stay, keep；表象系 seem, appear |
| **基本助动词**（primary aux） | 构成时态/语态/否定/疑问 | be（进行体+被动）；do（do-support/强调）；have（完成体） |
| **情态动词**（modal） | 表推测/义务/许可，后接原形 | can/could, may/might, shall/should, will/would, must, ought to, need, dare |
| **半助动词**（semi-aux） | 功能同助动词 | be going to, have to, be able to, be supposed to, be about to, used to, had better, would rather |

另按词形/性质切还有两刀：

- **限定（finite）vs 非限定（non-finite）**：限定动词带人称/时态变化、能当谓语；非限定（不定式、-ing、过去分词、动名词）**自己撑不起谓语**——认一个动词是不是谓语，就看它扛不扛时间
- **延续性 vs 非延续性**：live/work 能拖长（配 `for/since`）；die/arrive 是一眨眼的事，没法拖——`*He has died for three years` 非法，要说"死了三年"得换成 `has been dead for three years`（用状态说法绕开瞬间动词）

#### 限定 vs 非限定：这个动词"算不算数"的分水岭

**"限定"不是词类，是岗位**——同一个动词换位置就换身份：`is` 在 `is writing` 里是限定动词，在 `to be eaten` 里就是非限定。

**限定动词（finite）= 站在链首、扛时制的那个动词**。它干三件事：

1. **扛时间**：把整句钉在"现在/过去"上（may→might、has→had、is→was、writes→wrote）
2. **当 operator**：疑问倒装、否定 n't、附加问句全归它执行（`Can he go?` / `He can't go.` / `He can, can't he?`）——裸实义动词干不了这三件，得 do 来补位（`Did he go?`）
3. **让句子"算数"**：有了它，一堆词才升级成真可真假的句子；没有它，`running`、`to run` 只是概念，不是话

**非限定动词（non-finite）= 链上除链首外的所有动词 + 不定式/-ing/-ed 三形**。特征：

- 不扛时间、不随人称变——`to eat` `eating` `eaten` 放在任何时代都长一个样
- 撑不起谓语，只能当"建材"：在链里给助动词打下手（`be **working**`），或单飞去客串名词/形容词（`to eat` 当宾语、`eaten` 当定语）——这就是后面"三对正交参数"之外动词系统的另一半地盘

**为什么英语非要这么分**：英语规定一句（一个分句）只能有一个"时间锚"。多出来的动词不许都扛时间，必须降级——不定式、分词、动名词就是英语造出来的"降级通道"。这也是为什么 `*She is eats`、`*He will goes` 都非法：第二个动词带了时间/人称标记，撞了唯一锚点。

**判别三问**：

1. **它在不在链首**？限定只出现在链首——`to eat`/`eating`/`eaten` 永远排不进链首
2. **它带不带时制**？能按 present/past 配对就是限定：is/was、has/had、may/might、writes/wrote
3. **换时间谁变形**？把句子从现在换到过去，变形的那个词就是限定——`She may go → She might go`，变的是 may，不是 go

**特例**：modal 只有限定形态（`*to may` `*maying` `*mayed` 全不存在），所以 modal 一出场必占链首——这也是它只能当"开关四"占位词的原因。

### 动词短语的结构：最多 4 助动词 + 1 实义动词

```
槽位→        modal         perfect        progressive    passive        lexical
             情态          完成(have)     进行(be)       被动(be)       实义动词
She          may           have           been           being          interviewed
```

组装方向是**从右到左**：以最右的 `interviewed` 为核，每往左一个词就把右边整串再包一层——`interviewed`"被采访" → `being interviewed`"正在被采访"（passive 槽）→ `been being interviewed`"一直在被采访"（progressive 槽）→ `have been being interviewed`"已经一直在被采访"（perfect 槽）→ `may have been…`"可能已经一直在被采访"（modal 槽）。它不是单词堆砌，是一台按固定顺序组装的机器：`may(have(been(being(interviewed))))`。

两条规则：

1. **第一个动词是"限定成分"（finite/operator）**：时制、人称一致、否定、主谓倒装全压在它头上——`She may have been…` 里 `may` 扛限定功能（may/might 是同一 modal 的现在/过去变体）。这就是"谓语 = 把主语绑定到时间上"的实现方式：**绑定时间的不是实义动词，是链首那个限定词**——`running` 单独成不了谓语，`is running` 里的 `is` 才完成绑定
2. **实义动词永远在最后、且有且仅有一个**：它可以是任何非限定形式（原形/-ing/过去分词），但不承担限定功能——限定性全被链首"抢"走了

顺序固定，每层给后面的词强制一个形态：modal→原形、have→过去分词、be→现在分词、be→过去分词。

按助动词个数看阶梯（实战里 ≥3 层已罕见，4 层是理论上限）：

```
works                            0 aux：裸实义动词自己扛限定（他工作。）
is working                       1 aux：progressive（他正在工作。）
has been working                 2 aux：perfect + progressive（他一直在工作。）
may have been working            3 aux：modal + perfect + progressive（他可能一直在工作。）
may have been being followed     4 aux：modal + perfect + prog. + passive（他可能一直被人跟踪着。）
```

#### 各槽位能填什么词

每个槽位能填的词其实**非常少**——perfect/progressive/passive 三个槽各自只有一个词，只是形态会变：

| 槽位 | 能填的词 | 可能出现的形态 | 形态由谁决定 |
|---|---|---|---|
| **modal**（情态） | `can/could, may/might, shall/should, will/would, must` | 永远限定形，最多一个 | 只能站链首 |
| **perfect**（完成体） | 只有 `have` 一个词 | `have / has / had`（链首时）· `have`（modal 后） | 前一词强制的形态 |
| **progressive**（进行体） | 只有 `be` 一个词 | `is/am/are/was/were`（链首）· `be`（modal 后）· `been`（完成 have 后）。**注意没有 `being`**——`being` 跟在"进行 be"后意味着进行套进行（`*is being working` 非法），跟 have 后则是 `been`；`-ing` 形的 be 只属于被动槽 | 同上 |
| **passive**（被动） | 只有 `be` 一个词 | `is/am/are/was/were` · `be` · `been`（完成 have 后）· `being`（进行 be 后） | 同上 |
| **lexical**（实义动词） | 任意实义动词 | 原形（modal/一般时）· `-ing`（进行 be 后）· 过去分词（完成 have/被动 be 后） | 同上 |

所以这条"5 层链"的真相是：**只动用两个助动词单词 + 一个 modal 家族**——`have` 出完成，`be` 既出进行又出被动，modal 出情态。

**同一个 `be` 在不同槽位反复出场，形态由它左边紧邻的词决定**——接力规则对每个词一视同仁：modal 后→原形、have 后→-ed 形、进行 be 后→-ing 形。

```
槽位→                modal   perfect   progressive   passive   lexical       中文
                     情态    完成      进行         被动      实义
will be working      will    —         be            —         working       她将在工作着（modal+进行）
                                          ↑ G槽 be：左边是 modal → 原形 be
has been working     —       has       been          —         working       她一直在工作（完成+进行）
                                          ↑ G槽 be：左边是 have → -ed 形 been
is being interviewed —       —         is            being     interviewed   她正在被采访（进行+被动）
                                                        ↑ V槽 be：左边是 G槽 be → -ing 形 being
has been interviewed —       has       —             been      interviewed   她已经被采访了（完成+被动）
                                                        ↑ V槽 be：左边是 have → -ed 形 been
```

**关键辨析：`been` 同一个形状可以属于不同的槽**——`has been working` 和 `has been interviewed` 开头都是 `has been`，但两个 `been` 不是一回事：

- `has been **working**`：`been` 是**进行槽**的 be（后面跟 -ing → 正在做）
- `has been **interviewed**`：`been` 是**被动槽**的 be（后面跟 -ed → 被做）

判别方法：**看它右边一个词穿什么外衣**——`been + -ing` = 进行槽，`been + -ed` = 被动槽。

四槽全占时这条规则连轴转——每个词都干两件事：**自己穿左边邻居指定的外衣 + 给右边邻居下着装令**：

```
may            have              been                being              interviewed
modal(情态)    perfect(完成)     progressive(进行)    passive(被动)      lexical(实义)
没人管它       听 may 的令：      听 have 的令：       听进行be的令：      听被动be的令：
自带限定形      必须穿原形        必须穿 -ed 形        必须穿 -ing 形      必须穿 -ed 形
（链首老大）    → 就成了 have     → be 穿成 been       → be 穿成 being     → interview 穿成 interviewed
```

读法：**上一个词决定下一个词的长相**。所以 `may have`（不是 `*may has`）、`have been`（不是 `*have be`）、`been being`（不是 `*been be`）、`being interviewed`。

边界说明（四个不守规矩的情况）：

- **情态动词不能叠**：一句里只准有一个 may/can/will——`*He will can swim` 不行；想说"将会能"得换成 `will be able to swim`（`be able to` 这类短语是专门给情态动词当替身的——情态动词自己变不出非限定形态）
- **几个"编外"情态动词**：`ought to / used to / need / dare` 能干情态的活但形态不守规矩——`ought to` 后面带 to、`used to` 只有过去式、`need/dare` 有时像普通动词（`He needs to go`）
- **被动有口语版**：`He got fired`（他被炒了）里 `get` 顶替了被动槽的 `be`——口语常用、带"遭了这事"的味道，书面语还是用 `be`
- **`be going to / have to` 这类短语不占槽**：整个短语合起来当一个情态动词用，直接站链首——`He is going to be working` 里的 `is going to` 相当于 `will`

一句话：**链的骨架只有 `modal + have + be + be` 四块积木**，每个位置允许的词写死了；长链的变化全是"前一个助动词给后一个定形态"造成的表面变形。

#### 链尾实义动词的五张脸（原形 / 三单 / 过去式 / -ing / 过去分词）

助动词讲完了，轮到链尾真正干活的那个动词。**它穿什么由左边邻居点菜**：modal 后→原形、进行 be 后→-ing、have 或被动 be 后→过去分词；自己站链首当谓语时又能多穿两张脸。以 write 为例：

| 长什么样 | 什么时候穿 | 它表达什么 |
|---|---|---|
| **write** 原形 | modal 后、不定式、一般现在时非三单 | 光说"写"这个动作，啥都没加：`can write` / `to write` / `I write` |
| **writes** 三单 | 站链首 + 现在 + 主语是"他/她" | "他/她"现在写：`She writes.` |
| **wrote** 过去式 | 站链首 + 过去 | 这事发生在过去——它自己带时间：`She wrote.` |
| **writing** -ing | 跟在进行 be 后 | 正在写——钻进动作里面看：`is writing` |
| **written** 过去分词 | 跟在 have 后（完成）或被动 be 后（被动） | 写完的/被写的——动作已落地：`has written` / `was written` |

（过去分词：规则动词长 `-ed`，一批不规则动词长 `-en`：written/eaten/broken）

两个最容易混的点：

**1. `wrote` 和 `written` 都是"过去的长相"，但岗位完全不同**

- `wrote` = **过去时**（finite）：它是链首，自己扛时间——"写"这件事发生在过去
- `written` = **过去分词**（nonfinite）：不扛时间，只带"已完成/被施加"的味道——时间永远由它左边的助动词管

```
She wrote the letter.          wrote 扛"过去"
She has written the letter.    written 不带时间，has(present) 扛"现在回看"
The letter was written.        written 带"被施加"味，was(past) 扛"过去"
```

规则动词这张脸是重合的（`worked` 一身兼过去式+过去分词），所以容易混；不规则动词（write/wrote/**written**、eat/ate/**eaten**）把两个岗位分开了——背不规则动词表的价值就在这。

**2. `-ing` 和 `-ed` 脱离助动词也能用，但味道不变**

实义动词单飞作定语/名词时，外衣的味道就是它独立的含义：

```
-ing：主动/正在进行的味道
  a running man          一个正在跑的男人（他自己在跑）
  boring movie           令人烦的电影（电影"烦"别人，主动方）

-ed：被动/已完成的味道
  the fish eaten by the cat   被猫吃掉的鱼（鱼是被吃方）
  a broken window         一扇被打碎的窗
  a bored student         感到无聊的学生（学生是被弄烦的一方）
```

记忆线：`-ing` = "**主动/进行中**"（动作从自身发出还在进行），`-ed` = "**被动/已完结**"（动作施加到身上已成定局）。这和它在链里的岗位完全同源：进行体用 `-ing` 因为它表达"进动作内部看"，被动和完成都用 `-ed` 因为它表达"动作落地、主语承受结果"。

### 实义动词自身的分类（学语法时真正要记的）

- **按补足成分**：不及物（sleep）、及物（eat）、双宾（give sb sth）、系动词（become, seem）、宾补（make him go）——决定 5 大句型
- **按体性**：动态（run, write）vs 静态（know, belong）——静态动词不进进行体 `*I am knowing`
- **按形态**：规则（work/worked/worked）vs 不规则（go/went/gone，约 200 个要背）
- **按延续性**：延续（live, work——可配 for/since）vs 非延续（die, arrive——瞬间动作，持续义要换系表结构）

### 为什么说动词系统"最重"

名词只管数、格两件事；动词要管五件：**时、体、态、式、限定/非限定**。而且非限定三形式（不定式、-ing 分词、-ed 分词）又各自撑起名词化、状语从句缩减等一大片句法——英语句法几乎就是围绕动词链组织起来的。

### 三对正交参数（tense / aspect / voice）

**"正交" = 三个互相独立的开关**。每个轴自己选档，互不干扰，三档选择拼出一个动词形式。中文教学的"16 种时态"让人以为是一条线，其实是 **2 档 × 4 档（×2 档语态）** 的组合——记住三个开关各管什么，所有形式都能推出来。

先记住四个开关在助动词链上的落点（链的结构见上一节"动词短语的结构"）：

| 开关 | 落在哪 |
|---|---|
| tense 时 | **不占槽**——戳在链首第一个词身上 |
| aspect 体 | **perfect 槽（`have`）+ progressive 槽（`be`）**，两个槽 |
| voice 语态 | **passive 槽（`be`）**，一个槽 |
| mood 式 | modal 槽（详见下节"Modal 系统"） |

#### 开关一：Tense（时）——只有两档：present / past

Tense 是**动词形态**上的时间标记，英语动词形态只区分两档：

- **present**：`walk / walks`、`eat / eats`、`is / are`
- **past**：`walked`、`ate`、`was / were`

关键认知：

- `will go` **不是将来时**——`will` 是 modal（情态动词），形态上 `will` 本身就是 present 档（`would` 是它的 past 档）。英语没有"将来形态"，将来靠 modal、be going to、现在时表将来等手段表达
- Tense 管的是"动词自己长什么样"：`has written` 里 `has` 是 present 档，`had written` 里 `had` 是 past 档——所以 present perfect / past perfect 的"时"取决于助动词 `have/has` vs `had`

**时制跟链首走**——把同一个意思放进不同的槽位组合，"现在/过去"这枚戳永远盖在**链上最左边第一个非空槽**的词上：

```
槽位→        modal        perfect     progressive  passive   lexical
             情态         完成        进行         被动      实义
writes       —            —           —            —         writes / wrote
is writing   —            —           is / was     —         writing
has written  —            has / had   —            —         written
will write   will / would —           —            —         write
may write    may / might  —           —            —         write
             ↑ 时制戳的位置：每条链最左边那个非空的词
```

读出来：

```
She writes.         她写。（present·simple）
She wrote.          她写了。（past·simple）
She is writing.     她正在写。（present·progressive）
She was writing.    她当时在写。（past·progressive）
She has written.    她写完了。（present·perfect）
She had written.    她当时已写完。（past·perfect）
She will write.     她会写。（modal will = present 档）
She may write.      她可能写。（modal may = present 档）
```

一句规则：**句子的"现在/过去"永远只看链首第一个词的形态**；链上后面所有词的形态（been/being/written）都是接力规则被逼出的外衣，与时间无关。

#### 开关二：Aspect（体）——看动作的"视角"

体不管"动作发生在什么时间"（那是 tense 的事），管的是**说话人站在哪里看这个动作**。体占链上**两个槽**：perfect 槽（`have`）和 progressive 槽（`be`），各有"占/空"两档，2×2 拼出四种体：

| 体 | 形式 | 视角 |
|---|---|---|
| **simple** 一般体 | 动词原形/过去式 | 把动作当**一个完整的事件点**，不进内部看 |
| **perfect** 完成体 | `have + 过去分词` | 站在一个时间点**往回看**：动作已完成且与此刻有关联 |
| **progressive** 进行体 | `be + 现在分词` | 站在动作**内部看**：正在展开、未完成 |

（perfect 和 progressive 可叠加成第四档 perfect progressive：`have + been + -ing`）

对比例——同一个动作 `eat breakfast`，语义全靠换档：

```
I eat breakfast at 7.          → present + simple：习惯/事实，动作被压成一个点
I ate breakfast at 7.          → past    + simple：已完结的一个事件
I have eaten breakfast.        → present + perfect：站在"现在"回看，吃过→现在不饿
I had eaten when he arrived.   → past    + perfect：站在"他到达"那个过去点回看
I am eating breakfast.         → present + progressive：钻到动作内部，正吃着
I was eating when he arrived.  → past    + progressive：他到达那一刻，我正吃到一半
```

注意最后两句：`when he arrived` 这个时间状语完全一样，变的只是**视角**——`had eaten`（他到时已经吃完了，回看）vs `was eating`（他到时还在吃，进行）。这就是"体"干的活，tense 管不了这层差别。

再叠一档 perfect progressive：`I have been waiting for an hour.`——present 档 + perfect（回看）+ progressive（还在进行）：从过去一路持续到现在、此刻还没停。

从槽位形态看这四种体——simple 就是"两槽全空"（注意 perfect prog. 行的 `been`：它是**进行槽**的 be 被前面 have 逼成的 -ed 形）：

| 体 | modal(情态) | perfect(完成) | progressive(进行) | passive(被动) | lexical(实义) | present 例 | past 例 |
|---|---|---|---|---|---|---|---|
| simple | — | — | — | — | write(s) | She writes. | She wrote. |
| perfect | — | has / had | — | — | written | has written | had written |
| progressive | — | — | is / was | — | writing | is writing | was writing |
| perfect prog. | — | has / had | been | — | writing | has been writing | had been writing |

#### 开关三：Voice（语态）——两档：active / passive

语态管的是**主语和动作的关系**：

- **active**：主语是动作的发出者（施事）
- **passive**：主语是动作的承受者（受事）→ `be + 过去分词`，槽位翻转：原来的宾语搬来当主语

```
The cat ate the fish.              → active：cat 是施事
The fish was eaten (by the cat).   → passive：fish 是承受者，被搬上主语位
```

passive 不是换时间，是换"谁是主角"——同一件事，镜头对准承受者。

**纠偏：被动 ≠ 过去**——被动只是"passive 槽占了一个 be + 链尾实义动词穿 -ed 外衣"，`eaten` 不提供任何时间信息，时间照样只看链首（下表看 passive 列：be 在槽里，形态随链首位置变）：

| 时制 | modal(情态) | perfect(完成) | progressive(进行) | passive(被动) | lexical(实义) | 句子 | 中文 |
|---|---|---|---|---|---|---|---|
| present | — | — | — | is | eaten | The fish is eaten every day. | 这鱼天天被吃 |
| past | — | — | — | was | eaten | The fish was eaten. | 鱼被吃了 |
| modal | will | — | — | be | eaten | The fish will be eaten. | 鱼将被吃 |
| perfect | — | has | — | been | eaten | The fish has been eaten. | 鱼已经被吃了 |
| modal+perf. | may | have | — | been | eaten | The fish may have been eaten. | 鱼可能已经被吃了 |

**被动槽的 be 也要换外衣**——它穿什么由前一个词决定（接力规则对它同样有效）：

```
链首时         is/was eaten   The fish was eaten.          鱼被吃了
跟在 to 后      to be eaten    It wants to be eaten.        它想被吃掉
跟在介词/进行后  being eaten   afraid of being eaten        害怕被吃掉
跟在 have 后    been eaten     has been eaten              已经被吃了
be 全省（裸分词）eaten          the fish eaten by the cat    被猫吃掉的那条鱼
```

`has been eaten` 里有两个 -ed 形但归属不同槽：`been` 是**被动槽**的 be 被 have 逼的，`eaten` 是**实义动词**被被动槽逼的——一件外衣归一个槽，互不串岗。

变体两则：

- **get 被动**：`The fish got eaten` ≈ "鱼遭吃了"——`get` 顶替 passive 槽的 be，更口语、带"倒霉/遭遇"的情绪
- **状态被动**：`The door is closed` 歧义——事件被动（门被关上）vs 形容词用法（门关着的状态，`seems closed`/`very closed` 也通）

#### 组合：三个开关拼出全部形式

以 `write` 为例，tense(2) × aspect(4) = 8 格（中文教材"16 时态"把 will/would 也算两档时制；按形态 only present/past，所以只剩这 8 格）：

| | simple | progressive | perfect | perfect prog. |
|---|---|---|---|---|
| **present** | writes | is writing | has written | has been writing |
| **past** | wrote | was writing | had written | had been writing |

每格再 ×2 语态：

```
She has written the letter.      → present + perfect     + active
The letter has been written.     → present + perfect     + passive
   ↑has=present  ↑been written=perfect+passive 两层分词
She was being followed.          → past    + progressive + passive
   ↑was=past  ↑being=progressive  ↑followed=passive
```

回头看助动词链就很好懂了——**每一层助动词就是一个开关的物理实现**：

```
may                 have               been                 being             followed
[modal 式/情态]     [perfect 完成]     [progressive 进行]   [passive 被动]    [lexical 实义]
```

开关 → 槽位对照（正交参数与助动词链的映射）：

| 开关 | 占据的槽 | 说明 |
|---|---|---|
| mood 式 | modal 槽 | can/may/will 填进来才有 |
| aspect 体 | perfect + progressive 两槽 | 空+空=simple、have=perfect、be=progressive、双占=perfect progressive |
| voice 语态 | passive 槽 | 占=被动、空=主动 |
| **tense 时** | **不占槽** | 时制是印在链首词身上的戳：链首是 may→may/might、have→has/had、be→is/was、无助动词时实义动词自扛（walks/walked） |

认读练习——把动词链"翻译"回开关档位（固定三步：①链首词→tense/modal，②中间槽的 have/be→aspect/voice，③链尾→干了什么）：

（槽位缩写：**M**=modal(情态)，**P**=perfect(完成)，**G**=progressive(进行)，**V**=passive(被动)，**L**=lexical(实义)）

| 动词链 | 占位槽 | 开关档位 | 中文 |
|---|---|---|---|
| works | L | present·simple·active（裸动词扛时制） | 他工作 |
| is writing | G+L | present·progressive·active | 他正在写 |
| was eaten | V+L | past·simple·passive | 被吃了 |
| has been writing | P+G+L | present·perfect prog.·active | 一直在写 |
| had been eaten | P+V+L | past·perfect·passive | 到那时已被吃了 |
| will be interviewed | M+V+L | present(will)·simple·passive | 将被采访 |
| could have been done | M+P+V+L | modal·perfect·passive | 本可能已被做完 |
| may have been being followed | M+P+G+V+L 全占 | modal·perfect prog.·passive | 可能一直被人跟踪着 |

一句话总结：

- **Tense**：动词形态说"现在/过去"——只有两档，将来不存在
- **Aspect**：说"怎么看这个动作"——点看（simple）/ 回看（perfect）/ 进内部看（progressive）
- **Voice**：说"主语是打人的还是挨打的"——active / passive
- 三者各选一档拼起来，就是动词形式；中文所谓"16 时态" = 2×4（再 ×2 语态）的组合，不是 16 个孤立的东西

### Modal 系统

`can/could, may/might, shall/should, will/would, must, ought`：表达说话人的判断（可能性/义务/意愿），**永远后接原形动词**，第三人称不加 s，构成自己独立的否定/疑问能力（所以是 operator）。

常见 modal 的核心语义：

| modal | 核心义 | 例 |
|---|---|---|
| can / could | 能力 / 可能 | `I can swim.`（我会游泳）/ `It could rain.`（可能要下雨） |
| may / might | 许可 / 推测 | `May I go?`（我可以走吗）/ `It might be true.`（也许是真的） |
| must | 义务 / 肯定推测 | `You must go.`（你必须走）/ `He must be tired.`（他肯定累了） |
| will / would | 意愿 / 预测 | `I will help.`（我会帮忙）/ `That would be him.`（那应该就是他） |
| should / ought | 建议 / 应当 | `You should sleep.`（你该睡了） |
| shall | 提议 / 承诺（渐少用） | `Shall we go?`（我们走吗） |

### Mood（语气）

- **Indicative**（陈述）：常态
- **Imperative**（祈使）：原形
- **Subjunctive**（虚拟）：英语残迹，两条活口——`If I were you`（were 是仅存的虚拟形态）/ `I suggest he go`（mandative subjunctive，原形、无三单 s，美式尚活）。英语虚拟主要靠 modal + 时态后移（past 表"与现在相反"、past perfect 表"与过去相反"）实现：`If I **knew**, I would tell you.`（knew 是形式过去、意义现在）；`I wish I **had known**`（对过去）；`I wish I **knew**`（对现在）

## 六、名词短语（NP）—— 英语短语的"装配模板"

NP 是一条固定流水线，四个槽位各司其职：

```
[determiner] [premodifier(s)]  HEAD  [postmodifier(s)]
the          tall              man   in the corner who spoke yesterday
```

- **Head（中心词）**：唯一必选项，意义锚点（`the tall man in the corner` 砍光修饰剩 `man` 还能用）
- **Determiner（限定词）**：回答"哪个/谁的/多少"——冠词 a/the、指示 this/that、物主 my/John's、数量 some/every/no。两条铁律：
  1. **单数可数名词必须带限定词**——`*I saw dog` 非法，必须 `the/a/this/my dog`。冠词不是可选装饰，是名词的"出场许可证"
  2. **中央限定词只有一个坑位**——`*the my dog` ❌（the 和 my 抢同一个槽）
- **Premodifier**：短修饰语放前面——形容词、名词作定语（`stone wall`）、分词（`running water`/`broken window`）。多个形容词的惯用排序：opinion → size → age → shape → color → origin → material → purpose（`a beautiful big old red Chinese wooden table`）
- **Postmodifier**：长修饰语放后面——介词短语、定语从句、同位语、非限定分句。铁律 **"短前长后"**：修饰语一变长就必须挪到名词后面，否则中心词被埋——这也是定语从句存在的原因，英语没有"长形容词放前面"这条路

再拆一个"四槽位全占满"的：

```
those two old French coins found in the garden
det   num adj  adj    head  过去分词短语后置
```

### Articles 冠词（限定词里最难的槽）

- `a/an`（不定）：从集合里随便挑一个、**初次引入**——`I saw a dog.`（你不知道是哪只）
- `the`（定）：**双方都确定是哪只**——回指上文、独一无二、被修饰限定死——`The dog was black.`
- 零冠词：泛指/复数/不可数——`Dogs are loyal.` `Water is wet.`
- "泛指一类"的三种等价说法：`A dog is loyal` / `The dog is loyal` / `Dogs are loyal`

冠词换档=语义换档的最小对：

```
I need a pen.                   任意一支（不定）
The pen on the desk is mine.    特指桌上那支（定）
He goes to school.              去上学（零冠词 → 功能义）
He goes to the school.          去那栋楼（the → 建筑本身）
She is in hospital.             在住院（BrE，功能义）
She is in the hospital.         在那家医院里（不一定是病人）
```

### Countability 可数性

- **count**：a dog/dogs、配 many/fewer
- **mass**：water/information/advice/furniture——无复数、不可加 a、配 much/less（`information` 永远不可数，和汉语"一条信息"的直觉对着干）
- **一词两性**是高频坑：

  | mass 义 | count 义 |
  |---|---|
  | paper 纸 | a paper 报纸/论文 |
  | chicken 鸡肉 | a chicken 一只鸡 |
  | hair 一头头发 | a hair 一根头发 |
  | experience 经验 | an experience 一次经历 |
  | room 空间 | a room 一个房间 |
  | glass 玻璃 | a glass 一只玻璃杯 |
  | time 时间 | a time/times 次数 |
  | work 工作 | a work/works 作品 |

- **天然复数**：scissors/trousers/glasses——计数靠 `a pair of`

### Case 格 —— 已高度退化

英语只剩代词的格：`I/me/my`, `he/him/his`, `who/whom/whose`——主格管 S、宾格管 O/介词宾、所有格管 NP 内。这是古英语完整格系统（nom/acc/gen/dat）的残迹——格退休了，英语改靠**词序**干格原本干的活。

代词格全表：

| 主格（S） | 宾格（O/介词宾） | 所有格 |
|---|---|---|
| I | me | my |
| he | him | his |
| she | her | her |
| we | us | our |
| they | them | their |
| who | whom | whose |

格的实际作用：`He saw me` vs `I saw him`——词序同样的位置换格就换角色；`between you and me`（介词后宾格，`*between you and I` 是常见误用）。

`'s` 与 `of` 的分工：有生命/时间词用 `'s`（`John's book`、`today's paper`），无生命的长名词用 `of`（`the leg of the table`）。注意语义差：`a photo of John`（照片里有他）vs `a photo of John's`（他拥有的照片）——`'s` 是"所有"，`of` 是"关联"。

## 七、Agreement（一致）——英语的"形态对账"系统

### S-V agreement：现在时里唯一还活着的标记就是三单 -s

难点全在"什么样的主语算单数"：

| 情况 | 规则 | 例 |
|---|---|---|
| `there be` | 动词跟**后面的真主语**走 | `There **is** a book` / `There **are** books` |
| `either/neither...or` | **就近原则**——看离动词近的那个 | `Either he or I **am** wrong` |
| 集合名词 team/family/government | 英式可单可复，美式偏单 | `The team **is** winning`（美） |
| 不定代词 everyone/each/somebody | 永远单数 | `Everyone **is** here` |
| 整体量词（时间/金额/距离） | 当一个量看 → 单数 | `Ten years **is** a long time` |
| 国名/书名的复数形式 | 当实体 → 单数 | `The United States **is**...` |

更多坑：

```
The news is good. / Mathematics is hard.      -s 结尾的不可数/学科名仍单数
A number of students are absent.              a number of = 许多 → 复数
The number of students is rising.             the number = 数目本身 → 单数
Each of us has a key. / We each have a key.   each 位置不同，数不同
```

### Pronoun-antecedent agreement

代词必须能指回前文某个名词（数/性别匹配）：`Every student brought **his or her** book`——当代英语已接受单数 `they` 作性别中立解（`Everyone brought their book`）。

## 八、从属与并列（Subordination & Coordination）

英语搭句子只有两种焊接方式：并列焊同级，从属焊层级。

### Coordination（并列）

`and / or / but` 焊接**同级**单位，两边可互换、地位平等：`He came and left.`——并列的是两个谓语，主语共享。并列内部允许大量省略（`He came and (he) left` 括号部分都省了）。

成对的 correlative conjunction：`either...or`、`neither...nor`、`not only...but also`——

```
Either you go or I go.                同级二选一
Not only did he come, but he stayed.  前置分句时引起部分倒装
```

省略规则：并列的第二个分句可省掉与前面重复的一切——`She sings and (she) dances`、`He washed and (he) dried the dishes`（也可共享宾语）。

### Subordination（从属）——英语"长句"的引擎

#### 从属标记三型

把一个完整句子"降级"塞进大句子里，靠标记词开头，分三型：

| 标记 | 是否带意义 | 是否在从句内占成分 | 例 |
|---|---|---|---|
| **complementizer** that/whether/if | 不带 | 不占（纯语法胶水） | `that she left` |
| **wh-词** who/what/when/why | 带 | **占**（双重身份） | `what he said` |
| **subordinating conjunction** because/if/when/although | 带 | 不占（纯引子） | `because I was tired` |

#### 名词性从句 = "拿整个分句当名词使"

能站在名词能站的任何位置：

```
That she left surprised me.          （S——句首 that 不可省）她离开这件事让我惊讶。
I know (that) she left.              （O——宾语位 that 常省）我知道她走了。
The question is whether he comes.    （C——表语位）问题是他来不来。
The fact that he lied matters.       （同位语——that 从句不是修饰 fact，它就是 fact 的内容）他撒谎这个事实很要紧。
```

`whether` vs `if`：宾语从句里可互换（`I don't know whether/if he comes`），但主语位、表语位、介词后只能用 whether——`*If he comes is unclear.` → `Whether he comes is unclear.`

`what` = `the thing that`（融合型关系词，自带先行词）：`What he said was true` = `The thing that he said was true`——所以 `what` 前面**不需要**先行词，`*the thing what he said` 非法。

#### 定语从句 = "一个有缺位的从句 + 关系词补位"

英语语法最精妙的装置。结构：**先行词 + 关系词 + 带空洞的从句**——关系词是从空洞里"提取"出来的成分，替身在前面站岗：

```
the man [who ___ spoke]              who 占 S 位（不可省：*the man spoke）
the man [(who) I saw ___]            who 占 O 位（可省 → 零关系词 contact clause）
the house [where I live ___]         where 占状语位（= in which）
the man [whose car ___]              whose 占所有格位
the book [about which we talked ___] 介词连带提前（正式）
the book [(that) we talked about ___] 介词滞留句尾（口语）
```

限定性 vs 非限定性：`My brother who lives in Tokyo is a doctor`（我有多个兄弟，从句**缩小范围**）vs `My brother, who lives in Tokyo, is a doctor`（只有一个兄弟，从句**补充信息**）——逗号决定语义，非限定从句禁用 that。

逗号换语义的最小对：

```
The students who passed got prizes.      只有及格的学生得了奖（限定范围）
The students, who passed, got prizes.    学生全及格了，全都得奖（补充说明）
```

#### 状语从句 = "拿分句当副词使"

九类语义：time / condition / reason / concession / purpose / result / manner / comparison / place。两条规则：

- 前置要逗号：`If it rains, we stay.` / `We stay if it rains.`
- **时间/条件从句里将来时退化**：`When he comes (*will come), tell him.`——"将来"由主句的 will 统一管辖，从句用现在时代打

九类各一句：

```
time:        When he arrives, we eat.              他到了我们就吃。
condition:   If it rains, we stay.                 下雨我们就不走。
reason:      Because I was tired, I slept.         因为累了，我就睡了。
concession:  Although it rained, we went.          虽然下雨，我们还是去了。
purpose:     He whispered so that nobody heard.    他压低声音说，免得被人听见。
result:      He spoke so fast that I missed it.    他说得太快，我没听清。
manner:      Do it as I told you.                  照我告诉你的方式做。
comparison:  He runs faster than I (do).           他跑得比我快。
place:       Put it where it was.                  把它放回原处。
```

#### 非限定分句 = "被抽掉了时间的从句"

三种形态各有默认语义解读：

| 形态 | 默认解读 | 例 |
|---|---|---|
| `to do` | 目的/未实现（指向未来） | `I came to help` / `I want to go` |
| `doing` | 进行/同时发生 | `I saw him running`（看见时正在跑） |
| `done` | 被动/已完成 | `Seen from above, the city is small` |

不定式没写"谁去做"，默认归谁管：`I want ___ to go` 想走的是"我"（主句主语说了算，subject control）；`I told him ___ to go` 走的是"他"（宾语 him 说了算，object control）。悬垂分词是经典病句：`*Walking down the street, the house came into view`——分句的隐形主语默认 = 主句主语 the house，但房子不会走路。

更多控制关系与特例：

```
I persuaded him to leave.      object control（him 是不定式的主语）
It's hard for him to win.      for 引出不定式自己的主语
Seeing is believing.           -ing 分句直接当主语（动名词用法）
Weather permitting, we go.     独立主格：分句自带主语，不悬空
Having eaten, he left.         完成分词：动作先于主句
```

#### 不定式（infinitive）用法详解

`to do` 本质是从句瘦身成的短语——动词不扛时间了，整个东西就能当名词、形容词、副词用：

```
To err is human.                        当名词：主语位（犯错是人之常情）
I want to go.                           当名词：宾语位（我想走）
My plan is to leave early.              当名词：表语位（我的计划是早点走）
I need something to eat.                当形容词：后置修饰名词（我要点吃的；=something that I can eat）
I came to help.                         当副词：目的状语（我是来帮忙的）
He is too tired to walk.                当副词：too...to 结果（他累得走不动了）
I'm glad to see you.                    当副词：形容词补足（见到你很高兴）
```

形态变化：`to do`（一般）/ `to be done`（被动）/ `to have done`（完成，先于主句）——`He is said to have left`（据说他已离开）。

**bare infinitive（裸不定式）**——`to` 被剥掉的场合：

```
modal 后：        can swim / must go
使役动词：        make/let/have sb do    （*make him to go）
感官动词：        see/hear/watch sb do    （看见全过程；doing=看见片段）
固定短语：        had better do / would rather do / cannot help but do
help (to) do：    可加可不加 to
```

**不定式 vs 动名词：同一动词换形态=换语义**——这是不定式最值钱的一组对立：

| 动词 | to do | doing |
|---|---|---|
| remember | 记得**要去做**（未做） | 记得**做过**（已做） |
| forget | 忘了要去做 | 忘了已做过 |
| stop | 停下**去做**另一件 | **停止做**这件 |
| try | 努力去做 | 试着做（试验手段） |
| regret | 遗憾地通知（将说） | 后悔做过 |
| mean | 打算做 | 意味着 |

只接 to do 的动词：want/hope/decide/promise/agree/refuse/afford/manage/learn
只接 doing 的动词：enjoy/finish/avoid/mind/suggest/practice/consider/admit/imagine/keep

**分词的形容词用法**：`-ing` 表"令人…"（主动倾向），`-ed` 表"感到…/被…"（被动或完成）——`a boring movie`（电影让人烦）vs `a bored student`（学生感到烦）；`the running man` / `the broken window`。

## 九、总图景

```
word ──morphology──→ inflected word ──syntax──→ phrase ──→ clause ──→ sentence
                                                  ↑
                          功能词 + 词序 + 形态标记 = 显示语法关系
```

一句话概括英语语法的 DNA：**主语和谓语是强制的、词序是语法的、动词必须有限定形态、名词要交代可数性、修饰关系要显式标记**。这五条约束解释了英语语法里 90% 的"硬性规则"——为什么必须有主语、为什么动词变来变去、为什么介词到处飞、为什么从句要带关系词。