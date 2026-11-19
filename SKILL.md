---
name: 科研设备极简矢量插画
description: 将用户提供的科研实验装置、显微镜、流式仪、高速相机、医疗器械、工业设备照片或既有插图，按原始视角与布局转换为论文级极简 2D 扁平矢量风格插画；适合在 PowerPoint 中用基础形状复刻，或经 Adobe Illustrator 图像描摹转成低节点 SVG。仅在用户明确要求创作、编辑、转换这类设备示意图或相应生成提示词时使用；普通科研图表、数据可视化、无参考的设备结构设计不适用。
---

# 科研设备极简矢量插画

## 核心目标

将复杂的科研实验装置、医疗器械或工业设备转化为**大轮廓准确、无微细结构、无光影渐变、线条呈标准几何与贝塞尔曲线特征**的极简 2D 扁平矢量风格插画，使其便于学术论文排版、Adobe Illustrator 图像描摹和 PPT 基础形状复刻。

优先级：**原参考图的视角和拓扑准确性 > 标志性大轮廓可辨认 > 几何线条与纯色块干净 > 极简程度**。删除细节时，不能破坏设备的识别性或关键连接关系。

## 何时使用

- 用户提供实物照片或现有插图，要求生成可在 PPT 中临摹、复刻的极简 2D 设备示意图。
- 用户要求把科研实验系统、显微镜、流式仪、相机、传感器、医疗器械或工业设备改为纯色块、无阴影、无渐变的论文插图。
- 用户希望后续用 Illustrator 图像描摹导出干净的 SVG，尽量减少碎块路径和锚点。
- 用户希望对复杂设备进行“抓大放小”：保留标志性结构并删除细碎机械特征。

不适用：需要复现细微零件、电子元件引脚、内部光路或精密装配细节的工程图；要求实物照片写实处理；只需绘制常规统计图表或流程图的任务。

## 执行流程

### 1. 锁定参考图视角与确定性结构

1. **严格遵守原图视角**：透视、朝向、俯仰、构图、设备之间的空间关系、关键部件的相对位置必须与原参考图一致。不得擅自改成 45° 轴测图、正视图，不得镜像翻转。
2. 识别画面中清晰可见的主要组件及连接关系，如倒置显微镜的机身和双目镜、高速相机、显示器、支架、微流控芯片等。根据具体参考图确定清单，不要固定添加某种设备。
3. **禁止凭空补全**：被遮挡、模糊、不确定的结构直接省略；不得臆造内部光路、管路走向、接口、支架或机械零件。
4. 保留标志性外轮廓与整体拓扑。例如相机—镜头—显微镜间可见、明确的连接应保留；无证据的隐藏连接不应绘制。

### 2. 一刀切删除微小结构与冗余细节

- **旋钮与表面纹理**：调焦旋钮、调节轮等只保留光滑圆形或圆柱几何轮廓。删除防滑条纹、刻度、箭头和标记。
- **接口、接缝与紧固件**：删除螺丝、卡扣、紧固环、联轴套、细密拼缝；用连续的几何圆柱、块面或曲线概括光路管道和镜头接口。
- **面板细节**：删除按钮、开关、指示灯、散热孔、接口孔位等不影响识别的微小元素。
- **线缆**：删除杂乱线束和插头；至多保留 1–2 根体现确定核心连接关系的平滑单线。若连线不清楚，宁可不画。
- **小型核心部件**：微流控芯片等可在**原位**适当放大并简化，保持实际所在位置及上下游关系；不使用局部放大框、气泡框或引线。
- **屏幕**：所有屏幕均为无内容的单一纯色区域，不出现图像、网格、光斑、文字或 UI。

### 3. 论文级几何线条与纯平涂

- 路径以笔直线段、规则圆/椭圆弧、平滑二次或三次贝塞尔曲线构成；节点尽量少，曲率连续。
- 使用清晰、**均匀粗细**、闭合的黑色外轮廓；避免锯齿、重描、抖动、手绘笔触。
- **彻底禁止**高光、反射、投射阴影、环境光阴影、体积阴影、折角暗部、渐变、透明纹理、噪点、金属质感和摄影景深。
- 每一独立结构面只用一种均匀纯色填充。可用少量不同纯色区分真正不同的组件或可见的独立结构面，但不能借色块模拟明暗。
- 背景必须为**绝对纯白色（#FFFFFF）**；不得有地面投影、台面质感或装饰背景。
- 整图不得包含任何文字、标识、品牌 Logo、型号、字母、数字、箭头、图例或额外注释。

### 4. 根据用户要求交付

- 若用户要求**生成或修改图片**且已经提供明确的参考图，调用可用的图像生成/编辑工具，并使用下述英文主提示词结合参考图。不要只给提示词代替图片。
- 若用户明确只要**提示词**，交付填好设备描述和核心组件的英文提示词，不额外生成图片。
- 若用户明确要求可编辑的 **SVG/PPT 文件**，使用能够实际创建矢量路径或 PPT 基础形状的文件工具。不要把图片生成模型输出的位图称为“原生 SVG 矢量”。位图仅是便于随后描摹的图像来源。
- 未提供参考图而又要求严格复制原图时，不应编造视角或设备布局；向用户索取参考图。若用户只是让自由设计，则不声称“忠实于原图”。

## 英文图像生成提示词模板

将 `[设备系统描述]` 和 `[核心部件列表]` 替换为参考图中可以确认的内容；始终把参考图作为视角、布局和结构的唯一依据。

```text
A clean, publication-grade 2D flat vector illustration of [设备系统描述], strictly matching the exact camera angle, perspective, orientation, and layout of the reference image on a pure white background.

Vector & Line Art Quality (SVG & PPT Ready):
- Precision geometric vector paths constructed from clean straight lines, circular arcs, elliptical arcs, and smooth quadratic/cubic Bezier curves, with as few control points as possible.
- Strictly NO wobbly, shaky, or hand-drawn sketch lines. Uniform, crisp, closed bold black outlines.
- NO highlights, NO shadows, NO gradients, NO 3D shading, NO reflections, and NO surface textures. Pure solid flat color fills only, optimized for clean SVG vectorization and PowerPoint shape reproduction.
- Absolute pure white (#FFFFFF) background with no floor shadows or environmental effects.

Structural Fidelity & Detail Skipping:
- Keep the exact viewing angle, orientation, and positions of components in the original reference (do NOT force a 45-degree isometric view unless present in the original, and do NOT mirror the image).
- Keep only the recognizable main outer silhouettes of [核心部件列表] and their clearly visible, certain connections.
- Do NOT hallucinate or invent unclear, hidden, or occluded structures; if a detail is uncertain, omit it completely.
- Drop all microscopic details: smooth out all focus knobs (no ridges or markings), remove all screws, couplers, seams, buttons, lights, vents, ports, and unnecessary cables.
- Retain no more than 1–2 clean curved cable lines only if they are essential and clearly supported by the reference.
- Any small core component may be modestly enlarged in its original location, without changing its connections or adding an inset.
- All screens must be completely blank solid color rectangles.
- No zoom-in inset boxes, no text, no logos, no labels, no numbers, no symbols, and no arrows.
```

## 生成前与交付前检查

逐项检查；如有不符，优先修正，而不是通过增加细节弥补。

1. 参考图与生成图的视角、左右方向、部件相对位置是否相同？
2. 标志性大轮廓和可以确定的拓扑连接是否保留？
3. 模糊、被遮挡、不确定的结构是否完全省略？
4. 是否彻底删除按钮、刻度、纹理、紧固件、细密拼缝和多余线缆？
5. 线条是否是规则的几何线条/平滑贝塞尔曲线，而非手绘抖动线？
6. 是否只有纯色块，没有任何渐变、光影、高光、表面纹理和地面投影？
7. 背景是否为纯白，屏幕是否完全空白？
8. 是否没有文字、Logo、型号、箭头、放大框或注释？
9. 是否适合 PPT 基础形状重建和 Illustrator 低节点描摹？

## 易错点

- 不能为了图面“更立体”而改变原图视角、添加 45° 轴测透视或自行绘制背面结构。
- 避免在生成提示词中使用 `cartoon sketch`、`hand-drawn`、`pencil` 等词；应采用 `precision 2D flat vector illustration`、`smooth Bezier curves`、`clean geometric paths`。
- **宁缺毋滥**：遇到模糊的底座、光路连接、线缆或零件，优先简化/省略，不能虚构。
- 只输出必要的产物或简洁说明；规则与提示词均采用纯文本，不使用装饰性表情符号。
