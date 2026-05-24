# 28 Suno Custom Mode 字段职责

## 资料范围

本项使用 [suno-best-practice-source-bank-100.md](suno-best-practice-source-bank-100.md) 的100篇来源，重点参考 A、B、J 组。目标是让 `suno.md` 的每个字段都能直接复制到 Suno Custom Mode。

## 核心规则

- `Title` 负责搜索和记忆，不负责解释概念；最好来自 Chorus 主 Hook。
- `Style of Music` 负责声音边界，必须前置 genre、mood、vocal、rhythm engine、hook weapon、mix target。
- `Vocal Gender` 必须和 Style、Lyrics 人声提示一致。
- `Weirdness` 控制新鲜感，默认35-55，不要为了“爆”盲目拉高。
- `Style Influence` 控制风格遵循度，默认45-65；曲风明确时可高一点。
- `Model` 默认 `v5.5`。
- `Lyrics` 负责结构、歌词、段落动作和可执行制作提示。
- `Exclude` 负责反向保护，不超过8项，不排除正向元素。

## Suno 可执行写法

```markdown
## Title
心跳抢了拍

### Style of Music
Chinese viral pop rock, 甜燃心动, clean bright female vocal, tight clap groove, repeated title hook, phone-speaker clear vocal, 124 BPM, chorus lift, upfront vocal mix.

### Vocal Gender
Female

### Weirdness
42

### Style Influence
58

### Model
v5.5
```

## 常见失败

- Style 写成散文故事，Suno 不知道该生成什么声音。
- Vocal Gender 写 `Female`，Style 却写 male vocal。
- Weirdness 太高导致曲风跑偏。
- Title 很长，不能搜索和记忆。

## 修复策略

- 把 Style 缩成“曲风 + 情绪 + 人声 + 节奏 + Hook + mix”。
- 删除不能发声的抽象词，如“高级感、爆款感、算法友好”。
- 检查所有字段人声一致。

## 最终自检

- 字段顺序是否固定？
- Style 前半段是否包含核心声音？
- Vocal Gender 是否一致？
- slider 是否在合理区间？
- Title 是否短且可唱？

