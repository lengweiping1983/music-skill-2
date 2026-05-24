# 32 Suno 曲风漂移修复

## 资料范围

本项使用 [suno-best-practice-source-bank-100.md](suno-best-practice-source-bank-100.md) 的100篇来源，重点参考 E、F、G、J 组。目标是让用户指定曲风在 Suno 中更稳定。

## 核心规则

- 曲风漂移通常来自 Style 过长、风格互相冲突、乐器堆叠、Exclude 不配对。
- 每首歌只保留2-3个核心声音武器。
- 风格词放 Style 最前面。
- 非核心元素写 `accent`、`background`、`subtle layer`。
- 出现漂移时先删正向冲突词，再加 Exclude。

## 曲风模板

流行：

```text
Chinese viral pop, clean lead vocal, tight mid-tempo groove, repeated chorus hook, bright phone-speaker mix
```

工业：

```text
Chinese industrial pop rock, mechanical percussion, distorted synth pulse, chant hook, upfront vocal, tight low-end
```

金属：

```text
cinematic stadium metal, clean smooth warm male vocal, natural tone, gang chant hook, war drums, palm-muted heavy guitar riff
```

国风电子：

```text
Chinese electronic fusion, guzheng hook, electronic bass pulse, clear Mandarin vocal, modern drum groove, controlled stereo
```

R&B：

```text
Chinese R&B, breathy mixed vocal, smooth groove, syncopated hook, warm bass, intimate chorus
```

Anthem：

```text
Chinese anthem pop rock, clear lead vocal, group response, stomping drums, crowd-singable chorus, real-life detail
```

## 常见失败

- Style 同时写 pop、metal、folk、EDM、orchestral，模型抓不住主线。
- 国风写太多传统乐器，结果像混乱民乐。
- 金属男声被写成 `raw gritty screaming`，生成嘶吼。

## 修复策略

- 删除非核心风格词。
- 把辅助乐器降级为 `subtle accent`。
- 给 Exclude 加对立项：`acoustic ballad`、`EDM drop`、`buried vocals` 等。
- 金属男声优先 `clean smooth warm male vocal`。

## 最终自检

- Style 首词是否就是主曲风？
- 核心声音武器是否≤3个？
- 是否有冲突风格词？
- 辅助元素是否标为背景/点缀？
- Exclude 是否防最可能漂移方向？

