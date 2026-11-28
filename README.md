# M416 Cue Amplifier · Unsorted

Ward-Beck Systems M416, 1973|6. Wiki page: [M416 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M416.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 35 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 22 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 25 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 8 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 36 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Circuit description

From [1973 - M416 - P4.jpg](MANUALS/1973%20-%20M416%20-%20P4.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M416 watt cue amplifier provides three 20K ohm bridging inputs each of Which is isolated from one another In addition, sun input is provided which is intended to receive the cue feeds from the M441 input modules 21 and 22 form an actively balanced input which provides the necessary longitudinal balance characteristics The input amplifier is capable of handling an input level up to +l8dBm without over load The amplifier level control is located after the preamplifier _ This control maybe extended via pins and 8 to permit the adjustment of the amplifier output level up to distance of 10 feet This external control operates in series with the control located on the module For this external control type of operation, the module level control should remain in the full clockwise position. 23 forms the driver amplifier for the output power transistor 03 through Q6 _ The output signal is coupled through to pinS _ CR3 to CR6 form the overdrive protection circuit to prevent excessive power dissipation if the amplifier is inadvertently shorted while signal i5 present 01 and Q2 form regulator circuit which provides the bias voltage (approximately 10V to pin of z1, 22 and 23) The amplifier will operate from nominal 24 to 36 Vdc unregulated supply which has the negative side on the common terminal The unregulated dc voltage i5 applied to pin X and fed through fuse Fl and polarity reversing protection diode CRI

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1r4MBB9SVgckd4l9GgXmvQ-1HwZVin39L/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1r4MBB9SVgckd4l9GgXmvQ-1HwZVin39L" width="240" alt="1973 - M416 - DOC - 16-03-003 - THICK BLACK PLEXIGLASS TYPE.jpg"></a><br><sub>1973|6 · DOC - 16-03-003 - THICK BLACK PLEXIGLASS TYPE · <a href="MECHANICAL/1973%20-%20M416%20-%20DOC%20-%2016-03-003%20-%20THICK%20BLACK%20PLEXIGLASS%20TYPE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/17h47_vOXSy8ha77Pl8Qz9AtHecFp9O1r/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=17h47_vOXSy8ha77Pl8Qz9AtHecFp9O1r" width="240" alt="1973 - M416 - DOC - 416-03-003 - THICK BLACK PLEXIGLASS TYPE.jpg"></a><br><sub>1973|6 · DOC - 416-03-003 - THICK BLACK PLEXIGLASS TYPE · <a href="MECHANICAL/1973%20-%20M416%20-%20DOC%20-%20416-03-003%20-%20THICK%20BLACK%20PLEXIGLASS%20TYPE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1973 - 416-03-002 - ESCUTCHEON - DRN DPS - ISS 1 (2).jpg`, `1973 - 416-03-002 - ESCUTCHEON - DRN DPS - ISS 1.jpg`, `1973 - 416-03-003 - SWITCH MOUNTING PLATE - DRN DPS - ISS 1.jpg`

## 3-D model

[`MECHANICAL/M416.stl`](MECHANICAL/M416.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M416)

- **Size:** 54.19 × 226.26 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 1 holes and cut-outs, 1 knobs (front panel: `MECHANICAL/M416 - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M416.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1aMvSu5zwFzU2D6f7stCVqjzJVDDz6OL0/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1aMvSu5zwFzU2D6f7stCVqjzJVDDz6OL0" width="240" alt="1973 - 416-02-001 - CUE AMPLIFIER SCHEMATIC - DRN DGS - ISS 2.jpg"></a><br><sub>1973|6 · 416-02-001 - CUE AMPLIFIER SCHEMATIC - DRN DGS - ISS 2 · <a href="SCHEMATICS/1973%20-%20416-02-001%20-%20CUE%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DGS%20-%20ISS%202%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1JuaU52S1lVa00/view?resourcekey=0-nA3CPs2jva2c-RhDEyPcEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1JuaU52S1lVa00&resourcekey=0-nA3CPs2jva2c-RhDEyPcEQ" width="240" alt="1973 - M416 - 3-102-06-001 - CJE AMPLIFIER.jpg"></a><br><sub>1973|6 · 3-102-06-001 - CJE AMPLIFIER · <a href="SCHEMATICS/1973%20-%20M416%20-%203-102-06-001%20-%20CJE%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbVFvLTJIV0h4VG8/view?resourcekey=0-neoHhGdckeUEievPIEErNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbVFvLTJIV0h4VG8&resourcekey=0-neoHhGdckeUEievPIEErNg" width="240" alt="1973 - M416 - 412-02-002.jpg"></a><br><sub>1973|6 · 412-02-002 · <a href="SCHEMATICS/1973%20-%20M416%20-%20412-02-002%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUGFudldQeDdXQm8/view?resourcekey=0-8dvpgbiAGOtZlyCpgYzEkA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUGFudldQeDdXQm8&resourcekey=0-8dvpgbiAGOtZlyCpgYzEkA" width="240" alt="1973 - M416 - 412-02-003 - PLACES GIVEN ANGLES.jpg"></a><br><sub>1973|6 · 412-02-003 - PLACES GIVEN ANGLES · <a href="SCHEMATICS/1973%20-%20M416%20-%20412-02-003%20-%20PLACES%20GIVEN%20ANGLES%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV3htZnR1aVhxNFE/view?resourcekey=0-_bXV2YmDvzA0Q8jhufhqgw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV3htZnR1aVhxNFE&resourcekey=0-_bXV2YmDvzA0Q8jhufhqgw" width="240" alt="1973 - M416 - 416-02-001 (2).jpg"></a><br><sub>1973|6 · 416-02-001 (2) · <a href="SCHEMATICS/1973%20-%20M416%20-%20416-02-001%20(2)%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1973 - 3-102-06-001 - CUE AMPLIFIER PCB LAYOUT - DRN DGS - ISS 2.jpg`, `1973 - 416-02-001 - CUE AMPLIFIER SCHEMATIC - DRN DGS - ISS 1.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M416 - RTO-144 Connections.pdf`

## RTO-144 pinout

RTO-144 edge connector. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS2tXVUExYjcyT00/view?resourcekey=0-PvuIVQvjQAtDeEcgQA16HA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS2tXVUExYjcyT00&resourcekey=0-PvuIVQvjQAtDeEcgQA16HA" width="240" alt="1973 - M416 - 1.jpg"></a><br><sub>1973|6 · 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDd2eDlBcjZ0XzQ/view?resourcekey=0-6b1TaVW4Gh-vX_xqSzqaAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDd2eDlBcjZ0XzQ&resourcekey=0-6b1TaVW4Gh-vX_xqSzqaAw" width="240" alt="1973 - M416 - 10.jpg"></a><br><sub>1973|6 · 10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbExfTFRKUWVJVlE/view?resourcekey=0-2nvrYY9ufvf5hMxMrJ1Mlw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbExfTFRKUWVJVlE&resourcekey=0-2nvrYY9ufvf5hMxMrJ1Mlw" width="240" alt="1973 - M416 - 2.jpg"></a><br><sub>1973|6 · 2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbHRYVE81ejkzZWs/view?resourcekey=0-yCCQQPhFW2cRiPGTk3MQtQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbHRYVE81ejkzZWs&resourcekey=0-yCCQQPhFW2cRiPGTk3MQtQ" width="240" alt="1973 - M416 - 3.jpg"></a><br><sub>1973|6 · 3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWY5WHN4amRHVVk/view?resourcekey=0-Pb9o-go_J5Ymp2OrlKOepg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWY5WHN4amRHVVk&resourcekey=0-Pb9o-go_J5Ymp2OrlKOepg" width="240" alt="1973 - M416 - 4.jpg"></a><br><sub>1973|6 · 4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUo1OHI5VWRNYjA/view?resourcekey=0-mxHEk_NbAFw0C_aGBP96bA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUo1OHI5VWRNYjA&resourcekey=0-mxHEk_NbAFw0C_aGBP96bA" width="240" alt="1973 - M416 - 5.jpg"></a><br><sub>1973|6 · 5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVlhueHV2a0NPNjA/view?resourcekey=0-d_nVnCm1clB9R6QjVMX7rw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVlhueHV2a0NPNjA&resourcekey=0-d_nVnCm1clB9R6QjVMX7rw" width="240" alt="1973 - M416 - 6.jpg"></a><br><sub>1973|6 · 6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS2JQTEhMeWJEU00/view?resourcekey=0-bFbpItbHupZv0Pq0-GfWNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS2JQTEhMeWJEU00&resourcekey=0-bFbpItbHupZv0Pq0-GfWNA" width="240" alt="1973 - M416 - 7.jpg"></a><br><sub>1973|6 · 7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSUZyWXI0Zl9iQlE/view?resourcekey=0-rwSaM4Umkm0HfGle129Mvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSUZyWXI0Zl9iQlE&resourcekey=0-rwSaM4Umkm0HfGle129Mvg" width="240" alt="1973 - M416 - 8.jpg"></a><br><sub>1973|6 · 8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVRlNFlLLUxmWDg/view?resourcekey=0-Aq7AYO_1KOk3GBXNtK5I5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVRlNFlLLUxmWDg&resourcekey=0-Aq7AYO_1KOk3GBXNtK5I5Q" width="240" alt="1973 - M416 - 9.jpg"></a><br><sub>1973|6 · 9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblIzd2FVZ3hobG8/view?resourcekey=0-J6sWNRX8EExwDUZCxz5pqQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblIzd2FVZ3hobG8&resourcekey=0-J6sWNRX8EExwDUZCxz5pqQ" width="240" alt="1973 - M416 - P1.jpg"></a><br><sub>1973|6 · P1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRjgyWk93NVI2Zlk/view?resourcekey=0-UWDkOpVoaemb46EsqGKA7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRjgyWk93NVI2Zlk&resourcekey=0-UWDkOpVoaemb46EsqGKA7g" width="240" alt="1973 - M416 - P10.jpg"></a><br><sub>1973|6 · P10</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRHNzYmE2Zmh1dmc/view?resourcekey=0-jrd1vohFw3LS8Qs2RYs6GQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRHNzYmE2Zmh1dmc&resourcekey=0-jrd1vohFw3LS8Qs2RYs6GQ" width="240" alt="1973 - M416 - P2.jpg"></a><br><sub>1973|6 · P2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVNzQThCUmZvbVk/view?resourcekey=0-O-QKh_PzJzEDEEb1Qm5dMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVNzQThCUmZvbVk&resourcekey=0-O-QKh_PzJzEDEEb1Qm5dMA" width="240" alt="1973 - M416 - P3.jpg"></a><br><sub>1973|6 · P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZmdUSS1BcVFZTk0/view?resourcekey=0-7EtV-M3FeNV2LfImK5PB_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZmdUSS1BcVFZTk0&resourcekey=0-7EtV-M3FeNV2LfImK5PB_Q" width="240" alt="1973 - M416 - P4.jpg"></a><br><sub>1973|6 · P4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTGJ2X2hXMEFpdVk/view?resourcekey=0-3L78up2QM24WWvuOpJq-Cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTGJ2X2hXMEFpdVk&resourcekey=0-3L78up2QM24WWvuOpJq-Cg" width="240" alt="1973 - M416 - P5.jpg"></a><br><sub>1973|6 · P5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT3oybnd4ZE0wVEE/view?resourcekey=0-H65S4wcUMW9kqiXExoaGig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT3oybnd4ZE0wVEE&resourcekey=0-H65S4wcUMW9kqiXExoaGig" width="240" alt="1973 - M416 - P6.jpg"></a><br><sub>1973|6 · P6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUtqeDJFamI3YnM/view?resourcekey=0-vkilBow2pEf0Vo-WapR-mQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUtqeDJFamI3YnM&resourcekey=0-vkilBow2pEf0Vo-WapR-mQ" width="240" alt="1973 - M416 - P7.jpg"></a><br><sub>1973|6 · P7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3E3eElUZHlGTzQ/view?resourcekey=0-p_0dOu-3YlzQX3bCOihvGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3E3eElUZHlGTzQ&resourcekey=0-p_0dOu-3YlzQX3bCOihvGA" width="240" alt="1973 - M416 - P8.jpg"></a><br><sub>1973|6 · P8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNTM2cFNTLUlla2M/view?resourcekey=0-drP8L57W4QdaIHEMm2inXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNTM2cFNTLUlla2M&resourcekey=0-drP8L57W4QdaIHEMm2inXg" width="240" alt="1973 - M416 - P9.jpg"></a><br><sub>1973|6 · P9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/11nk-lYD_mbrHst_Yzl3pHO1uQI_jii9O/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=11nk-lYD_mbrHst_Yzl3pHO1uQI_jii9O" width="240" alt="19xx - M416 - DOC - Scan_20210323.jpg"></a><br><sub>19xx - M416 - DOC - Scan_20210323</sub></td></tr>
</table>

Not on Google Drive yet: `19xx - M416 - M416 (2).jpg`, `19xx - M416 - M416 Cue Amplifier Instruction Manual Index.jpg`, `19xx - M416 - M416.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1973 - 416-02-001 - CUE AMPLIFIER SCHEMATIC - DRN DGS - ISS 1.kicad_sch](KICAD/1973%20-%20416-02-001%20-%20CUE%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DGS%20-%20ISS%201.kicad_sch)
- [1973 - 416-02-001 - CUE AMPLIFIER SCHEMATIC - DRN DGS - ISS 2.kicad_sch](KICAD/1973%20-%20416-02-001%20-%20CUE%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DGS%20-%20ISS%202.kicad_sch)
- [1973 - M416 - 412-02-002.kicad_sch](KICAD/1973%20-%20M416%20-%20412-02-002.kicad_sch)
- [1973 - M416 - 412-02-003 - PLACES GIVEN ANGLES.kicad_sch](KICAD/1973%20-%20M416%20-%20412-02-003%20-%20PLACES%20GIVEN%20ANGLES.kicad_sch)
- [1973 - M416 - 416-02-001 (2).kicad_sch](KICAD/1973%20-%20M416%20-%20416-02-001%20(2).kicad_sch)
- [1973 - M416 - 416-02-001.kicad_sch](KICAD/1973%20-%20M416%20-%20416-02-001.kicad_sch)
- [M416.kicad_sym](KICAD/M416.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
