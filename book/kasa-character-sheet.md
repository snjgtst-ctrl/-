# Kasa — Character Sheet Specification

Reference-sheet package for KASA, the one-eyed paper-umbrella yokai (karakasa) of
*Kasa Keeps the Night*. Sheet A is the canon; every page illustration is generated with
Sheet A attached as a reference image.

Companion document: `book/kasa-keeps-the-night.md`

---

## 1. Spec card (these numbers are canon)

| Item | Locked spec | Failure mode if unspecified |
|---|---|---|
| Eye | **exactly ONE**, on the front of the canopy, slightly below the crown | models default to two eyes; every prompt must say "ONE single eye" |
| Iris | soft charcoal-violet `#3E3A4A` — **never pure black** | pure black reads as frightening |
| Lashes | five long soft upper lashes | without them the face goes inorganic |
| Mouth | below the eye, lower third of the canopy. **A single closed crescent line. No teeth, no tongue** | traditional karakasa has a long protruding tongue — it will appear unless suppressed. Highest-priority negative |
| Ribs | **exactly 8** visible | a shifting rib count reads as a different character |
| Arms | **none** — the canopy rim acts as hands | arms turn a yokai into a mascot costume |
| Leg | **one**, pale wooden shaft, one geta sandal | models default to two legs |
| Height | **92 cm** open — eye level with a three-year-old | taller is intimidating, shorter cannot protect |
| Canopy diameter | approx. 55 cm | |
| Surface | worn oiled paper: fine fold creases, frayed rim, 2-3 small age stains | a pristine surface kills the Japanese texture |

### Color chips

| Part | HEX |
|---|---|
| Canopy dusty rose | `#C99AA6` |
| Canopy pale lilac | `#B9AECB` |
| Ribs, faded bamboo | `#C8B79A` |
| Indigo trim | `#4A5273` |
| Wooden shaft | `#D8C9B4` |
| Geta sandal | `#8C7A66` |
| Eye white | `#F5EFE6` |
| Iris | `#3E3A4A` |
| Blush | `#E0AFAF` |
| Washi ground | `#EFE7DA` |

### Lighting rule for the sheets

The book is dark and low-contrast; the sheets are **not**. Reference sheets use flat,
even lighting on a light washi ground. A dark reference image bakes moonlight into every
downstream page.

---

## 2. Reusable CHARACTER block

Paste this verbatim into all three sheet prompts.

```
CHARACTER - KASA: a friendly one-eyed Japanese paper-umbrella yokai (karakasa).
Open canopy of aged oiled washi paper in dusty rose #C99AA6 and pale lilac #B9AECB,
EXACTLY EIGHT visible bamboo ribs in faded bamboo #C8B79A, a worn indigo #4A5273 trim
along the canopy edge, soft fold creases, frayed rim, two or three tiny age stains.
ONE single large round gentle eye on the FRONT of the canopy, slightly below the crown,
off-white #F5EFE6 with a soft charcoal-violet iris #3E3A4A (never pure black) and five
long soft upper lashes. Below the eye, on the lower third of the canopy, a small CLOSED
crescent smile drawn as a single soft line - NO teeth, NO tongue, NO open mouth. Two tiny
soft blush patches #E0AFAF. NO arms and NO hands. ONE slender pale wooden shaft #D8C9B4
as its single leg, ending in ONE small wooden geta sandal #8C7A66. Total height 92 cm,
canopy diameter 55 cm, the height of a three-year-old child. Gentle, grandfatherly, warm,
absolutely not frightening.
```

---

## 3. Sheet A - Turnaround (generate this one first)

```
Character turnaround model sheet for a children's picture book, five views of the SAME
character in one image, evenly lit, flat neutral studio lighting, no dramatic shadows,
warm off-white washi paper background #EFE7DA, thin pale grid lines and a height
reference line, clean reference-sheet layout.

[CHARACTER BLOCK]

THE FIVE VIEWS, left to right, all at the same scale on the same ground line:
1. FRONT view, canopy fully open, eye facing the viewer, smiling.
2. THREE-QUARTER view, canopy open, slight lean forward.
3. SIDE profile view, canopy open, showing the single leg and geta clearly.
4. BACK view, canopy open, no eye and no face visible from behind, only paper and ribs.
5. FOLDED / SLEEPING form, canopy closed thin and narrow, leaning at a slight angle,
   the eye closed as a soft downward crescent, peaceful.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, gentle line work, picture-book illustration for ages 3+, child-safe.
Label each view with small handwritten text underneath: "front", "3/4", "side", "back",
"folded (asleep)".

NEGATIVE: two eyes, multiple eyes, sharp teeth, visible teeth, open mouth, long tongue,
arms, hands, two legs, scary, creepy, horror, glowing red eye, pure black, harsh shadows,
dark background, night scene, moonlight, high contrast, neon, 3D render, photorealistic,
extra ribs, watermark.
```

---

## 4. Sheet B - Expressions (the eight states used in the book)

```
Expression sheet for a children's picture book character, EIGHT head-and-canopy close-ups
of the SAME character arranged in a 4x2 grid, evenly lit, flat neutral lighting, warm
off-white washi paper background #EFE7DA, clean reference-sheet layout.

[CHARACTER BLOCK]

THE EIGHT EXPRESSIONS, each labeled underneath in small handwritten text:
1. "awake"       - eye fully open, round and calm, small closed crescent smile.
2. "blinking"    - eye half closed, lashes lowered, very sleepy.
3. "shhh"        - the paper brim tipped low over the eye, only the lower half of the eye
                   showing, hushing gesture, no hands used.
4. "kind"        - eye softened into a warm arc, blush a little stronger, grandfatherly.
5. "listening"   - eye wide and still, brim tilted slightly to one side, attentive.
6. "watching"    - eye open and steady with a faint soft glow, alert but calm, night-guard
                   expression.
7. "half asleep" - eye almost closed, canopy drooping slightly, very soft.
8. "asleep"      - eye fully closed as a soft downward crescent, canopy folded thin,
                   completely at rest.

In every single expression the mouth stays a CLOSED soft crescent line - never open,
never showing teeth, never showing a tongue. The eye is always ONE eye.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
picture-book illustration for ages 3+, child-safe, gentle.

NEGATIVE: two eyes, sharp teeth, visible teeth, open mouth, long tongue, angry, sad,
crying, scary, creepy, glowing red eye, dark background, night scene, high contrast,
3D render, photorealistic, watermark.
```

Page mapping: p2 "opening/blinking", p3 "shhh", p5-9 "awake"/"listening",
p11 "kind", p12 "watching", p13 "half asleep", p14 "asleep".

---

## 5. Sheet C - Action poses

```
Action pose sheet for a children's picture book character, SIX full-body poses of the
SAME character in one image, evenly lit, flat neutral lighting, warm off-white washi
paper background #EFE7DA, all figures on the same ground line at the same scale.

[CHARACTER BLOCK]

THE SIX POSES, each labeled underneath in small handwritten text:
1. "closed"        - standing folded and closed, leaning against nothing, before waking.
2. "opening"       - canopy half open, unfolding slowly like a flower blooming.
3. "tap"           - standing open, the single geta foot just tapping the floor, small
                     soft ripple lines around the foot.
4. "spin"          - canopy spinning slowly like a pinwheel, faint soft spiral motion
                     lines, tiny drifting sparks.
5. "hop"           - mid-hop on the single leg, canopy tilted forward, light and
                     weightless.
6. "keeping watch" - canopy half folded, standing straight and still beside an implied
                     pillow, eye open with a faint soft glow, protective night-guard
                     posture.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
picture-book illustration for ages 3+, child-safe, gentle motion, soft rounded shapes.

NEGATIVE: two eyes, sharp teeth, open mouth, long tongue, arms, hands, two legs, violent
motion, scary, creepy, dark background, night scene, high contrast, 3D render,
photorealistic, watermark.
```

Page mapping: p1 "closed", p2 "opening"+"tap", p4 "spin", p5 "hop", p12 "keeping watch".

---

## 6. How to use the sheets

1. **Lock Sheet A first.** Accept only a generation where all five views hold the four
   invariants: one eye, eight ribs, one leg, closed mouth. A single broken view will
   propagate to all fourteen pages.
2. **Attach the approved Sheet A to every page generation**, with this line at the top of
   the page prompt:

   ```
   Use the attached character sheet as the exact reference for KASA. Keep the canopy
   colors, the eight ribs, the single eye, the closed crescent mouth, the single leg and
   geta identical to the sheet. Only re-light the character for this night scene - the
   sheet's flat daylight lighting must NOT be copied.
   ```

3. **Attach Sheets B and C only on pages that use those states.** Passing all three every
   time averages out the art direction.
4. **Momo needs the same treatment.** Once Kasa is locked, build a Momo turnaround from
   the same template — that is the next shortest path to a consistent book.

---

## 7. Per-page QA checklist

- [ ] Exactly one eye
- [ ] Mouth is a closed line — no teeth, no tongue
- [ ] Eight ribs
- [ ] One leg, one geta
- [ ] No arms or hands
- [ ] Height matches Momo
- [ ] No pure black anywhere
