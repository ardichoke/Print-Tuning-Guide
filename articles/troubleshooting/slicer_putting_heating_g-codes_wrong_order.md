[:arrow_left: Back to Table of Contents](/README.md)
# Slicer is Putting Heating G-codes in the Wrong Place/Order

For example:

- Your `PRINT_START` macro is running before your hotend or bed heat up. 

- Or you wish for your heating commands to come after `PRINT_START`, or to have one heater to heat before your start g-code, and one after.

The two options below allow you to control this order.

- Pass variables to `PRINT_START` (allows the most control, but is more complex)
    - See the *"Passing Variables to PRINT_START"* article 
    [:page_facing_up:here](/articles/passing_slicer_variables.md).

- Force g-code ordering (only allows changing the g-code order, but is easy to set up)

    - See the *"Controlling Slicer Temperature G-Code Order (Simple Method)"* article [:page_facing_up:here](/articles/controlling_slicer_g-code_order.md).