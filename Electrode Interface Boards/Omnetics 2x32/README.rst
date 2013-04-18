Omnetics 36-channel "nano-strip" connectors, 4 guide posts
---------------------------------------------------------------------------------

The 64ch_eib_omnetics_3fibers Electrode Interface Board  (EIB) is designed to form a connection between 64 microwire electrodes or individual wires forming stereotrodes or tetrodes, and two 32 channel omnetics connectors.

See the documentation on http://github.com/open-ephys/flexDrive for building and use instructions.

Connectors on EIB:
~~~~~~~~~~~~~~~

* male surface-mount vertical (A79026-001 / NPD-36-VV-GS)

Connectors on Headstage:
~~~~~~~~~~~~~~~~~~
 
* female surface-mount horizontal (A79025-001 / NSD-36-AA-GS)
* female surface-mount vertical (A79027-001 / NSD-36-VV-GS)


Pin mapping:
~~~~~~~~~~~~~~~~~~
The pin mapping for the GROUND and REFERENCE channels on this EIB are compatible with the mapping on the Intan evaluation system headstages (http://www.intantech.com/files/Intan_RHD2000_eval_system.pdf) and the open-ephys headstages (open-ephys.org)

(viewed down onto the eib, looking onto the bottom of the headstage connector this would be flipped)

| ref  | ch | ch | ... | ch | gnd |
| gnd | ch | ch | ... | ch | ref |


Hole sizes:
~~~~~~~~~~~~~~~~~~

The hole size on this EIB (0.3mm) is suited for use with SMALL neuralynx gold pins (http://neuralynx.com/products/electrode_interface_boards/eib_pins) 

The three mounting holes for optical fiber ferrules are sized for use with 1.25mm OD ferrules.

See the documentation on http://github.com/open-ephys/flexDrive for building and use instructions.


Fabrication instructions:
~~~~~~~~~~~~~~~~~~

This EIB can be fabricated with the following process
- 5mil trace with / 5mil trace space
- gold immersion finish
- 0.03 inch board thickness (not critical, can be made thicker)
- top silkscreen

