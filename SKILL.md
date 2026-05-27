---
name: music-skill-2
description: |
  火爆款 Suno 歌曲生成 Skill。用于把用户的主题、情绪、曲风或简单想法转成可直接复制到 Suno 平台生成音乐的最终版 suno.md，重点强化抖音神曲、TikTok viral song、短视频 BGM、爆款 Hook、15-31 秒黄金片段、卡点传播、强情绪、可二创、手机外放清晰度、好听旋律、歌词押韵、感情真实、画面感、意境和 Suno 最佳实践。触发场景包括：火爆款音乐、爆款歌曲、Suno 歌曲、抖音神曲、TikTok viral song、viral hit song、短视频音乐、爆款 Hook、生成 suno.md、只要 Suno 参数和歌词。
---

# music-skill-2 火爆款 Suno 歌曲生成

这个 Skill 只做一件事：生成可直接复制到 Suno 平台的最终版 `suno.md`。说明、流程、判断标准都用中文；固定字段名、Suno 参数、常用风格词可以保留英文。

## 输出目标

- 输出最终版 `suno.md`，字段固定，内容可直接复制到 Suno。
- 最终内容只保留 Suno 可执行字段、歌词、段落标签、括号提示和 Exclude。
- 本 Skill 必须独立自足，不依赖其他 skill、历史歌曲目录或外部本地路径。生成时只读取本 Skill 自带的 `SKILL.md` 和 `references/`。
- 输出内容不得包含资料来源、理论说明、审稿、营销计划、传播套件说明或创作分析。

## 必读参考

在写歌前，先阅读 `references/viral-suno-hit-model.md`；它是总索引，负责指向传播、音乐质量、Suno 生成三类分项。若用户需求明显涉及某个短板或风格重点，再按索引读取 `references/` 下对应分项。不要把参考文档中的资料来源或分析文字写入 `suno.md`。

Reference 分层：

- `01-15`：火爆传播因素。
- `16-27`：好音乐本体质量。
- `28-33`：Suno 生成最佳实践。
- `suno-v55-execution.md`、`chinese-lyric-structure.md`、`vocal-and-genre-execution.md`：基础执行规范。
- `34-suno-v55-viral-arrangement-playbook.md`：v5.5 爆款编曲、抓耳旋律、中文歌词、画面感和短视频黄金片段执行规则。
- `35-platform-shenqu-playbook.md`：平台爆款神曲、土嗨、全民二创、舞蹈挑战和短视频卡点执行规则。
<<<<<<< HEAD
- `36-military-homecoming-anthem-playbook.md`：军旅归途、边疆守护、家国与思念、国风电影电子 anthem 执行规则。
- `source-bank-50.md`、`good-music-source-bank-30.md`、`suno-best-practice-source-bank-100.md`、`suno-v55-best-practice-source-bank-50.md`：来源库，只在需要核查资料体系时读取；日常生成优先读提炼后的分项。
=======
- `36-guofeng-moon-urban-healing-playbook.md`：国风电子、月亮意象、都市夜景、许愿和轻治愈爆款执行规则。
- `37-humanized-lyrics-playbook.md`：去 AI 味、真人感歌词、自然语流、具体动作和反文案腔审稿规则。
- `source-bank-50.md`、`good-music-source-bank-30.md`、`humanized-lyrics-source-bank-20.md`、`suno-best-practice-source-bank-100.md`、`suno-v55-best-practice-source-bank-50.md`：来源库，只在需要核查资料体系时读取；日常生成优先读提炼后的分项。
>>>>>>> b177740488db9617c2d8fc8d9cb9bcdef7c94214

基础执行参考：

- 生成任何最终 `suno.md` 前必须读 `suno-v55-execution.md`。
- 生成任何最终 `suno.md` 前必须读 `34-suno-v55-viral-arrangement-playbook.md`，先确定节奏引擎、核心声音武器、Hook 旋律和短视频爆点。
- 生成任何最终 `suno.md` 前必须读 `37-humanized-lyrics-playbook.md`，写完歌词后做去 AI 味审稿。
- 字段职责、slider、人声一致性：读 `28-suno-custom-mode-fields.md`。
- metatags、段落结构、Hook Preview：读 `29-suno-metatags-structure-control.md`。
- Style 精简、Exclude 正负配对：读 `30-suno-style-exclude-pairing.md`。
- 中文歌词、人声稳定、咬字：读 `31-suno-lyrics-vocal-stability.md`。
- 曲风跑偏、风格漂移：读 `32-suno-genre-drift-fixes.md`。
- 任何最终版 `suno.md` 交付前至少经过 `33-suno-final-output-checklist.md`。
- 中文歌词、押韵、结构呼吸、发音和行长：读 `chinese-lyric-structure.md`。
- 人声真实感、曲风人声模板、金属男声保护：读 `vocal-and-genre-execution.md`。

分项读取原则：

- 开头弱、前奏长：读 `01-first-3-8-seconds.md`。
- Hook 不洗脑：读 `02-simple-repeated-hook.md` 和 `03-familiar-plus-strange-melody.md`。
- 歌词不适合传播：读 `04-quotable-lyrics.md`。
- 情绪散：读 `05-single-strong-emotion.md`。
- 不好卡点：读 `06-edit-friendly-rhythm.md` 和 `07-15-30-second-golden-clip.md`。
- 不适合二创或短视频：读 `08-ugc-remixability.md` 和 `09-video-scene-fit.md`。
- 人声、制作或转化问题：读 `10-vocal-identity.md`、`11-phone-speaker-production.md`、`15-viral-to-longterm-conversion.md`。
- 平台传播、发行和时代语境：读 `12-release-challenge-ugc-path.md`、`13-algorithm-signals.md`、`14-era-emotion-context.md`。
- 用户强调好听、旋律美：读 `16-melodic-beauty.md`。
- 用户强调抓耳、洗脑旋律：读 `17-catchy-melody-hook.md`。
- 用户强调押韵、顺口、中文语流：读 `18-lyric-rhyme-flow.md`。
- 用户强调感情、破防、真实：读 `19-emotional-truth.md`。
- 用户强调画面感、镜头感：读 `20-visual-imagery.md`。
- 用户强调意境、余韵、高级感：读 `21-artistic-mood-yijing.md` 和 `27-originality-and-aftertaste.md`。
- 用户强调和声、结构、律动、演唱、制作审美：读 `22-harmony-and-chord-color.md`、`23-structure-and-breathing.md`、`24-groove-and-prosody.md`、`25-vocal-performance-emotion.md`、`26-arrangement-and-production-taste.md`。
- 用户强调神曲、土嗨、全民二创、舞蹈挑战、短视频卡点：读 `35-platform-shenqu-playbook.md`。
<<<<<<< HEAD
- 用户提到《钢枪与玫瑰》、军旅、边疆、归途、守护、家国与思念、界碑、哨位、风雪灯火：读 `36-military-homecoming-anthem-playbook.md`。
=======
- 用户强调国风电子、月亮、许愿、治愈、都市夜景、轻伤感：读 `36-guofeng-moon-urban-healing-playbook.md`。
>>>>>>> b177740488db9617c2d8fc8d9cb9bcdef7c94214

## 主流程

1. 解析用户需求：提取主题、曲风、情绪、人声、目标场景、语言、禁忌元素。用户未指定时，默认中文人声歌曲、Suno `v5.5`、短视频传播优先。
2. 定位爆点：用一句话写清这首歌最适合别人拍什么视频，以及最想让听众记住哪一句。
3. 内部生成三套 Hook 草图：每套包含 Hook 首句、声音指纹、小怪点、适配场景。只在内部比较，不把草图输出到 `suno.md`。
4. 设计编曲爆点：先定节奏引擎、2-3 个核心声音武器、drop/停顿/chant/标题句卡点，再写完整歌词。
5. 若用户要神曲，先定可模仿动作、独特声音 Logo、口头禅 Hook、meme 弹幕句、系统提示/失控模因点、Post-Chorus 问答、半句 loop 尾巴和 15 秒卡点段。
6. 合成最佳方案：选择最顺口、最能卡点、最有画面、最容易二创的一套，吸收另外两套的优点。
7. 去 AI 味审稿：扫描抽象词、总结句、过度工整句、模板化治愈句、文案腔和假诗意；只替换低真人感句子，保留核心 Hook 与有效画面。
8. 写入 `suno.md`：只写固定字段和 Suno 可执行内容。
9. 自检并修正：检查前 3 秒、前 8 秒、15 秒爆点、黄金片段、Hook、歌词行长、真人感、编曲记忆点、Exclude 冲突和 Suno 输入纯净度。

## `suno.md` 固定格式

必须严格使用以下字段顺序：

```markdown
## Title

### Style of Music

### Vocal Gender

### Weirdness

### Style Influence

### Model

### Lyrics

### Exclude
```

字段规则：

- `Title`：短、可记、最好就是主 Hook 或 Hook 里的关键词。
- `Style of Music`：前半段必须包含曲风、情绪、人声、节奏引擎、Hook 武器、手机外放清晰度。字符数不超过 1000。
- `Vocal Gender`：使用 `Male`、`Female`、`Duet`、`Group` 等 Suno 可识别写法；不要使用 `Instrumental`。
- `Weirdness`：默认 35-55。大众流行 30-40，反差强或工业感 45-60。
- `Style Influence`：默认 45-65。需要更贴近主流时取高，想保留新鲜感时取中等。
- `Model`：默认 `v5.5`。
- `Lyrics`：只放歌词、段落标签和括号内可执行演唱/编曲提示。
- `Exclude`：不超过 8 项；必须先扫描正文白名单，不能排除 `Style of Music`、`Vocal Gender`、`Lyrics` 中正向要求的元素。

## 歌词与结构硬约束

- 前 3 秒必须有声音指纹：人声、口号、鼓点、特殊音色、强节奏切入或突然静止。
- 前 8 秒必须出现 `Hook Preview`，让人能立刻记住一句话或一个旋律动作。
- 15 秒内必须给出完整爆点片段，适合短视频截取。
- 设计 15-31 秒黄金片段，至少适合卡点、变装、剧情反转、情绪字幕、舞蹈、混剪中的一种。
- Hook 要简单、重复、可唱、可引用。优先口语动作句、对话句、画面句，避免正确判断句和口号作文感。
- 情绪必须单一强烈：燃、拽、甜、伤感、怀旧、复仇、释怀、土嗨等，不要多种情绪互相稀释。
- 每首歌保留“80% 熟悉 + 20% 小怪点”：顺耳旋律加一个停顿、反差唱腔、方言感、机械音色、节奏断点或集体 chant。
- 主歌必须有具体时间、地点、物件或动作，不能只写抽象情绪。
- 每个核心段落至少有一句能单独当短视频字幕的 6-12 字金句。
- 中文歌词尽量每行 4-10 字；如果为了叙事需要略长，必须仍然适合演唱和换气。
- 每首歌必须去 AI 味：用具体动作、物件、身体反应和没说出口的话替代空泛总结，避免模板化治愈、文案腔和 AI 式正确答案。

## 推荐结构

优先使用短视频友好的前置 Hook 结构：

```markdown
[Intro | sound fingerprint | 0-3s]

[Hook Preview | 3-8s]

[Verse 1 | visual scene]

[Pre-Chorus | rising tension]

[Chorus | viral hook | full mix]

[Post-Chorus | chant or rhythm hook]

[Verse 2 | deeper scene]

[Pre-Chorus | sharper turn]

[Chorus | stronger variation]

[Bridge | stripped contrast]

[Final Chorus | highest emotional point]

[Outro | loop-friendly tail]
```

可以按曲风调整段落，但不得把首次 Hook 埋到 30 秒后。

## 曲风处理

- 流行、R&B、民谣：人声靠前，Hook 简洁，主歌用具体生活细节，副歌给可复述金句。
- 电子、土嗨、舞曲：鼓点、停顿、drop 或 chant 必须可卡点，低频清楚但不糊。
- 金属、工业、摇滚：用 gang chant、重型 riff、鼓点停顿和一句战吼式 Hook，但主唱不能被合唱或乐器埋掉。
- 国风、古风、中国风电子：传统乐器只选 1-2 个核心声音武器，其余做点缀；避免堆满乐器名。
- 军旅、正能量、anthem：必须用真实物件和动作承载情绪，避免“我们要”“一定会”等空口号；需要队列可唱 Hook 和群体合唱入口。
- 军旅归途、边疆 anthem、国风电影电子：先写“守护的人为什么想回家”，再写“为什么还不能回家”；核心声音只选 marching snare、国风主音色、群体 Hook 或 cinematic bass 中的 2-3 个，Hook 必须能被普通人喊出，主歌必须落到界碑、家书、电话、灯、雪、鞋底泥等可拍物件。

## Suno 输入纯净规则

`suno.md` 不得出现以下内容：

- `Ref`、`Reference`、资料来源、VPI、EI、审稿、加分项。
- “爆款模型”“营销路径”“传播套件”“适用场景描述”等分析文本。
- 不能被 Suno 执行的理论词：声调映射、认知闭合、算法友好度、用户转化等。
- 与用户要求无关的解释性段落。

括号内只写 Suno 可执行提示，例如 `(male lead, tight drums, sudden pause)`、`(全员齐唱, 鼓点停顿, 人声靠前)`。

## 交付前自检

交付或写入 `suno.md` 前逐项检查：

- 是否只包含固定字段，没有额外说明。
- 前 3 秒是否有声音指纹。
- 前 8 秒是否有 `Hook Preview`。
- 15 秒内是否出现完整爆点。
- 是否有 15-31 秒黄金片段。
- Hook 首句是否像真人会唱出口的话，而不是正确判断句。
- 是否像真人会唱出口，有自然语流和真实停顿，而不是 AI 写作式鼓励。
- Hook 是否能清唱，且标题是否绑定主旋律。
- 编曲是否只有 2-3 个核心声音武器，并且有一个可记忆声音指纹。
- 情绪是否单一强烈。
- Verse 是否有具体场景、物件或动作。
- Verse 画面是否能直接拍成短视频。
- 每个核心段落是否有具体动作、物件、身体反应或没说出口的话。
- 是否避免模板化治愈、文案腔、假诗意和空泛升华。
- `Style of Music` 是否前置了曲风、情绪、人声、节奏引擎、Hook 武器和手机外放清晰度。
- `Exclude` 是否不超过 8 项，且没有排除正文正向元素。
- 是否只保留最终 `suno.md` 固定字段，且可直接复制到 Suno。
