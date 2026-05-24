# 11 手机外放制作

## 资料范围

本项使用 `source-bank-50.md` 的50篇来源，重点参考 S34-S36、S40、S48-S50。核心问题：很多爆款首先通过手机、小音箱和压缩音频被听到，制作提示必须保护清晰度。

## 50篇来源清单

本项来源清单见 [source-bank-50.md](source-bank-50.md) S01-S50；重点使用 loudness、dynamic range、小扬声器翻译、Suno prompt、Exclude、vocal engineering 资料。

## 共识结论

- 手机上最重要的是人声、主旋律、鼓点和中频冲击。
- 低频要有轮廓，不要糊；高频要有亮点，不要刺。
- 副歌要比主歌明显抬升，但不能靠混响堆满。
- 过多乐器会让 Suno 生成糊成一片，应控制核心声音武器。
- Exclude 应保护清晰度：`buried vocals, muddy bass, excessive reverb` 等。

## 冲突观点

- 大制作不等于大堆叠；短视频爆款常靠少数清楚元素胜出。
- 宽混响有氛围，但会牺牲字幕级歌词清晰度。

## 可执行 Suno 写法

`Style of Music` 写入：

```text
phone-speaker clear mix, upfront vocal, punchy midrange drums, tight low-end separation, bright but not harsh hook synth
```

`Exclude` 可用：

```text
buried vocals, muddy bass, excessive reverb, weak drums, harsh highs, cluttered arrangement, long intro, instrumental
```

## 反例

- Style 堆十几种乐器。
- `wide huge reverb` 同时要求歌词清楚。
- Exclude 写了正向要求的乐器。

## 交付自检

- 人声是否靠前？
- 鼓点和主旋律是否手机可辨？
- 低频是否写了分离和紧致？
- Exclude 是否保护清晰度且不冲突？

