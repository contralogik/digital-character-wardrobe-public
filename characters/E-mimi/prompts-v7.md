# 蜜蜜 v7 · 制作提示词（公开版）

2026-09-30。输出：[面部](face-views-v7.png)、[全身](full-body-views-v7.png)。生成方式为内置 imagegen，原生 PNG 直接保存，无图片后处理。

以下保留实际提交的提示词，原照文件标识已省略。原始输入照片和中间稿不公开，输入顺序及未公开输入由本机制作记录保存。`approved` 等词为当时提示词措辞，不代表用户已确认最终相似度。

## 提交 1

```text
Use case: photorealistic-natural.
Asset type: NEW Mimi v7 six-panel facial likeness reference, 3 columns x 2 rows.
Reconstruct the SAME adult woman's recognizable face DIRECTLY FROM ORIGINAL PHOTOGRAPHS. No previous generated face is an input. This is a likeness calibration, not a generic beautiful-model design.

Input roles:
1. [私有参考照片], the large near-frontal original CLOSE FACE, primary identity authority for full eye shape and opening, brows, tip/alar/nostril geometry, mouth shape and cheek-jaw-chin outline. Correct its slight upward/angled viewing perspective into a level front pose, but preserve the actual facial proportions.
2. [私有参考照片], relatively level three-quarter face, corroborates forehead, eye spacing, cheeks, bridge-tip-lips/chin relation and calm closed lips. Its tied hairstyle and flowers are NOT requested.
3. [私有参考照片], opposite-side turned head, corroborates the other three-quarter side and specific eye-nose-mouth and crisp lower-face outline. Do not use its bun or dress.
4. [私有参考照片], clear horizontal near-profile, main authority for nose projection and bridge/tip/nostril/columella and lips/chin silhouette. Do not copy microphone, jewelry or source outfit.
5. [私有参考照片], USER-SELECTED CURRENT LONG HAIRSTYLE ONLY: near-black natural side part, flowing smooth crown, face-framing broad outward bend, one side lightly tucked behind the ear, longer fuller loose S-curve cascade over the other shoulder. Warm source light must not become brown hair dye. Keep this style in ALL six panels.
The same original appearance is represented at different angles and makeup styles. Use identity from images 1–4, hair from image 5. Ignore all screenshot UI, text, source scenes, ornaments and props.

Panel layout, row-major: TOP LEFT level frontal neutral closed lips; TOP CENTER 45-degree facing left; TOP RIGHT 45-degree facing right; BOTTOM LEFT true 90-degree left profile; BOTTOM CENTER true 90-degree right profile; BOTTOM RIGHT level frontal with a very slight closed-mouth smile. All six are LARGE head-and-shoulder photographic portraits with equal scale, entire crown and chin in view, consistent light and same hairstyle. Each view contains the SAME recognizable face; do not create six different women or mirror-copy a profile mechanically.

Critical likeness details from the originals:
- Eyes are naturally LARGE expressive ALMOND eyes, with a clear curved upper lid, relatively open rounded inner/middle aperture and horizontally extending outer corners. Recover the actual eye opening and lid structure of image 1; do not reduce them into generic narrow sleepy model eyes. Preserve normal dark-brown irises and adult eyelid/lower-lid tissue, subtle individual asymmetry, clear understated eyeliner and separated lashes, not cartoon eye enlargement.
- Dark natural brows have a relatively calm inner body, a mild outer angle and tapering tail. Keep original brow-to-eye distance rather than lifting all eyebrows into a generic arch.
- Nose is PARTICULAR and dimensional, with natural root-to-dorsum transition, real length, smooth slightly descending bridge profile, distinct forward projection, softly rounded oval tip and real alar/nostril width. Match FRONT tip and nasal base directly to image 1, SIDE outline to image 4, and cross-check 2/3. Do not overinflate the bulb, narrow the alar base, erase nose wings, artificially lift the tip, make a ski-slope/button nose or replace it with a standard straight high narrow nose. Nose base, upper lip and chin must relate like the originals.
- Preserve upper-face/forehead width, smooth but real cheekbone and cheek volume, the naturally defined tapering jaw with a subtle real jaw turn, and a rounded chin of actual width and forward projection. The lower face is not an elongated thin generic oval or extreme V; preserve original vertical eye-nose-mouth-chin spacing without stretching the mid/lower face.
- Lips have a defined cupid bow and central upper-lip form, tapering outer upper lip and fuller lower lip, specific original mouth width and natural lip-to-chin distance; do not flatten/compress lips or impose a permanent sweet smile.

Neutral gray photographic background, soft balanced neutral studio light, plain opaque ivory crewneck, refined warm rose lip and understated reference-like eye makeup, real subtle pores/skin tonal variation. Identity priority is higher than standardized beauty. No porcelain filter, excessive smoothing, CG skin, extra aging, different facial anatomy by angle, jewelry, labels, text, logos or watermarks. Detailed likeness of originals, consistent six views, selected hair preserved.
```

## 提交 2

```text
Use case: identity-preserve.
Asset type: Mimi v7 four-view full-body reference synchronized to her NEW six-panel facial identity.
Image 1 is the NEW v7 six-panel facial MASTER reconstructed from originals. It has highest priority for every visible FACE: copy this exact individualized adult woman's eye shape/opening, eyebrow relationship, nasal bridge, tip/alar/nostril, mouth and jaw/chin. Do not substitute the older generated face.
Image 2 is the existing v6 full-body sheet, EDIT TARGET FOR NECK-DOWN, garments, stance and four-column composition ONLY. Keep its shoulders, chest/waist/hips, torso length, arm/leg volumes, natural slim straight legs, hands, ivory crewneck, charcoal straight trousers, ivory flats, gray studio and light. Its old face is not an invariant; replace visible facial anatomy using image 1.
Image 3 ([私有参考照片]) is the primary original close facial corroboration; match that recognizable adult appearance through image 1, avoiding generic beautification.
Image 4 ([私有参考照片]) is the USER-SELECTED CURRENT HAIRSTYLE reference only.
Image 5 is the original designated v2 body proportions reference below the neck only, for checking body structure; ignore its head and old hair.

Four equal panels left to right FRONT, 45-DEGREE THREE-QUARTER, TRUE SIDE and BACK. All four heads, hair and flat shoes inside the frame, equal figure scale/camera height and natural relaxed upright standing positions.
Every visible head must be the SAME v7 woman: naturally large expressive almond eyes with clearly curved upper lids and actual original eye opening, normal iris size, calm inner brows with mild outer turn, dimensional individual nose with real bridge length and forward softly rounded tip, natural alar width without swelling/pinching, specific nose-base-to-lip distance, shaped cupid bow and fuller lower lip, natural cheek volume and defined tapering jaw with rounded projecting chin of actual width. Preserve adult skin tone and subtle real skin detail. Face consistency across the three visible angles matters more than copying image 2's old head.

Hairstyle matches the user's image 4 selection: very long near-black hair with natural SIDE PART, tidy softly lifted crown and smooth flowing upper lengths, broad swept face-framing bend near cheek/jaw; one side lightly tucked behind an ear and falling back, opposite fuller loose elongated S-curve cascade over one shoulder, softly curled ends below chest. Match the same physical part/tuck side and length across views. Use organized flowing hair, reduce random root frizz; do not make uniformly fluffy dense waves from the scalp, a ponytail, bun or blunt fringe. Warm light in image 4 is not brown dye.

Neck-down preservation is strict; no enlarged bust, narrowed waist, wider hips, longer legs, changed clothes or pose tricks. Same realistic fine fabric and photographic skin. No text, jewelry, logo, watermark, malformed anatomy or cropped head/feet.
```

## 使用

当前面部与发型按本人物最新参考，颈部以下比例按人物卡指定身体基准。旧换装没有逐张同步；视图含生成补全，视觉相似度可继续审核。
