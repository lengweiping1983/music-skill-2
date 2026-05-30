# 42 催泪故事型华语慢歌 Suno Playbook

## 适用范围

用于用户反馈“不够打动人”“需要故事感”“想听哭”“感动人但不要喊口号”的华语慢歌、失恋后劲、旧房间、旧物告别和克制破防场景。重点不是更惨，而是让听众听见一个具体的人如何终于明白自己被告别了。

## 核心规则

- 一首歌只讲一个可拍事件，不写一生一世的大总结。
- 催泪公式：具体物件 + 没说出口的话 + 误会反转 + 克制低声 + 最后一处身体动作。
- Verse 1 写普通动作：回房间、开灯、脱外套、看鞋柜、拿钥匙，不急着说痛。
- Verse 2 写对方留下的痕迹：药、备用钥匙、小夜灯、便利贴、叠好的衣服、没扔的发圈。
- Bridge 必须给误会反转：原来对方不是走得狠，而是把告别做得太体面；主角这时才懂。
- Final Chorus 给身体化崩溃动作：不敢关灯、不敢坐下、不敢删掉号码、不敢碰那张纸。
- Hook 只钉一个中心句，像一句低声说出口的发现，不要平均堆多个金句。
- 不从痛苦跳到释怀；结尾只留一个动作，让听众自己哭完。

## Suno 声音执行

- BPM 优先 `68-74`，默认 `70 BPM`。
- 人声优先 `fragile low baritone male vocal`、`close dry almost spoken-sung verse`、`natural long breaths`、`restrained crying edge`、`slight vocal crack only in final chorus`。
- 编曲只选 2-3 个核心声音：felt piano、soft fingerpicked guitar、room tone 或 very soft brushed drums。
- Bridge 抽空：`bridge nearly a cappella`、`music drops out`、`single piano note`。
- 副歌不明亮抬升：`chorus stays low and painful`、`no bright pop lift`。
- 主唱必须居中靠前：`upfront vocal mix`、`phone-speaker clear vocal`、`minimal reverb`。

## 歌词结构

```markdown
[Intro | sound fingerprint | 0-3s]
(close male breath, light switch click, room tone, long silence)

[Hook Preview | 3-8s]
你替我关了灯
却留了一点亮

[Verse 1 | ordinary action]
半夜回旧房
钥匙转得轻

[Pre-Chorus | body tightens]
便利贴还在
我没敢念完

[Chorus | low painful hook]
你替我关了灯
却留了一点亮

[Verse 2 | traces left behind]
抽屉第二层
药还按天放

[Bridge | reversal truth]
我以为你走得狠
原来你怕我怕黑

[Final Chorus | body breaks]
我不敢关那盏灯
一关就承认你不回

[Outro | unresolved action]
灯还亮着
我没睡着
```

## 写词约束

- 每段至少有一个物件和一个动作。
- 尽量 4-10 字一行；必要叙事行可以略长，但必须能唱、能换气。
- 避免抽象词连用：遗憾、成长、答案、释怀、远方、光芒。
- 避免直接哭喊：不要反复写“我好痛”“我崩溃”“求你回来”。
- 不复用同专辑已成立的核心意象：门锁、回声、后来没有我们、回程、旁边的座、一直等。
- 允许直白，但必须落在物件上：`你替我关了灯 / 却留了一点亮` 比 `你给我最后的温柔` 更可唱。
- Bridge 的真相必须比副歌多一层信息，不能只把副歌换词重复。
- Final Chorus 必须让 Hook 的同一句变得更难唱，而不是新增一个新口号。

## 可执行 Suno 写法

Style 可加入：

```text
Chinese slow melancholic story ballad, fragile low baritone male vocal, close dry almost spoken-sung verse, slow 70 BPM, sparse felt piano, soft fingerpicked guitar, quiet room tone, natural long breaths, restrained crying edge, chorus stays low and painful, bridge nearly a cappella, final chorus slight vocal crack, upfront vocal mix, phone-speaker clear vocal, minimal reverb, no bright pop lift.
```

Lyrics 标签可用：

```markdown
[Intro | sound fingerprint | 0-3s]
(close male breath, light switch click, room tone, long silence)

[Bridge | reversal truth]
(music drops out, close dry male vocal, breath catches)
我以为你走得狠
原来你怕我怕黑
```

Exclude 可用：

```text
upbeat pop, dance beat, bright happy chorus, fast tempo, belting vocal, buried vocals, excessive reverb, cluttered arrangement
```

## 自检

- 是否只讲一个能拍出来的事件？
- Verse 1 是否先写普通动作，而不是先讲大道理？
- Verse 2 是否出现对方留下的具体痕迹？
- Bridge 是否有误会反转或迟到的理解？
- Final Chorus 是否有身体化崩溃动作？
- Hook 是否只有一个，并且能在 3-8 秒先出现？
- 是否避开门锁、回声、等待、回程、座位和“后来没有我们”路径？
- Style 是否保护低速、低声、贴耳、克制和中文清晰度？
- Exclude 是否不超过 8 项，且没有排除正向要求？
