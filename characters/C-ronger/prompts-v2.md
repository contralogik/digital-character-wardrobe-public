# 蓉儿 v2 · 制作提示词（公开版）

2026-09-30。输出：[面部](face-views-v2.png)、[全身](full-body-views-v2.png)。生成方式为内置 imagegen，原生 PNG 直接保存，无图片后处理。

以下保留实际提交的提示词，原照文件标识已省略。原始输入照片和中间稿不公开，输入顺序及未公开输入由本机制作记录保存。`approved` 等词为当时提示词措辞，不代表用户已确认最终相似度。

## 提交 1

```text
Use case: photorealistic-natural. Create a NEW three-view facial identity sheet for the established adult digital character Ronger. Both input photographs depict the SAME woman. Image 1 ([私有参考照片]) is the close original and primary authority for facial identity, skin, eyes, nose, lips and jaw. Image 2 ([私有参考照片]) supplies her polished evening styling and lively large-wave hair, not a different face. Ignore source clothing, balcony, earrings and city background.

One horizontal three-panel photographic contact sheet, large head-and-shoulder portraits: exact frontal, 45-degree three-quarter, true side profile. Preserve the original woman's slightly elongated oval face, natural cheek volume and softly defined cheekbones and jaw, subtly hooded horizontally extended almond eyes, natural textured dark brows, fairly straight clear nasal bridge and rounded tip, fuller lips with a defined cupid bow. Same adult face and features across views. Never narrow the jaw, enlarge the eyes, erase skin detail or substitute a generic glamour model.

Refine styling beyond the old bare-faced sheet: controlled elegant city makeup with slim softly extended brown-black upper liner, subtle taupe eye definition, healthy warm cheek color and defined muted rose-brown lips. Deep brown near-black long hair with a clearer SIDE PART, lift at the roots and organized broad S-shaped waves; leave much of the forehead and one cheek visible instead of a curtain of hair. Sophisticated, lively and recognizable, not heavy glam, artificial contour or older-looking. Neutral gray studio, soft balanced light, plain opaque ivory crewneck, calm closed lips, realistic photographic skin with fine texture, no jewelry, text or watermark.
```

## 提交 2

```text
Edit the first image: this is the current THREE-PANEL facial reference sheet of the established adult digital character Ronger. Keep her exact facial identity, adult age, eye/nose/mouth proportions, face outline, all three poses, ivory top, gray background and skin texture. Image 2 is her original polished evening look, image 3 her original close portrait. The first image is too bare-faced and its flyaway hair too untidy for the requested refined city styling.

Apply clearly visible, tasteful polished makeup CONSISTENTLY to all three views: softly defined warm taupe-brown eyeshadow around the upper eyelid and outer corner, a clean slender brown-black upper eyeliner with a small extended wing, defined separated upper lashes, groomed natural dark brows, subtle warm peach-rose cheek color, and an evenly applied muted rosewood lipstick with a gently defined cupid bow and soft satin finish. Makeup must be visible at the frontal portrait scale. Preserve the original lips' outline and volume and the real eyelid shape. No heavy smoky eye, no exaggerated lashes, no nose contour tricks and no porcelain beauty filter.

Refine the existing deep brown long hair into a deliberate side part with lifted roots, smooth orderly top, polished broad S waves from the upper-mid lengths downward, and one cheek/ear more exposed. Reduce the chaotic wispy strands crossing the face without removing all natural flyaways. This hair is voluminous and distinctly curly, unlike Mimi's mostly smooth upper-length black long hair. Keep a calm confident closed-mouth expression, real pores and fine texture, all three faces the SAME woman. Deliver the complete edited three-panel sheet, no labels, text, jewelry or watermark.
```

## 提交 3

```text
Use case: photorealistic-natural. Create a NEW four-view full-body reference sheet for the established ADULT digital character Ronger. Input 1 is her APPROVED UPDATED facial three-view sheet, the primary authority for head, face, skin, visibly polished city makeup and side-part long broad S waves. Input 2 is her older full-body sheet and is an authority ONLY BELOW THE NECK: preserve her designated natural shoulder width, rib cage, bust volume, torso length, waist/hip relationship, leg length and limb volume. Do not reuse the outdated bare face or untidy hair from input 2. Input 3 original portrait corroborates facial identity; input 4 original evening full-body photograph supports adult presence and curly hair but does not change the body baseline.

One horizontal photographic contact sheet of the SAME WOMAN in four equally sized panels: FRONT, 45-DEGREE THREE-QUARTER, TRUE SIDE, BACK. Head and all hair to soles fully visible in every panel; even scale and same camera height. User-set height 168 cm, naturally proportioned adult build, C-cup only as background info, no exaggerated reshaping. Body matches input 2; retain real leg volume. Neutral relaxed upright stance, arms slightly away at sides, no pose tricks.

Transfer the new exact identity from input 1: slightly elongated oval, natural cheek volume, softly defined cheekbone and jaw, subtly hooded horizontally extended almond eyes, textured brows, natural straight bridge and rounded tip, fuller rosewood lips. Transfer the clearly defined warm taupe eyeshadow, slim brown-black eyeliner and tasteful city polish without enlarging eyes or smoothing skin. Deep brown near-black long hair, clear SIDE PART, lifted roots and orderly broad S waves through upper-mid lengths to lower ends, much of forehead and one cheek visible. Same hair on all angles, clear long curled silhouette from the back.

Plain opaque ivory crewneck fitted everyday top, charcoal straight trousers and simple ivory low-heel flats, same garments all panels. Soft even neutral studio light, gray seamless background, natural photographic skin and fabric. No text, labels, jewelry, phone or watermark. No change in facial identity across the panels, no old face, no generic beauty face, no unnaturally tiny waist, no exaggerated legs or porcelain skin.
```

## 使用

当前面部与发型按本人物最新参考，颈部以下比例按人物卡指定身体基准。旧换装没有逐张同步；视图含生成补全，视觉相似度可继续审核。
