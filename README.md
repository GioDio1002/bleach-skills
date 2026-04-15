# bleach-skills

日本漫画死神的人物 skills 仓库。目标不是做“语录包”，而是把人物的性格、说话节奏、名台词触发条件、以及粉丝社区记忆点，蒸馏成装上就能用的角色 skills。

## What This Is

这个仓库当前围绕《死神》里的三个人物来做中文 skills：

- 蓝染惣右介
- 黑崎一护
- 石田龙弦

这些 skills 的目标是让你在 `with me` 里使用时，感觉自己像是真的在和漫画人物对话，而不是在和一个会模仿几句名台词的大模型说话。

## How These Skills Are Made

这些 skills 不是直接拼名台词，而是先走一轮我自己做的 `deep research pipeline`。

研究过程大致是：

1. 先回到原作人物设定和可追溯台词，拆出人格骨架、语气口吻、行为逻辑。
2. 再去看中文平台上的流行传播，重点参考：
   - 小红书
   - 抖音
   - B站
   - 贴吧
   - 以及这些平台里反复出现的评论区表达和二创记忆点
3. 最后把“原作里这个人会怎么说”和“中文社区记住他是怎么说的”整合起来，写成可复用的中文 skill。

这里最重要的不是“像不像某一句台词”，而是：

- 什么时候该说重话
- 什么时候该收着说
- 什么时候可以触发名台词
- 什么时候绝对不能硬塞名台词

## Why They Feel Like Real Characters

我专门做了“名言触发策略”。

也就是说，这些角色不会每三句就自动背一次名言。更合理的设计是：

- 蓝染会在“对方基于错误前提自信判断”时，触发错觉反问或认知压制
- 一护会在“有人要被放弃、有人要独自硬扛、有人自我否定”时，先站出来再说话
- 龙弦会在“需要止损、需要现实判断、有人拿牺牲当浪漫”时，冷冷地下判断，但会把关心藏在资源和条件里

换句话说，名台词只是结果，场景触发和角色逻辑才是本体。

## What You Get After Install

装完之后，你拿这些 skills 去对话，不应该只得到“像角色的表面语气”。

你应该能感受到：

- 蓝染是在重写你的理解框架
- 一护是在替你扛事、替你顶回去
- 龙弦是在不给你糖衣的情况下帮你活下来

如果它们工作正常，你在 `with me` 里会更像是在和人物本人对话，而不是在看一个 cosplay 机器人。

## Included Skills

- [蓝染惣右介](/Users/benedict/Documents/bleach-skills/skills/aizen-cn/SKILL.md)
- [黑崎一护](/Users/benedict/Documents/bleach-skills/skills/ichigo-cn/SKILL.md)
- [石田龙弦](/Users/benedict/Documents/bleach-skills/skills/ryuken-cn/SKILL.md)

## Example Reactions

下面不是完整 prompt，只是帮助你快速理解这些大人物的 skill 大概会怎么反应。

### 蓝染惣右介

适合的反应：

- 拆掉你的前提
- 用平静语气纠正你
- 在必要时触发“你是什么时候开始产生……的错觉？”

示例：

> 用户：你已经没有后手了吧？  
> 蓝染：你是什么时候开始产生我没有留下后手的错觉？你所看到的，不过是我愿意让你看到的部分。

### 黑崎一护

适合的反应：

- 先站出来
- 先顶回去
- 不让你轻易把自己丢掉

示例：

> 用户：反正我这种人被放弃也无所谓吧。  
> 一护：你在说什么啊。谁跟你说无所谓了？少擅自替别人做决定。我不可能看着你就这么被丢下。

### 石田龙弦

适合的反应：

- 先止损
- 先判断现实代价
- 不热情，但会兜底

示例：

> 用户：伤我先瞒着吧，不想让别人担心。  
> 龙弦：愚蠢。隐瞒伤势不会让风险消失，只会让处理时机一起消失。先处理伤口，再考虑你那点体面。

## Research Assets

如果你想看这套 skills 是怎么被拆出来的，可以直接看这些文件：

- [Deep Research 报告](/Users/benedict/Documents/bleach-skills/research/bleach-characters-deep-research.md)
- [角色扮演回归测试集](/Users/benedict/Documents/bleach-skills/research/bleach-roleplay-testcases.md)

## License

MIT
