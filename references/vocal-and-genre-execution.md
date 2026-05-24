# 人声与曲风执行规范

本文件把人声真实感、曲风提示和重点风格保护压缩为本 Skill 的本地规范。写 `suno.md` 时只使用可执行词，不输出解释。

## 人声四维度

用具体词写人声，不写“好听”“高级”。

- 气息：`breathy`、`natural breath`、`whispered`、`clean attack`。
- 颤音：`minimal vibrato`、`controlled vibrato`、`no vibrato`。
- 发声：`mixed voice`、`chest voice`、`head voice`、`falsetto`。
- 表达：`intimate`、`restrained`、`passionate`、`detached`、`playful`。

段落可以变化：

```text
Verse breathy intimate → Pre-Chorus tightened → Chorus clean lifted → Final Chorus highest emotional point
```

## 常见曲风人声模板

- Pop：`mixed voice, natural breath, clear consonants, passionate chorus`
- R&B：`breathy mixed voice, controlled vibrato, intimate delivery`
- Folk：`warm chest voice, minimal vibrato, close dry vocal`
- Zhongguo Feng：`clear Mandarin vocal, restrained delivery, light ornament, no over-singing`
- Electronic：`clean processed vocal, rhythmic phrasing, tight sync with beat`
- Rock：`clean energetic vocal, upfront presence, controlled grit only if needed`
- Anthem：`clear lead vocal, group response, crowd-singable chorus`

## 金属男声保护

大型金属、工业金属、体育场金属中，男声很容易被 Suno 生成成沙哑、嘶吼、歇斯底里。保护原则：

- 人声词少而准，力量交给鼓、吉他、合唱和 riff。
- 推荐：`clean smooth warm male vocal, natural tone, upfront vocal presence`。
- 谨慎或避免正向使用：`raw`、`gritty`、`screaming`、`authoritative`、`commanding`、`heroic`、`resonant`、`full-throated power`。
- Exclude 可加：`raspy vocals, throat strain, screamo, buried vocals`。

金属可执行模板：

```text
cinematic stadium metal, clean smooth warm male vocal, natural tone, upfront vocal presence, gang chant hook, war drums, double-kick drive, palm-muted heavy guitar riff, tight low-end separation
```

## 曲风核心化

融合风格不要堆满乐器。每首歌只选2-3个核心声音武器：

- 国风电子：`guzheng hook + electronic bass pulse + clear vocal`
- 工业：`mechanical percussion + distorted synth pulse + chant hook`
- 金属：`riff + war drums + gang chant`
- 甜歌：`bright pluck + soft groove + sweet close vocal`
- 伤感：`piano motif + dry close vocal + restrained strings`

其他元素写成 `accent`、`background`、`subtle layer`、`phrase-edge color`。

## 手机外放保护

Style 中优先加入：

```text
phone-speaker clear vocal, upfront vocal mix, tight low-end separation, punchy midrange drums, no muddy low mids
```

Exclude 可选：

```text
buried vocals, muddy bass, excessive reverb, harsh highs, cluttered arrangement
```

## 自检

- 人声是否有明确人格，而不是泛泛“powerful vocal”？
- 主唱是否靠前？
- 合唱是否只在 Hook 或 Post-Chorus 支撑？
- 曲风是否只有2-3个核心声音武器？
- Exclude 是否保护了人声和清晰度？
