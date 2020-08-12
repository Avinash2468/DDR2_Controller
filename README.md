# DDR2_controller

DDR2 RAM controller is a digital circuit that manages the flow of data going to and from the computer's main memory. A memory controller can be a separate chip or integrated into another chip, such as being placed on the same die or as an integral part of a microprocessor.

**The following modules make up the DDR2 SDRAM Controller**

- Control Interface Unit

```
A control interface module accepts the commands
from the processor and decodes the command and
provides the request to the command module. It is
basically an 8 state FSM with each state representing
the command like NOP ,REFRESH, READ, WRITE,
etc .

```
- Command Module

```
The basic function of the command module is to get
its control signal from the control interface module
and generate the addresses for the SDRAM.
Command module consists of an arbiter ,multiplexer
and three shift registers.

```

- Data Path Module

```
This module is used to read from the RAM or write to the RAM.

```

**For more info, refer to Report.pdf**
