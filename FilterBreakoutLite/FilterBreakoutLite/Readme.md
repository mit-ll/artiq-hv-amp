This folder contains KiCAD models of filter boards for use with DAC signals arranged in groups of 32 differential pairs in an HD-68 cable.
Jules designed the original and manufactured it for Marlo and I (dreens) made more recent modifications to extend to the rest of the LL ions lab.

Key organizing principles:
1. A 'motherboard' takes 32 pairs as input, and offers a number of jumper selectable options.
2. One option is to utilize 8 four channel daughter boards inserted via card edge connectors.
3. Another option is to use on-board low-pass filters with 10 kHz cutoff and 12 dB/octave rolloff.
4. Coax pickoffs enable monitoring or over-riding channels on a case by case basis.
5. Grounds can be passed through to an HD-68 differential output, or shorted to board ground.
6. Filtered signals may be accessed either at this output HD-68, or via a DB-25 connector with the first 25 channels.
7. The FilterMotherboard folder contains the latest motherboard as well as some low-pass daughterboards, which weren't produced in light of the on-board LP option that was added.
8. The FilterDaughterboard-old folder contains daughterboards useful for shuttling with a higher cutoff frequency.

Known Issues:
1. The DB-25 output connector has a left-right mirroring issue. Best to resolve using ribbon cable to connect out to enclosure.
2. There's not really a way to utilize the 32 pin differentially paired output right now.
   One could imagine a future where we run differential pairs all the way to the octagon / internal vacuum circuitboard.
3. Be sure to review CAD related issues below.

CAD for the enclosure:
1. Successfull 1U rack mount ordered from protocase.
2. Key issue: rear screws off by exactly 0.5"- too close to the front panel by this amount.
3. Key issue: needs rear panel re-design for DB25 style cases instead of COTIAC mil-spec 32 pin.
4. Key issue: needs to be updated for 2U height for use with card-insertable motherboards.
5. This will entail obtaining a new template from protocase (the included design has as its base an imported model from protocase).

Ordering from protocase:
1. I've had success with two options so far, powder coated steel, and aluminum. Former is a bit cheaper but latter is a bit better.
2. Make sure to utilize their "PEM" fasteners as done here- these are self-clinching fasteners that can make board installation a breeze.
3. PEM CAD available from PENN engineering, also cross check protocase' list of in-stock PEMs.
4. Ask for the case to be powdercoat screened in a few places to ensure electrical connectivity across all panels.
5. They'll want you to proof everything.

Ordering boards from advanced circuits:
1. I can't remember right now. Bug me (dreens) and I'll dig up my order documentation. I had them do assy too which was great.