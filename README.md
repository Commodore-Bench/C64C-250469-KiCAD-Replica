# discrepancies notes
- Inputs of 4066 in U18 and U21 are named differently.
- Global label INTRES near U6, a INTRES net is crossing, but there is no junction.
- C8 in the schematics is the same as C2 in the layout
- 9VAC global label seems to point the wrong direction
- R16 is anonymous in the schematic
- Power Switch symbols have no reference number and no pin numbers.
- kicad labels will not have slash inside ~{}, but will have them in symbol pin names
- C59 is missing its reference in the schematics. Schematics says it is C19.
- CASS_RD RP3 pin 8 is actually RP5 pin 8.
- C70 at U2 is actually C30.
- C18 in schematic is actually C48 on the pcb.
- RP4 pin 9 in the schematics was not marked with a number.
- C45 in the schematic is C65 in the layout
- Crystal Y1 in the schematics doesn't show the shield grounding and its connection.
- EXT_RESET at the serial port is called EXTRES at U22.

Other:
- PB0..7 and PA2 in the schematic share the same net between to the CIA ICs.

