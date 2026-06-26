# Proportions in Floor Planning: The Module and the Golden Ratio

A maximally detailed beginner's guide: how to get a proportional furniture layout using
a **module** and the **golden ratio**. With full theory, a working algorithm, a 65 m²
apartment example, and text schematics of the rooms.

---

## Part 1. Why proportions matter at all

The human eye loves **repeating rhythm** and **related sizes**. When everything in a
room drifts — a 195 cm sofa, a 210 cm rug, a 78 cm walkway, a 64 cm picture — it feels
chaotic, even though each item is fine on its own. When sizes are tied together by a
single rule, the brain reads it as order: "expensive and calm."

There are two tools for tying sizes together:

1. **The module** — you take one size as a "brick" and make everything else a multiple
   of it.
2. **The golden ratio** — you relate sizes through the magic number 1.618.

These don't contradict each other. The module is about **rhythm and multiples**; the
golden ratio is about **dividing a whole into pleasing parts**. They work strongest
together.

---

## Part 2. The module — the simplest and most reliable tool

### The idea
A module is the **base unit of measurement for your project**. Like a square on graph
paper. Everything on the sheet is placed along the squares, so everything "gets along."

Architecture has always worked this way: for the Greeks the module was the radius of a
column; for Le Corbusier it was the height of a person with a raised arm (his "Modulor"
system).

### How to choose a module for an apartment
The module should be **tied to the human body and to furniture**, not pulled from thin
air. Good candidates:

| Module | Size | Origin |
|---|---|---|
| Walkway width for 1 person | **60 cm** | anthropometry |
| Comfortable walkway | **90 cm** | anthropometry |
| Cabinet / seat depth | **60 cm** | furniture standard |
| Tile / floorboard width | e.g. **30 cm** | finishes |

A very convenient practical module for housing is **60 cm** (with its half 30 and its
double 120). Why: almost all furniture is built on it (kitchens, cabinets, countertops
come in steps of 60), and it matches the width of a person in a walkway.

### How to use it
Imagine the floor is ruled with a **60 × 60 cm** grid. Then:
- walkway = 1 module (60) minimum, better 1.5 (90)
- sofa depth = 1.5 modules (90)
- dining table = 1.5 × 2 modules (90 × 120)
- rug = a multiple of the grid (180 × 240 = 3 × 4 modules)
- room zones are "cut" along the grid lines

**Effect:** furniture lands without odd offcuts and crooked leftovers; walkways become
meaningful rather than "whatever's left."

> 📐 Beginner's rule: **first draw the grid, then place furniture along the lines**, not
> the other way around.

---

## Part 3. The golden ratio — for beautiful division

### The idea in one picture
Take a segment and divide it so that **the smaller part relates to the larger part as
the larger part relates to the whole**. That division is the golden ratio, and its
coefficient is:

**φ ≈ 1.618**

In practice you only need to remember this:
- to get the larger part — **multiply by 0.618**
- to get the smaller part — **multiply by 0.382**
- (0.618 + 0.382 = 1 — that's the division of a whole into two golden parts)

### A division example
A wall **4 meters (400 cm)** long. Where do you hang the point of interest (a picture,
a TV, a headboard)?
- 400 × 0.618 = **247 cm** from one edge
- so the second part = 153 cm

Not in the center (200/200 — boring, "institutional"), but at the golden point 247/153 —
lively and yet balanced.

### Where the golden ratio is genuinely useful in an apartment
- **dividing a room into zones** (living area / dining area in one room)
- **the proportions of the room itself** (an ideal room is not a square but ~1:1.6 →
  e.g. 3.1 × 5.0 m)
- **the hanging height of decor, the rug size relative to the zone, the aspect ratio of
  a table**
- **facade layout, splitting a wall into top / bottom**

### An easier-to-compute relative — the Fibonacci sequence
Numbers where each = the sum of the two before it:
**1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233 …**

Adjacent numbers give nearly the golden ratio (8/5 = 1.6; 13/8 = 1.625). The convenience:
they're **whole numbers**, easy to think with "by eye." You can use them directly as
centimeters × 10:
- 55, 89, 144, 233 cm → ready-made "golden" sizes for a rug, a walkway, a table, a sofa.

---

## Part 4. How to combine both methods — the working algorithm

The step-by-step process as it's done in practice.

### Step 0. Get exact dimensions
You need a **scaled plan** with the real sizes of every room (length × width), the
positions of windows, doors, and wet points (risers). Without this, proportions are
fantasy.

### Step 1. Choose the module
For housing use **M = 60 cm** (with its fractions 30 and 120). Rule the whole plan with
a 60 × 60 grid.

### Step 2. Assign functional zones by the golden division
Divide a long wall / room not in half, but in the ratio 0.618 / 0.382.

### Step 3. Place furniture as multiples of the module
Round each item to the nearest multiple of 60 (or to a Fibonacci number).

### Step 4. Check the walkways
Main walkways ≥ 90 cm (1.5 M), secondary ones ≥ 60 cm (1 M).

### Step 5. Tie the decor to the golden ratio
Picture heights, rug size, points of interest — at the golden points.

---

## Part 5. Example: a 65 m² apartment

Suppose the layout is as follows (realistic numbers, **replace with your own**):

```
Living-kitchen (studio)   5.0 × 4.2 m  = 21 m²
Bedroom                   3.6 × 3.4 m  = 12 m²
Kids' room / study        3.0 × 3.2 m  ≈ 10 m²
Entryway + corridor                    ≈ 8 m²
Bathroom + WC                          ≈ 6 m²
Balcony / loggia                       ≈ 4 m²
Walls / partitions                     ≈ 4 m²
                                  total ≈ 65 m²
```

### Living-kitchen 5.0 × 4.2 m — breakdown

**1) Divide the 5.0 m length by the golden ratio into zones:**
- 500 × 0.618 = **309 cm** → living zone ≈ 3.1 m
- remainder **191 cm** → kitchen / dining zone ≈ 1.9 m

So the zone boundary is not in the center, but at the 3.1 m mark. Round to the grid:
**300 cm / 200 cm** (5 modules and ~3.3 modules). We got a golden division aligned to
the module — ideal.

**2) Place furniture by the module M = 60:**

| Item | Size | In modules | Logic |
|---|---|---|---|
| Sofa | 240 × 90 | 4 × 1.5 | the base of the living zone |
| Rug under the sofa | 240 × 180 | 4 × 3 | repeats the sofa width |
| TV unit | 180 × 45 | 3 × 0.75 | opposite the sofa |
| Sofa↔TV distance | 240 | 4 | comfortable for the eyes |
| Dining table | 120 × 80 | 2 × 1.3 | in the kitchen zone |
| Kitchen front | 300 | 5 | standard kitchen step |
| Main walkway | 90–100 | 1.5 | along the zone |

**3) The golden ratio in the details:**
- Picture / panel above the sofa: width = sofa width × 0.618 = 240 × 0.618 ≈ **148 cm**
  (≈ 150). Looks "right" — not full-wall and not tiny.
- Height of the picture's center above the floor: 150 cm (eye level) — or, dividing a
  2.7 m wall by the golden ratio: 270 × 0.618 = 167 cm for the upper zone.

**ASCII schematic:**

```
 window                        window
══════════════════╗      ╔═══════════════
                  ║      ║
   ┌────────────┐ │      │  ┌──────────┐
   │   SOFA      │ │      │  │ KITCHEN  │   kitchen front
   │  240 × 90   │ │      │  │  300 cm  │   along the wall
   └────────────┘ │      │  └──────────┘
   ░░░░░░░░░░░░░░  │      │      ║ 60 ║
   ░ RUG 240×180 ░│      │   ┌────────┐
   ░░░░░░░░░░░░░░  │      │   │ TABLE  │  120×80
        ▲         │      │   │ ●  ●   │  4 chairs
     240 walkway  │      │   │ ●  ●   │
        ▼         │      │   └────────┘
   ┌────────────┐ │      │
   │ TV 180×45  │ │      │
   └────────────┘ │      │
 door ───────────────────────────────────
   ◄──── 3.0 m (living) ────►◄─ 2.0 m ─►
   ◄──────────── 5.0 m ─────────────────►
```

### Bedroom 3.6 × 3.4 m — breakdown
- Place a 160 × 200 bed centered on the long wall.
- Walkways on either side of the bed: (360 − 160) / 2 = **100 cm** each — excellent
  (≥ 1.5 M).
- Bedside tables 45–50 cm (≈ module / 1.2).
- A wardrobe 60 cm deep (1 M) along the end wall, width a multiple of 60 → 180 or 240.
- Golden division of the wall behind the headboard: accent zone = wall width × 0.618.

**ASCII schematic:**

```
 ════════ window ═══════
 ┌──────────────────────┐
 │ ▒▒▒  WARDROBE 240×60 ▒│  depth 1 M
 ├──────────────────────┤
 │                      │
 │  100   ┌──────┐  100 │  walkways of 1.5 M
 │ ◄───►  │  BED  │ ◄───►│
 │ ┌──┐   │160×200│  ┌──┐│
 │ │bt│   │       │  │bt││  bedside tables 45 cm
 │ └──┘   │       │  └──┘│
 │        └──────┘      │
 │   ░░ runner rug ░░░░░ │
 │                      │
 └────────── door ──────┘
   ◄──────── 3.6 m ──────►
```

### Kids' room / study 3.0 × 3.2 m — breakdown
- All furniture 60 cm deep (1 M): desk, shelving, loft bed.
- Arrange around the perimeter, keep the center free at least 90 × 90 (1.5 × 1.5 M)
  for play / an armchair.

**ASCII schematic:**

```
 ═══════ window ═══════
 ┌──────────────────┐
 │ ┌────┐  ┌───────┐│
 │ │DESK│  │SHELVES ││  desk 120×60
 │ │120 │  │180×40  ││  shelving 3 M
 │ └────┘  └───────┘│
 │                  │
 │   free center    │  center ≥ 90×90
 │   90×90          │  (1.5 × 1.5 M)
 │                  │
 │ ┌──────────────┐ │
 │ │  BED 90×200   │ │  against the wall, 1.5 M
 │ └──────────────┘ │
 └─────── door ─────┘
   ◄────── 3.0 m ─────►
```

### How to read the schematics
- `║ ═ ┌┐└┘` — walls and furniture
- `░ ▒` — rugs / wardrobes
- `◄──►` — control walkways (always check ≥ 90 cm main, ≥ 60 cm secondary)
- numbers — real centimeters, all multiples of the 60 module

---

## Part 6. The cheat sheet to keep at hand

**Module:**
- M = 60 cm. Derivatives: 30 / 60 / 90 / 120 / 180 / 240.
- Everything a multiple of M. Walkway ≥ 1.5 M (90 cm).

**Golden ratio:**
- Larger part = whole × **0.618**
- Smaller part = whole × **0.382**
- Ideal proportion of a room / table / rug ≈ **1 : 1.6**
- Put the point of interest at 0.618 of the length, not in the center.

**Fibonacci (cm):**
- 55 · 89 · 144 · 233 — ready-made "beautiful" sizes.

**Order of actions:**
1. Exact plan with dimensions →
2. 60 × 60 grid →
3. divide zones by the golden ratio (0.618 / 0.382) →
4. place furniture as multiples of the module →
5. check walkways (≥ 90 cm) →
6. tie decor to the golden ratio.

---

## Part 7. Common beginner mistakes

- **Computing proportions before measuring.** First the exact plan, then the beauty.
- **Dividing everything in half.** The center is "institutional." The golden point is
  livelier.
- **Fanaticism about φ.** The golden ratio is a guideline, not a law. If 0.618 gives a
  78 cm walkway — round up to the 90 module; comfort beats the formula.
- **Forgetting about the human.** Check every beautiful size with your body: can you get
  through, can you reach, won't you bang your knees.
- **Mixing too many modules.** One main module per apartment. Not "60 here, 45 there,
  50 over there."

---

## What's needed to plan your actual apartment

1. **The size of each room** (length × width), at least approximately.
2. Where the **windows and doors** are (on which wall).
3. Where the **risers / wet points** are (kitchen, bathroom are hard to move).
4. Which **furniture is mandatory** (sofa, bed size, desk, etc.).

Best of all — a photo of the floor plan or your sketch with numbers. Then each room can
be laid out on the grid and golden points with concrete centimeters.
