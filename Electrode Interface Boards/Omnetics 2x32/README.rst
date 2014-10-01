2x Omnetics 36-channel "nano-strip" connectors, 4 guide posts
---------------------------------------------------------------------------------

The 64ch_eib_omnetics_3fibers Electrode Interface Board  (EIB) is designed to form a connection between 64 microwire electrodes or individual wires forming stereotrodes or tetrodes, and two 32 channel omnetics connectors.

The 'offset variant' provides more space between the two omnetics connectors and can be soldered by hand if needed, but won't fit the 64 channel headstage.

The aligned variant fits the 64 channel headstage, and can also be used with 2x 32 channel headstages, if they're aligned with the PCB facing away from the center (this will affect the channel mapping).

See the documentation on https://open-ephys.atlassian.net/wiki/display/OEW/flexDrive for building and use instructions.

**WARNING:** These designs will not work if fabricated as 'standard quality' PCB, see Fabrication instructions and get in touch with your PCB maker before placing orders!

Connectors on EIB:
~~~~~~~~~~~~~~~

* male surface-mount vertical (A79026-001 / NPD-36-VV-GS)

Connectors on Headstage:
~~~~~~~~~~~~~~~~~~
 
* female surface-mount horizontal (A79025-001 / NSD-36-AA-GS)
* female surface-mount vertical (A79027-001 / NSD-36-VV-GS)


Pin mapping:
~~~~~~~~~~~~~~~~~~
The pin mapping for the GROUND and REFERENCE channels on the offset connector EIB are compatible with the mapping on the Intan evaluation system headstages (http://www.intantech.com/files/Intan_RHD2000_eval_system.pdf) and the open-ephys headstages (open-ephys.org)

(viewed down onto the eib, looking onto the bottom of the headstage connector this would be flipped)

| ref  | ch | ch | ... | ch | gnd |
| gnd | ch | ch | ... | ch | ref |

For channel mappings of individual EIB designs, look at the documenttaiopn in that EIBs folder. Orientation of headstages affects the channel mapping - when in doubt you should sanity check your mapping by connecting a EIB to your system and grounding out or injecting a signal on individual vias.


Hole sizes:
~~~~~~~~~~~~~~~~~~

The hole size on this EIB (0.3mm) is suited for use with SMALL neuralynx gold pins (http://neuralynx.com/products/electrode_interface_boards/eib_pins) 

The three mounting holes for optical fiber ferrules are sized for use with 1.25mm OD ferrules.

See the documentation on https://open-ephys.atlassian.net/wiki/display/OEW/flexDrive for building and use instructions.


Fabrication instructions:
~~~~~~~~~~~~~~~~~~

These EIBs can be fabricated with the following process
- 5mil trace with / 5mil trace space
- gold immersion finish
- 0.03 inch board thickness (not critical, can be made thicker)
- top silkscreen

