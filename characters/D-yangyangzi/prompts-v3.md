# 羊羊子 v3 · 制作提示词（公开版）

2026-09-30。输出：[面部](face-views-v3.png)、[全身](full-body-views-v3.png)。生成方式为内置 imagegen，原生 PNG 直接保存，无图片后处理。

以下保留实际提交的提示词，原照文件标识已省略。原始输入照片和中间稿不公开，输入顺序及未公开输入由本机制作记录保存。`approved` 等词为当时提示词措辞，不代表用户已确认最终相似度。

## 提交 1

```text
Use case: photorealistic-natural. Create a NEW three-view short-hair facial identity sheet for the established adult digital character Yangyangzi. Images 1 and 2 ([私有参考照片] and [私有参考照片]) are the closest original facial authority for the SAME woman, despite different hair lengths and light; images 3 and 4 ([私有参考照片] and [私有参考照片]) support the short-hair silhouette and adult presence. Do not copy source outfits, locations, flowers, jewelry, text or watermarks.

One horizontal three-panel photographic contact sheet, large head-and-shoulder portraits: exact frontal, 45-degree three-quarter, true side profile. Maintain her already accepted v2 short-hair identity with only measured polishing. Preserve the compact tapered oval face with softly rounded chin, large but adult elongated almond eyes and slight outer lift, relatively low calm brow arch, clearly shaped natural nose, naturally full lower lip and restrained confident gaze. Match the original eye-nose-mouth spacing and slightly asymmetric real face. Do not produce a different generic model, widen the eyes, sharpen the jaw, or change age.

Default hair remains a near-black SHOULDER-LENGTH BOB with a clear side part, subtle internal layers, natural root lift, one side lightly tucked behind the ear and ends close to the shoulders. Keep a fine controlled upper liner and soft coral-rose lip, realistic skin detail and restrained polish. No long hair in these three panels. Neutral gray studio, soft even light, plain opaque ivory crewneck, no jewelry, labels or watermark. The same face must remain recognizable in later full-body and wardrobe images.
```

## 提交 2

```text
Use case: photorealistic-natural. Create a NEW four-view full-body reference sheet for the established ADULT digital character Yangyangzi. Input 1 is the APPROVED UPDATED short-hair facial reference, the primary authority for exact face, adult age, skin, restrained makeup and bob. Input 2 is her designated v2 full-body reference and an authority ONLY BELOW THE NECK: preserve natural shoulder width, rib cage, full natural bust, torso length, waist/hip relationship, leg length and limb volume. Do not substitute the old face. Inputs 3 and 4 are original close and full-body short-hair photos of the SAME woman for identity and hairstyle corroboration.

One horizontal photographic contact sheet showing the SAME WOMAN in four equal panels: FRONT, 45-DEGREE THREE-QUARTER, TRUE SIDE and BACK, full head and all hair through soles completely visible. Consistent scale/camera height/light. User-set height 165 cm; naturally balanced adult proportions; F-cup only as background info, body volume from input 2. Do not enlarge bust, pinch waist or overextend legs. Neutral relaxed upright stance, arms a little away at sides. Normal human anatomy.

Transfer input 1's compact tapered oval face, softly rounded chin, adult elongated almond eyes with subtle outer lift, low calm brow arch, natural shaped nose, naturally full lower lip, restrained confident gaze, controlled fine upper liner and coral-rose lips. Face and age consistent between panels. Near-black SHOULDER-LENGTH BOB, clear side part, subtle internal layers and natural root lift, one side lightly tucked behind the ear, ends reaching near shoulders. The bob must be visible and coherent front/side/back, with no long hair extensions and no identity change.

Same plain opaque ivory crewneck everyday top, charcoal straight trousers and ivory low flats in all four panels. Neutral gray studio background, soft balanced light, realistic fine skin texture and fabric drape. No jewelry, text, labels, logos, watermark or source scenery. No porcelain skin, generic model face or exaggerated hourglass shaping.
```

## 使用

当前面部与发型按本人物最新参考，颈部以下比例按人物卡指定身体基准。旧换装没有逐张同步；视图含生成补全，视觉相似度可继续审核。
