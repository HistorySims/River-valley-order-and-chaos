# River Valley: Order & Chaos

A single-file browser simulation for the **"Geography is Destiny"** student lab packet.
Students play a farmer-leader in two river valley civilizations and *feel* the difference
between a predictable environment (Egypt / the Nile) and a chaotic one (Mesopotamia / the Tigris).

**No install needed** — open `index.html` in any modern browser. It has no required
dependencies, so it also works offline on classroom Chromebooks.

## How the game supports the packet

| Packet item | In-game feature |
|---|---|
| Part 1 stories (Menes & Enki) | The advisors are Menes's father and Enki's mother, quoting the packet stories during play |
| Round 1: "look at the Flood Timer" | Egypt shows a visual **Nilometer** with the "Mark of Plenty" plus a flood countdown; the flood follows the same fixed 16-month cycle every time |
| Round 1/2: food counts at Month 20 & 40 | A **Scribe's Census** modal pauses the game at Months 20 and 40, shows total food harvested, and tells students to record it in Part 2 of the packet |
| Round 2: "no timer… unpredictable" | Mesopotamia has no countdown — only **omens** that hint at next month's river *and sometimes lie* (false alarms and silent flash floods give students their "the game tricked me" moment) |
| Round 2: Technology unlock | Levee unlock modal appears at Month 10; gates can be **closed** (blocks small floods, no silt) or **opened** (floods fields, captures silt); huge floods can breach a closed gate, but never more than once per 12 months |
| Part 3: Safety vs. Anxiety → religion | The **village mood** indicator drifts toward "At Peace — Ma'at" in Egypt and "Fearful — the gods are angry" in Mesopotamia, making the emotional contrast visible and discussable |
| Silt economics | Flooded plots turn to black silt (3× harvest) that dries out after 6 months; dry earth yields 1× |

## Core rules (unchanged from the original design)

- 5 energy per month; planting costs 1, harvesting is free, levee costs 3
- Crops ripen in 4 months; floods destroy any crops they cover
- Egypt floods on a fixed 16-month cycle (rise → peak → recede → 9 safe months)
- Mesopotamia's river is a random walk with a 5% flash-flood chance each calm month
- Closed levee blocks floods of width ≤ 2 and collapses at width ≥ 3 — but at most
  once per 12 months: a recently rebuilt levee strains and holds against anything

## Immersion features

Animated river/flood water, lightning + screen shake on flash floods, day-cycle sun,
civilization-specific skylines (pyramids vs. ziggurat), a village that grows as the
granary fills, synthesized ambient sound effects (muted by default — toggle in the
header, no audio files needed), and Egyptian season names (Akhet / Peret / Shemu)
on the calendar.
