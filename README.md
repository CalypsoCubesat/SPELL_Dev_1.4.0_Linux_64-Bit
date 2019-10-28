# Download SPELL

This download area contains the latest releases of SPELL (2.5.4) and SPELL-GUI (4.0.2). In addition to the source code, we provide the 32bit Windows/Linux binaries of SPELL-GUI as well.

**Note**: The documentation in the [Documentation](https://sourceforge.net/projects/spell-sat/files/Documentation/) folder refers to SPELL version 2.4.4 and is partly outdated (build manual, in particular).

# Release Notes

The latest releases of SPELL (2.5.4) and SPELL-GUI (4.0.2) contain a number of bug fixes an features, here are the highlights:

### SPELL
  
  - Hardening of the SPELL protocol and context in case of connection failures, client crashes, and unexpected input
  - Improved performance of LoadDictionary function and file imports
  - Fix binary operators bw,nbw skipping the last retry
  - Fix Verify precision for large float number comparisons

### SPELL-GUI

 - "Force Prompt Confirm" option to confirm operator inputs
 - Significant improvement of procedure execution speed with low ExecutionDealy (<80ms)
 - Fix "Memory left" calculation and display
 - Migration to Eclipse Neon 4.6.2

# Getting Started

As of version 2.5.0, SPELL and SPELL-GUI are built separetely. For SPELL-GUI, the easiest way is to download the binary packages. To build SPELL on Linux, please refer to the INSTALL file in the source folder. Afterwards, please read the [Documentation](https://sourceforge.net/projects/spell-sat/files/Documentation/) and contact us if you have any questions or problems!