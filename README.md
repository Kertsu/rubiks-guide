# Rubik's Cube Solving Guide

A beginner-friendly, layer-by-layer method: solve the ⚪️ white layer first, then the MIDDLE layer, then the 🟡 yellow layer. **8 steps. 7 short algorithms.**

---

## Contents

| Step | Goal | Algorithm |
|---|---|---|
| [Step 1: Build the Daisy](#step-1-build-the-daisy) | Four ⚪️ white edges around the 🟡 yellow center | None |
| [Step 2: Make the White Cross](#step-2-make-the-white-cross) | ⚪️ White cross on the BOTTOM | None |
| [Step 3: Solve the White Corners](#step-3-solve-the-white-corners) | Complete the ⚪️ white face | [A: White Corner Trigger](#algorithm-a-white-corner-trigger) |
| [Step 4: Solve the Middle Layer](#step-4-solve-the-middle-layer) | Complete the MIDDLE layer | [B: Insert Edge RIGHT](#algorithm-b-insert-edge-right) · [C: Insert Edge LEFT](#algorithm-c-insert-edge-left) |
| [Step 5: Make the Yellow Cross](#step-5-make-the-yellow-cross) | 🟡 Yellow plus sign on TOP | [D: Yellow Cross](#algorithm-d-yellow-cross) |
| [Step 6: Match the Yellow Edges](#step-6-match-the-yellow-edges) | Cross edges match their centers | [E: Yellow Edge Cycle](#algorithm-e-yellow-edge-cycle) |
| [Step 7: Position the Yellow Corners](#step-7-position-the-yellow-corners) | Corners in their correct spots | [F: Yellow Corner Cycle](#algorithm-f-yellow-corner-cycle) |
| [Step 8: Twist the Yellow Corners](#step-8-twist-the-yellow-corners) | 🟡 Yellow facing UP. Solved! | [G: Yellow Corner Twist](#algorithm-g-yellow-corner-twist) |

**Reference:** [Glossary](#glossary) · [Color Key](#color-key) · [Move Key](#move-key) · [Common Mistakes](#common-mistakes)

---

## How to Read This Guide

### Glossary

- **Center** = one-color square in the middle of a face. Centers never move relative to each other, so each center tells you the color of its face.
- **Edge** = two-color piece (sits between two corners).
- **Corner** = three-color piece (sits where three faces meet).
- **Partner color** = the other color on an edge. For a ⚪️ white edge, it's the non-white color.
- **Slot** = the spot a piece belongs in, decided by the centers it touches.
- **Match** = a sticker is the same color as the center of the face it's on.
- **Positions** = **TOP**, **BOTTOM**, **FRONT** (the face toward you), **BACK**, **LEFT**, **RIGHT**.

### Color Key

Opposite colors sit on opposite faces:

- ⚪️ White ↔ 🟡 Yellow
- 🔴 Red ↔ 🟠 Orange
- 🔵 Blue ↔ 🟢 Green

### Move Key

Every move in this guide is written the same way: **arrow emoji + Turn the + move in bold.**

| Emoji | Move | What it means |
|---|---|---|
| ⬅️ ➡️ | **TOP layer LEFT** / **TOP layer RIGHT** (same for the BOTTOM layer) | The part of that layer closest to you slides toward your LEFT or RIGHT. |
| ⬆️ ⬇️ | **RIGHT side UP** / **RIGHT side DOWN** (same for the LEFT side) | The part of that side closest to you moves UP or DOWN. |
| 🔃 | **FRONT face CLOCKWISE** (same for the BACK face) | Turn the face the way a clock's hands move. |
| 🔄 | **FRONT face COUNTERCLOCKWISE** (same for the BACK face) | Turn the face the opposite way. |

**Rules**

- Every turn is a quarter turn (90°) unless it says **twice** (180°).
- **again** = a repeat of your previous turn of that same layer, side, or face.
- **CLOCKWISE** is judged while looking directly at the face you're turning (for the BACK face, that means from behind).
- **Do NOT rotate the whole cube** in the middle of an algorithm.
- When a step says **Turn the WHOLE cube**, spin it LEFT or RIGHT only, so ⚪️ white stays DOWN and 🟡 yellow stays UP.

---

## Step 1: Build the Daisy

**Goal:** Surround the 🟡 yellow center with four ⚪️ white edges, white stickers facing **UP**, like a 🌼 flower. The yellow center is the middle and the white edges are the petals. Corners don't matter.

**Hold your cube**

- 🟡 Yellow center facing **UP**
- ⚪️ White center facing **DOWN**

**How to build it**

Bring each ⚪️ white edge to the TOP layer with its white sticker facing **UP**. A white edge that's already on TOP with white facing UP is a petal, so leave it.

- **White edge in the MIDDLE layer:** turn the face that shows its non-white sticker, in the direction that lifts the edge UP.
- **White edge in the BOTTOM layer, white sticker facing DOWN:** turn the face its other sticker is on **twice**.
- **White edge in the TOP or BOTTOM layer, white sticker facing a side:** turn the face that shows the white sticker once to move the edge into the MIDDLE layer, then use the first rule.
- **Protect your petals:** before turning a face, turn only the **TOP layer** so no petal sits on that face's top edge.

**Good to know:** the petals' partner colors do **NOT** need to match the centers yet. [Step 2](#step-2-make-the-white-cross) lines them up by turning the TOP layer.

✅ **Check:** Four ⚪️ white edges surround the 🟡 yellow center, all with white facing UP. Then continue to [Step 2: Make the White Cross](#step-2-make-the-white-cross).

[🔝 Back to Contents](#contents)

---

## Step 2: Make the White Cross

**Goal:** Move the ⚪️ white edges down to the ⚪️ white center to form a white cross on the BOTTOM face.

**Hold your cube**

- 🟡 Yellow center facing **UP**
- ⚪️ White center facing **DOWN**

**What to do**

1. Turn only the **TOP layer** until a petal's partner color matches the center directly below it.
2. Turn that face **twice** (180°) to send the petal down to the BOTTOM face. Use the one that applies:
    - ⬇️ Turn the **RIGHT side DOWN** twice.
    - ⬇️ Turn the **LEFT side DOWN** twice.
    - 🔃 Turn the **FRONT face CLOCKWISE** twice.
    - 🔃 Turn the **BACK face CLOCKWISE** twice.
3. Repeat for the remaining petals until all four are down. If several petals already line up with their centers, send them down one after another.

✅ **Check:** A ⚪️ white cross on the BOTTOM face, and each white edge's partner color matches the center on its side face. Then continue to [Step 3: Solve the White Corners](#step-3-solve-the-white-corners).

[🔝 Back to Contents](#contents)

---

## Step 3: Solve the White Corners

**Goal:** Complete the entire ⚪️ white face (all four white corners on the BOTTOM) so the side colors line up with their centers.

**Hold your cube**

- ⚪️ White cross facing **DOWN**
- 🟡 Yellow center facing **UP**

(After Step 2 it should already be this way. If not, flip the cube.)

**What to do**

1. **Find a white corner.** Look at the TOP layer for a corner with ⚪️ white plus two other colors. Example: ⚪️ White + 🟠 Orange + 🟢 Green. That corner belongs at the BOTTOM, between the 🟠 orange and 🟢 green centers.
2. **Line it up.** Turn only the **TOP layer** until the corner is directly above its slot.
3. **Turn the WHOLE cube** so that corner sits at the **TOP FRONT-RIGHT** (closest to you, on your right).
4. **Do [Algorithm A: White Corner Trigger](#algorithm-a-white-corner-trigger)** and repeat it until the corner is correctly placed, with its ⚪️ white sticker facing **DOWN**. It may take several repetitions (up to 5). Always finish all 4 moves before checking.
5. **Repeat** with the next white corner until the white face is finished.
6. **No white corner on TOP?** See [Stuck White Corner](#stuck-white-corner).

### Algorithm A: White Corner Trigger

Hold the cube still. Don't rotate it.

1. ⬆️ Turn the **RIGHT side UP**.
2. ⬅️ Turn the **TOP layer LEFT**.
3. ⬇️ Turn the **RIGHT side DOWN**.
4. ➡️ Turn the **TOP layer RIGHT**.

### Stuck White Corner

A white corner can be stuck in the BOTTOM layer in the wrong slot or twisted. To free it:

1. Turn the **WHOLE cube** so the stuck corner sits at the **BOTTOM FRONT-RIGHT** (closest to you, on your right).
2. Do [Algorithm A: White Corner Trigger](#algorithm-a-white-corner-trigger) **once**. The corner pops up to the TOP layer.
3. Go back to the **What to do** list in [Step 3](#step-3-solve-the-white-corners).

✅ **Check:** The whole ⚪️ white face is solid, and the bottom row of each side matches its center. Then continue to [Step 4: Solve the Middle Layer](#step-4-solve-the-middle-layer).

[🔝 Back to Contents](#contents)

---

## Step 4: Solve the Middle Layer

**Goal:** Fill the MIDDLE layer so every edge there matches the centers on both sides. The ⚪️ white face stays complete.

**Hold your cube**

- ⚪️ White face facing **DOWN**
- 🟡 Yellow center facing **UP**
- Any other color facing **YOU**

**What to do**

1. **Find an edge.** Look at the TOP layer for an edge (two colors, not a corner) with **NO 🟡 yellow** on either side. Example: an edge that's 🟠 orange and 🟢 green.
2. **Match one color.** Turn only the **TOP layer** until the sticker facing you matches the center directly below it. Example: 🟠 orange on the piece and a 🟠 orange center below it. Don't turn the whole cube yet.
3. **Choose the direction.** Look at the sticker on the TOP face and see which side center it matches:
    - Matches the **RIGHT** center → do [Algorithm B: Insert Edge RIGHT](#algorithm-b-insert-edge-right).
    - Matches the **LEFT** center → do [Algorithm C: Insert Edge LEFT](#algorithm-c-insert-edge-left).
4. **Repeat** with the next edge until the MIDDLE layer is full.
5. **No edge without yellow on TOP?** See [Stuck Middle Layer Edge](#stuck-middle-layer-edge).

### Algorithm B: Insert Edge RIGHT

Hold the cube still. Don't rotate it.

1. ⬅️ Turn the **TOP layer LEFT**.
2. ⬆️ Turn the **RIGHT side UP**.
3. ➡️ Turn the **TOP layer RIGHT**.
4. ⬇️ Turn the **RIGHT side DOWN**.
5. ➡️ Turn the **TOP layer RIGHT** again.
6. 🔄 Turn the **FRONT face COUNTERCLOCKWISE**.
7. ⬅️ Turn the **TOP layer LEFT**.
8. 🔃 Turn the **FRONT face CLOCKWISE**.

### Algorithm C: Insert Edge LEFT

Hold the cube still. Don't rotate it.

1. ➡️ Turn the **TOP layer RIGHT**.
2. ⬆️ Turn the **LEFT side UP**.
3. ⬅️ Turn the **TOP layer LEFT**.
4. ⬇️ Turn the **LEFT side DOWN**.
5. ⬅️ Turn the **TOP layer LEFT** again.
6. 🔃 Turn the **FRONT face CLOCKWISE**.
7. ➡️ Turn the **TOP layer RIGHT**.
8. 🔄 Turn the **FRONT face COUNTERCLOCKWISE**.

### Stuck Middle Layer Edge

If **all 4 edges on the TOP layer have 🟡 yellow** but the MIDDLE layer isn't finished, that's completely normal. The pieces you need are already in the MIDDLE layer, just in the wrong slot or flipped. Take one out first:

1. Look at the MIDDLE layer and find an edge whose colors **don't match** the centers beside it.
2. Turn the **WHOLE cube** so that edge sits at the **FRONT-RIGHT** of the MIDDLE layer.
3. Do [Algorithm B: Insert Edge RIGHT](#algorithm-b-insert-edge-right) **once**. The edge pops out to the TOP layer. It's okay if another wrong edge takes its place.
4. Go back to the **What to do** list in [Step 4](#step-4-solve-the-middle-layer).

✅ **Check:** The ⚪️ white face and the MIDDLE layer are solved, so the bottom two layers match their centers on every side. Then continue to [Step 5: Make the Yellow Cross](#step-5-make-the-yellow-cross).

[🔝 Back to Contents](#contents)

---

## Step 5: Make the Yellow Cross

**Goal:** A 🟡 yellow plus sign (+) on the TOP face. Ignore the corners, since they can be any color.

**Hold your cube**

- 🟡 Yellow center facing **UP**
- ⚪️ White face facing **DOWN**

**What to do**

Look at the 🟡 yellow edges on the TOP face, find your pattern, and repeat until you have the plus sign:

| What you see on TOP | What to do |
|---|---|
| A 🟡 plus sign (+) | You're done. Go to [Step 6](#step-6-match-the-yellow-edges). |
| Only the 🟡 center (a **dot**) | Do [Algorithm D](#algorithm-d-yellow-cross) once. You'll get an **L shape**. |
| Two **touching** 🟡 edges (an **L shape**) | Turn the **WHOLE cube** so the two yellow edges are at the **BACK** and **LEFT**. Do [Algorithm D](#algorithm-d-yellow-cross). You'll get a **line**. |
| Two **opposite** 🟡 edges (a straight **line**) | Turn the **WHOLE cube** so the line runs **LEFT to RIGHT**. Do [Algorithm D](#algorithm-d-yellow-cross). You'll get the **plus sign**. |

### Algorithm D: Yellow Cross

Hold the cube still. Don't rotate it.

1. 🔃 Turn the **FRONT face CLOCKWISE**.
2. ⬆️ Turn the **RIGHT side UP**.
3. ⬅️ Turn the **TOP layer LEFT**.
4. ⬇️ Turn the **RIGHT side DOWN**.
5. ➡️ Turn the **TOP layer RIGHT**.
6. 🔄 Turn the **FRONT face COUNTERCLOCKWISE**.

✅ **Check:** A 🟡 yellow plus sign (+) on the TOP face. Don't turn anything else yet. Then continue to [Step 6: Match the Yellow Edges](#step-6-match-the-yellow-edges).

[🔝 Back to Contents](#contents)

---

## Step 6: Match the Yellow Edges

**Goal:** Each edge of the 🟡 yellow cross has a partner color that matches the center below it (the FRONT edge matches the FRONT center, and so on).

**Hold your cube**

- 🟡 Yellow center facing **UP**
- ⚪️ White face facing **DOWN**

**What to do**

1. Turn only the **TOP layer** until as many cross edges as possible match the centers below them.
2. Find your case:

| What you see | What to do |
|---|---|
| All 4 edges match | Done! Go to [Step 7](#step-7-position-the-yellow-corners). |
| 2 edges match and they're **next to each other** | Turn the **WHOLE cube** so the two matched edges are at the **BACK** and **RIGHT**. Do [Algorithm E](#algorithm-e-yellow-edge-cycle). Then turn the **TOP layer** until all 4 edges match. |
| Only 1 edge matches, or 2 match but they're **opposite** each other | Do [Algorithm E](#algorithm-e-yellow-edge-cycle) once (from any position), turn the **TOP layer** until as many edges as possible match, then compare again. |

Repeat until all 4 edges match. Your yellow corners may look scrambled. That's normal, and we fix them in [Step 7](#step-7-position-the-yellow-corners) and [Step 8](#step-8-twist-the-yellow-corners).

### Algorithm E: Yellow Edge Cycle

Hold the cube still. Don't rotate it.

1. ⬆️ Turn the **RIGHT side UP**.
2. ⬅️ Turn the **TOP layer LEFT**.
3. ⬇️ Turn the **RIGHT side DOWN**.
4. ⬅️ Turn the **TOP layer LEFT** again.
5. ⬆️ Turn the **RIGHT side UP**.
6. ⬅️ Turn the **TOP layer LEFT** twice.
7. ⬇️ Turn the **RIGHT side DOWN**.

✅ **Check:** All four 🟡 yellow cross edges match their centers: FRONT edge to FRONT center, RIGHT to RIGHT, BACK to BACK, LEFT to LEFT. Then continue to [Step 7: Position the Yellow Corners](#step-7-position-the-yellow-corners).

[🔝 Back to Contents](#contents)

---

## Step 7: Position the Yellow Corners

**Goal:** Every 🟡 yellow corner sits in its correct slot. The yellow sticker does **NOT** need to face UP yet.

**How to check a corner:** its three colors match the three centers it touches (🟡 yellow plus the two side centers). Example: a corner that's 🟡 yellow + 🔴 red + 🔵 blue belongs between the 🔴 red and 🔵 blue centers.

**Hold your cube**

- 🟡 Yellow center facing **UP**
- ⚪️ White face facing **DOWN**

**What to do**

1. Look for a corner that's already in its correct slot.
2. If you found one, turn the **WHOLE cube** so it sits at the **TOP FRONT-RIGHT** (closest to you, on your right). If none is correct, hold the cube any way you like.
3. Do [Algorithm F: Yellow Corner Cycle](#algorithm-f-yellow-corner-cycle).
4. Check the corners again. Repeat steps 1 to 3 until all four corners are in their correct slots.

### Algorithm F: Yellow Corner Cycle

Hold the cube still. Don't rotate it. The TOP FRONT-RIGHT corner stays put while the other three corners cycle around it.

1. ⬅️ Turn the **TOP layer LEFT**.
2. ⬆️ Turn the **RIGHT side UP**.
3. ➡️ Turn the **TOP layer RIGHT**.
4. ⬆️ Turn the **LEFT side UP**.
5. ⬅️ Turn the **TOP layer LEFT**.
6. ⬇️ Turn the **RIGHT side DOWN**.
7. ➡️ Turn the **TOP layer RIGHT**.
8. ⬇️ Turn the **LEFT side DOWN**.

✅ **Check:** Every corner sits between its three matching centers, even if the yellow stickers point in different directions. Then continue to [Step 8: Twist the Yellow Corners](#step-8-twist-the-yellow-corners).

[🔝 Back to Contents](#contents)

---

## Step 8: Twist the Yellow Corners

**Goal:** All four 🟡 yellow corners have their yellow sticker facing **UP**. The cube will look scrambled while you work. That's normal, and it comes back together at the end.

**Hold your cube**

- 🟡 Yellow center facing **UP**
- ⚪️ White face facing **DOWN**
- Any side facing **YOU**. Then **do not rotate the whole cube** until this step is finished.

**What to do**

1. Bring a corner whose 🟡 yellow sticker is **not** facing UP to the **TOP FRONT-RIGHT**. A corner that already has yellow facing UP is finished, so skip it.
2. Do [Algorithm G: Yellow Corner Twist](#algorithm-g-yellow-corner-twist) and repeat it until that corner's 🟡 yellow sticker faces **UP** (usually 2 or 4 times). Always finish all 4 moves.
3. Turn **ONLY the TOP layer LEFT** until the next corner with 🟡 yellow NOT facing UP reaches the TOP FRONT-RIGHT. You can turn more than once.
4. Repeat steps 2 and 3 for every unfinished corner.
5. When all four corners have 🟡 yellow facing UP, turn the **TOP layer** until every side lines up with its centers.

**⚠️ Very important**

- Don't rotate the whole cube.
- Don't try to repair the scrambled MIDDLE or BOTTOM layers.
- Don't stop halfway through the 4 moves.
- Keep the same side facing **YOU**, even when the TOP layer turns.

### Algorithm G: Yellow Corner Twist

1. ⬇️ Turn the **RIGHT side DOWN**.
2. ⬅️ Turn the **BOTTOM layer LEFT**.
3. ⬆️ Turn the **RIGHT side UP**.
4. ➡️ Turn the **BOTTOM layer RIGHT**.

✅ **Check:** Every face is a single solid color. 🎉 **Your cube is solved!**

[🔝 Back to Contents](#contents)

---

## Common Mistakes

- Turning the **WHOLE cube** in the middle of an algorithm.
- Mixing up directions. UP, DOWN, LEFT, and RIGHT always describe the part **closest to you**.
- Stopping an algorithm halfway.
- Judging CLOCKWISE from the wrong angle. Look directly at the face you're turning.
- Moving on before the ✅ **Check** of the previous step is true.
- Feeling lost? Re-hold the cube with ⚪️ white DOWN and 🟡 yellow UP, then compare it to the last ✅ **Check** you passed.

[🔝 Back to Contents](#contents)
