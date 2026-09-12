# Hane — Character Sheet Specification

Reference-sheet package for HANE, the child tengu of *Hane Keeps the Wind*
(Yokai Night Watch, Book 2).

Companion documents: `book/hane-keeps-the-wind.md`, `book/momo-character-sheet.md`,
`book/kasa-character-sheet.md`

**The highest-risk character in the series.** Left unspecified, image models draw an
angry red-faced long-nosed tengu — the exact opposite of what this book needs. The
negative list matters more here than anywhere else.

---

## 1. Spec card (canon)

| Item | Locked spec | Failure mode if unspecified |
|---|---|---|
| Height | **88 cm** — deliberately **shorter than Momo at 95 cm** | those 7 cm are what make him "a little one with a job" rather than a protector |
| Proportions | three heads tall, same as Momo | |
| **Face color** | warm pale skin `#F0DCCB`; **dusty coral `#D98C86` on the cheeks ONLY**. **A red face is forbidden** | the biggest failure mode — a red face reads as an oni |
| **Nose** | **short round button nose**, not yet grown | tengu means long nose to every model; it will grow unless suppressed, and its shortness is the hinge of page 9 |
| Beak | **none** — not a karasu-tengu | |
| Eyes | large, round, iris `#3E3A4A`. **No slanted eyes, no angry brows** | |
| Hair | charcoal `#2E2A33`, small topknot | |
| Tokin cap | small **black box-shaped yamabushi tokin** `#3A3644` on the forehead, thin cord | frequently dropped; without it he reads as a bird child |
| Wings | **exactly two**, smoke grey `#9AA0AE` with pale moss tips, **five visible flight feathers per wing**, slightly **too big** for his body | a drifting feather count breaks recognition |
| Robe | knee-length indigo `#4A5273` yamabushi robe, pale moss `#A8B49A` sash, **two small pale moss pom-poms** on the chest cords | the two pom-poms are a cheap, reliable consistency anchor |
| Feet | **bare** — no sandals (deliberate contrast with Kasa's geta) | |
| Fan | **one** leaf-shaped hauchiwa, 30 cm total (20 cm blade + 10 cm handle), pale moss green `#9FB08C` with fine veins | if the size drifts, the shrinking strokes stop reading |
| Character | earnest, willing, slightly clumsy. **Zero haughtiness, zero menace** | an adult tengu's expression ruins the book |

### Color chips

| Part | HEX |
|---|---|
| Skin | `#F0DCCB` |
| Cheek blush | `#D98C86` |
| Iris | `#3E3A4A` |
| Hair | `#2E2A33` |
| Tokin cap | `#3A3644` |
| Wings | `#9AA0AE` |
| Feather tips | `#A8B49A` |
| Robe | `#4A5273` |
| Sash and pom-poms | `#A8B49A` |
| Leaf fan | `#9FB08C` |
| Washi ground | `#EFE7DA` |

## 2. Wing spread is the second metronome

The fan stroke is the book's visible metronome; the wings are the second one. They close
down in step with it. Children read quiet from silhouette width before they read it from
anything else.

| Page | Fan | **Wing spread** |
|---|---|---|
| p1-3 | — | half open (just landed, unsettled) |
| p4 | WHOOSH | **fully spread** — largest silhouette in the book |
| p5 | Fwoo | half open |
| p6 | Foo | quarter |
| p7-8 | tiny | folding |
| p9-12 | stopped | **fully closed, pressed flat to his back** |

---

## 3. Reusable CHARACTER block

```
CHARACTER - HANE: a very small child tengu, total height 88 cm, soft rounded three-heads
-tall chibi proportions, round full cheeks. Warm pale skin #F0DCCB with soft DUSTY CORAL
blush #D98C86 on the cheeks ONLY - the face is NOT red. A SHORT ROUND BUTTON NOSE: he is
still young and his tengu nose has not grown yet. NO beak, NO long nose. Big round gentle
dark eyes with iris #3E3A4A, soft short lashes, round friendly eyebrows - never slanted,
never angry. Soft charcoal #2E2A33 hair gathered into a small topknot. A tiny black
box-shaped yamabushi tokin cap #3A3644 sits on his forehead, held by a thin cord.
EXACTLY TWO soft feathered wings growing from his upper back in smoke grey #9AA0AE with
pale moss #A8B49A feather tips, FIVE large visible flight feathers per wing, the wings
slightly TOO BIG for his small body. A knee-length indigo #4A5273 yamabushi robe with
wide sleeves, a pale moss #A8B49A sash, and TWO small pale moss pom-poms on the chest
cords. Bare feet with small round toes - no sandals. He holds ONE leaf-shaped hauchiwa
fan, 30 cm long, a pale moss green #9FB08C leaf blade with fine veins on a short handle.
Earnest, gentle, a little clumsy, proud of his small job. Never proud in a haughty way,
never fierce, never frightening. NO claws, NO fangs, NO weapon, NO staff.
```

---

## 4. Sheet G - Turnaround (generate first)

```
Character turnaround model sheet for a children's picture book, five views of the SAME
character in one image, evenly lit, flat neutral studio lighting, no dramatic shadows,
warm off-white washi paper background #EFE7DA, thin pale grid lines and a height
reference line marked 88 cm, clean reference-sheet layout.

[CHARACTER BLOCK - HANE]

THE FIVE VIEWS, left to right, all at the same scale on the same ground line:
1. FRONT view, standing, wings half open, holding the leaf fan in one hand at his side,
   calm earnest face.
2. THREE-QUARTER view, standing, wings half open, slight forward lean.
3. SIDE profile view, standing, wings folded, showing the SHORT ROUND NOSE silhouette,
   the tokin cap on the forehead, and the robe length clearly.
4. BACK view, standing, wings FULLY SPREAD, showing the five flight feathers on each wing
   and how the wings attach to his upper back. No face visible.
5. SCALE COMPARISON: Hane standing beside MOMO, the three-year-old child from the attached
   reference sheet. Momo is 95 cm and Hane is 88 cm - Hane is clearly a little SHORTER
   than the child. Do not change Momo's design.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, gentle line work, picture-book illustration for ages 3+, child-safe.
Label each view with small handwritten text underneath: "front", "3/4", "side", "back
(wings open)", "with Momo".

NEGATIVE: red face, bright red skin, crimson, long nose, big nose, beak, crow head, bird
head, oni, demon, mask, angry eyebrows, slanted eyes, fierce, fangs, claws, weapon, staff,
sword, four wings, one wing, adult tengu, tall, muscular, dark background, night scene,
moonlight, high contrast, neon, 3D render, photorealistic, watermark, extra fingers.
```

Attach Momo's Sheet D for view 5. The moment Hane is visibly smaller than the child, the
book's emotional design is locked.

---

## 5. Sheet H - Expressions

```
Expression sheet for a children's picture book character, EIGHT head-and-shoulders close
-ups of the SAME character arranged in a 4x2 grid, evenly lit, flat neutral lighting,
warm off-white washi paper background #EFE7DA, clean reference-sheet layout.

[CHARACTER BLOCK - HANE]

THE EIGHT EXPRESSIONS, each labeled underneath in small handwritten text:
1. "shy"           - eyes looking slightly away, small closed mouth, a little nervous,
                     newly arrived.
2. "polite bow"    - head lowered in a formal little bow, eyes closed politely.
3. "off balance"   - eyes wide in surprise, mouth a small open circle, tipping forward,
                     one wing flared out to catch himself, comic but gentle.
4. "eager"         - eyes bright and round, small open smile, chin up, about to try.
5. "oops"          - eyebrows raised in the middle, mouth a small flat embarrassed line,
                     cheeks a little warmer - he swung the fan too hard.
6. "concentrating" - eyes narrowed slightly in focus, tongue tip NOT showing, lips
                     pressed, working carefully on a very small movement.
7. "looking at his nose" - eyes turned down toward his own short round nose, a small
                     thoughtful, slightly wistful expression.
8. "on watch"      - eyes open, steady and calm, chin lifted, a quiet faint glow around
                     him, serious in a gentle way - the face of someone doing their first
                     real job.

Across all eight panels the face stays soft and kind. No anger, no fierceness, no crying,
no fear. The nose stays SHORT and ROUND in every single panel. The tokin cap stays on the
forehead in every panel.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
picture-book illustration for ages 3+, child-safe, gentle.

NEGATIVE: red face, bright red skin, long nose, beak, oni, demon, angry, fierce, slanted
eyes, fangs, crying, screaming, scary, creepy, dark background, night scene, high contrast,
3D render, photorealistic, watermark.
```

Page mapping: p2 "shy", p3 "polite bow" + "off balance", p4 "eager", p5 "oops",
p6-8 "concentrating", p9 "looking at his nose", p10-12 "on watch".

---

## 6. Sheet I - The five fan strokes (the working sheet)

This single sheet is the spine of the book's art. The five stroke sizes *are* the story's
decay curve. If this sheet is vague, no page will communicate that the wind is shrinking.

```
Action sheet for a children's picture book, FIVE full-body poses of the SAME character in
one image, showing ONE continuous motion getting progressively SMALLER from left to right.
Evenly lit, flat neutral lighting, warm off-white washi paper background #EFE7DA, all five
figures at the same scale on the same ground line, clean reference-sheet layout.

[CHARACTER BLOCK - HANE]

THE FIVE FAN STROKES, left to right, each smaller than the last. The wings close down in
step with the fan:
1. "WHOOSH"  - a huge two-handed swing, the fan sweeping in a wide arc above his head,
               wings FULLY SPREAD, whole body committed, feet leaving the ground slightly,
               broad sweeping motion lines, a leaf tumbling away. Largest silhouette.
2. "Fwoo"    - a careful half swing, fan held closer to his chest, wings HALF OPEN, body
               steady, fewer and shorter motion lines, one feather drifting.
3. "Foo"     - a small stroke from the elbow only, fan low, wings a QUARTER OPEN, body
               almost still, only two or three faint motion lines.
4. "tiny"    - a tiny flick from the wrist alone, fan barely moving, wings FOLDED, body
               completely still, a single hairline motion line.
5. "stopped" - no motion at all. The fan lowered and held quietly in both hands against
               his chest, wings FULLY CLOSED and pressed flat to his back, standing
               perfectly still. Smallest, quietest silhouette. No motion lines anywhere.

The silhouette must shrink visibly and steadily from pose 1 to pose 5. This descending
sequence is the point of the sheet.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, picture-book illustration for ages 3+, child-safe, gentle motion.
Label each pose underneath in small handwritten text: "WHOOSH", "Fwoo", "Foo", "tiny",
"stopped", with the label size shrinking to match each pose.

NEGATIVE: red face, long nose, beak, oni, demon, angry, fierce, fangs, claws, weapon,
violent motion, action lines like a fighting manga, speed lines, dark background, night
scene, high contrast, 3D render, photorealistic, watermark, extra wings.
```

Page mapping: p4 "WHOOSH", p5 "Fwoo", p6 "Foo", p7-8 "tiny", p9 onward "stopped".

---

## 7. Sheet J - Series line-up (covers and Amazon)

Not used inside either book, but required for the covers and the series page. Cheapest to
make now, while all three designs are fresh.

```
Series line-up reference sheet for a children's picture book series, THREE characters
standing side by side in one image on the same ground line, evenly lit, flat neutral
lighting, warm off-white washi paper background #EFE7DA, a height scale marked at the
left, clean reference-sheet layout.

Use the three attached character sheets as exact references and do not change any design.
Left to right:
1. KASA, the one-eyed paper-umbrella yokai, 92 cm, canopy open, one round gentle eye.
2. MOMO, the three-year-old child, 95 cm, standing, calm sleepy face. The tallest of
   the three, but only just.
3. HANE, the small child tengu, 88 cm, standing, wings half open, holding his leaf fan.
   The smallest of the three.

All three face the viewer, relaxed and friendly, standing close together like a small
family. Label each figure with small handwritten text underneath: "Kasa 92cm",
"Momo 95cm", "Hane 88cm".

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, picture-book illustration for ages 3+, child-safe.

NEGATIVE: red face, long nose, beak, two eyes on Kasa, sharp teeth, scary, creepy, dark
background, night scene, high contrast, 3D render, photorealistic, watermark.
```

---

## 8. How to use the sheets

Attach **Momo Sheet E (sleeping poses) + Hane Sheet G** to every page generation. For
pages 4 through 9, attach **Sheet I as a third reference** — those pages live or die on
the stroke stage, and are worth the extra reference.

```
Use the attached sheets as exact references: sheet 1 for MOMO, sheet 2 for HANE.
Keep both designs identical to the sheets. MOMO is lying down on the futon, never sitting
up or standing. HANE's nose stays SHORT and ROUND and his face is NOT red. In this scene
his fan stroke and wing spread must match the "<stage name>" pose. Only re-light both
characters for this night scene; the flat daylight lighting of the sheets must NOT be
copied.
```

---

## 9. Per-page QA checklist

- [ ] Face is not red — blush on the cheeks only
- [ ] Nose short and round
- [ ] No beak
- [ ] Two wings, five flight feathers each
- [ ] Tokin cap on the forehead
- [ ] Two pom-poms on the chest cords
- [ ] Bare feet
- [ ] One leaf fan, consistent size
- [ ] **Fan stroke and wing spread match this page's stage**
- [ ] Shorter than Momo
