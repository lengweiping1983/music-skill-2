# 39 古琴旧物氛围人声 Suno 爆款 Playbook

## 资料范围

本项吸收 `39-guqin-ambient-viral-suno-source-bank-50.md` 的 50 条资料，覆盖古琴审美、琴学中的“韵”、中国五声音阶、旧物/修复叙事、环境音乐制作、人声清晰度、混响空间，以及 Suno v5.5 的 Custom Mode、metatags、Voices、Custom Models 和提示词实践。

## 核心结论

- 这类歌的核心不是“古风词多”，而是一个旧物在当下被人重新听见。
- 古琴感来自过程音：泛音、按音、滑音、余音、留白和一声之后的静，不来自堆满古乐器名。
- “韵”要写成可执行声音：slow guqin decay、breath pause、sparse room tone、temple bell tail、controlled vocal lift。
- 旧物叙事必须有职业手和动作：修琴、补漆、拓碑、装帧、补瓷、擦灰、换弦、听旧磁带。
- 爆款化不能靠大鼓强推；要靠 3-8 秒可记的短句、15-31 秒可截取的情绪段、标题句重复和一个声音 Logo。
- Suno 中要把整体气质放在 `Style of Music`，把段落动作放在 Lyrics 的 metatags 和括号提示中；不要把研究结论写进最终 `suno.md`。

## 旧音专辑写法

- 主题公式：`旧物/旧声 + 一个修复动作 + 一个不说满的人间关系 + 一句可清唱 Hook`。
- 情绪公式：怀旧、敬畏、轻微疼痛、被唤醒；不要同时写治愈、燃、爱情、家国。
- 角色优先：古琴修复师、漆器修复师、碑刻拓印师、旧唱片修复师、装帧师、补瓷人、钟表师、庙里守灯人。
- 物件优先：断纹、漆灯、拓包、碑灰、旧唱针、纸页、碎瓷、铜钟、木窗、香灰。
- 时间锚优先：`8:00`、`15:00`、`第7天`、`某年某月`、`一百年前`，但每段不超过 1-2 个数字，避免报数感。

## 编曲执行

- 核心声音武器只选 2-3 个：guqin harmonics、xiao breath、temple bell、woodblock pulse、lacquer brush scratch、vinyl dust crackle。
- 无鼓或轻鼓都可以；若要更爆款，使用极轻的木鱼/木板/低频心跳脉冲，不用 trap、EDM drop 或重鼓。
- Verse 保持稀疏：近距离人声、一个主乐器、一个环境采样。
- Chorus 做“庄严打开”：人声加宽、和声层增加、主音色 tremolo 或高八度，不要俗化大嗓门。
- Bridge 抽空：只留人声和旧物声音，让一句人话刺出来。
- 手机外放保护：人声靠前，混响短尾，低频少而清楚，灰尘/雨声/香灰类采样不要盖住辅音。

## Hook 规则

- 标题句必须能清唱，优先 6-10 个字。
- Hook 句式优先：
  - `不是坏了 是还在等`
  - `你听见了吗`
  - `灯还亮着`
  - `旧声没有走`
  - `慢一点 别抹平`
- 避免解释型副歌：不要连续写“这代表传承/这是记忆/这是时间”。
- 允许认知反转，但只能一层：`不是裂 / 是还记着` 这类结构有效，不能每段都“不是X是Y”。
- Post-Chorus 用短回声或问答：`一声 一灯 / 等 等 等你听`，但要避免所有歌都同一模板。

## Suno 可执行模板

`Style of Music`：

```text
Chinese traditional ambient vocal, old-object restoration narrative, restrained female vocal, sparse guqin harmonics and xiao breath, soft woodblock pulse, dust crackle sound logo, 72 BPM, minor pentatonic color, close upfront vocal, clear melodic chorus, phone-speaker clear mix, short reverb tail, stripped verse to solemn chorus lift.
```

`Lyrics`：

```markdown
[Intro | sound fingerprint | 0-3s]
(guqin harmonic, dust crackle, close whisper)

[Hook Preview | 3-8s]
灯还亮着
旧声没有走

[Chorus | restrained viral hook | full mix]
(controlled vocal lift, guqin tremolo, soft woodblock pulse)
灯还亮着
旧声没有走
```

`Exclude`：

```text
trap beats, EDM drop, rock guitars, cluttered arrangement, buried vocals, excessive reverb, generic ancient lyrics, bright dance pop
```

## 去 AI 味检查

- 每段是否有手上动作：擦、补、拓、吹、换、停、听、按住。
- 每段是否有可触摸物件：漆、灰、纸、弦、灯芯、木窗、铜钟。
- 是否有一处没有说出口的话，而不是把道理讲完。
- 古词是否克制：少用“山河、红尘、千年、宿命、轮回、归处”等泛古风词。
- 最后一段是否留画面，不写成“传承永远不会消失”的总结句。

## 最终自检

- 0-3 秒是否有旧物声音 Logo。
- 3-8 秒是否有标题或主 Hook。
- 15 秒内是否能进入可截取副歌或 Hook 完整句。
- Style 是否清楚写出核心声音、BPM、人声、空间和手机外放保护。
- Exclude 是否保护克制氛围，没有排除正文正向元素。
- 是否听起来像一首可以生成的歌，而不是一篇关于非遗的散文。
