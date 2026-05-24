# Suno v5.5 执行规范

本文件把 Suno 生成所需的技术规则压缩成本 Skill 可直接使用的本地规范。生成 `suno.md` 时只输出字段和可执行内容，不输出本文件的解释。

## 专项参考

- [Suno Custom Mode 字段职责](28-suno-custom-mode-fields.md)
- [Suno Metatags 与结构控制](29-suno-metatags-structure-control.md)
- [Suno Style 与 Exclude 正负配对](30-suno-style-exclude-pairing.md)
- [Suno 中文歌词与人声稳定性](31-suno-lyrics-vocal-stability.md)
- [Suno 曲风漂移修复](32-suno-genre-drift-fixes.md)
- [Suno 最终输出检查表](33-suno-final-output-checklist.md)
- [Suno 生成最佳实践 100篇资料清单](suno-best-practice-source-bank-100.md)

## 固定字段

`suno.md` 必须按此顺序：

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

## 字段写法

- `Title`：短、可搜、可唱，最好来自 Chorus 主 Hook。
- `Style of Music`：像制作简报，不像散文；前半段放曲风、情绪、人声、节奏引擎、Hook 武器、手机外放清晰度。
- `Vocal Gender`：使用 `Male`、`Female`、`Duet`、`Group`，本 Skill 不使用 `Instrumental`。
- `Weirdness`：默认35-55。主流流行30-40，工业/反差/怪点45-60。
- `Style Influence`：默认45-65。越高越贴近风格描述，越低越让 Suno 自由发挥。
- `Model`：默认 `v5.5`。
- `Lyrics`：只放歌词、结构标签和括号内可执行提示。
- `Exclude`：不超过8项；写元素名，不写长句，不写抽象评价。

## Style of Music 公式

```text
曲风, 明确情绪, 人声特征, 节奏引擎, Hook武器, 核心乐器或音色, 手机外放清晰度, BPM, 调性感, mix保护
```

示例：

```text
Chinese viral pop rock, 燃感都市逆袭, clean smooth male vocal, tight stomping drums, gang chant hook, punchy guitar riff, phone-speaker clear vocal, 128 BPM, minor verse to major chorus lift, upfront vocal mix.
```

## Metatags

结构标签必须放在段落标签第一位：

```markdown
[Intro | sound fingerprint | 0-3s]
[Hook Preview | 3-8s]
[Verse 1 | visual scene]
[Pre-Chorus | rising tension]
[Chorus | viral hook | full mix]
[Post-Chorus | chant hook]
[Bridge | stripped contrast]
[Final Chorus | highest point]
[Outro | loop-friendly tail]
```

括号内只写 Suno 可执行提示：

```text
(近距离男声, 鼓点停顿)
(sub drop, sudden cut)
(全员齐唱, clap clap)
```

不要写理论说明、评分、资料来源、营销计划或“这里适合短视频”。

## Exclude

写 Exclude 前先扫描正文白名单：

- `Style of Music`
- `Vocal Gender`
- `Lyrics` 方括号标签
- 括号内制作提示

不得排除正文正向要求的元素。例：正向写了 `gang chant`，Exclude 不能写 `chanting`；正向写了 `heavy guitar`，Exclude 不能写 `rock guitars`。

常用保护项：

```text
long intro, buried vocals, muddy bass, weak hook, generic lyrics, excessive reverb, harsh highs, instrumental
```

## Suno 输入纯净检查

最终 `suno.md` 不得出现：

- Reference、资料来源、研究结论、评分、VPI、EI、审稿。
- “爆款模型”“算法友好”“传播路径”等分析词。
- 任何不能被 Suno 执行的解释。
- 其他 skill 路径、历史目录、外部本地文件名。
