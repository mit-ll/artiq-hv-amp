# artiq-hv-amp

Schematic designs for a 1U rack mountable amplifier for the Zotino and Fastino. 

These are from the sinara family of DACs (https://github.com/sinara-hw/Zotino, https://github.com/sinara-hw/Fastino) and output 32 channels from -10 to +10 V and offer similar capabilities to the underlying AD9910 and AD9912 DACs from analog devices on which these cards are based. The amplifiers in this repository provide the following capabilities:

1. x4 amplification based on Linear's LTC6090 low noise HV amp.
2. Differential pair routing and differential inductors on all outputs.
3. MHz bandwidth and low output impedance.
4. Differentially paired HD68 input/output compatible with zotino, fastino.
5. ESD protection on all outputs with high speed low capacitance diodes.
6. Reverse polarity protection on high voltage input power.

DISTRIBUTION STATEMENT A. Approved for public release. Distribution is unlimited.

This material is based upon work supported under Air Force Contract No. FA8702-15-D-0001. Any opinions, findings, conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the U.S. Air Force.

© 2022 Massachusetts Institute of Technology.

Delivered to the U.S. Government with Unlimited Rights, as defined in DFARS Part 252.227-7013 or 7014 (Feb 2014). Notwithstanding any copyright notice, U.S. Government rights in this work are defined by DFARS 252.227-7013 or DFARS 252.227-7014 as detailed above. Use of this work other than as specifically authorized by the U.S. Government may violate any copyrights that exist in this work.
