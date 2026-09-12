# Hane — Character Sheet Specification

Reference-sheet package for HANE, the **small tengu** of *Hane Keeps the Wind*
(Yokai Night Watch, Book 2).

Companion documents: `book/hane-keeps-the-wind.md`, `book/momo-character-sheet.md`,
`book/kasa-character-sheet.md`

**Two things make this the highest-risk design in the series.** Left unspecified, image
models draw an angry red-faced long-nosed tengu. And "small tengu" is not "tengu child":
he is fully grown and will always be this size. Any childlike or apprentice-like reading —
oversized wings, flailing, a puppyish face — undoes the emotional design of the book.

---

## 1. Who he is

Hane is a **small adult tengu**, in the folkloric line of the *konoha-tengu*: the lesser
tengu of the leaves, low-ranked and overlooked. He is not learning. He is simply too small
for the mountain to ever call on him, and he has been waiting a long time for someone to
need exactly what he can do.

Register, and why it is bounded on both sides:
- **Not a child** — no clumsiness, no apprentice energy, no oversized features.
- **Not an elder** — no beard, no staff, no stoop. Kasa already holds the grandfatherly
  register in Book 1, and two volumes cannot share it.
- He lands in between: **quiet, modest, precise, unhurried.** A small craftsman.

---

## 2. Spec card (canon)

| Item | Locked spec | Failure mode if unspecified |
|---|---|---|
| Height | **88 cm** — deliberately **shorter than Momo at 95 cm** | a grown tengu shorter than a three-year-old is the whole picture: he is small, not young |
| Proportions | **four heads tall**, compact — small but adult | three heads reads as a child and collapses the premise |
| **Face color** | warm pale skin `#F0DCCB`; **dusty coral `#D98C86` on the cheeks ONLY**. **A red face is forbidden** | the biggest failure mode — a red face reads as an oni |
| **Nose** | **short round nose, about 4 cm**, a small rounded ridge. Short because he is *small*, not because he is young | tengu means long nose to every model; it will grow unless suppressed |
| Beak | **none** — the crow-faced konoha-tengu variant is not used | |
| Eyes | calm and round, iris `#3E3A4A`, **faint kind creases at the outer corners**, level brows. No slanted eyes, no angry brows | the creases are the one adult marker that reads as warmth rather than age |
| Hair | charcoal `#2E2A33`, small neat topknot | |
| Tokin cap | small **black box-shaped yamabushi tokin** `#3A3644` on the forehead, thin cord | frequently dropped; without it he reads as a bird |
| Wings | **exactly two**, smoke grey `#9AA0AE` with pale moss tips, **five flight feathers per wing**, **well proportioned to his body** but **clearly well used — a few worn tips** | oversized wings are a child marker; wear is what says "grown" |
| Robe | knee-length indigo `#4A5273` yamabushi robe, **faded and softened at the hem**, pale moss `#A8B49A` sash, **two small pale moss pom-poms** on the chest cords | the two pom-poms are a cheap, reliable consistency anchor |
| Feet | **bare** — no sandals (deliberate contrast with Kasa's geta) | |
| Fan | **one** leaf-shaped hauchiwa, 30 cm total (20 cm blade + 10 cm handle), pale moss green `#9FB08C`, **handle darkened by years of use** | if the size drifts, the shrinking strokes stop reading |
| Forbidden | red face, long nose, beak, fangs, claws, weapon, staff, **beard**, clumsiness | beard and staff would collide with Kasa; clumsiness would make him a child |

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

## 3. Wing spread is the second metronome

The fan stroke is the book's visible metronome; the wings are the second one. They close
down in step with it. Children read quiet from silhouette width before they read it from
anything else.

| Page | Fan | **Wing spread** |
|---|---|---|
| p1-3 | — | folded neatly (he has just landed, and he is tidy about it) |
| p4 | WHOOSH | **fully spread** — largest silhouette in the book |
| p5 | Fwoo | half open |
| p6 | Foo | quarter |
| p7-8 | tiny | folding |
| p9-12 | stopped | **fully closed, pressed flat to his back** |

---

## 4. Reusable CHARACTER block

```
CHARACTER - HANE: a very small adult tengu, total height 88 cm, compact four-heads-tall
proportions - small but grown, not a child. Warm pale skin #F0DCCB with soft DUSTY CORAL
blush #D98C86 on the cheeks ONLY - the face is NOT red. A SHORT ROUND NOSE, about 4 cm, a
small rounded ridge: he is a SMALL tengu, so his nose is small. NO beak, NO long nose.
Calm round dark eyes with iris #3E3A4A, faint kind creases at the outer corners, level
friendly eyebrows - never slanted, never angry. Soft charcoal #2E2A33 hair in a small neat
topknot. A tiny black box-shaped yamabushi tokin cap #3A3644 on his forehead on a thin
cord. EXACTLY TWO feathered wings from his upper back in smoke grey #9AA0AE with pale moss
#A8B49A tips, FIVE large flight feathers per wing, well proportioned to his small body but
clearly WELL USED - a few feather tips slightly worn. A knee-length indigo #4A5273
yamabushi robe, softened and faded at the hem, a pale moss #A8B49A sash, TWO small pale
moss pom-poms on the chest cords. Bare feet with small round toes - no sandals. He holds
ONE leaf-shaped hauchiwa fan, 30 cm long, a pale moss green #9FB08C leaf blade with fine
veins, its handle darkened from years of use. Quiet, modest, precise, completely
unhurried. Never haughty, never fierce, never frightening. NO claws, NO fangs, NO weapon,
NO staff, NO beard.
```

---

## 5. Sheet G - Turnaround (generate first)

```
Character turnaround model sheet for a children's picture book, five views of the SAME
character in one image, evenly lit, flat neutral studio lighting, no dramatic shadows,
warm off-white washi paper background #EFE7DA, thin pale grid lines and a height
reference line marked 88 cm, clean reference-sheet layout.

[CHARACTER BLOCK - HANE]

THE FIVE VIEWS, left to right, all at the same scale on the same ground line:
1. FRONT view, standing straight and composed, wings folded neatly, holding the leaf fan
   in one hand at his side, calm level face.
2. THREE-QUARTER view, standing, wings folded, weight settled evenly.
3. SIDE profile view, standing, wings folded, showing the SHORT ROUND NOSE silhouette,
   the tokin cap on the forehead, and the robe length clearly.
4. BACK view, standing, wings FULLY SPREAD, showing the five flight feathers on each wing,
   a few worn feather tips, and how the wings attach to his upper back. No face visible.
5. SCALE COMPARISON: Hane standing beside MOMO, the three-year-old child from the attached
   reference sheet. Momo is 95 cm and Hane is 88 cm - Hane is clearly a little SHORTER
   than the child, while being visibly a grown adult, not a second child. Do not change
   Momo's design.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, gentle line work, picture-book illustration for ages 3+, child-safe.
Label each view with small handwritten text underneath: "front", "3/4", "side", "back
(wings open)", "with Momo".

NEGATIVE: red face, bright red skin, crimson, long nose, big nose, beak, crow head, bird
head, oni, demon, mask, angry eyebrows, slanted eyes, fierce, fangs, claws, weapon, staff,
sword, beard, four wings, one wing, oversized wings, childlike, chibi child, toddler
proportions, clumsy, off balance, adult tengu that is tall, muscular, dark background,
night scene, moonlight, high contrast, neon, 3D render, photorealistic, watermark, extra
fingers.
```

Attach Momo's Sheet D for view 5. The moment he reads as **a grown tengu shorter than a
three-year-old**, the book's emotional design is locked. If view 5 reads as two children
standing together, reject the generation and raise the head count to four.

---

## 6. Sheet H - Expressions

```
Expression sheet for a children's picture book character, EIGHT head-and-shoulders close
-ups of the SAME character arranged in a 4x2 grid, evenly lit, flat neutral lighting,
warm off-white washi paper background #EFE7DA, clean reference-sheet layout.

[CHARACTER BLOCK - HANE]

THE EIGHT EXPRESSIONS, each labeled underneath in small handwritten text:
1. "modest"          - eyes lowered slightly, small closed mouth, quietly self-effacing.
2. "deep bow"        - head folded all the way down in a deep formal bow, eyes closed,
                       perfectly correct posture. Comic only because he is so small and
                       so serious.
3. "mountain wind"   - chin lifted, eyes bright and wide open, the single moment of tengu
                       pride in the whole book. Confident, never haughty.
4. "correcting"      - eyes level, mouth a small flat line, a quiet private realisation
                       that the last stroke was too much. Not embarrassed, not apologetic.
5. "precise"         - eyes narrowed very slightly in focus, lips closed, the face of
                       someone measuring a very small movement exactly.
6. "content"         - a small closed-mouth smile, eyes softened into gentle arcs, the
                       cheek creases showing. Satisfied that something has settled.
7. "small and steady"- looking outward, level and unsentimental, neither sad nor proud.
                       Completely at peace with being small.
8. "on watch"        - eyes open, calm and unwavering, chin level, a quiet faint glow
                       around him. The face of someone doing work they are good at.

Across all eight panels the face stays soft, adult and kind. No anger, no fierceness, no
crying, no fear, no childish exaggeration. The nose stays SHORT and ROUND in every panel.
The tokin cap stays on the forehead in every panel.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
picture-book illustration for ages 3+, child-safe, gentle.

NEGATIVE: red face, bright red skin, long nose, beak, oni, demon, angry, fierce, haughty,
slanted eyes, fangs, beard, crying, screaming, childlike, exaggerated cartoon expression,
scary, creepy, dark background, night scene, high contrast, 3D render, photorealistic,
watermark.
```

Page mapping: p2 "modest", p3 "deep bow", p4 "mountain wind", p5 "correcting",
p6-7 "precise", p8 "content", p9 "small and steady", p10-12 "on watch".

---

## 7. Sheet I - The five fan strokes (the working sheet)

This single sheet is the spine of the book's art. The five stroke sizes *are* the story's
decay curve.

**The motion quality changed with the character.** This is not a novice failing and
retrying. It is a skilled small tengu dialing a tool down on purpose: every stroke is
controlled, and each one is smaller because he decided it should be.

```
Action sheet for a children's picture book, FIVE full-body poses of the SAME character in
one image, showing ONE deliberate motion being dialed DOWN step by step from left to
right. Every pose is controlled and skilled - this is a craftsman reducing a tool's
output on purpose, NOT a beginner failing and retrying. Evenly lit, flat neutral lighting,
warm off-white washi paper background #EFE7DA, all five figures at the same scale on the
same ground line, clean reference-sheet layout.

[CHARACTER BLOCK - HANE]

THE FIVE FAN STROKES, left to right, each smaller than the last. The wings close down in
step with the fan:
1. "WHOOSH"  - one huge committed two-handed swing, the fan sweeping in a wide arc above
               his head, wings FULLY SPREAD, feet just leaving the ground, broad sweeping
               motion lines, a leaf tumbling away. Confident and expert. Largest
               silhouette in the book.
2. "Fwoo"    - a measured half swing, fan held closer to the chest, wings HALF OPEN, body
               steady and balanced, fewer and shorter motion lines, one feather drifting.
3. "Foo"     - a small stroke from the elbow only, fan low, wings a QUARTER OPEN, body
               still, only two or three faint motion lines.
4. "tiny"    - a precise flick from the wrist alone, fan barely moving, wings FOLDED, body
               completely still, a single hairline motion line.
5. "stopped" - no motion at all. The fan lowered and held quietly in both hands against
               his chest, wings FULLY CLOSED and pressed flat to his back, standing
               perfectly still. Smallest, quietest silhouette. No motion lines anywhere.

The silhouette must shrink visibly and steadily from pose 1 to pose 5. This descending
sequence is the point of the sheet.

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, picture-book illustration for ages 3+, child-safe, gentle controlled
motion.
Label each pose underneath in small handwritten text: "WHOOSH", "Fwoo", "Foo", "tiny",
"stopped", with the label size shrinking to match each pose.

NEGATIVE: red face, long nose, beak, oni, demon, angry, fierce, fangs, claws, weapon,
staff, beard, clumsy, flailing, off balance, struggling, stumbling, childlike, violent
motion, fighting manga action lines, speed lines, dark background, night scene, high
contrast, 3D render, photorealistic, watermark, extra wings.
```

Page mapping: p4 "WHOOSH", p5 "Fwoo", p6 "Foo", p7-8 "tiny", p9 onward "stopped".

---

## 8. Sheet J - Series line-up (covers and Amazon)

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
3. HANE, the very small adult tengu, 88 cm, standing, wings folded, holding his leaf fan.
   The smallest of the three, and clearly a grown adult rather than a second child.

All three face the viewer, relaxed and friendly, standing close together like a small
household. Label each figure with small handwritten text underneath: "Kasa 92cm",
"Momo 95cm", "Hane 88cm".

STYLE: hand-painted gouache with soft colored-pencil grain, muted dusty pastel palette,
soft rounded shapes, picture-book illustration for ages 3+, child-safe.

NEGATIVE: red face, long nose, beak, two eyes on Kasa, sharp teeth, beard, childlike
tengu, scary, creepy, dark background, night scene, high contrast, 3D render,
photorealistic, watermark.
```

---

## 9. How to use the sheets

Attach **Momo Sheet E (sleeping poses) + Hane Sheet G** to every page generation. For
pages 4 through 9, attach **Sheet I as a third reference** — those pages live or die on
the stroke stage, and are worth the extra reference.

```
Use the attached sheets as exact references: sheet 1 for MOMO, sheet 2 for HANE.
Keep both designs identical to the sheets. MOMO is lying down on the futon, never sitting
up or standing. HANE is a small ADULT tengu, not a child: his nose stays SHORT and ROUND,
his face is NOT red, and he is calm and controlled, never clumsy. In this scene his fan
stroke and wing spread must match the "<stage name>" pose. Only re-light both characters
for this night scene; the flat daylight lighting of the sheets must NOT be copied.
```

---

## 10. Per-page QA checklist

- [ ] Face is not red — blush on the cheeks only
- [ ] Nose short and round
- [ ] No beak, no beard
- [ ] Two wings, five flight feathers each, proportionate and worn — not oversized
- [ ] Tokin cap on the forehead
- [ ] Two pom-poms on the chest cords
- [ ] Bare feet
- [ ] One leaf fan, consistent size
- [ ] **Fan stroke and wing spread match this page's stage**
- [ ] Shorter than Momo — and still reads as an adult, not a second child
