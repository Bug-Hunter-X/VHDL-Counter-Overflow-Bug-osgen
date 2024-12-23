# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL code: counter overflow.  The provided `counter_bug.vhdl` file contains a simple counter that increments on each clock cycle.  However, it lacks a mechanism to handle the situation when the counter reaches its maximum value.  This can lead to unexpected behavior and potential errors in the design.

The solution, found in `counter_solution.vhdl`, addresses this issue by adding a check to prevent the counter from exceeding its maximum value.