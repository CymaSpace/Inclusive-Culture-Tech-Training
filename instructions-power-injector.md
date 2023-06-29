# Assembling & Using WLED PICO & the USB C Power Injector

## Materials needed:
1. 1x Female JST Connector (or locking barrel type for 12V)
2. 1x Male JST Connector.
3. USB PD Trigger Board.
4. 3D Printed protective case for strain relief.
5. Wire stripper.

## Asembly Steps
1. Unscrew the green terminals using a small flat-head screw driver.
2. Strip the wires to leave 1/4" of wire exposed on all the JST connector ends.
3. Insert the USB C PD Trigger into enclosure, ensure the JST Connect cables are inserted throught the strain relief holes.
4. Take 1x Female and 1x Male JST Connector and using a Wago nut (or solder together) the green wires
5. Using those same JST connectors twist together the red wires, and insert them into the USB C PD Trigger `VBUS` terminal.
6. Using those same JST connectors, twist together the white wires, and insert them into the USB C PD Trigger `GND` terminal.
7. Test the connections (should see a blue LED turn on the PD Trigger Board when USB C cable is connected to it. Should see the WLED Pico red led power when connecting the female JST connector to it).
8. Add the top to the enclosure (press fit).