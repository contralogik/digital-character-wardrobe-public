# 鹿儿 v2 · 制作提示词（公开版）

2026-09-30。输出：[面部](face-views-v2.png)、[全身](full-body-views-v2.png)。生成方式为内置 imagegen，原生 PNG 直接保存，无图片后处理。

以下保留实际提交的提示词，原照文件标识已省略。原始输入照片和中间稿不公开，输入顺序及未公开输入由本机制作记录保存。`approved` 等词为当时提示词措辞，不代表用户已确认最终相似度。

## 提交 1

```text
Use case: photorealistic-natural. Create a NEW three-view facial identity sheet for the established adult digital character Luer. The three input photographs ([私有参考照片], [私有参考照片], [私有参考照片]) show the SAME woman's original face at different scales. Image 1 is the primary close facial authority. Preserve her own facial proportions instead of blending with any other character. The source photos are likeness references only; ignore their phone, clothing, room, jewelry and poses.

One horizontal three-panel photographic contact sheet, large head-and-shoulders views: exact frontal, 45-degree three-quarter, true profile. Make the same recognizable adult face in every panel. Maintain her compact soft oval outline, naturally fuller upper cheeks, slightly rounder yet almond-shaped eyes with real lids, soft medium-fine brows, proportionate straight nose with a softly rounded tip, naturally shaped rosy lips and a small but rounded chin. Keep original eye spacing and nose-lip-chin relations. A gentle approachable closed-mouth expression is fine; do not make her childlike, increase iris size, or shrink her chin into a sharp point.

Distinct fixed styling: user-specified natural WARM CHESTNUT brown hair with slightly darker roots, light airy wisps across the forehead, a low loose SIDE BRAID visible over one shoulder, soft face-framing pieces. NO high bun, no near-black straight center-parted hair. Natural warm blush, restrained rose lip and soft eye makeup while keeping realistic skin texture. The hair and softer eye-cheek geometry must clearly separate her from Xinran when both wear the same plain opaque ivory crewneck against the same gray studio and soft even light. No jewelry, labels, watermark, source outfit or background.
```

## 提交 2

```text
Use case: photorealistic-natural. Generate a NEW v2 four-view full-body photographic reference sheet of adult character Luer. Input 1 is her approved NEW v2 facial three-view MASTER; it has absolute priority for the same face, smile, forehead wisps, chestnut color and side braid. Input 2 is her existing full-body sheet for NECK-DOWN BODY PROPORTIONS and four-column framing only. Ignore all its older heads, facial details and high bun. Input 3 is the original close facial photograph; corroborate her individual eyes, cheeks, mouth and adult age, not the outfit or room.
Four equal columns: front, 45-degree three-quarter, true profile, back, same scale and camera height, complete head-to-shoes. Neutral gray studio and soft balanced light. Opaque ivory crewneck shirt, charcoal straight trousers and light low sneakers, as original body reference. Preserve input 2's fixed 172cm body impression, natural shoulders/chest/waist/hip shape, torso/leg lengths, thigh/calf volume, arms and relaxed stance. No larger bust, narrower waist, wider hips, longer legs or new body.
All heads must be the exact same Luer identity from input 1: compact soft oval outline with naturally rounded cheeks and small rounded chin, rounder adult almond eyes with natural iris size, delicate calm brows, proportionate rounded nasal tip and original nose-lip spacing, gentle relaxed closed-mouth smile. Warm chestnut long hair with slightly darker roots, light AIRY FOREHEAD FRINGE, one LOW LOOSE SIDE BRAID over a shoulder. Every angle, including back, must show the same side-braid construction rather than an old top bun. NO high bun, black center-parted straight hair or childish doll face. Real skin/fabric texture and subtle warm makeup, no jewelry, text, watermarks or malformed anatomy. Keep heads and footwear fully visible.
```

## 使用

当前面部与发型按本人物最新参考，颈部以下比例按人物卡指定身体基准。旧换装没有逐张同步；视图含生成补全，视觉相似度可继续审核。
