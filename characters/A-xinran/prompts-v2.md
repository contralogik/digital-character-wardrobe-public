# 欣然 v2 · 制作提示词（公开版）

2026-09-30。输出：[面部](face-views-v2.png)、[全身](full-body-views-v2.png)。生成方式为内置 imagegen，原生 PNG 直接保存，无图片后处理。

以下保留实际提交的提示词，原照文件标识已省略。原始输入照片和中间稿不公开，输入顺序及未公开输入由本机制作记录保存。`approved` 等词为当时提示词措辞，不代表用户已确认最终相似度。

## 提交 1

```text
Use case: photorealistic-natural. Create a NEW three-view facial identity sheet for the established adult digital character Xinran. All four input photos show the same woman's original appearance: image 1 ([私有参考照片]) is the main close facial authority; images 2 and 3 ([私有参考照片], [私有参考照片]) check her face in another light and at more angles; image 4 ([私有参考照片]) supplements angle and hair structure. These photos are likeness references only. Do not copy their outfits, phone, room, accessories or poses.

One horizontal three-panel photographic contact sheet, large head-and-shoulders views: exact frontal, 45-degree three-quarter, true profile, with identical facial anatomy in all panels. Reconstruct her own naturally elongated soft oval face and upper-face fullness, delicately tapered but not pinched lower jaw, gently rounded small chin, narrower horizontally extended almond eyes with a subtle lifted outer corner, relatively calm mid-density eyebrows, straight refined nose with natural nostril width, soft defined lips and natural mouth width. Preserve the original spacing among eyes, nose, lips and chin. Keep the adult face and subtle asymmetry; do not enlarge eyes, slim the face into a V shape, or replace her with a generic doll-like model.

Give her near-black deep brown long hair in a LOW back half-up arrangement, remaining hair smooth and straight, almost center parted, forehead more open with only a few long face-framing strands. NO high bun, no dense wispy forehead bangs. Understated natural makeup, restrained soft rose lip, calm poised expression; her distinction is clean elongated eye and face shapes, not exaggerated cosmetics. Neutral gray studio, soft even light, plain opaque ivory crewneck, real photographic skin texture, no jewelry, labels or watermarks. Her identity must remain recognizable even when compared with another woman in identical clothing.
```

## 提交 2

```text
Use case: photorealistic-natural. Generate a NEW v2 four-view full-body photographic sheet of adult character Xinran. Input 1 is the approved NEW Xinran facial three-view MASTER and has absolute priority for her face, calm expression and hair. Input 2 is her existing full-body sheet as NECK-DOWN BODY PROPORTIONS and four-column camera/layout reference only. Ignore its old high bun and every old face; do not carry the old head into this new sheet. Input 3 is her original close face, for individualized eyes, nose, lips and adult age.
Four equal columns: front, 45-degree three-quarter, true side, back, matching figure scale, full head-to-flat-shoe view, gray studio and even light. Opaque ivory crewneck tee, charcoal straight trousers and pale ballet flats. Maintain input 2's fixed tall 178cm body impression, same shoulders/chest/waist/hips, torso and leg lengths, natural thigh/calf thickness, arms and natural standing positions. No enlarged bust, pinched waist, reshaped hips or stretched limbs.
Use the SAME Xinran v2 face from input 1 in every visible head: soft elongated oval outline, narrower extended almond eyes, natural calm brows, refined straight nose with rounded tip, original nose/lip/chin spacing, gentle jaw taper with a rounded small chin. No generic rounded doll face. Calm closed lips. Hair near-black deep brown in a low back HALF-UP arrangement with almost center part, a few long cheek-side strands, smooth long loose hair falling straight down the back. NO high bun, braid, dense forehead bangs or full loose waves. Back view accurately shows low half-up gathering and straight hair. Natural skin/fabric texture, no jewelry, labels, watermark, deformed hands or feet. Keep all heads and shoes inside the frame.
```

## 使用

当前面部与发型按本人物最新参考，颈部以下比例按人物卡指定身体基准。旧换装没有逐张同步；视图含生成补全，视觉相似度可继续审核。
