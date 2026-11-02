# 画面清洁度与细节控制

根据用户提供的提示词截图整理。默认在生图构思和成图复查时使用；具体程度由文字、参考图与用户明确要求决定。

## 默认原则

- **分配细节**：大面积背景、远景、暗部和留白保持平整、安静、连续；优先在视觉焦点及必要的主体关系处安排细节。避免在无关区域自动铺满裂纹、污点、颗粒、砂砾、浮雕纹或重复纹理。
- **明暗与边缘**：优先宽而自然的明暗层次、低至中等的局部对比度和适度锐度；边缘根据形态需要在清晰、柔化与消隐之间变化，避免每一处都加重局部对比或锐化。
- **材质尺度**：纹理与主体尺度、观察距离和所选媒介相符；保留真实需要或表达意义的笔迹、纤维、擦痕及材质差异，去掉与主体无关的随机微纹理和虚假细节。
- **检查缺陷**：关注数字和彩色噪点、无目的的颗粒覆盖、过锐化、边缘光晕、过强局部对比、HDR 式刺眼效果、油腻高光、蜡质表面、无意的脏灰色调、重复纹样、压缩伪影与过度做旧。只在实际出现或确有生成风险时指定相应避免项，不必机械堆叠长串否定词。
- **提示词选择**：不要把 `film grain`、`texture overlay`、`grunge`、`weathered`、`ultra-detailed surface`、`intricate texture`、`razor sharp` 或 `HDR` 当作默认装饰性质量词；确实适合原句、参考或用户明确要求时仍可使用，并说明其视觉作用。

## 与意象画的兼容

素材中的线条既可能构成主体，也可能延伸成力场；这些线条是画面的意义，不因“保持干净”而被抹掉。可让主体及其受力区域保留有方向、有节奏的线迹，同时让远离焦点的背景保持安静。密集线场如果本身是表达需要，也可以有意铺满画面；判断标准是细节是否有功能，而非是否绝对稀疏。

截图提出的“干净的摄影机原始画质”适用于确实要求摄影或摄影感的任务。对绘画、线描、混合媒介或其他非摄影作品，转译为干净、克制、媒介一致的画质，不额外强制摄影写实、真实光学或真实世界材质尺度。

## 可选提示词片段

```text
Keep the large background areas calm and continuous. Place purposeful detail where it supports the subject and the visual relationship. Use natural tonal transitions and controlled sharpness; avoid arbitrary microtexture, repeated patterns, digital noise, oversharpening and artificial HDR. Preserve the expressive marks and material characteristics essential to the chosen medium.
```

按具体画面删改：高对比、尖锐边缘、颗粒或粗粝表面若本来就是创作目标或参考的关键部分，应保留，不套用相反的默认设置。
