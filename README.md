# palette

[中文](#中文) | [English](#english)

## 中文

数学讲解视频的配色，为 Manim 设计。所有套的颜色角色一致（背景、文字、对象 A/B/C、结论、错误、次要），可以直接互换。

对外视频默认用培玉（浅色）；需要深色时用培玉·深色。蓝图和孔版印刷留给特定专题，其余几套是备用。

![培玉 / 培玉·深色](previews/peiyu.png)

### 品牌主题

这两套是培玉课程实际在用的主题，作为真实案例收录。

> 色值随本仓库的 MIT 许可发布，可以自由使用；「培玉」/ Peiyu 名称和 logo 是培玉智能的商标，不在许可范围内。

#### 培玉 Peiyu（默认）

培玉的品牌色卡，浅色。松绿和赤金取自 logo，再配石青、赭石，是青绿山水的一套颜色。logo 原色在米白底上太淡，文字都用压深后的同色相版本。

`C_A` 和 `C_A_2` 是同一色相的两层，适合原数列→一阶差这种逐层推出的关系；两个并列对象用 `C_A` 和 `C_B`。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/F7F4EE/F7F4EE.png) `#F7F4EE` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/1A2822/1A2822.png) `#1A2822` |
| 对象 A | `C_A` | ![](https://placehold.co/14x14/1E4A36/1E4A36.png) `#1E4A36` |
| 对象 A 下一层 | `C_A_2` | ![](https://placehold.co/14x14/2F7A56/2F7A56.png) `#2F7A56` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/2F5D8A/2F5D8A.png) `#2F5D8A` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/A35A32/A35A32.png) `#A35A32` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/B5843A/B5843A.png) `#B5843A` |
| 强调小字（浅底用） | `C_HL_INK` | ![](https://placehold.co/14x14/8A6230/8A6230.png) `#8A6230` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/B03A2E/B03A2E.png) `#B03A2E` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/8A8478/8A8478.png) `#8A8478` |
| logo 松绿（不用于文字） | `C_BRAND_GREEN` | ![](https://placehold.co/14x14/90B898/90B898.png) `#90B898` |
| logo 赤金（不用于文字） | `C_BRAND_GOLD` | ![](https://placehold.co/14x14/B89058/B89058.png) `#B89058` |

#### 培玉·深色 Peiyu Dark

深松墨底，和浅色版的键完全相同，换一行 import 就能切换。适合代码讲解、长视频。logo 松绿在深底上对比度够，`C_A` 直接用原色。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/15241E/15241E.png) `#15241E` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/EEF0E6/EEF0E6.png) `#EEF0E6` |
| 对象 A（logo 松绿） | `C_A` | ![](https://placehold.co/14x14/90B898/90B898.png) `#90B898` |
| 对象 A 下一层 | `C_A_2` | ![](https://placehold.co/14x14/5E9C78/5E9C78.png) `#5E9C78` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/8DB2DC/8DB2DC.png) `#8DB2DC` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/E09A70/E09A70.png) `#E09A70` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/E2B866/E2B866.png) `#E2B866` |
| 强调小字 | `C_HL_INK` | ![](https://placehold.co/14x14/E2B866/E2B866.png) `#E2B866` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/F07E6C/F07E6C.png) `#F07E6C` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/6E7F76/6E7F76.png) `#6E7F76` |

### 专题

几何构造、集合交并等场景下，这两套的视觉手法本身就在帮着讲题，不改成品牌色。

#### 蓝图 Blueprint

深蓝图纸加细网格和虚线辅助线，适合几何与构造。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/0F2A4A/0F2A4A.png) `#0F2A4A` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/EAF2FF/EAF2FF.png) `#EAF2FF` |
| 对象 A | `C_A` | ![](https://placehold.co/14x14/9FD3FF/9FD3FF.png) `#9FD3FF` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/7FE0C2/7FE0C2.png) `#7FE0C2` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/FFB4A2/FFB4A2.png) `#FFB4A2` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/FFE066/FFE066.png) `#FFE066` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/FF6B6B/FF6B6B.png) `#FF6B6B` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/5B7BA3/5B7BA3.png) `#5B7BA3` |
| 背景网格 | `C_GRID` | ![](https://placehold.co/14x14/2B4C75/2B4C75.png) `#2B4C75` |

#### 孔版印刷 Riso

荧光粉和孔版蓝叠印出紫色，重叠处本身就是交集。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/F4F1EA/F4F1EA.png) `#F4F1EA` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/1B1B3A/1B1B3A.png) `#1B1B3A` |
| 对象 A | `C_A` | ![](https://placehold.co/14x14/FF48B0/FF48B0.png) `#FF48B0` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/0078BF/0078BF.png) `#0078BF` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/FFE800/FFE800.png) `#FFE800` |
| 对象 C 描边（浅底用） | `C_C_INK` | ![](https://placehold.co/14x14/B39A00/B39A00.png) `#B39A00` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/6C2E8F/6C2E8F.png) `#6C2E8F` |
| 荧光笔底色 | `C_HL_MARK` | ![](https://placehold.co/14x14/FFE800/FFE800.png) `#FFE800` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/E4572E/E4572E.png) `#E4572E` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/A7A3B5/A7A3B5.png) `#A7A3B5` |

### 备用

和培玉定位重合，保留但不再推荐给新视频。

![第 1–3 套](previews/set1.png)
![第 4–6 套](previews/set2.png)

#### 草稿纸 Paper

浅色，像彩色铅笔画在草稿纸上，适合题目讲解。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/F7F3EA/F7F3EA.png) `#F7F3EA` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/1E2430/1E2430.png) `#1E2430` |
| 对象 A | `C_A` | ![](https://placehold.co/14x14/2563A8/2563A8.png) `#2563A8` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/2F7D5B/2F7D5B.png) `#2F7D5B` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/C2561F/C2561F.png) `#C2561F` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/FFD84D/FFD84D.png) `#FFD84D` |
| 强调描边（浅底用） | `C_HL_INK` | ![](https://placehold.co/14x14/B7860B/B7860B.png) `#B7860B` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/C0392B/C0392B.png) `#C0392B` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/9AA0A8/9AA0A8.png) `#9AA0A8` |

#### 黑板 Chalkboard

深墨绿黑板配粉笔色，课堂感。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/1E2B27/1E2B27.png) `#1E2B27` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/F1EEE4/F1EEE4.png) `#F1EEE4` |
| 对象 A | `C_A` | ![](https://placehold.co/14x14/F4A6B7/F4A6B7.png) `#F4A6B7` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/9AD9C8/9AD9C8.png) `#9AD9C8` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/AFC3F2/AFC3F2.png) `#AFC3F2` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/FFE28A/FFE28A.png) `#FFE28A` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/FF8C7A/FF8C7A.png) `#FF8C7A` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/6F7F79/6F7F79.png) `#6F7F79` |

#### 玉夜 Jade Night

深青色底，适合代码和技术类内容。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/0E1A1C/0E1A1C.png) `#0E1A1C` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/E7F0EC/E7F0EC.png) `#E7F0EC` |
| 对象 A | `C_A` | ![](https://placehold.co/14x14/35C3AE/35C3AE.png) `#35C3AE` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/F2A35E/F2A35E.png) `#F2A35E` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/9C8CFF/9C8CFF.png) `#9C8CFF` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/F6C945/F6C945.png) `#F6C945` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/EF5B5B/EF5B5B.png) `#EF5B5B` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/5E6E6D/5E6E6D.png) `#5E6E6D` |

### 已弃用

#### 宣纸朱砂 Xuan

> 已弃用：和培玉同为暖纸加墨色，容易选混，新视频请用培玉。数据保留，旧脚本不受影响。

宣纸配墨线，结论用朱砂印章标出。

| 角色 | 变量 | 色值 |
|---|---|---|
| 背景 | `BG` | ![](https://placehold.co/14x14/F3ECDD/F3ECDD.png) `#F3ECDD` |
| 主文字 | `FG` | ![](https://placehold.co/14x14/22201C/22201C.png) `#22201C` |
| 对象 A | `C_A` | ![](https://placehold.co/14x14/2D4E87/2D4E87.png) `#2D4E87` |
| 对象 A 填充 | `C_A_FILL` | ![](https://placehold.co/14x14/3B74C4/3B74C4.png) `#3B74C4` |
| 对象 B | `C_B` | ![](https://placehold.co/14x14/4A7C59/4A7C59.png) `#4A7C59` |
| 对象 C | `C_C` | ![](https://placehold.co/14x14/B07A2A/B07A2A.png) `#B07A2A` |
| 结论 / 强调 | `C_HL` | ![](https://placehold.co/14x14/C8361F/C8361F.png) `#C8361F` |
| 错误 / 排除 | `C_NO` | ![](https://placehold.co/14x14/5A5550/5A5550.png) `#5A5550` |
| 次要 / 网格 | `C_DIM` | ![](https://placehold.co/14x14/A79F92/A79F92.png) `#A79F92` |

### 用法（Manim）

```python
from palettes import PEIYU as P   # 深色：PEIYU_DARK；也可以用 DEFAULT
config.background_color = P["BG"]
C_A, C_B, C_C = P["C_A"], P["C_B"], P["C_C"]
```

透明度和描边宽度等参数也在 `palettes.py` 里。其他工具可以读 `palette.json`。

### 作者与许可

作者：Boxi Yu（[@BoxiYu](https://github.com/BoxiYu)）

代码和配色数据以 [MIT 许可](LICENSE)发布。使用、修改、再分发时请保留 `LICENSE` 中的版权声明。用这些配色制作的视频不需要署名，欢迎注明出处。

如何引用见 [CITATION.cff](CITATION.cff)。


## English

Color palettes for math explainer videos, designed for Manim. Every palette uses the same color roles (background, text, objects A/B/C, conclusion, error, secondary), so they can be swapped directly.

Public videos default to Peiyu (light); use Peiyu Dark when a dark theme is needed. Blueprint and Riso are kept for specific topics; the rest are alternates.

![Peiyu / Peiyu Dark](previews/peiyu.png)

### Brand themes

These two are the themes Peiyu courses actually use, included as a real-world example.

> The colour values are covered by this repo's MIT license and are free to use; the name 「培玉」/ Peiyu and its logo are trademarks of 培玉智能 and are not licensed.

#### Peiyu (培玉, default)

Peiyu's brand colour card, light. Pine green and red-gold come from the logo, paired with azurite blue and ochre: a blue-green landscape (青绿山水) palette. The logo's original colours are too faint on the off-white background, so all text uses darker versions of the same hues.

`C_A` and `C_A_2` are two layers of the same hue, suited to relations derived layer by layer, such as a sequence and its first differences; for two parallel objects use `C_A` and `C_B`.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/F7F4EE/F7F4EE.png) `#F7F4EE` |
| Main text | `FG` | ![](https://placehold.co/14x14/1A2822/1A2822.png) `#1A2822` |
| Object A | `C_A` | ![](https://placehold.co/14x14/1E4A36/1E4A36.png) `#1E4A36` |
| Object A, next layer | `C_A_2` | ![](https://placehold.co/14x14/2F7A56/2F7A56.png) `#2F7A56` |
| Object B | `C_B` | ![](https://placehold.co/14x14/2F5D8A/2F5D8A.png) `#2F5D8A` |
| Object C | `C_C` | ![](https://placehold.co/14x14/A35A32/A35A32.png) `#A35A32` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/B5843A/B5843A.png) `#B5843A` |
| Emphasis small text (on light backgrounds) | `C_HL_INK` | ![](https://placehold.co/14x14/8A6230/8A6230.png) `#8A6230` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/B03A2E/B03A2E.png) `#B03A2E` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/8A8478/8A8478.png) `#8A8478` |
| Logo pine green (not for text) | `C_BRAND_GREEN` | ![](https://placehold.co/14x14/90B898/90B898.png) `#90B898` |
| Logo red-gold (not for text) | `C_BRAND_GOLD` | ![](https://placehold.co/14x14/B89058/B89058.png) `#B89058` |

#### Peiyu Dark (培玉·深色)

Dark pine-ink background with exactly the same keys as the light version, so switching is a one-line import change. Suited to code walkthroughs and long videos. The logo pine green has enough contrast on the dark background, so `C_A` uses it as is.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/15241E/15241E.png) `#15241E` |
| Main text | `FG` | ![](https://placehold.co/14x14/EEF0E6/EEF0E6.png) `#EEF0E6` |
| Object A (logo pine green) | `C_A` | ![](https://placehold.co/14x14/90B898/90B898.png) `#90B898` |
| Object A, next layer | `C_A_2` | ![](https://placehold.co/14x14/5E9C78/5E9C78.png) `#5E9C78` |
| Object B | `C_B` | ![](https://placehold.co/14x14/8DB2DC/8DB2DC.png) `#8DB2DC` |
| Object C | `C_C` | ![](https://placehold.co/14x14/E09A70/E09A70.png) `#E09A70` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/E2B866/E2B866.png) `#E2B866` |
| Emphasis small text | `C_HL_INK` | ![](https://placehold.co/14x14/E2B866/E2B866.png) `#E2B866` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/F07E6C/F07E6C.png) `#F07E6C` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/6E7F76/6E7F76.png) `#6E7F76` |

### Special-purpose

In scenes such as geometric constructions or set unions and intersections, the visual devices of these two palettes help explain the problem, so they are not switched to the brand colours.

#### Blueprint (蓝图)

Dark blueprint paper with a fine grid and dashed guide lines; suited to geometry and constructions.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/0F2A4A/0F2A4A.png) `#0F2A4A` |
| Main text | `FG` | ![](https://placehold.co/14x14/EAF2FF/EAF2FF.png) `#EAF2FF` |
| Object A | `C_A` | ![](https://placehold.co/14x14/9FD3FF/9FD3FF.png) `#9FD3FF` |
| Object B | `C_B` | ![](https://placehold.co/14x14/7FE0C2/7FE0C2.png) `#7FE0C2` |
| Object C | `C_C` | ![](https://placehold.co/14x14/FFB4A2/FFB4A2.png) `#FFB4A2` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/FFE066/FFE066.png) `#FFE066` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/FF6B6B/FF6B6B.png) `#FF6B6B` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/5B7BA3/5B7BA3.png) `#5B7BA3` |
| Background grid | `C_GRID` | ![](https://placehold.co/14x14/2B4C75/2B4C75.png) `#2B4C75` |

#### Riso (孔版印刷)

Fluorescent pink and riso blue overprint to purple, so the overlap is itself the intersection.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/F4F1EA/F4F1EA.png) `#F4F1EA` |
| Main text | `FG` | ![](https://placehold.co/14x14/1B1B3A/1B1B3A.png) `#1B1B3A` |
| Object A | `C_A` | ![](https://placehold.co/14x14/FF48B0/FF48B0.png) `#FF48B0` |
| Object B | `C_B` | ![](https://placehold.co/14x14/0078BF/0078BF.png) `#0078BF` |
| Object C | `C_C` | ![](https://placehold.co/14x14/FFE800/FFE800.png) `#FFE800` |
| Object C stroke (on light backgrounds) | `C_C_INK` | ![](https://placehold.co/14x14/B39A00/B39A00.png) `#B39A00` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/6C2E8F/6C2E8F.png) `#6C2E8F` |
| Highlighter background | `C_HL_MARK` | ![](https://placehold.co/14x14/FFE800/FFE800.png) `#FFE800` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/E4572E/E4572E.png) `#E4572E` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/A7A3B5/A7A3B5.png) `#A7A3B5` |

### Alternates

These overlap with Peiyu in purpose. They are kept but no longer recommended for new videos.

![Palettes 1–3](previews/set1.png)
![Palettes 4–6](previews/set2.png)

#### Paper (草稿纸)

Light, like colored pencil on scratch paper; suited to worked problems.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/F7F3EA/F7F3EA.png) `#F7F3EA` |
| Main text | `FG` | ![](https://placehold.co/14x14/1E2430/1E2430.png) `#1E2430` |
| Object A | `C_A` | ![](https://placehold.co/14x14/2563A8/2563A8.png) `#2563A8` |
| Object B | `C_B` | ![](https://placehold.co/14x14/2F7D5B/2F7D5B.png) `#2F7D5B` |
| Object C | `C_C` | ![](https://placehold.co/14x14/C2561F/C2561F.png) `#C2561F` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/FFD84D/FFD84D.png) `#FFD84D` |
| Emphasis stroke (on light backgrounds) | `C_HL_INK` | ![](https://placehold.co/14x14/B7860B/B7860B.png) `#B7860B` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/C0392B/C0392B.png) `#C0392B` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/9AA0A8/9AA0A8.png) `#9AA0A8` |

#### Chalkboard (黑板)

Chalk colors on a dark green-black board; a classroom feel.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/1E2B27/1E2B27.png) `#1E2B27` |
| Main text | `FG` | ![](https://placehold.co/14x14/F1EEE4/F1EEE4.png) `#F1EEE4` |
| Object A | `C_A` | ![](https://placehold.co/14x14/F4A6B7/F4A6B7.png) `#F4A6B7` |
| Object B | `C_B` | ![](https://placehold.co/14x14/9AD9C8/9AD9C8.png) `#9AD9C8` |
| Object C | `C_C` | ![](https://placehold.co/14x14/AFC3F2/AFC3F2.png) `#AFC3F2` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/FFE28A/FFE28A.png) `#FFE28A` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/FF8C7A/FF8C7A.png) `#FF8C7A` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/6F7F79/6F7F79.png) `#6F7F79` |

#### Jade Night (玉夜)

Dark teal background; suited to code and technical content.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/0E1A1C/0E1A1C.png) `#0E1A1C` |
| Main text | `FG` | ![](https://placehold.co/14x14/E7F0EC/E7F0EC.png) `#E7F0EC` |
| Object A | `C_A` | ![](https://placehold.co/14x14/35C3AE/35C3AE.png) `#35C3AE` |
| Object B | `C_B` | ![](https://placehold.co/14x14/F2A35E/F2A35E.png) `#F2A35E` |
| Object C | `C_C` | ![](https://placehold.co/14x14/9C8CFF/9C8CFF.png) `#9C8CFF` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/F6C945/F6C945.png) `#F6C945` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/EF5B5B/EF5B5B.png) `#EF5B5B` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/5E6E6D/5E6E6D.png) `#5E6E6D` |

### Deprecated

#### Xuan (宣纸朱砂)

> Deprecated: like Peiyu it is warm paper with ink colours, so the two are easy to confuse; use Peiyu for new videos. The data is kept, so existing scripts are unaffected.

Ink lines on xuan paper, with conclusions marked by a cinnabar seal.

| Role | Variable | Value |
|---|---|---|
| Background | `BG` | ![](https://placehold.co/14x14/F3ECDD/F3ECDD.png) `#F3ECDD` |
| Main text | `FG` | ![](https://placehold.co/14x14/22201C/22201C.png) `#22201C` |
| Object A | `C_A` | ![](https://placehold.co/14x14/2D4E87/2D4E87.png) `#2D4E87` |
| Object A fill | `C_A_FILL` | ![](https://placehold.co/14x14/3B74C4/3B74C4.png) `#3B74C4` |
| Object B | `C_B` | ![](https://placehold.co/14x14/4A7C59/4A7C59.png) `#4A7C59` |
| Object C | `C_C` | ![](https://placehold.co/14x14/B07A2A/B07A2A.png) `#B07A2A` |
| Conclusion / emphasis | `C_HL` | ![](https://placehold.co/14x14/C8361F/C8361F.png) `#C8361F` |
| Error / excluded | `C_NO` | ![](https://placehold.co/14x14/5A5550/5A5550.png) `#5A5550` |
| Secondary / grid | `C_DIM` | ![](https://placehold.co/14x14/A79F92/A79F92.png) `#A79F92` |

### Usage (Manim)

```python
from palettes import PEIYU as P   # dark: PEIYU_DARK; DEFAULT also works
config.background_color = P["BG"]
C_A, C_B, C_C = P["C_A"], P["C_B"], P["C_C"]
```

Opacity, stroke width and other parameters are also in `palettes.py`. Other tools can read `palette.json`.

### Author and license

Author: Boxi Yu ([@BoxiYu](https://github.com/BoxiYu))

The code and color data are released under the [MIT License](LICENSE). When using, modifying, or redistributing them, please keep the copyright notice in `LICENSE`. Videos made with these palettes do not require attribution, but crediting the source is welcome.

For how to cite, see [CITATION.cff](CITATION.cff).
