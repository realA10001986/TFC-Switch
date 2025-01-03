# TFC Switch

This [repository](https://tfc.out-a-ti.me) holds some instructions for building a TFC Drive Switch as known from the Delorean Time Machine.

<img src="img/mytfc.jpg">
<img src="img/total1.jpg">
<img src="img/total2.jpg">

This switch is fully compatible with CircuitSetup's [Time Circuits Display](https://tcd.out-a-ti.me) kit. Rotating the handle fake-powers on/off the TCD, and the "RESET" mushroom button triggers a time travel.

I tried to build it exactly like in the movies, which turned out to be a bit difficult as this switch looks different in the various cars used in the movies. The one currently on exhibition in the [Petersen Museum](https://www.petersen.org/vehicle-spotlights/1981-delorean-back-to-the-future) is the restored A-car, so it *should* be the most authentic one. However, it appears that, during restoration, the switch was taken out of a different car, as it is clearly not the one shown in the very first time travel scene (where Einstein travels one minute into the future, and Doc explains the Time Circuits to Marty). The box looks different, the labels are at different locations, and some more minor differences. Also the back side, which is hardly ever visible in Part I (only at the end, when Marty waits for the alarm to go off), looks different in every time, as does the knob at the very front of the box.

After some consideration, I decided to go for the version shown first in the movies, ie in said scene with Einstein.

List of components and remarks:

### Box 

While for the cars shown later in the series and the one now in the Petersen Museum, they apparently used a Radio Shack 270-274, the box shown in the beginning of Part I looks a bit different. However, the Radio Shack version is no longer available.

[CircuitSetup](https://circuitsetup.us/product/tfc-drive-switch-aluminum-enclosure/) offers pre-cut/drilled boxes now. 

When I built my switches, those weren't available either. So I used a Teko model 384, which is approx. 7mm shorter and 7mm lower than the Radio Shack one. 
- https://www.reichelt.at/us/en/aluminium-housing-203x160x70-mm-teko-384-p21197.html?r=1
- https://www.teko.it/uploads/manuali/pdf/384.pdf
- https://www.soselectronic.com/en/products/teko/384-18-298999
- https://www.anteipaolucci.it/contenitori-metallici/contenitore-in-alluminio-203x160x695mm-teko-384-7838.html#

### Dayton Switch

These switches - going by Dayton Drum Switch 2X442 - are still made and available at [Grainger](https://www.grainger.com/product/DAYTON-Drum-Switch-Maintained-Reversing-2X442).

For the screws that hold it in place, I used [these](https://www.accu.co.uk/slotted-round-head-screws/368952-SFB-1-4-20-1-2-A2), 1/4-20 UNC, length 1".

Since the switch comes with a different type label, I sourced some replica stickers on ebay and attached them to a custom made aluminum plate. Dimensions are 88.0x32.0x0.5mm, corner radius 4mm.

The acrylic glass is 102mm wide, and some 250mm in overall length, 1mm thick. I bent it using a heat gun (160-170°C/320°F) and used the Dayton's original metal enclosure as a kind of mold; put the metal enclosure, a suitable piece of acyrlic (102mm wide, >=250mm in length) and a flat piece of wood into a machine vice, and carefully heat the acrylic (by moving the heat gun sideways, like in stripes) to bend it evenly over the metal. 

<img src="img/bending.png" height="200">

Next, in order to check shape and to mark length and screw holes, put it on the switch; it should fit without using force to bend it any further; if it doesn't you need to go over it with the heat gun again, otherwise you will get cracks over time. When it fits shape-wise, mark the length and cut off excess material with a box cutter; with minimum pressure cut along the line a few times, then break the glass over a sharp edge. 

The acrylic is held in place by the original Dayton screws, plus an elastic rubber washer in order to avoid cracks and scratches. The next step therefore is to mark the spots for the screw holes. Use a HSS (metal) drill (which should not be new, use it on metal a couple of times beforehand), and drill at very low speed, with minimum pressure on the material. Also, don't forget to put some paper tape on the back side before drilling, this will prevent cracks. I ended up drilling holes and cutting out the piece towards the bottom, so that I had "U" - or rather "V" - shaped holes. This gives you more flexibility when attaching the acrylic.

The most difficult part is attaching the handle.

The handle itself is a battery contact cleaner in real life, going under the name "Lynx" sometimes, and can be bought at [remybattery](https://remybattery.com/3-in-1-battery-cleaning-brush.html) in the US, or [at bikeshops](https://www.biketeile-service.de/en/electrics/battery/accessoriesforbatteries/3in1batterypostandterminalcleaner.html) in Germany. The one I got from the shop in Germany is [this one](https://www.lampa.it/en/articles/70021-3-in-1-battery-post-and-terminal-cleaner). They sometimes come with white covers which then obviously need painting.

In order to attach the handle to the switch, I bought a 1/4 inch drive extension set, cut one of those extensions in two parts and welded the male part, approx. 1.5cm in length, to the switch, right on top of the existing square end of the axle. Since the connection between male and female parts of this extension set was too loose for my taste, I welded a nut on top of the female end, and drilled out the thread so the nut holds the axle with the male end better in place. Then I adjusted the female part in length so that it fits exactly into the handle and its rear end touches the end of the handle's inside. That part also got some excess weld points and a few superficial cuts using a cutting disc, in order to make the surface as rough as possible. The final step was to pour some epoxy resin into the handle, immediately put the female part in and ... wait. I repeated that process until the epoxy level was close the the top of the metal part. Beware: There is a hole in the handle on the side of the golden brush where resin might flow out in the process; cover this with tape before starting.

<img src="img/dayt1.jpg">
<img src="img/dayt2.jpg">
<img src="img/dayt3.jpg">

In order to reduce stress on the handle when turning the switch, I exchanged the spring with a weaker one. Also, I added a washer at the rear end of the switch's axle in order to keep it better in place; without the washer, the small wheel inside the retention mechanism sometimes fell out when turning the switch.

### Mushroom button
I used an Allen-Bradley 800T-D with 800T-XA switch block, but I don't know if this is an Original part; could also be Eaton HT8CBR. It needs a bunch of washers to fix it in place; I used thick plastic washers to keep the weight down.

### Lights
Dialco (Dialight) vintage faceted green and red pilot light, 1" diameter. Green ones are a bit hard to find, though. These are not the ones with a thread on top; instead, they are just pushed into the holder.

<img src="img/glightlens.jpg">

### Pot button

The TFC switches had different buttons in the movies. I went for this one, as it looks like the one first shown:

Leviton 402-6616 Black

<img src="img/leviton.jpg">

The pot knob does nothing on my switches, but it could be attached to a [rotary encoder](https://tcd.out-a-ti.me#rotary-encoder) to set the speed on the speedometer. This requires two additional wires from/to the TCD (SDA, SCL for i2c connection; please consider cross-talk when choosing a cable). I didn't do that because that knob is not easily accessible, given its location below the handle.

### Switches

The side switches are standard toggle switches, in different sizes. I have no specific models for recommendation.

The switch with the green cover is a toggle switch with a safety cover (aka "aircraft guard cover"), it is available on ebay.

### Electronics

Not much of "electronics" inside; this switch is really only a switch that connects two wires for the TCD fake power when turning the Dayton switch, and two other wires when pressing the Mushroom button.

I made a small PCB acting as a switch board, using a mini relay for the lights; I used 12V GU4 LED bulbs for the green and red lights since low power standard LEDs were too weak for those thick Dialight lenses. (If you want to use LEDs with up to 5V voltage, you can connect them to the "LEDS" terminal and put a suitable resistor at R1.)

<img src="img/lamp.jpg">

If you want to install a rotary encoder, you need to wire SDA and SCL from the TCD as well. These are clocked signals, I therefore recommend using a twisted pair cable to avoid cross-talk. Pair both SDA and SCL with a GND wire. For more information on rotary encoder support, please see [here](https://tcd.out-a-ti.me#rotary-encoder).

Gerbers and EasyEDA-Std file is in the [Electronics](https://github.com/realA10001986/TFC-Switch/tree/main/Electronics) folder here. [JLCPCB](https://jlcpcb.com/) can make it for you; just create an account and upload the Gerber file. Then choose PCB color but leave the other production parameters at their default.

Additionally to the PCB, you need:
- 2x [Panasonic TQ2-5V](https://www.mouser.com/ProductDetail/Panasonic-Industrial-Devices/TQ2-5V?qs=HLLy2pIPwutHaTSpVfb1kw%3D%3D) or [Kemet EA2-5Nx](https://www.mouser.com/ProductDetail/KEMET/EA2-5NU?qs=UeqeubEbzTX2QGWq8LyCiw%3D%3D) or FRT5-5V mini relay
- 3x TE Connectivity [284514-4](https://www.mouser.com/ProductDetail/TE-Connectivity/284514-4?qs=woBvfblj%2Fzy48ih9AmO90g%3D%3D) (+1 for rotary encoder)
- 3x TE Connectivity [284506-4](https://www.mouser.com/ProductDetail/TE-Connectivity/284506-4?qs=pW%2FyRk%2FT1EFUJ80efaE%2FeA%3D%3D) (+1 for rotary encoder)
- 1x TE Connectivity [284514-3](https://www.mouser.com/ProductDetail/TE-Connectivity/284514-3?qs=woBvfblj%2FzwGS50caoQlYA%3D%3D)
- 1x TE Connectivity [284506-3](https://www.mouser.com/ProductDetail/TE-Connectivity/284506-3?qs=pW%2FyRk%2FT1EErkHTioRHy7Q%3D%3D) 
- 2x TE Connectivity [284514-2](https://www.mouser.com/ProductDetail/TE-Connectivity/284514-2?qs=woBvfblj%2FzwP8grZOAh0Gg%3D%3D) (+1 for rotary encoder)
- 2x TE Connectivity [284506-2](https://www.mouser.com/ProductDetail/TE-Connectivity/284506-2?qs=pW%2FyRk%2FT1EEEaP6r3xD3uw%3D%3D) (+1 for rotary encoder)

### Labels

- Rotex 880 or Dymo Office Mate II Label Maker 1540, with suitable font wheel
- Back side: 9mm (3/8"): "XMAS", "TREE", "REAR", "DECK", "PROJ.", "LAMP", "UP/CON", "CAP.", "PULSE", "DEAD", "FREON"
- Mushroom: 12mm (1/2"): "RESET"

For the red labels on the driver's side, see the [Labels](https://github.com/realA10001986/TFC-Switch/tree/main/Labels) folder in this repository.

_Text & images: (C) Thomas Winischhofer ("A10001986"). See LICENSE._ Source: https://tfc.out-a-ti.me
