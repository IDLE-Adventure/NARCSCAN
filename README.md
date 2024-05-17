Welcome!

This is a portscanner made entirely with Python.

The portscanner currently utilizes AF_INET(IPv4) and SOCK_STREAM(TCP).

You can add hostname or IPv4 in adst(Add Destination).

You can either add ports manually(aports in the DST-unit) or use range to define from start-to-end on how many ports it should scan(qs in the SCAN-unit).

There is also the ability to remove ports(rports in the DST-unit) and remove destinations(rdst - in the DST-unit)

It utilizes socket.getservbyport to determine the service on the port.
