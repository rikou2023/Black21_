# BLACK21 狼人表情包 — AI 生成提示词

> 微信/LINE 风格贴纸表情。**Q 版大头**,和前面的写实半身插画是**不同风格**,专为小尺寸表情设计。

## ⚠️ 铁律（每张都适用）

1. **上传 `logo.png` 当角色参考**(保持是同一只狼:灰毛、青眼、青色耳机带狼头 emblem)。
2. **固定 seed**,整套表情角色才统一。
3. **正方形 `--ar 1:1` + 透明背景**(`transparent background`,方便当贴纸)。
4. **不要让 AI 写字**(中文/英文都容易糊)——**文字后期我或你用 PS 加**,提示词里只画表情动作。
5. **Q 版比例**:大头、身体小、表情夸张、线条干净,**128px 缩小也认得出**。

**通用负面词:**
```
text, letters, chinese characters, watermark, signature, realistic proportions, blurry, low-res, complex background, extra limbs, oversaturated
```

**通用风格串**（每条开头都带上）:
```
chibi kawaii sticker, cute big-head anthropomorphic grey wolf, small body, wearing cyan gaming headphones with a glowing wolf emblem, ice-blue eyes, black hoodie with cyan trim, bold clean outline, flat cel shading, exaggerated expression, transparent background, sticker die-cut style, cyberpunk cyan #00B2E0 accents
```

---

## 建议的 16 个表情（先做常用的几个）

| # | 情绪/动作 | 加在提示词末尾的动作描述（英文） | 后期配字建议 |
|---|---|---|---|
| 1 | 点赞 | `giving a big thumbs up, confident grin` | 赞! |
| 2 | 比心 | `making a finger heart, sparkling eyes, blush` | 爱了 |
| 3 | 大笑 | `laughing hard, eyes closed, tears of joy` | 哈哈哈 |
| 4 | 无语 | `flat unamused face, half-lidded eyes, sweatdrop` | 无语 |
| 5 | 震惊 | `shocked jaw-drop, eyes wide, hands on cheeks` | 震惊 |
| 6 | 生气 | `angry pouting, furrowed brow, steam from ears` | 生气! |
| 7 | 哭 | `crying with big teary eyes, trembling` | 呜呜 |
| 8 | 疑惑 | `confused, tilted head, floating cyan question mark` | ？？ |
| 9 | 冲/加油 | `fist pump, determined fiery eyes` | 冲! |
| 10 | OK | `making an OK hand sign, wink` | OK |
| 11 | 睡觉 | `sleeping, eyes closed, floating cyan Zzz` | 晚安 |
| 12 | 耍酷 | `wearing sunglasses, arms crossed, smug smile` | 就这? |
| 13 | 拜托 | `pleading puppy eyes, paws clasped together` | 求求了 |
| 14 | 摊手 | `shrugging with both palms up, blank face` | 我能怎么办 |
| 15 | 干杯 | `holding a soda can, cheerful toast pose` | 干杯 |
| 16 | 打工 | `tired dead-eyes, holding a laptop, slumped` | 打工人 |

**用法示例(第 1 个「点赞」):**
```
chibi kawaii sticker, cute big-head anthropomorphic grey wolf, small body, wearing cyan gaming headphones with a glowing wolf emblem, ice-blue eyes, black hoodie with cyan trim, bold clean outline, flat cel shading, exaggerated expression, transparent background, sticker die-cut style, cyberpunk cyan #00B2E0 accents, giving a big thumbs up, confident grin --ar 1:1
```

---

## 做法建议

- **先做 1、3、8、11、12** 这 5 个(点赞/大笑/疑惑/睡觉/耍酷)最常用,验证风格统一了再补齐 16 个。
- 出完透明底 PNG,我可以帮你**批量加文字**(用统一像素字体),或做成网站上的互动彩蛋(点狼人蹦表情)。
- 想要动图(GIF)版的话,单张先做好,后面再考虑 2-3 帧的简单动效。
