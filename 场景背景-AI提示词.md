# BLACK21 像素场景背景 — AI 生成提示词

> 用于横版闯关站的**关卡背景**。角色由我(代码)单独叠在前面,所以**这些背景里不要出现狼人角色**。

## ⚠️ 通用要求（每张都适用）

1. **不要角色、不要文字、不要 logo**（纯环境;文字/招牌我后期加或让 AI 只画空招牌框）。
2. **风格与角色一致**:pixel-art anime、赛博朋克夜、青色霓虹 + 深蓝黑,和你那只狼同一世界。
3. **尺寸**:`--ar 16:9`,分辨率越高越好(目标 ≥1920×1080)。
4. **下方留出平整地面/地板**:角色会站在画面下部,别让下面 1/4 堆满杂物,留一条能站人的地面线。
5. **配色红线**:主色深蓝黑,强调色只用青 `#00B2E0`(可少量白光点缀),**禁止紫粉渐变**。

**通用负面词:**
```
character, wolf, person, humanoid, text, letters, watermark, signature, blurry, low-res, purple pink gradient, cluttered foreground, oversaturated
```

**提示**:每个场景可多出几张挑最合适的;若某张能分出"远/中/近"三层单独出图更好(我能做更强视差),但一张整图也够用。

---

## ① Hero —— 赛博东京夜街（首页）
```
pixel-art anime cyberpunk cityscape at night, Tokyo-style neon street, layered skyscrapers with glowing cyan windows, distant moon, faint stars, cyan neon signs (empty sign frames, no readable text), atmospheric depth, dark navy #06080E palette with cyan #00B2E0 accents, clean flat ground strip along the bottom, crisp pixel-art, no characters --ar 16:9
```

## ② About —— 狼人的房间 / 工位（像素室内）
```
pixel-art anime cyberpunk bedroom / dev workstation interior at night, dark room, desk with glowing monitors showing cyan code, gaming chair, LED strips, posters, plants, warm-cool contrast but cyan-dominant, cozy hacker den vibe, dark navy palette with cyan #00B2E0 glow, flat floor in the lower area, crisp pixel-art, no characters --ar 16:9
```

## ③ Projects —— 霓虹小巷 / 工作室（关卡）
```
pixel-art anime cyberpunk back alley at night, narrow Tokyo alley, vending machines, hanging cables, neon shop signs (empty frames), steam, puddles reflecting cyan light, moody atmosphere, dark navy palette with cyan #00B2E0 neon, clear walkable ground along the bottom, crisp pixel-art, no characters --ar 16:9
```

## ④ Tools —— 工作台 / 实验室（关卡）
```
pixel-art anime cyberpunk workshop / lab at night, workbench with gadgets, floating holographic cyan UI panels, tools on pegboard, server racks with blinking cyan lights, technical clean vibe, dark navy palette with cyan #00B2E0 accents, flat floor at the bottom, crisp pixel-art, no characters --ar 16:9
```

## ⑤ Contact —— 天台夜景（结尾关卡）
```
pixel-art anime cyberpunk rooftop at night overlooking a neon city skyline, railing, rooftop AC units and antennas, big moon, sea of glowing buildings below, wind, quiet lonely mood, dark navy palette with cyan #00B2E0 glow, flat rooftop floor along the bottom, crisp pixel-art, no characters --ar 16:9
```

---

## 做法建议

- **一关一张**,滚动时在场景间过渡 + 角色叠前面——最适合你出图,也最好看。
- 先出 **① Hero + ② About** 两张,我接进引擎跑通一个完整关卡给你看,对味了再出其余三张。
- 想要更强纵深:某张(尤其 Hero)可再单出一张"只有远景天际线 + 月亮 + 星空"的**远景层**(透明或深底),我让它比近景慢,视差更立体。
