Welcome!

This is a portscanner made entirely with Python.

The portscanner currently utilizes AF_INET(IPv4) and SOCK_STREAM(TCP).

You can add hostname or IPv4 in adst(Add Destination).

You can either add ports manually(aports in the DST-unit) or use range to define from start-to-end on how many ports it should scan(qs-quickscan in the SCAN-unit).

There is also the ability to remove ports(rports in the DST-unit) and remove destinations(rdsts - in the DST-unit)

----
I also tested socket.recv() and I received a message from the MobaXterm FTP client that I hosted and it is sort-of a "Version control", it is experimental while I am trying to figure it out. It can find services attached to (standard or non-standard)ports that send a message.

Still a noob with Github but I am learning.
