# 01 前 3-8 秒抓耳

## 资料范围

本项使用 `source-bank-50.md` 的50篇来源，重点参考 S01-S07、S19-S21、S37-S41、S48-S50。核心问题：短视频用户在极短时间内决定是否继续听，Suno 歌曲必须把声音指纹和 Hook Preview 前置。

## 50篇来源清单

本项来源清单见 [source-bank-50.md](source-bank-50.md) S01-S50；本项重点使用 TikTok/Luminate、MBW、Chartmetric、Hook 写作、30秒注意力捕获、Hook Preview 与 Suno v5.5 prompt 工程资料。

## 共识结论

- 前奏超过3秒会显著削弱短视频留存，除非前奏本身就是强声音指纹。
- 3秒内至少出现一种辨识事件：人声、鼓点、口号、特殊音色、突然静止、sub drop、采样切片。
- 8秒内必须让听众听到主 Hook 的文字或旋律影子。
- “先给结果，再回故事”比传统长铺垫更适合抖音/TikTok。
- Hook Preview 不等于完整副歌，最好只放核心首句或2句以内的片段。

## 冲突观点

- 传统歌曲允许慢热铺垫，短视频歌曲不适合默认慢热。
- 电影感或古风需要氛围，但也要在3秒内给出可辨识声音，如古琴泛音、人声气口、鼓点停顿。
- 电子歌可以先 buildup，但短视频首段仍要有 drop 预告或节奏签名。

## 可执行 Suno 写法

`Style of Music` 写入：

```text
前3秒人声切入, signature vocal chop, tight first-beat drum hit, no long intro, phone-speaker clear hook
```

`Lyrics` 写入：

```markdown
[Intro | sound fingerprint | 0-3s]
(突然停顿, 一声近距离人声, 鼓点落下)

[Hook Preview | 3-8s]
把眼泪调成静音
把眼泪调成静音
```

## 反例

- `[Intro] (长氛围铺垫, 20秒)`。
- 第一段只写抽象情绪，没有 Hook Preview。
- 开头堆满乐器名，但没有可记住的声音动作。

## 交付自检

- 前3秒是否有声音指纹？
- 前8秒是否出现主 Hook 文字或旋律影子？
- Intro 是否不超过3秒，或本身就是爆点？
- Hook Preview 是否能独立剪成短视频开头？

