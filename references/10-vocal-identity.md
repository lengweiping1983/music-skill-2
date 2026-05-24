# 10 人声辨识度

## 资料范围

本项使用 `source-bank-50.md` 的50篇来源，重点参考 S19、S31、S35-S36、S49-S50。核心问题：短视频里用户常先记住“这个声音是谁/像什么人格”，而不是复杂唱功。

## 50篇来源清单

本项来源清单见 [source-bank-50.md](source-bank-50.md) S01-S50；重点使用 vocal timbre、formant emotion、Suno vocal engineering、Hook和手机外放资料。

## 共识结论

- 辨识度来自声音人格：沙哑、甜、拽、破碎、少年感、烟嗓、哭腔、机械感、群体 chant。
- 炫技不能压过歌词可懂度和 Hook 记忆。
- 主唱必须靠前，合唱、和声、乐器都服务主唱。
- 一句里最好有“表演钩子”：气口、停顿、咬字、尾音、破音边缘或近讲感。
- Suno 提示要写可执行人声特征，不写抽象评价。

## 冲突观点

- 强处理人声能有记忆，但过度 auto-tune 会削弱情绪可信度。
- 群体 chant 很有传播力，但不能抢掉主唱旋律。

## 可执行 Suno 写法

`Style of Music` 写入：

```text
close upfront smoky male vocal, clear consonants, emotional breath before hook, group backing only in post-chorus, lead vocal above mix
```

`Lyrics` 提示：

```markdown
[Hook Preview | vocal signature]
(近距离气声, 尾字轻破)
别回头看我
```

## 反例

- `powerful vocal` 但没有具体人声标签。
- 合唱墙盖住主唱。
- 转音太多，Hook 字听不清。

## 交付自检

- 人声是否有一句可辨识表演？
- `Style` 是否写清人声人格？
- 主唱是否被要求居中靠前？
- 和声是否只在需要时出现？

