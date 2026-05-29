# 40 忧郁华语情歌 Suno Playbook

## 适用范围

用于忧郁、伤感、失恋后遗症、克制破防、感动中国听众的华语流行歌曲。重点不是照搬苦情歌套路，而是把一个普通生活瞬间写到人心里。

## 核心规则

- 忧郁来自细节，不来自哭喊。优先写电梯、消息框、旧耳机、门锁、楼道灯、房间回音、半夜水声等现代物件。
- 主人公不要一直乞求。更有效的是嘴硬、沉默、错过、忍住、突然失控。
- Hook 要短、口语、可清唱，最好是一个生活声响触发的误认反应，不要直接解释标题概念。
- 主歌克制，副歌低声加重，Bridge 给最真实的刺点；不要从痛苦直接跳到治愈。
- 参考歌若是哀求挽留型，新歌必须避开同类关键词和镜头：不写海浪、花、求你别走、现实枷锁、回忆漩涡。
- 当用户反馈“不打动人”“没感觉”“太概念”“想感动人”“声音低”“速度慢”时，默认启用低速低声破防模式。

## 低速低声破防模式

- BPM 优先 `68-76`，默认 `72 BPM`；不要用普通都市 pop 的 88-98 BPM。
- 人声优先 `low baritone male vocal`、`almost whispered verse`、`close dry vocal`、`long vocal breaths`、`trembling tail notes`。
- 副歌不是明亮抬升，而是 `chorus stays slow and heavy`；Final Chorus 才允许轻微破音或远处和音。
- 编曲使用低频钢琴、稀疏指弹吉他、极轻鼓刷和房间底噪；不要让鼓点、明亮合成器或大副歌把痛感冲淡。
- Exclude 必须保护低速伤感方向，优先排除 `upbeat pop`、`dance beat`、`bright happy chorus`、`fast tempo`。

## 遗憾舍不得模式

- 当用户要求遗憾、舍不得、挣扎、卑微、脆弱、敏感，或反馈声音不如上一首、有点硬、不够打动人、不够脆弱敏感时，优先启用本模式。
- 人声优先 `fragile low baritone male vocal`、`sensitive trembling delivery`、`humble restrained tone`、`intimate almost spoken-sung verse`。
- 副歌约束为 `chorus stays low, slow, and fragile`，避免普通抒情大副歌或明亮流行抬升。
- 情绪重点不是哭喊和复合请求，而是“差一点成真”“不敢承认结束”“身体不敢动作”。
- 编曲空间要收近，优先贴耳人声、车厢/房间暗底噪、稀疏钢琴和低频脉冲，让脆弱感在近处发生。

## 暗色卧室 Alt-R&B 脆弱声线模式

- 只有当用户明确要求曲风差异，且当前生成结果已经有足够伤感、遗憾、舍不得时，才启用本模式；不要因为“声音不够好”单独触发。
- 如果用户同时反馈不伤感、没感觉、声音太稳、缺少遗憾舍不得，必须跳过本模式，优先进入“伤感优先回退模式”。
- Style 核心使用 `Chinese dark bedroom alt-R&B breakup ballad`、`fragile close-mic male vocal`、`breathy low register`、`near-whispered verse`、`restrained falsetto cracks`、`Rhodes electric piano`、`sub-bass heartbeat`、`minimal rim clicks`、`68 BPM`。
- 避免继续把 `sparse low piano and fingerpicked guitar` 当主配方；这会让同专辑慢情歌过于相似。
- 主歌贴耳干声，副歌不大开，只加窄和声、气声 double、轻微失真边缘和低频脉冲。
- 适合表达分手后劲、无法承认结束、失恋后每个普通时刻都被刺痛的情绪。
- Alt-R&B 不等于低声含混；中文主唱必须优先写 `clear Mandarin consonants`、`lead vocal centered and upfront`、`lyric intelligibility first`。
- 若 Suno 生成听不清，删除或减弱 `tape hiss`、`sub-bass heartbeat`、`narrow harmony` 和过度 whisper，改用 `dry close vocal`、`restrained breath not whisper`。
- 中段情绪没出来时，用演唱动作提示补强：`voice tightens`、`breath catches`、`almost spoken but clear`、`clear consonants`。

## 伤感优先回退模式

- 不要为了差异化牺牲伤感。当用户明确要求伤感、忧郁、遗憾、舍不得、挣扎时，优先使用 `Chinese slow melancholic breakup ballad`。
- Alt-R&B 只在用户明确要求曲风差异且生成结果仍有情绪时使用；若用户反馈不伤感、没感觉、声音太稳、没有遗憾舍不得，立刻回退到 slow melancholic pop ballad。
- 清晰度提示不能压过情绪提示；避免把 `lyric intelligibility first` 放在情绪歌核心 Style 中。
- 声音优先写 `raw fragile low male vocal`、`restrained crying edge`、`voice almost breaks on chorus`、`slight pitch trembling`、`chorus stays slow and heavy`。
- 必要清晰度只作为辅助：`phone-speaker clear vocal`、`upfront vocal mix`，不要把人声磨成干净稳定的 R&B 唱法。
- 当用户说“参考 01-回声症 的声音”时，优先复用它的有效声线逻辑：低、近、脆、慢、气口明显、尾音发抖、副歌慢重但不喊。
- 中段情绪不足时，不要先换曲风；先加强表演动作提示，例如 `restrained crying edge`、`breath catches`、`voice tightens`、`half-beat silence`、`music drops out`。

## 歌词执行

- Verse 每段至少有一个物件和一个动作：例如“电梯停在七楼”“旧耳机漏一格电”“消息框亮了又黑”。
- Pre-Chorus 用身体反应推高：喉咙发紧、手指停住、屏幕变暗、钥匙响了一下。
- Chorus 只钉一个中心 Hook，重复时让声音更低、更重、更难忍，不新增多个口号。
- 避免标题概念直接入词，例如不要写 `我得了回声症` 这种诊断式表达；用动作和声音让听众自己听出标题。
- Hook 优先写“生活声响 + 误认反应”，例如 `门锁一响 / 我就以为是你`，比解释情绪更容易打动人。
- 副歌可以直白、重复、低姿态，但不能照抄参考歌的哀求句式或核心表达。
- 遗憾舍不得型 Hook 可以写“核心物件 + 卑微等待”，例如 `回程无你 / 我还留着旁边的座`。
- 低姿态句可以使用 `像你只是迟到 / 不是不要我了` 这类自我欺骗式表达，但不能进入复合请求或照抄哀求。
- Bridge 优先放遗憾真相，例如 `我们差一点成真`，让听众明白主角舍不得的不是物件，而是差一点发生的未来。
- Final Chorus 必须有身体化动作崩溃点，例如不敢往前坐、没敢起身、手停住、把名字咽回去。
- Post-Chorus 可用短词或半句残响，但必须服务主 Hook。
- Outro 留一个可听见的动作或声音，不解释结局。

## 编曲与和声

- 曲风优先：Chinese slow melancholic pop ballad、Chinese sad pop ballad、urban breakup pop。
- 常规忧郁歌可用 88-98 BPM；若目标是感动人、低声破防、Suno 生成后不空，优先降到 68-76 BPM。
- 核心声音只选 2-3 个：克制男声、指弹吉他或低频钢琴、轻和音或暗色 pad。
- Verse 用小调、悬置感和少量 add9 色彩；Chorus 给稳定落点，避免一直悬空。
- Bridge 可以抽空，只留近距离人声、低频钢琴或吉他泛音。

## 人声与和音

- 男声主歌 close dry、低声、字清、自然气口；副歌 lifted but not belting。
- 情绪表演使用轻破音、尾音收住、半句停顿，不使用全程大哭腔。
- 和音只在 Chorus 和 Final Chorus 加轻垫，三度或六度即可；Final Chorus 可加远处回应。
- 主唱永远靠前，和音不能盖过歌词。

## Suno 可执行写法

Style 可加入：

```text
Chinese slow melancholic pop ballad, fragile low baritone male vocal, sensitive trembling delivery, humble restrained tone, intimate almost spoken-sung verse, slow 72 BPM, sparse low piano and fingerpicked guitar, very soft brushed drums, long vocal breaths, trembling tail notes, chorus stays low, slow, and fragile, restrained harmony only in final chorus, minor key, close dry vocal, dark room ambience, phone-speaker clear vocal, upfront vocal mix, minimal reverb, no bright pop lift.
```

暗色卧室 Alt-R&B Style 可加入：

```text
Chinese dark bedroom alt-R&B breakup ballad, fragile close-mic male vocal, breathy low register, sensitive trembling delivery, humble restrained tone, near-whispered verse, slow 68 BPM, Rhodes electric piano, sub-bass heartbeat, minimal rim clicks, faint tape hiss, long vocal breaths, trembling tail notes, restrained falsetto cracks only in final chorus, chorus stays low, intimate, and painful, minor7 chord color, close dry vocal, vocal-forward mix, minimal reverb, no bright pop lift.
```

Lyrics 标签可用：

```markdown
[Intro | sound fingerprint | 0-3s]
(close male breath, single guitar harmonic, room tone, sudden stop)

[Hook Preview | 3-8s]
门锁一响
我就以为是你
```

遗憾舍不得型 Lyrics 可用：

```markdown
[Hook Preview | 3-8s]
回程无你
我还留着旁边的座

[Chorus | low fragile hook]
回程无你
我还留着旁边的座
像你只是迟到
不是不要我了

[Bridge | vulnerable truth]
我不是舍不得
这趟回程
我是舍不得
我们差一点成真

[Final Chorus | lowest breaking point]
回程无你
我却没敢往前坐
像我一坐过去
就承认你不来了
```

Exclude 可用：

```text
upbeat pop, dance beat, bright happy chorus, fast tempo, buried vocals, muddy bass, overdramatic belting, cluttered arrangement
```

暗色卧室 Alt-R&B Exclude 可用：

```text
bright pop chorus, acoustic folk ballad, dance beat, belting vocal, buried vocals, muddy bass, excessive reverb, cluttered arrangement
```

## 自检

- 是否没有复用参考歌的核心意象、哀求方式和关键词？
- 标题是否短、可记、能进入副歌？
- 主歌是否具体到物件和动作？
- Hook 是否能清唱，并且只围绕一个中心句？
- 是否避免了直给概念句，例如 `我得了回声症`？
- 若目标是打动人，是否使用了 68-76 BPM、低声男声、贴耳主歌和慢重副歌？
- 若目标是遗憾舍不得，是否使用了脆弱敏感人声、卑微低姿态句、差一点成真的 Bridge 和身体化动作崩溃点？
- 若用户说曲风太像或声音不够好，是否改用 Alt-R&B/Rhodes/sub-bass/minimal rim clicks，而不是继续沿用钢琴吉他慢情歌主配方？
- 若用户只是说声音不够好，但同时要求伤感、遗憾、舍不得或挣扎，是否没有误切到 Alt-R&B，而是先回到慢速低声伤感底座？
- 若用户反馈听不清楚、声音糊、人声埋或中段情绪没出来，是否优先保护中文咬字、主唱居中靠前，并移除过度 whisper、tape hiss、sub-bass 和窄和声？
- 若用户反馈不伤感、没感觉、声音太稳或没有遗憾舍不得，是否回退到 slow melancholic breakup ballad，并把情绪提示放在清晰度提示之前？
- 人声是否克制到释放，而不是全程满格？
- 编曲是否只有 2-3 个核心声音武器？
- Exclude 是否没有排除正向要求？
