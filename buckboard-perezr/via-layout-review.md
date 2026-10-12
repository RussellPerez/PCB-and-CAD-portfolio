#Function

A lot of your parts are very close to the edge of the pcb but it doesnt fail DRC so

Looks great

There's not really a need for the 499k resistor because we aren't using the PG pin. If you read the datasheet, the PG pin is meant for a MCU to know if the power is good/not, thus why it's routed to a test point. Since we don't have that nor are we routing it back to the MCU, we don't need it.

#Design

Good use of the copper pours

Could delete the user drawings so it's easier to read your PCB / move them around too.

It's worth looking at your PCB in the 3D view. I think you might want to consider moving your connector to have the headers face an edge.
