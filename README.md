# Remora-RT1052

Remora-RT1052 is a port of Remora firmware for the Digital Dream Ethernet CNC controllers. This firmware allows these Mach3 boards to be used with LinuxCNC.

Supported boards: NVEM, EC300, EC500

v1.0 of the firware now has dynamic configuration capability via TFTP upload of a configuration file. This allows users to load only the modules needed for their application and to assign IO numbering as required.

v1.0.0 released for testing.

v2.1.0 released. Stepgen running at up to 500khz via DMA.

v3.0.0 released 15.11.23. Major change to Remora-eth component.

v3.1.0 released 17.11.23. Addition of dirHold parameter to DMA stepgen.

v3.1.1.bug fix released 2.12.23. Fixed direction not always correct in DMA stepgen.
