# M470E Input Module · Input Pre Amps

Ward-Beck Systems M470E, 1984|17. Wiki page: [M470E on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M470E.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 21 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 16 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 183 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 8 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 29 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Circuit description

From [1984 - M470E - Input Module (2).pdf](MANUALS/1984%20-%20M470E%20-%20Input%20Module%20(2).pdf) pages 4-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The 14470E input module provides there c t f t t tes o f a COllplete input. ixin g channel with the exception oft he a tt enuato rand an optional external equalizer.

In.m INPUT Selectors witches Sill, SII2 and SII] allow a choice of inputs election between one line and two microphone f nput s. Additionally, SW 4 provides the insertion of a 20 dB loss pad fort he microphone sources. When operating from a MICROPHONEs our c e, the fnput impedance of the unit is substantially higher than the source impedance. Int he LINE position, the H410B presents abridging f mped a nce of ]Ok oh. t o the source. All inputs tot he module are trans for. e r coupled t o the prea mp l ifier.

Pr ea ll pl i ff e r The secondary side of the input tra&quot;sfor ller Tlc o nnec t s to the pr eamp li fie r input sect ion, c ompr f sing Ql through Q5 with their e s s oct ate d components. SENSITIVITY control 11.26 allows continuous level adjustment of all input signals over a range of ] 0 dB. The SENSITIVITY control thus permits opera t ion with microphone input levels fr olll -60 to -30 dBm int he direct node, and with levels f rOIl -40 to -10 dBm when the PAD is inserted. S1l1f la r l y, ll ne levels f rOIl -10 dBll t o +20 dBIi can be a c cOllmodated in the LINE e ee e.

Egualiz e r Insert Following Q4 and Q5, the signal is brought out to connector PI, p t n 22 andre turned tot he unit via Pl. p1n Z. This insert point lIla y be used to insert the M472 equalize r into the signal path.

HI GHPASS Filter

Following PI. pin Z, a 12 dB/octave HIGH-PASS ftlte r is

integrated into the pr ulIl plf f h r. Three distinct cutoff

frequencies can be selected. By pressing 5W5, 5W6 o r both

switches s i mult a neo us l y, the -3 dB r olloff point 100'11 1 be located at 10 Hz, 100 Hz o r 150 Hz respect t vej y.

Pr e Bmpl if i er Output Bnd PHASE ReverSB 1 The output o f the filter feeds the p reamplif ier output stage. consisting of 21, Q6, Q7, z a, Q8 and Q9. The actively balanced output is subsequently routed through the PHASE rev e r sal switch tot h ein s e r t point.

INSERT Point 1.. balanced INSERT point 15 provided between P2. pins 8/J and Pl. pins 6 / F to allow the use of insert jacks. perllitting the insertion of ancillary e q u f pe en t into the signal path. The INSERT point is followed by the CHANNEL ON switch.

CHANHE lON Switch The CHANNEL ON switch s waco nt r o ls all outputs o f the module with thee xc e p t ton of the PFL output.

PR::FAOE-liSTEN (PH) and PEAK Overload Indicator The bridging takeoff forth e PFl output and the PEAk. o...e rloa d indicator is picked up between the INSERT point and the CHANNEL ON switch. 2J operates a s a...01 tage c Ollp ara tor. It ce epe r-es the rectified audio signal with an externally supplied reference voltage, applied to connector Pl, pin 16. With there fe re nc e...o ltage ranging f roll 0 to approx i lute l y +10 volts, c a I1b rat lon of the overload point fr oll -6 dill to +27 dBm is possible. PEAK overload is indicB ted on OS2.

Followings wa, the signal is brought out of the module via Pl, pins 7/H for insert ion of a balanced fader. The output of the fader is return e d to the Illoclule on P2, pins 5/E. The inputs ide oft he fader also supplies the feed for the four PREFAOE AUXILIARY channels via switches SW9 through SWI2.

Sooste r AlIlplHhr

24 and Z5 c eep e t seth e booster alllpl1 r r er, operating at again

of 15 dB. The booster recovers the loss incur red &gt;/1th the

fade r placed in its nominal 15 dB fti n _ha nd position.

CIRClJlTDESCRIPTION H470EIN PlJTHODULE

DIRECT Output TIle out put si9&quot;,1 of the booster I lip l if i e r feeds the DIRECT output I t connector P2, pins 3 / e. This output i s designed to c per e t ein to abridging load of 10k ohms or higher. The nominal level of the DIRECT output is 0 dBm.

SlJBHASTER and AUXILIARY Outputs The booster amp l if i era ls o provides the feeds for the left Ind right SUBMASTER outputs via PAN swftch SW13 and PAN control RB4 through R8 7. Addit ionll feeds ares u pp lied to the SOLO output via SW22 In(l tot he four AUXILIARY outputs when in the POSTFAO£ mode. With the exception of the DIRECT output, all out puts are designed as 30 1: ohlll currents ourc es, t o operate into zero impedance summing nodes. Each summing output is equipped with its own assignment switch. Control Functions DC control and logic Illl,lt ing functions are pr:.o v ided through the &quot;I e / LINE INPUT Selectors wft c hes and the CHANNEL ON switch to facl1 itate studio mute control functions. to minimizes y stem transients, the de current i n these circuits should be limited to 1 rnA. Further control contacts are provided on the SOLO switch SW22 as well as on all SIJBM ASTER assignments e t t che s.

Power Supply Deco uplin9 Power supply de coupling isp r o v i ded by OlD, Qll and their u s ocfa ted cc e po nent s • The dec oup ling network reduces the module voltage to +20 volts fro lll the nOlJli nal supply voltage of 1&quot;25 volts.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTDI5b0FmajRRUHc/view?resourcekey=0-tL4oLIVFPysldQGpd7lSww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTDI5b0FmajRRUHc&resourcekey=0-tL4oLIVFPysldQGpd7lSww" width="240" alt="1984 - M470E - 470-04-013 - IRECT RIGHT OUT SHELD.jpg"></a><br><sub>1984|17 · 470-04-013 - IRECT RIGHT OUT SHELD · <a href="MECHANICAL/1984%20-%20M470E%20-%20470-04-013%20-%20IRECT%20RIGHT%20OUT%20SHELD%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRzNoVExEV3VaaWs/view?resourcekey=0-cMIBICPwlgxrTeTELlFJMw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRzNoVExEV3VaaWs&resourcekey=0-cMIBICPwlgxrTeTELlFJMw" width="240" alt="1984 - M470E - 470-04-014 - SWZI NHEN DEPRESSED NDPIGHT OUTPUT FED TANEOUS VID.jpg"></a><br><sub>1984|17 · 470-04-014 - SWZI NHEN DEPRESSED NDPIGHT OUTPUT FED TANEOUS VID · <a href="MECHANICAL/1984%20-%20M470E%20-%20470-04-014%20-%20SWZI%20NHEN%20DEPRESSED%20NDPIGHT%20OUTPUT%20FED%20TANEOUS%20VID%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaS1OVUJ4cUNRbmM/view?resourcekey=0-t7w2EymkNIYlv1Q3p7Xjyg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaS1OVUJ4cUNRbmM&resourcekey=0-t7w2EymkNIYlv1Q3p7Xjyg" width="240" alt="1984 - M470E - 470-04-014 - WHEN DEPRESSED ENABLES PAN CONTROL AUX PRE.jpg"></a><br><sub>1984|17 · 470-04-014 - WHEN DEPRESSED ENABLES PAN CONTROL AUX PRE · <a href="MECHANICAL/1984%20-%20M470E%20-%20470-04-014%20-%20WHEN%20DEPRESSED%20ENABLES%20PAN%20CONTROL%20AUX%20PRE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc3EweVZBQ2FtMGs/view?resourcekey=0-WjU62YFtJ7VqW9l8s8kRdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc3EweVZBQ2FtMGs&resourcekey=0-WjU62YFtJ7VqW9l8s8kRdQ" width="240" alt="1984 - M470E - 470-01-006 - CONTROL SUMMING BUS.jpg"></a><br><sub>1984|17 · 470-01-006 - CONTROL SUMMING BUS · <a href="SCHEMATICS/1984%20-%20M470E%20-%20470-01-006%20-%20CONTROL%20SUMMING%20BUS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekRORFNtakNsMEk/view?resourcekey=0-PwRvwV1fRFKIstWyE-kqlg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekRORFNtakNsMEk&resourcekey=0-PwRvwV1fRFKIstWyE-kqlg" width="240" alt="1984 - M470E - 470-01-006 - INSERT CHAN INSERT PHASE JACKS.jpg"></a><br><sub>1984|17 · 470-01-006 - INSERT CHAN INSERT PHASE JACKS · <a href="SCHEMATICS/1984%20-%20M470E%20-%20470-01-006%20-%20INSERT%20CHAN%20INSERT%20PHASE%20JACKS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWNvd2oyTS1VakU/view?resourcekey=0-lv81zax9lRqwwEuf0PBezw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWNvd2oyTS1VakU&resourcekey=0-lv81zax9lRqwwEuf0PBezw" width="240" alt="1984 - M470E - 470-02-006 - PI-P DSSMOD IICKD USED.jpg"></a><br><sub>1984|17 · 470-02-006 - PI-P DSSMOD IICKD USED · <a href="SCHEMATICS/1984%20-%20M470E%20-%20470-02-006%20-%20PI-P%20DSSMOD%20IICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRVpneWI5VXhSN2s/view?resourcekey=0-mmigl8JhVuj1ZrUafjYsLw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRVpneWI5VXhSN2s&resourcekey=0-mmigl8JhVuj1ZrUafjYsLw" width="240" alt="1984 - M470E - 470-06-012 - FINAL ASSEMBY ADP THE FOLLOWING CON.jpg"></a><br><sub>1984|17 · 470-06-012 - FINAL ASSEMBY ADP THE FOLLOWING CON · <a href="SCHEMATICS/1984%20-%20M470E%20-%20470-06-012%20-%20FINAL%20ASSEMBY%20ADP%20THE%20FOLLOWING%20CON%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkxwN3BlN3F3MHc/view?resourcekey=0-SMRe8cgqQBBvcHP_lvs8mw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkxwN3BlN3F3MHc&resourcekey=0-SMRe8cgqQBBvcHP_lvs8mw" width="240" alt="1984 - M470E - 8470-06-005 - SOC UHZ MATT JLDER SIDE.jpg"></a><br><sub>1984|17 · 8470-06-005 - SOC UHZ MATT JLDER SIDE · <a href="SCHEMATICS/1984%20-%20M470E%20-%208470-06-005%20-%20SOC%20UHZ%20MATT%20JLDER%20SIDE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZjRsMGlYZFB0Qk0/view?resourcekey=0-bK4vLDOHSn0LwJvCwhz_-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZjRsMGlYZFB0Qk0&resourcekey=0-bK4vLDOHSn0LwJvCwhz_-w" width="240" alt="1984 - M470E - 470-04-013 - CONNECTOR REAR VIEW.jpg"></a><br><sub>1984|17 · 470-04-013 - CONNECTOR REAR VIEW · <a href="PINOUTS/1984%20-%20M470E%20-%20470-04-013%20-%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M470E - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 18 of 20 contacts; 2 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree P2-5: kept ATT OUT (out); RTO-144 sheet says FADER-RETURN + (in)
- disagree P2-E: kept ATT OUT (out); RTO-144 sheet says FADER-RETURN - (in)

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | LINE IN | in | LINE IN | medium |
| 2 | N/C | nc |  | medium |
| 3 | DIRECT OUT | out | DIRECT | medium |
| 4 | SHIELD | shield |  | medium |
| 5 | ATT OUT | out | ATT OUT | medium |
| 6 | CH ON IN | control_in | CH ON IN | medium |
| 7 | CH ON OUT | control_out | CH ON OUT | medium |
| 8 | PRE OUT | out | PRE OUT | medium |
| 9 | N/C | nc |  | medium |
| 10 | N/C | nc |  | medium |
| 11 | N/C | nc |  | medium |
| 12 | N/C | nc |  | medium |
| 13 | SUB 4 CONTROL | control_in | SUB 4 CTL | medium |
| 14 | SUB CTL COMMON | ground |  | medium |
| 15 | CH ON AUX CONTACT | control_out | CH ON AUX CONTACT | medium |
| 16 | CONTROL COMMON | ground |  | medium |
| 17 | MIC 2 MUTE CONTROL | control_in | MIC 2 MUTE CTL | medium |
| 18 | CONTROL COMMON | ground |  | medium |
| 19 | -25 V | power |  | medium |
| 20 | 25 V COMMON | ground |  | medium |
| 21 | +25 V | power |  | medium |
| 22 | CHASSIS | ground |  | medium |
| A | LINE IN | in | LINE IN | medium |
| B | N/C | nc |  | medium |
| C | DIRECT OUT | out | DIRECT | medium |
| D | SHIELD | shield |  | medium |
| E | ATT OUT | out | ATT OUT | medium |
| F | CH ON IN | control_in | CH ON IN | medium |
| H | CH ON OUT | control_out | CH ON OUT | medium |
| J | PRE OUT | out | PRE OUT | medium |
| K | N/C | nc |  | medium |
| L | N/C | nc |  | medium |
| M | SUB 3 CONTROL | control_in | SUB 3 CTL | medium |
| N | SUB 2 CONTROL | control_in | SUB 2 CTL | medium |
| P | SUB 1 CONTROL | control_in | SUB 1 CTL | medium |
| R | SUB CTL COMMON | ground |  | medium |
| S | CH ON AUX CONTACT | control_out | CH ON AUX CONTACT | medium |
| T | ? MUTE CONTROL | control_in | T MUTE CTL | medium |
| U | ? MUTE CONTROL | control_in | U MUTE CTL | medium |
| V | SOLO CONTROL | control_in | SOLO CTL | medium |
| W | ? CTL COMMON | ground |  | medium |
| X | ? CTL COMMON | ground |  | medium |
| Y | +24 V | power |  | medium |
| Z | CH ON LAMP | control_out | CH ON LAMP | medium |

**Straps:** JMP.Z.W: P2-Z P2-W · JMP.2: P2-W P2-18 · JMP.Y.21: P2-Y P2-21 · JMP.20.18: P2-20 P2-18 · JMP.8.6: P2-8 P2-6 · JMP.J.F: P2-J P2-F · JMP.7.5: P2-7 P2-5 · JMP.H.E: P2-H P2-E · JMP.Z.22: P1-Z P1-22

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDBnSDB0ZnZQaFE/view?resourcekey=0-qLpUSZnVipCnGKBMFSj31g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDBnSDB0ZnZQaFE&resourcekey=0-qLpUSZnVipCnGKBMFSj31g" width="240" alt="1984 - M470E - Input Module (2).pdf"></a><br><sub>1984|17 · Input Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblFJMFBrTkNERFk/view?resourcekey=0-nnpExbtkwZNxbJTTS947eg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblFJMFBrTkNERFk&resourcekey=0-nnpExbtkwZNxbJTTS947eg" width="240" alt="1984 - M470E - Input Module.pdf"></a><br><sub>1984|17 · Input Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNzlqUEJLSnppc1E/view?resourcekey=0-SeYVfrYVOzEtsHzmjrrIow" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNzlqUEJLSnppc1E&resourcekey=0-SeYVfrYVOzEtsHzmjrrIow" width="240" alt="1984 - M470E - P001 - Title Page.jpg"></a><br><sub>1984|17 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlpoMEdiQnA5dVk/view?resourcekey=0-gS86aPsVYu_sGGKj5WNAgg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlpoMEdiQnA5dVk&resourcekey=0-gS86aPsVYu_sGGKj5WNAgg" width="240" alt="1984 - M470E - P002.jpg"></a><br><sub>1984|17 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGNRVVpqRXBtV2c/view?resourcekey=0-i407QjwvbRqh_ihGHl9m-w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGNRVVpqRXBtV2c&resourcekey=0-i407QjwvbRqh_ihGHl9m-w" width="240" alt="1984 - M470E - P003 - 1-1.jpg"></a><br><sub>1984|17 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNW42N3NQNVd1UTQ/view?resourcekey=0-soJALJl0--S1vgQbX8OvVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNW42N3NQNVd1UTQ&resourcekey=0-soJALJl0--S1vgQbX8OvVw" width="240" alt="1984 - M470E - P004 - 2-1.jpg"></a><br><sub>1984|17 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2pOSTFPX0hCTHc/view?resourcekey=0-83_BFoz_faF_WL6PZHSzbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2pOSTFPX0hCTHc&resourcekey=0-83_BFoz_faF_WL6PZHSzbQ" width="240" alt="1984 - M470E - P005 - 2-2.jpg"></a><br><sub>1984|17 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYU4tNWE3YTNweHc/view?resourcekey=0-nv8a1WGSlqHzBtsVXlfYOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYU4tNWE3YTNweHc&resourcekey=0-nv8a1WGSlqHzBtsVXlfYOw" width="240" alt="1984 - M470E - P006 - 2-3.jpg"></a><br><sub>1984|17 · P006 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTU9XcXV0OTVxNnc/view?resourcekey=0-ENG3lrr8ybcb_9Pr-3SvPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTU9XcXV0OTVxNnc&resourcekey=0-ENG3lrr8ybcb_9Pr-3SvPQ" width="240" alt="1984 - M470E - P007 - 3-1.jpg"></a><br><sub>1984|17 · P007 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU2xMX2Jlcnc2U3M/view?resourcekey=0-osWdlZELLchAsnHSsBiu1A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU2xMX2Jlcnc2U3M&resourcekey=0-osWdlZELLchAsnHSsBiu1A" width="240" alt="1984 - M470E - P008 - 4-1.jpg"></a><br><sub>1984|17 · P008 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlk3THFDdFdFUEU/view?resourcekey=0-GXY39buplcksurVKXuVIOg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlk3THFDdFdFUEU&resourcekey=0-GXY39buplcksurVKXuVIOg" width="240" alt="1984 - M470E - P009 - 4-2.jpg"></a><br><sub>1984|17 · P009 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUktCNnRYQmx3aFk/view?resourcekey=0-1NEqxprJEAuJoel61o6Kkw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUktCNnRYQmx3aFk&resourcekey=0-1NEqxprJEAuJoel61o6Kkw" width="240" alt="1984 - M470E - P010 - 4-3.jpg"></a><br><sub>1984|17 · P010 - 4-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT213ZmpjX3NwYk0/view?resourcekey=0-5_QeL3WzjH0L1M3WwpphMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT213ZmpjX3NwYk0&resourcekey=0-5_QeL3WzjH0L1M3WwpphMA" width="240" alt="1984 - M470E - P011 - 4-4.jpg"></a><br><sub>1984|17 · P011 - 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0t4Y2g2MElIUWc/view?resourcekey=0-jdHgdFkjv0LNO15HE3giQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0t4Y2g2MElIUWc&resourcekey=0-jdHgdFkjv0LNO15HE3giQA" width="240" alt="1984 - M470E - P012 - 4-5.jpg"></a><br><sub>1984|17 · P012 - 4-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0FNaEpVWFZFQ0E/view?resourcekey=0-tbVg2z6Ri24wqBuypL3I7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0FNaEpVWFZFQ0E&resourcekey=0-tbVg2z6Ri24wqBuypL3I7A" width="240" alt="1984 - M470E - P013 - 4-6.jpg"></a><br><sub>1984|17 · P013 - 4-6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQkFKZmc5ZEhoRTA/view?resourcekey=0-CIKO2sCOpienPUILlVwlyg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQkFKZmc5ZEhoRTA&resourcekey=0-CIKO2sCOpienPUILlVwlyg" width="240" alt="1984 - M470E - P014 - 4-7.jpg"></a><br><sub>1984|17 · P014 - 4-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHhRajFYb1JrZUU/view?resourcekey=0-gR96dUaT3CDBCTC1A4NAww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHhRajFYb1JrZUU&resourcekey=0-gR96dUaT3CDBCTC1A4NAww" width="240" alt="1984 - M470E - P015 - 4-8.jpg"></a><br><sub>1984|17 · P015 - 4-8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUnlrNjFUU3JuVGs/view?resourcekey=0-4x0drn6w7Swk6EnEIgbtQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUnlrNjFUU3JuVGs&resourcekey=0-4x0drn6w7Swk6EnEIgbtQg" width="240" alt="1984 - M470E - P018 - LB470-02-006 01.jpg"></a><br><sub>1984|17 · P018 - LB470-02-006 01</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTVpYdHg4cXVIZDQ/view?resourcekey=0-dtJzEuzW1w4WpfJVlR4MnA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTVpYdHg4cXVIZDQ&resourcekey=0-dtJzEuzW1w4WpfJVlR4MnA" width="240" alt="1984 - M470E - P018 - LB470-02-006 02.jpg"></a><br><sub>1984|17 · P018 - LB470-02-006 02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNm44MUFPZHpwQ2c/view?resourcekey=0-FZgIcVjSZXniZE__IxLBRw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNm44MUFPZHpwQ2c&resourcekey=0-FZgIcVjSZXniZE__IxLBRw" width="240" alt="1984 - M470E - P018 - LB470-02-006 03.jpg"></a><br><sub>1984|17 · P018 - LB470-02-006 03</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1984 - M470E - 470-01-006 - CONTROL SUMMING BUS.kicad_sch](KICAD/1984%20-%20M470E%20-%20470-01-006%20-%20CONTROL%20SUMMING%20BUS.kicad_sch)
- [1984 - M470E - 470-01-006 - INSERT CHAN INSERT PHASE JACKS.kicad_sch](KICAD/1984%20-%20M470E%20-%20470-01-006%20-%20INSERT%20CHAN%20INSERT%20PHASE%20JACKS.kicad_sch)
- [1984 - M470E - 470-02-006 - PI-P DSSMOD IICKD USED.kicad_sch](KICAD/1984%20-%20M470E%20-%20470-02-006%20-%20PI-P%20DSSMOD%20IICKD%20USED.kicad_sch)
- [1984 - M470E - Input Module (2) p19.kicad_sch](KICAD/1984%20-%20M470E%20-%20Input%20Module%20(2)%20p19.kicad_sch)
- [1984 - M470E - Input Module (2) p23.kicad_sch](KICAD/1984%20-%20M470E%20-%20Input%20Module%20(2)%20p23.kicad_sch)
- [1984 - M470E - Input Module p19.kicad_sch](KICAD/1984%20-%20M470E%20-%20Input%20Module%20p19.kicad_sch)
- [M470E.kicad_sym](KICAD/M470E.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
