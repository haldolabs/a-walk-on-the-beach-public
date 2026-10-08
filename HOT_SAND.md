# Hot sand: when will there be more thinking sand than beach?

*A back-of-the-envelope from the bunker, 2026-10-08. We did the math; the math is approximate.*

The question, as asked: think of all the sand on all the beaches in the world. Then think of
every ingot of silicon ever grown to make the machines that compute with transistors. Which is
more, by how much, and if the second keeps growing the way it has, when does it pass the first?

Short answer: **the beaches win by about a million to one.** Every grown ingot of chip silicon
since 1960 comes to roughly half a million tonnes. The world's sandy beaches hold roughly a
thousand billion tonnes. If the chip industry kept growing at its historical rate, the mass
of thinking sand would catch the beaches **around the year 2230, give or take a century**, and
long before that the growth would have to stop, because by then we would be turning more
silicon into crystals every year than all the sand and gravel humanity moves today, and
spending a hundred times the world's electricity to do it.

Everything below is an order-of-magnitude estimate. Where two reasonable people could pick
numbers a factor of three apart, we say so.

## Ingot or boule?

Both words are used for the same thing. A crystal grown by pulling it from a melt (the
Czochralski method, which is how nearly all chip silicon is made) is a **boule** to a crystal
grower. The semiconductor industry calls the same cylinder an **ingot** before it is sliced
into wafers. "Ingot" originally meant cast metal, so the purist's word for a grown single
crystal is boule. We say ingot below because that is what the wafer makers say.

## How much beach there is

Nobody has measured the world's beach sand. The best starting point is a satellite survey of
every ice-free shoreline on Earth (Luijendijk and others, *The State of the World's Beaches*,
Scientific Reports, 2018), which found that **31% of it is sandy**. The same study says about
80,000 km of sandy beach is eroding and that this is 24% of the sandy total, which puts the
world's sandy shoreline at **roughly 330,000 km**.

A beach is not only the dry sand you walk on. The sand body runs out under the surf to the
depth where waves stop moving it, typically a few hundred metres to a kilometre offshore,
and it is a few metres thick. So the volume depends a lot on what you count:

| Case | Width × thickness | Volume | Mass of sand | Silicon in it |
|---|---|---|---|---|
| Dry beach only | 50 m × 3 m | 50 km³ | 80 billion t | 2.6 × 10¹³ kg |
| **Beach plus shoreface (central)** | 500 m × 4 m | 660 km³ | **1,100 billion t** | **3.5 × 10¹⁴ kg** |
| Wide shoreface | 1,000 m × 8 m | 2,600 km³ | 4,200 billion t | 1.4 × 10¹⁵ kg |

Sand is taken at 1,600 kg/m³ in bulk, about 70% quartz by mass (many beaches are shell and
coral instead), and quartz is 47% silicon by mass. The central case is about **10¹⁵ kg of
sand, of which about 3 × 10¹⁴ kg is silicon**. In grains of half a millimetre, that is around
6 × 10²¹ grains, six thousand billion billion.

For scale: humanity digs up about 50 billion tonnes of sand and gravel a year (UNEP's
estimate), so at that rate we would move every beach on Earth in about twenty years. We are
not, mostly: construction sand comes from rivers and quarries.

## How much thinking sand there is

Chip silicon is counted by wafer area. The industry body SEMI reports worldwide wafer
shipments of **14,713 million square inches in 2022** (the record) and **12,602 million in
2023**; call a typical recent year 13,000 million square inches, about 8.4 million m².

A wafer is 775 µm thick and silicon weighs 2,330 kg/m³, so a year's wafers weigh about
**15,000 tonnes**. The grown ingot is heavier than the wafers cut from it: the crown and tail
are cut off, and a third or more of the crystal is lost as sawdust and in grinding. Call the
ingots **about 36,000 tonnes a year**, which agrees with the tonnage of electronic-grade
polysilicon the industry reports consuming. (Solar panels use thirty to forty times more
silicon than this, but a solar cell does not think.)

Wafer area has grown at something like 7% a year over the long run, faster in the 1990s,
slower since 2010. If annual production grows exponentially at rate *g*, everything ever made
adds up to about one year's production divided by *g*:

| Long-run growth | Doubling time | All chip ingots ever grown |
|---|---|---|
| 4% a year | 17 years | 0.9 million t |
| **7% a year** | **10 years** | **0.5 million t** |
| 10% a year | 7 years | 0.4 million t |

So about **5 × 10⁸ kg of thinking sand has ever been grown**. Measured in grains of beach
sand, one 300 mm wafer is worth about 740,000 grains, and all the ingots ever grown come to
about 3 × 10¹⁵ grains: three million billion.

## The ratio

| | Sand on beaches | Chip ingots ever grown | Ratio |
|---|---|---|---|
| By mass | ~10¹⁵ kg | ~5 × 10⁸ kg | **~2,000,000 : 1** |
| By silicon atoms | ~3 × 10¹⁴ kg | ~5 × 10⁸ kg | **~700,000 : 1** |
| Counting only the dry beach | ~8 × 10¹³ kg | ~5 × 10⁸ kg | ~150,000 : 1 |

**About a million to one**, with the honest range running from a hundred thousand to ten
million depending on how much of the sea floor you call beach. One grain in a million has
been taught to think. The rest are on holiday.

## The Moore's-law answer

Chip silicon doubles about every ten years at 7% growth. To close a gap of a million needs
log₂(10⁶) ≈ 20 doublings:

| Growth holds at | Doubling | Crossover | Year | Ingots grown that year |
|---|---|---|---|---|
| 4% a year | 17 years | in 360 years | **~2390** | 42 billion t |
| **7% a year** | **10 years** | **in 210 years** | **~2230** | 74 billion t |
| 10% a year | 7 years | in 145 years | **~2170** | 106 billion t |

So: **around 2230, plus or minus a century.** That is the Moore's-law kind of result, and like
every Moore's-law extrapolation it is a statement about a curve, not about the world. The
last column is the tell. In the crossover year the industry would be growing seventy billion
tonnes of single-crystal silicon, more than all the sand and gravel humanity moves today for
every purpose, and the Siemens process that purifies it takes about 60 kWh per kilogram, so
the electricity bill that year would be some four million terawatt-hours, about a hundred and
fifty times the world's present generation. Something gives first: the growth rate, the
process, or the need for more transistors.

Two things that would move the date and are not in the table. First, the beaches are not
standing still: the same survey found a quarter of them eroding, and the ratio's denominator
only ever grows, since a thinking grain stays a crystal in a landfill long after the phone
dies. Second, if the question is all sand rather than beach sand, the deserts and the
sea floor add two or three more orders of magnitude, and the crossover moves out another
century at every rate.

## What this has to do with a beach walk

Nothing, and everything. The game is a beach made of numbers, drawn by sand that was taught
to think, for an otter who would rather it had not been. Every grain the otter walks on is a
million grains that were left alone. The ones that were not are in the bunker, warm,
counting.

## Sources and assumptions

* Sandy share of the world's shoreline, and the eroding fraction: Luijendijk, A. et al.,
  *The State of the World's Beaches*, Scientific Reports 8, 6641 (2018); the 330,000 km of
  sandy shoreline is back-calculated from its 80,000 km eroding at 24%.
* Wafer shipments: SEMI Silicon Manufacturers Group, annual releases for 2022 (14,713 MSI)
  and 2023 (12,602 MSI).
* Sand and gravel extraction, about 50 billion tonnes a year: UNEP, *Sand and Sustainability*
  (2019 and later).
* Beach width, sand thickness, quartz fraction, bulk density, kerf loss, the 7% long-run
  growth and the 60 kWh/kg are our own round numbers. Each could be off by a factor of two or
  three; together they could be off by ten either way, which is why every answer above is
  given to one digit.
* The arithmetic is a fifty-line Python script; the numbers in the tables are its output,
  rounded.

© Haldo Labs. Numbers are free to reuse; so is the conclusion, which is that the sand is
winning and will for a while yet.
