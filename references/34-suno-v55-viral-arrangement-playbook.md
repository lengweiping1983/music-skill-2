# 34 Suno v5.5 爆款编曲与写歌 Playbook

## 资料范围

本项使用 [Suno v5.5 爆款编曲与写歌最佳实践 50篇来源库](suno-v55-best-practice-source-bank-50.md)，重点提炼 v5.5 官方功能、Custom Mode、metatags、Exclude、爆款编曲、旋律 Hook、中文歌词、画面感和短视频黄金片段。

## v5.5 使用边界

- v5.5 更适合表达力、人声身份和个性化声音，但仍需要清楚的结构、Hook 和编曲指令。
- `Voices`、`Custom Models`、`My Taste` 负责身份与偏好；`Style of Music` 仍负责本首歌的曲风、情绪、节奏引擎、编曲和 mix。
- 有自定义模型时，少堆曲风名，多写本首歌的结构动作：`stripped verse builds to chant chorus`、`drop after title phrase`。
- 没有自定义模型时，`Style of Music` 必须更完整：主曲风、情绪、人声、BPM、核心音色、Hook 武器、手机外放保护。
- v5.5 不会自动修复弱歌词、长前奏、无 Hook、编曲过满或 Exclude 冲突。

## 爆款编曲规则

- 先定节奏引擎，再写歌词：四拍舞曲、stomping rock、trap bounce、lo-fi swing、marching snare、reggaeton dembow 等。
- 每首歌只保留 2-3 个核心声音武器：主鼓型、主音色、人声 Hook。其他乐器只做边缘颜色。
- Verse 少，Chorus 多；Pre-Chorus 推高，Bridge 抽空，Final Chorus 加一层人声或鼓点。
- 0-3 秒必须有声音指纹：近距离人声、chant、反拍鼓、停顿、特殊音色、环境采样或一声喊。
- Drop、停顿、clap、chant 和标题句要绑定，方便短视频卡点。
- 手机外放优先中频：人声、军鼓/拍手、主旋律、短低频；避免低频、混响、垫底铺满。

## 旋律与 Hook

- Hook 使用 3-6 音核心动机，内部重复 2-4 次。
- 优先 AA 开头：第一句让人听懂，第二句让人记住。
- 标题句必须绑定主旋律，最好落在副歌最高点或最明显的节奏断点。
- Verse 旋律叙事，Chorus 旋律开阔，Post-Chorus 用 chant、拟声或短词组做二级记忆点。
- 保持 80% 熟悉 + 20% 小怪点：顺耳进行加一个停顿、尾音、切分、反差唱腔或怪音色。
- Production hook 可以抓耳，但不能替代可清唱的旋律 Hook。

## 中文歌词与画面

- 中文歌词每行优先 4-10 字，Hook 金句优先 6-12 字。
- 主歌必须有时间、地点、物件、动作或镜头；不要只写抽象情绪。
- 副歌少讲道理，多写能被观众代入的动作句、对话句、画面句。
- 押韵服务演唱，不为了押韵牺牲口语自然度。
- 意境来自“具体画面 + 强情绪 + 留白”，不是堆古风词或漂亮名词。
- 结尾留下一个可回味画面，不把主题解释完。

## Suno 可执行写法

`Style of Music`：

```text
Chinese viral electro pop, 甜拽夜跑情绪, close bright female vocal, four-on-the-floor kick and clap engine, micro-repeated title hook, rubber bass stab and glassy pluck, 128 BPM, phone-speaker clear vocal, tight low-end separation, stripped verse to chant chorus.
```

`Lyrics`：

```markdown
[Intro | sound fingerprint | 0-3s]
(近距离女声气口, clap clap, sudden stop)

[Hook Preview | 3-8s]
别回头 看我亮
别回头 看我亮

[Chorus | viral hook | full mix]
(drop on title phrase, chant doubles, bass stab)
别回头 看我亮
亮到风都让一让
```

`Exclude`：

```text
long intro, buried vocals, muddy bass, cluttered arrangement, weak hook, excessive reverb, generic lyrics, harsh highs
```

## 反例

- Style 同时写 5 个主曲风、10 个乐器和多个互相冲突的情绪。
- Hook 只有编曲音色，没有能清唱的一句话。
- Intro 长铺垫，30 秒后才进主 Hook。
- 每段都满编制，Verse、Chorus、Bridge 没有对比。
- Exclude 排除了正文正向要求的乐器、人声或 chant。

## 自检

- 编曲是否有一个能被记住的声音武器？
- 节奏引擎是否能支持卡点、变装、剧情反转或情绪字幕？
- Hook 是否能清唱，且标题是否在 Hook 上？
- 0-3 秒是否有声音指纹，3-8 秒是否有 Hook Preview？
- 15 秒内是否出现完整爆点，15-31 秒能否单独剪成短视频？
- Verse 是否像一个镜头，副歌是否像一句会被转发的话？
- 是否只有 2-3 个核心声音武器，且人声没有被埋？
