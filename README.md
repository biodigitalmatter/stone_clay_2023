# Stone & Clay workshop Lund

## Context

Workshop given to master students in the Computational Design studio (part of
[MAEF](https://www.lth.se/english/master-programme-structure/maef/)) by PhD
students Anton Tetov Johansson (LTH) & Kunaljit Chadha ([Gramazio Kohler
Research, ETH Zürich](https://gramaziokohler.arch.ethz.ch/)).

## Location

[Composite Design](https://www.composite-design-sweden.com/)'s factory in Arlöv
("Gamla Saabfabriken") 

[Google maps link](https://maps.app.goo.gl/uRWeMaJthnySdcUT6)

### How to get there

#### Buss 130 or 172

[10 min walk from bus stop Arlöv Sockerbitstorget](https://maps.app.goo.gl/GxAtCrZTEqiAcE4U7)

#### Train to Burlöv station

[18 min walk from Burlöv station](https://maps.app.goo.gl/21KMc5Jw8nuQVAnN9)

## Links

### File storage

- [File storage (Sharepoint)](https://lunduniversityo365.sharepoint.com/:f:/r/sites/bioDigitalMatter/Delade%20dokument/Stone%20and%20Clay%20workshop%202023?csf=1&web=1&e=wVlJ8l)

### Code
- [Design and frontend](https://github.com/biodigitalmatter/stone_clay_py)
- [ROS side](https://github.com/biodigitalmatter/stone_clay_ros)
- [Localization](https://github.com/biodigitalmatter/compas_mrr)

## Schedule

### w 49
|              | Monday (4/12)           | Tuesday (5/12)        | Wednesday (6/12)          | Thursday (7/12)   | Friday (8/12)           |
| ------------ | ----------------------- | --------------------- | ------------------------- | ----------------- | ----------------------- |
| Notes        |                         | @Arlöv, A & D         | @Arlöv, A, D & K          | @Arlöv, A, D & K  | @Arlöv, A, D & K        |
| 09.15--12.00 | Self study              | Introduction to setup | Design intro              | Guest lecture     | Design/Production       |
| 13.15--18.00 | Self study              | Dry tests             | Design/Wet tests          | Design/Production | Production, summary, AW |

### w 50

- **Monday (11/12)** Start seminar and site visit
- **Tuesday (12/12)** Anton cleanup & transport
- **Wednesday (13/12)** Ragn-Sells construction waste pickup

## Goal

Non linear fabrication process constructing building element from clay/earth on
top of existing layer of crushed stone (100-200 mm grain size) based on student
designed target surface.

## Process

### Input

- 3D-volume describing goal shape.
- 3D-scan of work area.
- Extrusion parameters

### Output

Goal shape on top of work area within a given tolerance.

### Steps

1. Generate print path based on goal shape (layer based)
2. Define placement in work area, situate print path above highest point in work
   area.
3. Modify movement speed based on measured difference between scan and desired shape based on samples.

## Equipment

- Bettan, IRB4600 mounted on caterpillar tracks. See [Klöckner et al
  (2023)](https://doi.org/10.22260/ISARC2023/0014).
- Pump and extruder
- Depth scanners
- Position tracking

## Material

- clay/sand mixture
- stone
