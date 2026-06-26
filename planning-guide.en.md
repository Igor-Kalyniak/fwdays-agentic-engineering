# Proportions in Floor Planning: The Apartment's Module and the Golden Ratio

A maximally detailed guide: how to organize space in 3D (length × width × **height**)
through a **module derived from the apartment itself** and the **golden ratio**. With no
attachment to the standard "60" — the module is computed from the real dimensions and
openings.

---

## Part 0. This apartment's source data (client's comments)

> These data are the basis of all calculations below.

- Total area: **65 m²**
- **Ceiling height: 2800 mm**
- **Height of all openings (doors/windows): 2100 mm** — a mandatory constraint;
  everything aligns to this line.

Rooms:

| Room | Area | Wall lengths | Note |
|---|---|---|---|
| Tambour / corridor | 8.9 m² | — | part goes to expanding the walk-in closet |
| Kitchen-living | 18.7 m² | 4440 × 3910 | |
| Balcony / study | — | — | not counted anywhere, assigned to the bedroom |
| Bedroom | 15.8 m² | 4870 × 3260 | + balcony/study |
| Kids' room | 11.9 m² | 3330 × 3570 | |
| Bathroom | 5.5 m² | — | |
| Walk-in closet | 2.2 m² | — | expands at the corridor's expense |

> ⚠️ **Forget about module = 60 cm.** Below, the module is derived from the ceiling and
> openings of this specific apartment.

---

## Part 1. Why proportions matter

The human eye loves **repeating rhythm** and **related sizes**. When everything drifts
(a 195 sofa, a 210 rug, a 78 walkway, a 2050 opening, a shelf at 1630) it feels chaotic.
When sizes are tied by a single rule, the brain reads it as "expensive and calm."

Two tools to tie sizes together:

1. **The module** — one size as a "brick," everything else a multiple of it. Works in
   3D: across the floor (length/width) and up the height.
2. **The golden ratio** — dividing a whole into pleasing parts via the number 1.618.

The module gives **rhythm and multiples**; the golden ratio gives **beautiful division**.
Together they're strongest.

---

## Part 2. THIS apartment's module — how it's derived

### Principle: the module comes from the apartment itself
The module must "live" inside your walls. The hardest, unchangeable vertical dimensions
are the **ceiling height (2800)** and the **opening height (2100)**. Find their common
divisor and you get a module that reconciles both the ceiling and every door/window.

### The calculation
The greatest common divisor of 2800 and 2100:

```
2800 = 4 × 700
2100 = 3 × 700
GCD(2800, 2100) = 700
```

### 🎯 The apartment's module: **M = 700 mm**

Derivatives (the project's working "ruler"):

| Notation | Size | Where to use |
|---|---|---|
| ¼M | **175 mm** | fine adjustment, thickness/offsets |
| ½M | **350 mm** | furniture depths/widths, fine grid |
| **M** | **700 mm** | base step, comfortable 1-person walkway |
| 1.5 M | **1050 mm** | wide walkway, 0.9 bed |
| 2 M | **1400 mm** | table, TV zone, bed zone |
| 3 M | **2100 mm** | = opening height, sofa/bed length |
| 4 M | **2800 mm** | = ceiling height, large zone |

**Why 700 is a good horizontal step too:** 700 mm = a comfortable walkway for one
person; ½M = 350 covers furniture depths; a bed 2000 ≈ 3M; a sofa 2100 = 3M.

> 📐 This is the apartment's "single cell" — **700 × 700 × 700 mm** in space.

---

## Part 3. The vertical — what people forget (openings and height)

The 700 module divides the 2800 height into exactly **4 bands**, and the 2100 opening
line lands precisely on the boundary of the 3rd band. This gives a ready-made height
system for the whole apartment:

```
2800 ┌────────────────────────────┐ ── 4M ── CEILING
     │  CROWN   2100–2800 (1M)     │  antresols, cabinet tops, curtain pelmet, lighting
2100 ├────────────────────────────┤ ── 3M ── OPENING HEADS (all doors/windows)
     │  UPPER   1400–2100 (1M)     │  upper kitchen cabinets, pictures (center ~1500)
1400 ├────────────────────────────┤ ── 2M
     │  MID      700–1400 (1M)     │  table 750, counter 900, sill, switches
 700 ├────────────────────────────┤ ── 1M
     │  BASE       0–700 (1M)      │  seats, low drawers, sockets
   0 └────────────────────────────┘ ── 0 ─── FLOOR
```

What this gives in practice:
- **All openings 2100 = 3M** — a single upper line for doors and windows across the
  whole apartment.
- **Exactly 1M (700) above an opening** — a band for antresols, tops of tall cabinets,
  curtain pelmets and lighting. Tall cabinets go to the ceiling (4M), upper kitchen
  cabinets to the opening line (3M = 2100), and everything matches.
- **Sills, countertops, pictures** are tied to band boundaries (2M = 1400 — bottom of
  upper cabinets; ~1500 — picture center; 1M = 700 — bottom of the mid tier).
- For fine tuning (counter 900, table 750) use ½M = 350 — yielding 8 bands of 350.

> Rule: **pull the top of any tall item either to 3M (2100, like an opening) or to 4M
> (2800, ceiling).** Intermediate "unfinished" heights are the main source of visual
> clutter.

---

## Part 4. The golden ratio — for dividing zones

### The idea
Divide a segment so the smaller part relates to the larger as the larger to the whole.
Coefficient **φ ≈ 1.618**. In practice:
- larger part = whole × **0.618**
- smaller part = whole × **0.382**

### The link to the module
First divide the zone by the golden ratio, then **round the boundary to the nearest
700/350 grid line**. This gives both a "lively" division and module multiples.

### Where to apply it in the apartment
- dividing the kitchen-living room into "living / kitchen" zones;
- the accent zone behind the headboard / behind the sofa;
- rug size relative to the zone, the aspect ratio of a table;
- splitting a wall by height (together with the bands from Part 3).

### Fibonacci (as a backup "golden" sequence)
`… 13, 21, 34, 55, 89, 144, 233 …` — adjacent numbers ≈ 1.6. Handy as ready sizes in
cm: 55, 89, 144, 233.

---

## Part 5. The working algorithm

1. **Fix the hard constraints:** height 2800, openings 2100, real wall lengths.
2. **Module:** M = 700 (from GCD 2800/2100). Fractions ½M=350, ¼M=175.
3. **Vertical:** mark out the 4 bands of 700 (Part 3), tie all heights to them.
4. **Plan:** rule the floor with a 700 × 700 grid (350 × 350 for fine detail).
5. **Zones:** divide by the golden ratio (0.618 / 0.382), round the boundary to a grid
   line.
6. **Furniture:** lengths and walkways — multiples of M; depths — by ergonomics (see
   below), position faces and gaps on the grid.
7. **Walkways:** main ≥ 1M (700), better 1.5M (1050); secondary ≥ ½M+ (≈600).
8. **Pull tops of items** to 3M (2100) or 4M (2800).

> On furniture depths: industry standards (kitchen/wardrobe 600, sofa seat depth ~900)
> are kept for ergonomics, but **placed so that lengths, gaps and walkways land on the
> 700/350 grid**. The module governs structure and heights; ergonomics govern depths.

---

## Part 6. Room-by-room breakdown (real dimensions)

### 6.1. Kitchen-living 4440 × 3910 (18.7 m²)

**Golden zoning of the long 4440 wall:**
- 4440 × 0.618 = **2744** → living; round to grid → **2800 (4M)**
- remainder **1640** (≈ 2.3M) → kitchen

**Vertical:** upper kitchen cabinets bottom 1400 (2M) — top 2100 (3M, like an opening);
above them to the ceiling an antresol 700 (1M). Counter 900 (on the ½M grid).

```
 window                            window
══════════════════╗          ╔════════════════
                  ║          ║  KITCHEN (1640)
   ┌────────────┐ ║          ║  ┌───────────┐
   │   SOFA       │║          ║  │ front 2100 │ cabinet top = 3M
   │  2100 × 900  │║          ║  │ (3M)       │ cabinet bottom = 2M
   └────────────┘ ║          ║  └───────────┘
   ░░░░░░░░░░░░░░  ║          ║   counter 900
   ░ RUG          ░║          ║  ┌────────┐
   ░ 2100 × 1400 ░ ║          ║  │ TABLE  │ 1400×700 (2M×1M)
   ░ (3M × 2M)    ░║          ║  │ ● ●    │ 4 chairs
   ░░░░░░░░░░░░░░  ║          ║  │ ● ●    │
        ▲         ║          ║  └────────┘
     1400 (2M)    ║          ║
        ▼         ║          ║
   ┌────────────┐ ║          ║
   │ TV 1400(2M)│ ║          ║
   └────────────┘ ║          ║
 door (2100=3M)───────────────────────────────
   ◄──── 2800 (living, 4M) ──►◄─ 1640 ─►
   ◄─────────────── 4440 ───────────────►
```

### 6.2. Bedroom 4870 × 3260 (15.8 m², + balcony/study)

- Bed **1600 × 2000** (≈ 3M long) with the headboard against the 3260 wall.
- Side walkways: (3260 − 1600) / 2 = **830** each (comfortably free).
- Wardrobe 600 deep along the end wall, height to the ceiling **2800 (4M)**, facades
  split into 2M + 1M (lower part / antresol above the opening line).
- The balcony/study joins at the end — a work zone by the window, counter 900.
- Accent behind the headboard = 3260 × 0.618 ≈ **2015**, centered on the bed.

```
 ════════ window ═════════
 ┌─────────────────────────┐
 │ ▒▒▒ WARDROBE to 2800(4M)▒│  depth 600
 ├─────────────────────────┤
 │   accent 2015 (0.618)    │
 │  830  ┌─────────┐  830   │
 │ ◄──►  │   BED    │ ◄──►   │
 │ ┌──┐  │1600×2000 │  ┌──┐  │  bedside tables 350 (½M)
 │ │bt│  │ (≈3M)    │  │bt│  │
 │ └──┘  │          │  └──┘  │
 │       └─────────┘        │
 │  ░░ runner rug ░░░░░░░░░  │
 └──────── door (3M) ───────┘
   ◄────────── 3260 ─────────►   (room depth 4870)
```

### 6.3. Kids' room 3330 × 3570 (11.9 m²)

- Nearly square → keep the center free **1050 × 1050 (1.5M × 1.5M)**.
- Bed 900 × 2000 (0.9 ≈ 1.5M wide) along a wall.
- Desk 1200 × 600 by the window (counter 750, on the ½M grid).
- Shelving 1050 (1.5M) wide, height to 2100 (3M, opening line) + antresol to 2800.

```
 ═══════ window ═══════
 ┌──────────────────┐
 │ ┌────┐  ┌───────┐│
 │ │DESK│  │SHELVES ││ desk 1200×600
 │ │1200│  │to 3M   ││ shelving 1050(1.5M)
 │ └────┘  └───────┘│
 │                  │
 │  free center     │ 1050×1050
 │   1050 × 1050    │ (1.5M × 1.5M)
 │                  │
 │ ┌──────────────┐ │
 │ │  BED 900      │ │ ×2000, against the wall
 │ └──────────────┘ │
 └─────── door ─────┘
   ◄────── 3570 ─────►   (3330 on the other wall)
```

### 6.4. Tambour/corridor 8.9 m² + walk-in closet 2.2 m²

- The closet **expands at the corridor's expense**: move the partition onto a 700 grid
  line so the closet grows to ~3.5–4 m².
- Keep the corridor walkway **≥ 1050 (1.5M)** where there are doors, and no narrower
  than **700 (1M)** at the tightest point.
- In the closet, 600-deep shelving with height sections: 0–700 (shoes/drawers),
  700–1400 (lower rail), 1400–2100 (upper rail), 2100–2800 (antresol) — exactly the
  4 module bands.

### 6.5. Bathroom 5.5 m²

- Lay tile so the joint lands on the grid, and the **top of the door (2100=3M)** matches
  the grout/layout line. Mirror and boxing — into the 700 bands.

### How to read the schematics
- `║ ═ ┌┐└┘` — walls and furniture; `░ ▒` — rugs/wardrobes; `◄──►` — control walkways.
- Numbers — real millimeters; `M` = 700 mm.

---

## Part 7. Cheat sheet

**Apartment module:** M = 700 mm (= GCD of ceiling 2800 and opening 2100).
Ruler: 175 / 350 / 700 / 1050 / 1400 / 2100 / 2800.

**Vertical (4 bands of 700):**
- 0–700 base · 700–1400 mid · 1400–2100 upper · 2100–2800 crown.
- Openings = 3M (2100). Ceiling = 4M (2800). Item tops → 3M or 4M.

**Golden ratio:** larger = ×0.618; smaller = ×0.382; round the zone boundary to the grid.

**Walkways:** main ≥ 1M (700)/better 1.5M (1050); secondary ≥ ~600.

**Furniture depths** — by ergonomics (kitchen/wardrobe 600, sofa ~900); lengths and gaps
— by the module.

---

## Part 8. Common mistakes

- **Borrowing someone else's module (60).** The module is derived from your 2800 and
  2100 → 700.
- **Forgetting the vertical and the openings.** Height is the third axis; the 2100 line
  ties everything together.
- **Unfinished heights.** A cabinet top at 1850 instead of 2100/2800 is visual clutter.
- **Dividing zones in half.** The golden point (0.618) is livelier than the center.
- **Module fanaticism for depths.** Depths are ergonomics; the module is structure and
  heights.
- **Narrow walkways.** Check with your body: main walkway ≥ 1050.

---

## What else to send for an exact layout

1. The positions of **windows and doors** on each room's walls (which wall, offset).
2. The positions of **risers / wet points** (kitchen, bathroom).
3. The side where the **balcony/study** joins the bedroom.
4. Mandatory furniture and its sizes (beds, sofa, desk).

With this, each room can be laid out on the 700 grid and golden points to the
millimeter.
