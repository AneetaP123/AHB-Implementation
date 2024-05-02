AHP – Advanced High Performance Bus​
AMBA AHB is a bus interface suitable for high-performance synthesizable designs. ​

It defines the interface between components, such as Managers, interconnects, and Subordinates. ​

AMBA AHB implements the features required for high-performance, high clock frequency systems including: ​

• Burst transfers ​

• Single clock-edge operation ​

• Non-tristate implementation ​

• Configurable data bus widths ​

• Configurable address bus width​

AHP Block diagram
The most common AHB Subordinates are internal memory devices, external memory interfaces, and high-bandwidth peripherals. ​

AHB also supports multi-Manager designs by the use of an interconnect component that provides arbitration and routing signals from different Managers to the appropriate Subordinates.​

Interconnect
An interconnect component provides the connection between Managers and Subordinates in a system.​

A multi-Manager system requires the use of an interconnect that provides arbitration and the routing of signals from different Managers to the appropriate Subordinates. This routing is required for address, control, and write data signaling​

Decoder : This component decodes the address of each transfer and provides a select signal for the Subordinate that is involved in the transfer. It also provides a control signal to the multiplexor.​

Multiplexor A Subordinate-to-Manager multiplexor is required to multiplex the read data bus and response signals from the Subordinates to the Manager. The decoder provides control for the multiplexor​
