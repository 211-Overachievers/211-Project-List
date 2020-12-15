# Lab-10: Interrupts and Preemptive Multitasking
 * `interrupt_example.s`, `config_GIC.s`, `interrupt_ID.s`, and `key_isr.s`, and `address_map_arm.s` together form an interrupt program for the keys of the DE1-SoC
    * Provided by the Intel FPGA Monitor program and CPEN 211 2020W
  * `part2.s` builds on `interrupt_example.s` to support clock interrupts
  * `config_GIC2.s` builds on `config_GIC.s` to support clock and keyboard interrupts
  * `part3.s` builds on `part2.s` to support keyboard interrupts
  * `part4.s` builds on `part3.s` to support time slicing between 2 programs, where program 1 is outputting keyboard interrupts to the terminal and program 2 is a counter that displays on the LED's