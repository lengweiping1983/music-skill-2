# 29 Suno Metatags 与结构控制

## 资料范围

本项使用 [suno-best-practice-source-bank-100.md](suno-best-practice-source-bank-100.md) 的100篇来源，重点参考 B、F、G、J 组。目标是让 Suno 看懂段落、能量、演唱和转场。

## 核心规则

- Metatags 只放在 `Lyrics`，不要塞进 `Style of Music`。
- 段落标签结构名必须第一位：`[Chorus | full mix]`，不要写 `[full mix | Chorus]`。
- `Intro` 不超过3秒，或本身就是声音指纹。
- `Hook Preview` 放在前3-8秒，只放主 Hook 片段。
- `Pre-Chorus` 负责收紧，`Chorus` 负责释放，`Bridge` 负责换视角。
- 括号提示只写可执行声音动作。

## Suno 可执行写法

```markdown
[Intro | sound fingerprint | 0-3s]
(一声近距离气口, clap落下)

[Hook Preview | 3-8s]
心跳抢了拍
心跳抢了拍

[Verse 1 | visual scene | close vocal]

[Pre-Chorus | rising tension | drums build]

[Chorus | viral hook | full mix]

[Post-Chorus | chant hook | clap clap]

[Bridge | stripped contrast | vulnerable vocal]

[Final Chorus | highest point | upgraded hook]

[Outro | loop-friendly tail]
```

## 常见失败

- 没有结构标签，Suno 把歌词唱成一坨。
- 括号里写“这里要爆款”，Suno 无法执行。
- Bridge 没有新信息，只是重复副歌。
- Final Chorus 不升级。

## 修复策略

- 给每段加结构标签和一个声音功能。
- 把解释词改成声音动作：`算法友好` → `Hook Preview | 3-8s`。
- 把“情绪更强”改成 `full mix, higher harmony, drums lift`。

## 最终自检

- 每段是否有结构标签？
- 结构名是否第一位？
- 前8秒是否有 Hook Preview？
- 括号是否只写可执行声音？
- Final Chorus 是否有升级？

