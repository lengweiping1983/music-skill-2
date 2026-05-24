# 31 Suno 中文歌词与人声稳定性

## 资料范围

本项使用 [suno-best-practice-source-bank-100.md](suno-best-practice-source-bank-100.md) 的100篇来源，重点参考 D、F、G、H 组。目标是提高中文可唱性、咬字、人声真实感和歌词稳定生成。

## 核心规则

- 中文歌词优先4-10字一行，Hook 更短。
- 少用生僻字、多音字和绕口连续字。
- 主歌具体，副歌短，Bridge 给新信息。
- 括号里用可执行人声提示：`close vocal`、`clear Mandarin consonants`、`natural breath`。
- 人声提示要具体，不写“唱得好听”。

## Suno 可执行写法

```markdown
[Verse 1 | close vocal | clear Mandarin]
凌晨三点半
灯还没关怀
你那句早点睡
亮了一整夜

[Chorus | clear title hook | lifted vocal]
把眼泪调成静音
别让你听见我
```

Style 可加：

```text
clear Mandarin vocal, natural breath, upfront vocal, short singable lines
```

## 常见失败

- 歌词太长，Suno 吞字。
- 生僻字导致发音奇怪。
- 句子像散文，节奏不稳定。
- 人声提示全是抽象评价。

## 修复策略

- 把长句拆成短行。
- 替换多音字和生僻字。
- Chorus 押韵并重复主 Hook。
- 用 `clear Mandarin consonants` 和 `upfront vocal` 保护咬字。

## 最终自检

- 每行是否适合换气？
- Hook 是否短且可唱？
- 是否避免多音字/生僻字？
- 是否有人声清晰度提示？
- Bridge 是否有新信息？

