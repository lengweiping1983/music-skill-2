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
- `Lyrics` 已去 AI 味，没有模板化治愈、文案腔、空泛升华或假诗意。
- 每个核心段落有具体动作、物件、身体反应或没说出口的话。
- 同一首歌只有一个绝对中心 Hook，第二传播句、Post-Chorus 和 Outro 都服务它。
- 括号只写可执行声音动作。
- `Exclude` ≤8项，无冲突。

## 禁止内容

`suno.md` 不得出现：

- 来源、Reference、研究、评分、审稿、VPI、EI。
- “适合短视频”“算法友好”“传播路径”等分析语。
- 旧路径、其他 skill、历史目录。
- 额外说明文件、伴随文档、音频生成说明。
- “去 AI 味审稿”“真人感评分”等内部分析语。

## 常见失败

- 在 `suno.md` 开头写说明。
- Exclude 排除了正向要求。
- Lyrics 里把 metatag 写成普通句子。
- Lyrics 里出现 AI 式正确答案、应用提示式俏皮句、抽象概念堆叠或鸡汤总结。
- 副歌平均塞入多个口号，导致最强 Hook 不突出。
- 已经成立的歌词被反复打磨到失去自然口语和记忆点。
- Style 过长、过散、堆满抽象词。

## 修复策略

- 删除所有非字段内容。
- 精简 Style 到一行制作简报。
- 检查 Lyrics 方括号标签。
- 用具体动作、物件或身体反应替换低真人感句子。
- 重新扫描 Exclude 白名单冲突。

## 复制到 Suno 前自检

- 是否能直接复制？
- 是否没有解释文字？
- 是否不生成纯音乐？
- 是否不生成音频文件？
- 是否不生成额外说明文件或伴随文档？
- 是否只服务 Suno 平台生成歌曲？
- 是否没有 AI 味句子进入 `Lyrics`？
- Final Chorus 是否用真实动作或情绪变化收束，而不是空泛升华？
- 是否已经达到可生成状态？如果只剩偏好级修改，停止文字优化，进入音频验证。
