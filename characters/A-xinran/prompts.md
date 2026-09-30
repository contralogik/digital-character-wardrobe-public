> 历史制作记录。当前版本见[欣然 v2 提示词](prompts-v2.md)与[人物卡](profile.md)。

# 欣然人物参考图提示词

生成方式：内置 imagegen，非 CLI。

## 1. 全身四视图

```text
Use case: photorealistic-natural.
Asset type: photorealistic full-body character turnaround reference sheet for future clothing try-on.
Primary request: Create one high resolution wide reference sheet with four equally sized vertical panels showing the SAME adult woman from the supplied reference photographs: straight front view, three-quarter view, true 90-degree side profile, and straight back view. These are four views of one person, not four different women.
Input images: Images 1, 2, 3 and 4 are appearance reference photographs of the same person. Image 1 is a useful face and casual-clothing reference. Images 2 and 3 show natural full-body proportions; use their body proportions, not their clothing or posing. Image 4 contains additional face and side/back appearance references. Faithfully preserve this particular person's face and natural body proportions without beautification or exaggeration.
Subject: adult woman, character A / Xinran. User-supplied character height 178 cm and E-cup wardrobe sizing. Express a tall stature and preserve the reference's naturally full bust, defined waist, softly curved hips, long limbs, and relatively slim arms; do not exaggerate or reduce any body feature. Soft oval face, tapering rounded lower jaw and small softly pointed chin, dark almond-shaped eyes, medium natural gently arching dark brows, straight delicate nose with small rounded tip, natural rose-pink lips with slightly fuller lower lip. Light skin with a neutral-warm undertone, interpreted in neutral studio light. Very dark brown nearly black long hair, in the same simple half-up hairstyle in every panel, slight near-center part and wispy face-framing strands. For the back view let the long hair rest naturally down her back. Her individual facial likeness must closely match the references rather than becoming a generic fashion model.
Wardrobe: identical fully opaque plain cream fitted short-sleeve crew-neck knit top and matte charcoal-gray fitted full-length trousers in every panel, simple flat shoes. Clothes fit naturally, suitable for a neutral fashion-fitting reference. No accessories, phone, handbag, bikini, lingerie, or props.
Composition: full body including head and feet in each panel, same scale, same floor baseline and comfortable even margins. Stand straight with level shoulders, head aligned with the torso, neutral calm expression and arms relaxed slightly apart from torso. No hip cocking, no crossed legs, no fashion posing. In the front view look directly forward; in the true side view torso, feet and head all face exactly the same side, no glance back. Front-facing camera with long portrait lens and minimal perspective distortion.
Backdrop and lighting: seamless very light warm-gray studio background, soft diffuse balanced studio light, subtle natural floor shadows. Real photographic skin texture, fine fabric texture and believable anatomy, no illustration, no 3D rendering, no heavy retouching.
Text: small clean labels underneath panels, in this exact order: "正面", "45°", "侧面", "背面". No other text or measurements.
Constraints: same identity, same body proportions, same hairstyle, same clothing, same lighting in all four panels. Use the supplied reference person as the strongest visual anchor. These are generated reference views, not an anatomical measurement chart. No logos, watermark, extra people, cropped feet, extra fingers or limbs, exaggerated hourglass figure, unnaturally long legs, widened eyes or sharpened chin.
```

## 2. 面部三视图

```text
Use case: photorealistic-natural.
Asset type: photorealistic face identity reference sheet for future fashion try-on, character A / Xinran.
Primary request: One wide high resolution triptych showing the same adult woman in three head-and-shoulders photographic views: true straight front view, three-quarter 45-degree view, and true 90-degree side profile. Prioritize her particular facial likeness from the original photographs, with accurately preserved facial feature spacing, jaw outline, nose and mouth. The images must look like real neutral studio portraits of one individual, not generic fashion model faces.
Input images: Images 1 through 4 are the original appearance references for this same woman. Use the face details visible in all of them as the primary identity reference. Image 1 shows a close facial angle; images 2 and 3 show additional facial proportions; image 4 includes several additional facial angles. Image 5 is the previously generated full-body reference sheet; use it only for continuity of cream clothing, half-up hairstyle, background and lighting. The original photographs should remain the strongest authority for facial likeness.
Subject details: soft oval face with gently tapering lower jaw, small subtly pointed but rounded chin, gentle cheek contour, dark elongated almond-shaped eyes with restrained fine eyeliner, medium natural dark eyebrows with a low soft arch and tapering tails, relatively straight narrow nose with small rounded tip, soft natural rose-pink lips and slightly fuller lower lip. Light skin in neutral-warm studio lighting with real pores and fine natural texture. Nearly black dark-brown long hair, same simple half-up hairstyle and wispy face-framing strands in all panels, as the previous sheet. Hair should not obscure the eyes, nasal profile, lips or jaw silhouette.
Wardrobe and pose: the same opaque plain cream crew-neck knit top, no jewelry. Relaxed neutral expression with closed lips, level head and shoulders. Front portrait head and shoulders directly facing camera, eyes toward camera. 45-degree portrait head and shoulders rotate together. True side portrait shows an exact 90-degree profile, head and shoulders rotated together and gaze straight ahead in that direction, not looking back at the camera.
Composition: equal-sized panels, same scale, matched head height and eye-line, show full top of head and upper shoulders without cropping hair. Crisp face detail, consistent low-distortion portrait camera perspective. Soft diffuse balanced lighting and seamless very light warm-gray background. Understated natural makeup.
Text: one small clean label below each portrait, in exact order: "正面", "45°", "侧面". No other text.
Constraints: preserve individual appearance; no wider eyes, sharpened chin, heavily smoothed skin, altered lip shape, artificial symmetry, smile variation, new haircuts, glasses, phones, jewelry, or props. Identical person, age appearance, facial proportions, hairstyle and lighting in every panel. This is a clothed, neutral character reference. No cartoon, 3D render, watermark, logos, extra faces or panel overlays.
```
