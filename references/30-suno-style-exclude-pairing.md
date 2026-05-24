# 30 Suno Style 与 Exclude 正负配对

## 资料范围

本项使用 [suno-best-practice-source-bank-100.md](suno-best-practice-source-bank-100.md) 的100篇来源，重点参考 C、E、G、J 组。目标是防止曲风漂移、混音糊、人声被埋和弱 Hook。

## 核心规则

- Style 写“要什么”，Exclude 写“不要什么”，二者配对。
- Exclude 不超过8项，越具体越好。
- 不写 `no`，直接写元素名。
- 不排除正文正向要求。
- 优先保护：开头、主唱、低频、Hook、混响、曲风、编曲密度。

## Suno 可执行写法

Style：

```text
Chinese viral pop rock, clean bright female vocal, tight clap groove, repeated title hook, phone-speaker clear vocal, upfront vocal mix
```

Exclude：

```text
long intro, buried vocals, muddy bass, weak hook, generic lyrics, excessive reverb, harsh highs, instrumental
```

## 常见失败

- Exclude 写 `bad music` 这种抽象词。
- Exclude 超过12项，反向指令稀释。
- Style 写 `gang chant`，Exclude 又写 `chanting`。
- Style 写太多曲风，Exclude 无法保护核心。

## 修复策略

- 先确定2-3个核心声音武器。
- 每个核心问题写一个反向保护。
- 先扫描白名单，再写 Exclude。
- 曲风跑偏时，删除多余风格词，比堆 Exclude 更有效。

## 最终自检

- Exclude 是否≤8项？
- 是否没有抽象词？
- 是否与 Style 配对？
- 是否没有排除正向元素？
- 是否保护了主唱、Hook 和清晰度？

