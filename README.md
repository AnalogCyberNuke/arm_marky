# arm_marky
ARM differential fuzzer for ARM (de/en)coders

AM works by proposing random sequences and verifying against real ARM hardware (arm_marky_client) or by verifying against another (de/en)coder.
To do verification against other encoders a translation mapping is required for either the internal structural representation, or, a translation mapping for the resulting formatted output.

This project will be fully released with over 1000(!) encoding bugs in popular ARM encoders (mostly llvm), when the accompanying talk has been given at a TBA conference.
