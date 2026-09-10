# Momo — Character Sheet Specification

Reference-sheet package for MOMO, the three-year-old of *Kasa Keeps the Night*.

Companion documents: `book/kasa-keeps-the-night.md`, `book/kasa-character-sheet.md`

**The key difference from Kasa's package:** Momo is lying down on all fourteen pages, so
the standing turnaround (Sheet D) is an identity reference for humans only. The
**sleeping-pose sheet (Sheet E) is the one attached to page generations.** Feeding the
standing sheet to a page prompt makes the model stand the child up.

---

## 1. Spec card (canon)

| Item | Locked spec | Failure mode if unspecified |
|---|---|---|
| Height | **95 cm** — nearly eye to eye with Kasa at 92 cm | the Momo/Kasa height relation is the per-page sanity check |
| Proportions | **three heads tall**, soft rounded chibi | a drifting ratio makes the age swing between 2 and 6 |
| Hair | soft charcoal `#2E2A33`, **never pure black**. Bob cut level just below the ears, straight blunt bangs above the eyebrows | pure black plus long hair reads as a horror child |
| Hair on the pillow | **bangs part slightly, the ends of the bob fan out across the pillow** | without this the hair stays in its standing shape while the child sleeps |
| Eyes | large and round, iris `#4A4152`, short soft upper lashes, no lower lashes | |
| Gender | **neutral. No gender markers at all** (no ribbons, no emphasized lashes, no pink) | the text is written with zero pronouns; art that fixes a gender breaks the design |
| Pajama | pale lavender-grey `#C7C3D2` yukata-style, **small sparse white crescent moons** 1.5 cm across | changing print density reads as a different garment — always write "sparse" |
| Feet | **bare**, no socks | |
| Quilt | indigo `#4A5273`, lining smoke pink `#D9B6BB` | the indigo matches Kasa's trim and ties the world together |
| Emotional range | sleepy, calm, gently curious. **No crying and no anger exist in this book** | |

### Color chips

| Part | HEX |
|---|---|
| Hair | `#2E2A33` |
| Skin | `#F0DCCB` |
| Blush | `#E8B4AE` |
| Iris | `#4A4152` |
| Pajama base | `#C7C3D2` |
| Crescent print | `#F5EFE6` |
| Quilt face | `#4A5273` |
| Quilt lining | `#D9B6BB` |
| Washi ground | `#EFE7DA` |

---

## 2. Reusable CHARACTER block

Paste verbatim into all three sheet prompts.

```
CHARACTER - MOMO: a small three-year-old child, total height 95 cm, soft rounded
three-heads-tall chibi proportions, round full cheeks, a small round nose, big round
gentle dark eyes with iris #4A4152 and short soft upper lashes, warm pale skin #F0DCCB
with two soft blush patches #E8B4AE. Hair is a neat bob in soft charcoal #2E2A33 (never
pure black), cut level just below the ears, with straight blunt bangs sitting just above
the eyebrows. Wearing a loose yukata-style pajama in pale lavender-grey #C7C3D2, printed
with SMALL, SPARSE white crescent moons #F5EFE6 about 1.5 cm across, wide sleeves, a soft
sash tied loosely at the waist, ankle length. Bare feet, no socks. The expression is
always calm, sleepy or gently curious - never crying, never angry, never frightened.
GENDER-NEUTRAL by design: no hair ribbons, no bows, no jewelry, no long lashes, no pink
clothing, no gendered styling of any kind. The child must read equally as a boy or a girl.
```

---

## 3. Sheet D - Standing turnaround (identity reference)

```
Character turnaround model sheet for a children's picture book, five views of the SAME
character in one image, evenly lit, flat neutral studio lighting, no dramatic shadows,
warm off-white washi paper background #EFE7DA, thin pale grid lines and a height
reference line marked 95 cm, clean reference-sheet layout.

[CHARACTER BLOCK - MOMO]

THE FIVE VIEWS, left to right, all at the same scale on the same ground line:
1. FRONT view, standing straight, arms relaxed at the sides, calm sleepy face.
2. THREE-QUARTER view, standing, slight natural lean.
3. SIDE profile view, standing, showing the bob silhouette and the pajama drape clearly.
4. BACK view, standing, showing the back of the bob and the loosely tied sash.
5. SCALE COMPARISON: the child standing beside KASA, the one-eyed paper-umbrella yokai
   from the attached reference sheet, both on the same ground line. The child is 95 cm,
   Kasa is 92 cm - they are almost exactly eye to eye. Do not change Kasa's design.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, gentle line work, picture-book illustration for ages 3+, child-safe.
Label each view with small handwritten text underneath: "front", "3/4", "side", "back",
"with Kasa".

NEGATIVE: gendered styling, hair ribbon, bow, jewelry, long eyelashes, pink dress, older
child, teenager, realistic adult proportions, big dense floral pattern, socks, shoes,
crying, angry, scared, scary, creepy, pure black hair, dark background, night scene,
moonlight, high contrast, neon, 3D render, photorealistic, watermark, extra fingers.
```

Attach Kasa's Sheet A when generating view 5. The height relation established here is the
sanity check for every page.

---

## 4. Sheet E - Sleeping-pose turnaround (the working sheet)

```
Sleeping-pose reference sheet for a children's picture book, FIVE views of the SAME
child lying down, arranged clearly in one image, evenly lit, flat neutral lighting, warm
off-white washi paper background #EFE7DA, clean reference-sheet layout. The child is
lying on a low Japanese futon in every view.

[CHARACTER BLOCK - MOMO]

FUTON: a low Japanese futon, off-white sheet, with a quilt in deep indigo #4A5273 whose
folded-back lining shows smoke pink #D9B6BB, and a small flat pillow.

THE FIVE VIEWS, each labeled underneath in small handwritten text:
1. "flat, awake"  - seen from directly above, lying on the back, quilt up to the chest,
                    eyes wide open, ten bare toes poking out at the bottom of the quilt
                    and wiggling.
2. "flat, side"   - seen from the side at floor level, lying on the back, only the head,
                    the quilt mound and the toes visible, low horizon.
3. "curled"       - lying on one side, knees drawn up slightly, one hand near the cheek,
                    quilt up to the shoulder.
4. "pillow face"  - close-up of the head on the pillow seen from pillow height, cheek
                    pressed softly, the bangs slightly parted and the ends of the bob
                    fanned out across the pillow.
5. "asleep"       - seen from above, lying on the back, eyes closed as soft downward
                    crescents, mouth just barely open, completely still, quilt up to the
                    chin.

IMPORTANT: the child is lying down in all five views. Do NOT draw the child sitting up,
kneeling or standing. Whenever the child is lying down, the bangs part a little and the
ends of the bob fan out onto the pillow - the hair must never look like the standing
hairstyle.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, picture-book illustration for ages 3+, child-safe, calm and cozy.

NEGATIVE: sitting up, kneeling, standing, western bed, mattress with legs, headboard,
gendered styling, hair ribbon, bow, crying, angry, scared, scary, creepy, pure black
hair, dark background, night scene, high contrast, 3D render, photorealistic, watermark,
extra fingers, extra toes.
```

---

## 5. Sheet F - Expressions

```
Expression sheet for a children's picture book character, EIGHT head close-ups of the
SAME child arranged in a 4x2 grid, evenly lit, flat neutral lighting, warm off-white
washi paper background #EFE7DA, clean reference-sheet layout. In every panel the head is
resting on a pillow, seen from pillow height, with the bangs slightly parted and the
ends of the bob fanned out.

[CHARACTER BLOCK - MOMO]

THE EIGHT EXPRESSIONS, each labeled underneath in small handwritten text:
1. "wide awake"  - eyes fully open and round, alert, not sleepy at all.
2. "curious"     - eyes open, eyebrows raised slightly, mouth a small soft circle.
3. "tiny laugh"  - eyes squeezed into happy arcs, mouth open in a small silent laugh,
                   one hand over the mouth.
4. "wonder"      - eyes very wide and shining softly, completely still, amazed.
5. "whisper"     - lips pursed small, eyes half open, quiet and secretive.
6. "big yawn"    - mouth wide open in a slow yawn, eyes squeezed shut, one small fist
                   near the cheek.
7. "heavy lids"  - eyes almost closed, lids drooping, on the very edge of sleep.
8. "asleep"      - eyes closed as soft downward crescents, mouth barely open, perfectly
                   peaceful.

The face stays calm and warm throughout. No crying, no anger, no fear in any panel.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
picture-book illustration for ages 3+, child-safe, gentle.

NEGATIVE: gendered styling, hair ribbon, bow, long eyelashes, crying, tears, angry,
scared, screaming, scary, creepy, pure black hair, dark background, night scene, high
contrast, 3D render, photorealistic, watermark.
```

Page mapping: p1 "wide awake", p2 "curious", p3 "tiny laugh", p4 "wonder", p6 "whisper",
p10 "big yawn", p11 "heavy lids", p12-14 "asleep".

---

## 6. How to use the sheets

Attach **Kasa Sheet A and Momo Sheet E together** to every page generation, with this
line at the top of the page prompt:

```
Use the two attached sheets as exact references: sheet 1 for KASA, sheet 2 for MOMO.
Keep both designs identical to the sheets. MOMO is lying down on the futon in this
scene, exactly as in the sleeping-pose sheet - never sitting up or standing. Only
re-light both characters for this night scene; the flat daylight lighting of the sheets
must NOT be copied.
```

Do **not** pass Sheet D to page generations — it makes the model stand the child up.
Sheet D exists so a human can verify the face and the height relation.

Attach Sheet F only on pages whose expression is doing real work (p3, p10, p11).

---

## 7. Per-page QA checklist

- [ ] Lying down — no sitting or standing has crept in
- [ ] Three heads tall
- [ ] Bangs parted on the pillow
- [ ] Crescent print small and sparse
- [ ] No gender markers (ribbons, bows, pink)
- [ ] Hair is charcoal, not pure black
- [ ] Eye level matches Kasa
