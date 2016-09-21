# Upgrading the printer

I have enjoyed my Robo3D R1+ since Christmas 2015. It works really well and I haven't had too many issues with it, but I was born a tinkerer. E3D recently came out with a few interesting things, the Titan extruder and the v6 hot end with a little silicone sleeve to keep the block clean. Well I obviously need this. I was also made aware of a new controller board gaining some traction, the Duet WiFi. It is time for an upgrade.

### First things first

The printer came with some cable management, a tube of plastic to hold all of the extruder and hot end wire. Not near cool enough. I found a great cable chain model on thingiverse.com and began printing. 38 links later and that was done. This upgrade also fully replaces the extruder and extruder motor on the machine. I will need a new mounting plate, also found this model on thingiverse. 

### Extruder and hot end

Once these were printed I was ready to go. I purchased a fully assembled extruder, it was only a couple bucks more. Attaching the extruder to the hot end was simple, following the E3D instructions it came together just fine. I needed to replace the stock bolts that held the old extruder in place as they were a bit too for the new pieces.

After threading the hot end through the carriage, I was able to bolt down the new mounting plate and run all of the wire through the cable chain to the wire access hole in the case. At this point I could just hook up to the Arduino in the correct spaces, update my firmware, and start printing.

### Duet WiFi

I still had this Duet board to swap in. Going with the Duet gives my printer a _much_ beefier platform for processing g-code as well as direct access to my WiFi. This means I can initiate prints from anywhere in the house, update firmware via the web interface, check print status while cooking dinner, and a few other niceties. The board was very clearly labeled and hooking it up caused no real issues. 

### BOM

| Quantity | Item                                     | Cost each |   Total |
| -------- | ---------------------------------------- | --------: | ------: |
| 1        | [Duet WiFi](http://www.filastruder.com/collections/electronics/products/duet-wifi) |   $170.00 | $170.00 |
| 1        | [Titan Extruder](http://www.filastruder.com/collections/titanextruder/products/e3d-titan-extruder) |    $65.00 |  $65.00 |
| 1        | [E3D V6](http://www.filastruder.com/collections/e3d-hotends/products/all-metal-e3d-v6-hotend-assembled) |    $85.00 |  $85.00 |
|          |                                          |           | $320.00 |








