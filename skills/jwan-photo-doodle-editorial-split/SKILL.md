---
name: jwan-photo-doodle-editorial-split
metadata:
  version: 1.0.0
  author: Jwan
  license: MIT
description: Transform each uploaded photo into its own premium 3:4 editorial poster with an authentic photo upper half and a sparse, imaginative naïve hand-drawn lower half; default subtle Jwan signature.
---

# Jwan Photo Doodle Editorial Split

## Purpose
将每张用户照片单独制作成一张「原片摄影 × 稚拙涂鸦编辑插画」高级海报。保留照片的真实瞬间，用极简、富有作者性的手绘语言重新讲述这一瞬间。作品应像高品质独立生活杂志，不像儿童手账或模板拼贴。

## Fixed defaults / 不可随意更改
1. **每张照片独立输出**。收到多张照片则生成等量独立海报，不把不同照片拼在同一张画布。
2. **画布为3:4竖版，水平精确中线分割**。上半与下半均占整体画布高度的**50%**；两半同宽，无边框、无错位。若实际像素高度是奇数，最多容许1 px舍入差。只有用户明确提出新画幅/布局才更改。
3. **上半使用原图像素，而不是让模型重新生成相似照片**。主体身份、脸、五官、表情、姿势、手指/肢体、服装、真实肌理、构图逻辑、光线及原色氛围保真。只许可轻微裁切或克制的编辑调色；不拉伸人物、不改年龄、不换脸、不新增物品。为适配上半3:2区域，优先调整无关背景的画幅、自然延展环境，而非缩放变形主体。
4. **下半不是原图描摹或写实滤镜**。提炼最独特的主体动作、姿态方向、人物关系、表情/事件情绪，经过删除、取舍、重组、错位与比例再设计，变为少量有力量的插画形象。
5. **默认署名 `Jwan`**。位于整张海报右下角安全边距内（建议距边2%–4%），尺寸极小、清晰、笔触自然、颜色克制；不能抢主视觉，不用投影、粗描边或图章。此署名为固定规则，用户明确要求去除或改动时例外。

## Visual language / 手绘语言
- Hand-drawn Doodle Lifestyle Illustration / Naïve Illustration / Marker Drawing，搭配少量粗蜡笔、油画棒和纸面粉彩痕迹。
- 单色偏细黑色或深褐色不完整轮廓；微颤、断续、局部交错、线宽有轻微差异；形态简单、幼态但不廉价，允许不对称和克制的手作误差。
- 以低细节和抓形为先，不追求完整透视、解剖精准或逐个还原环境道具；仍需保留主体最有识别度的表情、配色和关系。
- 颜色从该张原图提取再轻柔重组：奶油黄、桃粉、珊瑚红、天空蓝、湖青、浅绿、薰衣草紫等作为可选色，而非每图全用。建议每图仅2–4个点睛颜色 + 深色线稿 + 暖白底。
- 下半默认用暖白/浅奶油低对比纸纹，不画复杂背景。装饰性笔触必须基于该图的动作或叙事，不随机堆砌星星、爱心、云彩、箭头。

## Whitespace and layout / 留白与编辑排版
- **主动留白优先**：下半大部分面积保持空白；实色画面和短文字应小而有凝聚力。可偏置到左/右、贴近某个边、悬置或局部裁出画框；不强制居中。
- 先确认视觉重心、隐形网格和阅读动线，再布置小画和少量文字；让文字与人物的肩线、头部方向、动作线、物件位置或留白区发生视觉呼应。
- 文案默认**一条简短、真正相关的词组**（中文或英文，由画面决定），搭配至多一行极小辅助文字；不固定 `SLOW AFTERNOON`，除非用户明确指定。
- 文字仿自然手写，轻盈、略不均匀，但行距字距和落点按成熟编辑设计控制。禁止大段说明、居中套模板、菜单式信息罗列。
- 场景每张重判；家庭、旅行、食物、宠物、建筑用各自独有的视觉线索，而不是复制上一个案例的插画元素。

## Execution workflow / 工作流程
1. **逐图理解**：识别不可改变的主体特征、最突出的互动、空间关系、情绪瞬间；选出1–3个足够讲述故事的视觉标记。
2. **锁定上半**：计算上半真实像素区（3:4成品中的上部50%，形状为3:2横向区域）；保留原图像素。必要时裁剪无关环境或只延展背景；不得重生成人脸/主体。
3. **重构下半**：先画小比例粗略布局，规划大量暖白负空间；确定简笔形体、节奏线、2–4色、自然手写短语的位置。只用与原图有关的图形。
4. **精准合成**：优先以生成的下半**独立插画**与原照片像素级拼合，以最大程度确保上半严格保真；不可靠的“参考图重绘上半”不能声称完全保留原图。
5. **署名收尾**：右下安全边距加入小 `Jwan`；检查文字准确性与人物手脚数量。
6. **逐图交付**：每图独立文件；不要将多张拼成展示板，也不要把案例图作为用户新照片的替代。

## Image generation instruction / 可直接执行的创作指令
For each input photo, independently create a premium 3:4 vertical editorial split poster. Top 50% must be the authentic supplied photo, not a redrawn imitation: preserve faces, expressions, poses, clothing, hands, color/light, and environmental realism. Adapt only by restrained cropping/background extension, without distorting people. Bottom 50% is warm-ivory editorial paper with a small, highly selective naïve hand-drawn illustration of the photo's unique emotional/narrative core. Simplify through deletion and rearrangement, rather than tracing the whole scene. Use imperfect fine black ink outlines, marker/crayon/oil-pastel fills, and only a few soft vivid colors borrowed from that particular photo. Make negative space a primary element; use asymmetric, intentional magazine-like placement. Add one meaningful short handwritten phrase integrated with the illustration; no long text, repetitive generic icons, or fixed templates. Add discreet handwritten `Jwan` at the outer bottom-right safe margin. Preserve human anatomy and number of people and limbs; do not invent extra people or hands. Every photo yields one independent poster.

## Conflict handling / 优先级
用户本轮明确要求 > 固定人物/原片保真 > 3:4 / 上下各50% / 独立输出 > 绘画语言与留白 > 文案建议。用户明确指定 `16:9左右各50%` 等变体时，按其要求只改对应项目，其余保真、极简、手绘、署名规则继续有效。**不要把某次案例的具体人物、车、衣裙、标题或画幅意外固化成所有后续作品的默认。**

## Fail conditions / 不合格项
- 上半重绘、改变脸/动作、出现变形人物；上下不等高；多张照片拼贴。
- 下半完整复制原背景、信息过密、满版装饰；只在人物上套卡通滤镜。
- 人物/手/脚数量无故增加，主体性别、服装或互动被篡改。
- 与图片无关的随机自行车、花朵、星星等，或所有图都用同一个短语。
- 文案拼写错误，署名缺失/过大，或排版看起来像机械居中的固定模板。