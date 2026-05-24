# 33 Suno 最终输出检查表

## 资料范围

本项使用 [suno-best-practice-source-bank-100.md](suno-best-practice-source-bank-100.md) 的100篇来源，重点参考 J 组和所有 Suno 专项。目标是保证最终 `suno.md` 可直接复制到 Suno。

## 核心规则

最终只能输出 `suno.md` 固定字段，不输出解释、来源、评分或报告。

## 最终字段检查

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

## 内容检查

- `Title` 短、可搜、最好来自 Hook。
- `Style of Music` 前半段包含：曲风、情绪、人声、节奏引擎、Hook武器、mix保护。
- `Vocal Gender` 与 Style 和 Lyrics 一致。
- `Model` 为 `v5.5`。
- `Lyrics` 有结构标签，前8秒有 Hook Preview。
- 括号只写可执行声音动作。
- `Exclude` ≤8项，无冲突。

## 禁止内容

`suno.md` 不得出现：

- 来源、Reference、研究、评分、审稿、VPI、EI。
- “适合短视频”“算法友好”“传播路径”等分析语。
- 旧路径、其他 skill、历史目录。
- `design.md`、`metadata.md`、音频生成说明。

## 常见失败

- 在 `suno.md` 开头写说明。
- Exclude 排除了正向要求。
- Lyrics 里把 metatag 写成普通句子。
- Style 过长、过散、堆满抽象词。

## 修复策略

- 删除所有非字段内容。
- 精简 Style 到一行制作简报。
- 检查 Lyrics 方括号标签。
- 重新扫描 Exclude 白名单冲突。

## 复制到 Suno 前自检

- 是否能直接复制？
- 是否没有解释文字？
- 是否不生成纯音乐？
- 是否不生成音频文件？
- 是否不生成 `design.md` 或 `metadata.md`？
- 是否只服务 Suno 平台生成歌曲？

