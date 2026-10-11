---
name: giant-calligraphy-print-poster
description: 巨型书法解构·东方套色实验字体海报：以两个巨型书法汉字为骨架，融合书法解构、复古三色套印、传统白描线描与现代编辑排版，生成一张 9:16 浓烈而有文化密度的实验字体海报。当用户提到"巨型汉字海报 / 书法解构海报 / 套色印刷海报 / 东方实验字体"或给出岭南醒狮、昆曲游园等主题时使用。Use when the user asks for a giant Chinese calligraphy poster, deconstructed calligraphy, multi-color registration print poster, or Eastern experimental typography — produces one bold poster with two giant brush characters, vermilion/cyan-blue/ink-black blocks and embedded baimiao line drawings.
license: MIT
---

# 巨型书法解构 · 东方套色实验字体海报 · Giant Calligraphy Print Poster

两个巨字撑满画面，三色套印穿插笔画，白描故事藏在字里，微型题跋散在边缘。
Two giant brush characters, three-color registration blocks, baimiao scenes embedded inside the strokes, micro inscriptions at the edges.

## 输入 · Inputs

```
【主题】：如 岭南醒狮、昆曲游园、武侠江湖、山海异兽
【核心汉字】：两个大字
【书法题名】：四字文化题名
【英文副标题】：
【文化线描元素】：3–5 个相关人物 / 建筑 / 器物 / 山水
【辅助题跋】：3–5 句中文短句（可自动创作）
【配色】：朱红、青蓝、墨黑、暖米白、少量古金（默认）
【比例】：9:16（默认）
```

## 使用规则 · Agent rules
- **不要追问，不输出分析**。缺失字段根据【主题】协调补全：
  - 核心汉字：两个真实、规范、与主题紧密相关且有意义的汉字（如 醒狮 →"醒""狮"）。
  - 书法题名：四字、文化上成立。
  - 辅助题跋：有真实文化含义；可原创短句，引用古文时必须准确并标对出处，**不张冠李戴、不编造名句**；无乱码、无错字。
  - 英文副标题：自然地道，不逐字直译。
  - 配色、比例用默认值。
- 只输出一张海报；环境不能生图时，输出已填好的 [prompt.md](prompt.md) 提示词。

示例见 [examples/themes.md](examples/themes.md)。

## 核心规则 · Core rules

### 目标 · Goal
高完成度东方实验字体艺术海报：巨型书法汉字解构 + 复古多色套印 + 传统白描线描 + 现代编辑排版；大胆、浓烈、文化丰富。

### 一 巨型汉字解构 · Giant character deconstruction
- 两个核心汉字放大至画面高度约 **80%**，笔画粗重、有表现力。
- 夸张拉伸、交错叠压、局部出画裁切，形成强烈抽象几何构成，同时保持基本可读。
- 笔势随主题变化，保有自然的书写节奏与气势。

### 二 三色套色穿插 · Three-color registration
- 朱红、青蓝、墨黑三色大块有机色块，在笔画内部相互穿插、切割、遮挡、嵌套；米白留白构成丰富的图底关系。
- 色彩鲜明饱和，边缘利落，丝网印刷 + 书法笔触质感。
- 不要简单的彩色文字叠加，不要 3D 阴影。

### 三 东方文字排版 · Eastern editorial layout
- 左上角古金色竖排书法题名，旁配精细英文副标题。
- 顶部、两侧与留白处：多组微型竖排中文题跋（宋体/明朝体，少量书法），2–4 枚朱红印章，精细分隔线，少量竖排英文。
- 强调巨型书法与微型文字的尺度反差；文字有真实文化含义；错落丰富、成熟的东方编辑排版。

### 四 精密文化白描 · Fine baimiao
- 画面下方约 **1/3**：与主题相关的传统人物、建筑、动物、植物、器物，**嵌入巨字内部**。
- 精细白色传统线描：丰富的服饰纹样、建筑结构、自然细节，呈现叙事性古典木刻版画效果。
- 少量白色几何细线框连接各场景。
- 插画与红/蓝/黑色块交织，而非分开排列；复杂而统一。

### 五 整体 · Overall
- 不对称、高张力的自由构图：巨字主导，微型题跋在边缘，白描嵌于下方，层级清晰。
- 干净暖米白背景；平面、哑光、高对比的套色印刷美学。
- 远看图形冲击强烈，近看文化细节丰富。
- 每张海报主题完整、文案真实、艺术表达独立，系列风格统一。

### 避免 · Avoid
简单彩色文字叠加、3D 阴影与立体效果、乱码/错字/伪汉字、张冠李戴或编造的引文、插画与文字分离排列、巨字失去可读性、色块边缘浑浊、渐变或光泽塑料感、背景杂乱、水印与 logo。
