# open-register-design-tool
This repo is a work in progress...

Ordt is a tool for automation of IC register definition and documentation.  It currently supports 2 input formats:
  1. SystemRDL - a stardard register description format released by Accellera.org (see http://accellera.org/activities/working-groups/systemrdl)
  2. JSpec - a register description format used within Juniper Networks

The tool can generate several outputs from SystemRDL or JSpec, including:
  - SystemVerilog/Verilog RTL code description of registers
  - UVM model of the registers
  - XML and text file register descriptions
  - SystemRDL and JSpec (conversion)