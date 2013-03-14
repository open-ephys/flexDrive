The flexDrive is an implant for chronic extracellular electrophysiology.

The design of the flexDrive and all associated components is released under the The TAPR Open Hardware License.


Get the latest revision of the design source files at http://github.com/open-ephys/flexDrive


Editing the .brd files requires the free version of Cadsoft Eagle (http://www.cadsoftusa.com/)






2013 Jakob Voigts, Joshua H Siegle, Dominique L Pritchett, Christopher I. Moore






About:
The 64ch_eib_omnetics_3fibers Electrode Interface Board  (EIB) is designed to form a connection between 64 microwire electrodes or individual wires forming stereotrodes or tetrodes, and two 32 channel omnetics connectors.

The pin mapping for the GROUND and REFERENCE channels on this EIB are compatible with the mapping on the Intan evaluation system headstages (http://www.intantech.com/files/Intan_RHD2000_eval_system.pdf) and the open-ephys headstages (open-ephys.org)

(viewed down onto the eib, looking onto the bottom of the headstage connector this would be flipped)
| ref  | ch | ch | ... | ch | gnd |
| gnd | ch | ch | ... | ch | ref |

The hole size on this EIB (0.3mm) is suited for use with SMALL neuralynx gold pins (http://neuralynx.com/products/electrode_interface_boards/eib_pins) 

The three mounting holes for optical fiber ferrules are sized for use with 1.25mm OD ferrules.

See the documentation on http://github.com/open-ephys/flexDrive for building and use instructions.



Fabrication instructions:

This EIB can be fabricated with the following process
- 5mil trace with / 5mil trace space
- gold immersion finish
- 0.03 inch board thickness (not critical, can be made thicker)
- top silkscreen

