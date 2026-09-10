# Kasa Keeps the Night — Picture Book Bible

Fixed-layout Kindle children's book (KDP, international/EN).
Target: age 3, read aloud by mother, at bedtime **stage B** (already in the futon, wide awake).
Yokai: **Karakasa-obake** (one-eyed paper umbrella).
Parent pain point solved: **guilt about falling asleep before the child.**
Hard rules: no moralizing, no "be good", no "go to sleep now", no gore, no genuinely scary faces.

---

## 1. Core design decisions

### 1.1 Momo never leaves the futon
Stage B means the child is already lying down. An adventure that requires standing up
undoes the bedtime. So: **Kasa spins its canopy and the futon floats — the room comes to
the child.** Momo is horizontal on all 14 pages. The illustrated posture matches the
reader's real posture.

### 1.2 Kasa takes the night watch (the guilt killer)
On page 12 Kasa says it will guard the night **and "the big warm one" beside the child** —
i.e. the parent. The hand-off of night duty happens inside the story. A front-matter page
addressed to the grown-up states it plainly.

### 1.3 Gender-neutral by construction
The child is only ever called "Momo". No pronouns anywhere in the book text.

---

## 2. Characters (fixed descriptions — reuse verbatim in every image prompt)

**MOMO**: a small three-year-old child, round soft cheeks, short black bobbed hair with
blunt bangs, big gentle sleepy dark eyes, wearing a pale lavender-grey yukata-style pajama
printed with tiny white crescent moons, bare feet, soft rounded chibi proportions.

**KASA**: a friendly one-eyed Japanese paper-umbrella yokai (karakasa), canopy of dusty
rose and pale lilac oiled washi paper with faded bamboo ribs and worn indigo trim, ONE
single large round gentle eye with long soft lashes, a small closed crescent smile with no
visible teeth and no tongue, one slender pale wooden leg ending in one tiny wooden geta
sandal, about the height of a three-year-old child, gentle and grandfatherly.

Note: traditional karakasa has a long protruding tongue. Deliberately removed — "no scary
faces" takes priority.

---

## 3. Two-layer structure

### 3.1 Surface layer (the adventure the child experiences)

| P | Surface |
|---|---|
| 1 | Can't sleep. Something in the dark corner goes *click*. |
| 2 | An old umbrella opens, slow as a flower. |
| 3 | Meet Kasa. "Shhh — the house is falling asleep." |
| 4 | "Do not get up. Tonight the room will come to you." The futon lifts. |
| 5 | The futon boat drifts down the dark hallway. |
| 6 | Goodnight to two teacups. |
| 7 | The wind chime rings once, then decides not to. |
| 8 | A fish sinks into the cool dark and stays. |
| 9 | The other umbrellas are already asleep by the door. |
| 10 | The moon pulls a cloud over its face. A big slow yawn. |
| 11 | The futon comes home, soft as snow. |
| 12 | Kasa stands watch by the pillow — and over the big warm one too. |
| 13 | The room breathes with Momo. |
| 14 | Quiet. Quiet. Goodnight. |

### 3.2 Hidden layer (the sleep device — seven descending sliders)

| Slider | P1-4 | P5-9 | P10-14 |
|---|---|---|---|
| Words per page | 33 -> 25 | 22 -> 14 | 12 -> 3 |
| Reading voice | normal | whisper | breath only |
| Sentence form | compound | simple | single words |
| Consonants | hard k/t/p | s/sh/m/n | m/n + long vowels ee/oo |
| Light sources in art | 3 (moon+shoji+lantern) | 2 -> 1 | 1 -> afterglow only |
| Camera | wide, moving | slow lateral drift | still, close -> final quiet wide |
| Questions to the child | yes (wiggle toes) | only join the "shhh" | **zero** (questions wake children) |

Extra mechanics:
- The refrain shortens every time: "Goodnight, cups." -> "Goodnight, chime." ->
  "Goodnight, fish." -> by p13 it has decayed into breathing only.
- P13 is a **breath pacer**: "In... and out..." slows the *reading parent's* breathing too.
- P13 + P14 total 7 words, so a half-asleep parent can finish the book.
- P14 lands on stillness and darkness alone; if the reader's voice stops, the art still lands.

---

## 4. Page text + image prompts

### Shared prompt blocks (paste into every page prompt)

```
[STYLE] pastel goth Japanese picture book illustration, hand-painted gouache with
soft colored-pencil grain on warm washi paper texture, muted dusty pastel palette of
ash lavender, smoke pink, pale moss green, indigo shadow and warm off-white, deep but
gentle darkness with no pure black and no harsh contrast, moonlight filtered through
shoji paper screens, tatami and old wood texture, dreamy low-contrast lighting, soft
rounded shapes, cozy and safe, absolutely no scary faces, no sharp teeth, no horror,
child-safe, ages 3+.

[MOMO] a small three-year-old child, round soft cheeks, short black bobbed hair with
blunt bangs, big gentle sleepy dark eyes, wearing a pale lavender-grey yukata-style
pajama printed with tiny white crescent moons, bare feet, soft rounded chibi proportions.

[KASA] a friendly one-eyed Japanese paper-umbrella yokai (karakasa), canopy of dusty
rose and pale lilac oiled washi paper with faded bamboo ribs and worn indigo trim, ONE
single large round gentle eye with long soft lashes, a small closed crescent smile with
no visible teeth and no tongue, one slender pale wooden leg ending in one tiny wooden
geta sandal, about the height of a three-year-old child, gentle and grandfatherly.

[FORMAT] landscape 16:10, 2560x1600 px, keep the bottom 22% quiet and low-detail as a
clear area for text, nothing important in the center vertical seam.

[NEGATIVE] scary, creepy, horror, sharp teeth, long tongue, blood, glowing red eyes,
harsh black shadows, neon colors, high saturation, 3D render, photorealistic, extra
limbs, two eyes on Kasa, watermark, distorted text.
```

---

### Front matter — "For the grown-up" (not read to the child)

**Text**
```
If you fall asleep before your child tonight, you did not fail.
You stayed. That was the whole job.
Kasa has the watch now.
Goodnight, big one.
```

**Prompt**
```
[STYLE] [KASA] [FORMAT]
Simple, quiet page. [KASA] alone, folded, standing watch in a dark empty tatami room,
one gentle glowing eye open, seen from behind and slightly above. Ninety percent empty
soft darkness. No child, no people. Calm and reassuring.
The four lines of text "If you fall asleep before your child tonight, you did not fail.
You stayed. That was the whole job. Kasa has the watch now. Goodnight, big one." are
written in the center-lower area in a small soft italic handwritten font, warm off-white.
[NEGATIVE]
```

---

### Page 1 — 33 words

**Text**
```
Momo was in bed.
Momo was not asleep.
Ten wiggly toes. Two wide eyes.
Outside, the moon leaned on the paper window.
And in the dark corner, something went...
click.
```

**Prompt**
```
[STYLE] [MOMO] [FORMAT]
Wide shot of a small Japanese tatami room at night. [MOMO] lies on a low futon under a
soft indigo quilt, eyes wide open, ten bare toes poking out and wiggling. Large round
moon glowing behind a shoji paper screen, casting a pale lavender grid of light across
the tatami. In the far dark corner, a closed old paper umbrella leans against the wall,
barely visible, one faint round glimmer where its eye will be. Three light sources:
moon, shoji glow, a tiny paper lantern. Awake, curious, safe.
The text "Momo was in bed. Momo was not asleep. And in the dark corner, something went...
click." is written in the lower area in a soft rounded handwritten storybook font, warm
off-white, gently spaced over three lines.
[NEGATIVE]
```

---

### Page 2 — 30 words

**Text**
```
The old umbrella opened,
slow as a flower.
One round eye blinked.
One wooden foot tapped the floor.
Tap.
Tap.
Tap.
```

**Prompt**
```
[STYLE] [KASA] [FORMAT]
Medium shot of the dark corner of the tatami room. [KASA] is opening its canopy slowly,
like a flower blooming, dusty rose washi petals unfolding, faint dust motes drifting in
the moonbeam. Its one large round eye is half-open and blinking, gentle and sleepy. Its
single wooden geta foot has just tapped the tatami, three small soft ripple lines around
it. [MOMO] visible only as a small silhouette of a head at the edge of the frame,
watching. Moonlight from the left.
The text "The old umbrella opened, slow as a flower. Tap. Tap. Tap." is written in the
lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 3 — 27 words

**Text**
```
"I am Kasa," said the umbrella.
"I keep the night."
Momo laughed - a very, very small laugh.
Kasa tipped its brim over its eye.
"Shhh. The house is falling asleep."
```

**Prompt**
```
[STYLE] [MOMO] [KASA] [FORMAT]
Close two-shot. [KASA] stands beside the futon and tips its paper brim low over its one
round eye in a "shhh" gesture. [MOMO] lies on the futon, quilt up to the chin, mouth
open in a tiny delighted silent laugh, one hand over the mouth. Warm gentle mood, very
soft smoke-pink rim light on both. Background dissolves into ash-lavender darkness.
Two light sources only: moon through shoji, small floor lantern.
The text "'I am Kasa,' said the umbrella. 'I keep the night. Shhh - the house is falling
asleep.'" is written in the lower area in a soft rounded handwritten storybook font,
warm off-white.
[NEGATIVE]
```

---

### Page 4 — 25 words

**Text**
```
"Do not get up," said Kasa.
"Stay in your warm futon.
Tonight, the room will come to you."
Kasa turned its brim, slow and round.
```

**Prompt**
```
[STYLE] [MOMO] [KASA] [FORMAT]
[KASA] slowly spins its open canopy like a pinwheel, trailing soft spirals of pale
lilac light and tiny drifting moon-shaped sparks. [MOMO] stays lying flat on the futon,
quilt tucked to the chin, eyes wide with wonder, NOT sitting up, NOT standing. The
tatami mats beneath the futon begin to blur into gentle water-like ripples. Dreamy,
weightless, hushed.
The text "'Do not get up,' said Kasa. 'Tonight, the room will come to you.'" is written
in the lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 5 — 22 words

**Text**
```
The futon lifted.
Not high. Never high.
Just enough to float,
like a leaf on slow water,
down the long dark hallway.
```

**Prompt**
```
[STYLE] [MOMO] [KASA] [FORMAT]
Side view. The futon with [MOMO] still lying flat upon it floats about thirty
centimeters above a long wooden hallway, drifting slowly like a leaf on water, with soft
ripple lines beneath it. [KASA] hops alongside on its one geta foot, brim tilted
forward. The hallway recedes into deep gentle indigo, shoji screens glowing faintly
lavender on the right. Slow horizontal motion, dust motes suspended. Light dimmer than
the previous page.
The text "The futon lifted. Not high. Never high. Just enough to float." is written in
the lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 6 — 20 words

**Text**
```
Two teacups sat on the shelf.
"Goodnight, cups," whispered Momo.
The cups leaned together
and closed their small round mouths.
```

**Prompt**
```
[STYLE] [MOMO] [KASA] [FORMAT]
Quiet kitchen shelf in near darkness. Two small round ceramic teacups in smoke pink and
pale moss lean gently against each other, each with a tiny sleepy closed-eye face, soft
and cute. The floating futon with [MOMO] lying on it drifts past in the near dark on the
right, [MOMO] whispering with one small hand raised in a tiny wave. [KASA] behind,
mostly silhouette, one soft glowing eye. Only ONE light source now: a faint moon glow
from a high window.
The text "'Goodnight, cups,' whispered Momo." is written in the lower area in a soft
rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 7 — 18 words

**Text**
```
On the wooden porch, the wind chime rang once.
Ting.
Then it decided not to.
"Goodnight, chime."
```

**Prompt**
```
[STYLE] [MOMO] [KASA] [FORMAT]
Night engawa wooden veranda open to a dark garden. A small glass furin wind chime hangs
still, its little paper tail hanging straight down, one faint circular sound-ripple
fading in the air around it. Dark garden beyond in ash lavender and indigo, one pale
stone lantern unlit. The floating futon and [MOMO] are small and low in the frame, half
in shadow. [KASA] beside it, a soft dark shape with one gentle glowing eye. Very still,
very quiet, low contrast.
The text "The wind chime rang once. Then it decided not to. Goodnight, chime." is written
in the lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 8 — 16 words

**Text**
```
In the pond, one fish went down,
down,
into the cool dark,
and stayed.
"Goodnight, fish."
```

**Prompt**
```
[STYLE] [FORMAT]
Looking down into a dark garden pond at night. One pale koi fish, smoke pink and off
white, is sinking slowly downward into deep indigo water, already half dissolved into
the dark, leaving a few soft rising bubbles. A single wobbling reflection of the moon on
the water surface. [MOMO]'s small round face and [KASA]'s single round eye appear only
as faint reflections at the very top edge of the water. Deep, calm, downward movement.
Darker than every previous page.
The text "One fish went down, down, into the cool dark, and stayed." is written in the
lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 9 — 14 words

**Text**
```
By the door, the other umbrellas were already asleep.
Folded thin.
Leaning close.
```

**Prompt**
```
[STYLE] [KASA] [FORMAT]
A dim Japanese genkan entryway. Four or five old paper umbrellas stand folded thin in a
wooden stand, leaning against one another, each with one closed sleeping eye drawn as a
soft downward crescent line, peaceful and cozy like a family sleeping together. Their
colors are faded dusty rose, pale moss and ash lavender. [KASA] stands nearby, awake,
looking at them fondly with its one open eye. The floating futon with [MOMO] is a soft
blur in the background. Almost no light, only a pale moon slit under the door.
The text "The other umbrellas were already asleep. Folded thin. Leaning close." is
written in the lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 10 — 12 words

**Text**
```
The moon pulled a cloud over its face.
Momo's mouth opened wide -
a big, slow yawn.
```

**Prompt**
```
[STYLE] [MOMO] [FORMAT]
Wide night sky above a dark tiled Japanese roofline. A large soft pale moon is half
covered by a slow drifting cloud shaped like a thin quilt being pulled over a face.
Below, small in the frame, [MOMO] lies on the floating futon with mouth open in a big
slow yawn, eyes squeezed shut, one small fist near the cheek. Sky in deep ash lavender
and smoke grey. Contagious sleepy mood. Very low contrast, no bright highlights.
The text "The moon pulled a cloud over its face." is written in the lower area in a soft
rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 11 — 10 words

**Text**
```
The futon came home
and touched the floor,
soft as snow.
```

**Prompt**
```
[STYLE] [MOMO] [KASA] [FORMAT]
The original tatami bedroom. The floating futon is settling down onto the tatami, a
breath above it, with a few tiny soft white particles drifting around it like slow snow.
[MOMO] lies on it with eyes now half closed, heavy lids, deeply relaxed. [KASA] lowers
its canopy gently over the scene like a soft roof. Almost monochrome ash lavender with
one faint warm off-white glow. Extremely soft edges, everything blurring.
The text "The futon came home and touched the floor, soft as snow." is written in the
lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 12 — 10 words  (guilt-release page)

**Text**
```
Kasa folded down beside the pillow.
"Sleep," said Kasa.
"I will keep the night.
I will keep the big warm one, too."
```

**Prompt**
```
[STYLE] [MOMO] [KASA] [FORMAT]
Close, low, quiet shot at pillow height. [KASA] has folded its canopy half closed and
stands watch beside the pillow like a small night guard, its one round eye open and
softly glowing, calm and steady. [MOMO] sleeps on the futon with eyes closed. Beside
[MOMO], the shoulder and arm of a grown-up lie asleep too, only partly in frame, one
hand resting near the child - the grown-up is asleep first. Kasa watches over BOTH.
Deep gentle indigo darkness, one single soft glow from Kasa's eye. Protective, tender.
The text "'Sleep,' said Kasa. 'I will keep the night. I will keep the big warm one,
too.'" is written in the lower area in a soft rounded handwritten storybook font, warm
off-white.
[NEGATIVE]
```

---

### Page 13 — 8 words  (breath pacer)

**Text**
```
In... and out.
In... and out.
The room breathed with Momo.
```

**Prompt**
```
[STYLE] [FORMAT]
Almost abstract. The dark tatami room seen very softly out of focus, with the shoji
screen glow expanding and contracting like a slow breath, rendered as two overlapping
soft haloes of pale lavender light. [MOMO] is only a small gentle mound under the quilt.
[KASA]'s single eye is a small dim glow at the edge. Nearly monochrome, deep smoke grey
and ash lavender, minimal detail, maximum calm. No sharp edges anywhere.
The text "In... and out. In... and out." is written large, slow and widely spaced in the
lower area in a soft rounded handwritten storybook font, warm off-white.
[NEGATIVE]
```

---

### Page 14 — 3 words  (silence / landing)

**Text**
```
Quiet.
Quiet.
Goodnight.
```

**Prompt**
```
[STYLE] [FORMAT]
Very wide, very dark, very still. The whole tatami room from a distance, almost fully
dark in deep indigo and ash lavender. The futon is a small soft shape. [KASA] is now
fully folded and leaning asleep against the wall, its eye closed as a soft downward
crescent. A single faint moon glow behind the shoji is the only light. Ninety percent of
the frame is quiet empty darkness. Nothing moving. Absolute stillness.
The text "Quiet. Quiet. Goodnight." is written small and centered in the lower area in a
soft rounded handwritten storybook font, warm off-white, with generous space around it.
[NEGATIVE]
```

---

## 5. Production note

Image models render English text well but can still corrupt spelling in longer lines.
Zoom in and proofread every generated page. For any page whose text breaks, regenerate
with the bottom 22% left blank and typeset the line in Kindle Create — in a fixed-layout
book the result is identical.

---

## 6. KDP metadata

### Title candidates

| | Title | Rationale |
|---|---|---|
| A (recommended) | **Kasa Keeps the Night** | Short, memorable, series-ready; "keeps the night" is the promise made to the parent |
| B | Goodnight, Little Umbrella | Leads with "Goodnight" — strongest search behavior among EN-speaking parents |
| C | One Eye, One Moon | Most differentiated and poetic; weakest discoverability, needs the subtitle to carry it |

### Subtitle
A Gentle Japanese Yokai Bedtime Story for Toddlers Ages 2-5 - and for the Tired Grown-Up
Reading It

### Categories (KDP browse nodes)
1. Kindle eBooks > Children's eBooks > Growing Up & Facts of Life > Health > Daily Activities
2. Kindle eBooks > Children's eBooks > Fairy Tales, Folk Tales & Myths > Multicultural
3. Kindle eBooks > Children's eBooks > Literature & Fiction > Family Life > Siblings & Family

Set Age Range 2-5 and Grade Preschool-Kindergarten, or the book drops out of bedtime search.

### Keywords
1. japanese bedtime story for toddlers
2. yokai picture book for kids
3. calming bedtime book 3 year old
4. goodnight story to help child fall asleep
5. japanese folklore children book
6. read aloud bedtime picture book preschool
7. sleepy time story for exhausted parents

### Description (148 words)
```
Some nights, the house just will not go to sleep. And neither will Momo.

Then, in the dark corner of the tatami room, an old paper umbrella opens - slow as a
flower. One round eye. One wooden foot. "I am Kasa," it says. "I keep the night."

Kasa never asks Momo to get up. The futon simply floats, and the sleeping house drifts
past: two teacups, a wind chime that rings once and changes its mind, a fish sinking into
the cool dark, umbrellas already asleep by the door.

With every page the words grow fewer, the light grows softer, and the room grows quieter -
until there is nothing left but breathing.

A hushed Japanese yokai bedtime story in dusty pastel moonlight, written for children ages
2-5 and built for the grown-up holding the book.

And if you fall asleep first? Kasa has the watch.
```

---

## 7. Next step

Generate Page 1 and Page 12 first. Those two test both the world (pastel goth + Japanese
DNA) and character consistency across a wide shot and a close shot before committing to
the full set.
