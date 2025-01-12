# Minisforum UM790 Pro Dual 120mm Fan Antenna Mod

Thank's to [peteh](https://github.com/peteh/um790-pro-120mm-fan-case) for the inspiration.

![Minisforum UM790 Pro Dual 120mm Fan Mod](/images/IMG_20250112_120347_443.jpg)

## Description

This mod focuses on improving Bluetooth/Wi-Fi connection quality and reducing the overall heat of the components.
The main goal was to reuse the available fan connectors for the RAM/SSD and CPU fan, without losing the ability to revert everything back to stock.

I use this PC with my TV while sitting on the couch. The distance is about 4 meters, and no matter what kind of wireless controller I used, the connection quality was poor.
With the (ugly) antenna mod, I was able to play from the second floor without any connection drops.

For the new CPU heatsink, I tried several models. Since I wanted to keep the original heatsink in place to cover the different chipsets and account for the height differences between them, the available space was limited.
My final choice was the _"Dell Precision T3500 T5500 T7500 Primary CPU Heatsink T021F"_. It was the largest one I could find that fit into the space after cutting the socket mounting holes, resulting in the following dimensions: width: **65 mm, height: 86 mm, depth: 90 mm**
Before the heatsink upgrade, I had temperatures of 75°C. After the upgrade, the temperature dropped to 51°C while the fan ran at medium speed. I used [FurMark](https://geeks3d.com/furmark/) in both cases for the GPU stress test.

Besides the necessary parts listed below, you will also need to solder the DIY fan adapter, as the UM790 motherboard uses a non-standard fan connector.

## List of used parts

This list includes the necessary parts for the DIY fan adapter. You can use the Amazon affiliate links to purchase them (check the quantity of each part), or find similar parts online.
You will also need some basic tools for soldering, cutting, bending, insulating, etc.

| Name                                                                 | Affiliation Link                    | Quantity                   | Image                                                                                                                                              |
| -------------------------------------------------------------------- | ----------------------------------- | -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fan Cable Extension PWM 4-Pin Molex                                  | https://amzn.to/4gRze8a             | 2                          | ![Fan Cable Extension PWM 4-Pin Molex](/images/Screenshot_20250112_115219.png)                                                                     |
| M3 x 5 mm Screw                                                      | https://amzn.to/4afPldk             | 24                         | ![M3 x 5 mm Screw](/images/Screenshot_20250112_115347.png)                                                                                         |
| Press-in Nuts, Thread Insert M3                                      | https://amzn.to/4gQj4vZ             | 24                         | ![Press-in Nuts, Thread Insert M3](/images/Screenshot_20250112_115704.png)                                                                         |
| Micro JST MX 1.25mm 4 Pin                                            | https://amzn.to/427EAaP             | 2                          | ![Micro JST MX 1.25mm 4 Pin](/images/Screenshot_20250112_115715.png)                                                                               |
| M4 Screws and Nuts M4x60mm                                           | https://amzn.to/4gQj4vZ             | 4                          | ![M4 Screws and Nuts M4x60mm](/images/Screenshot_20250112_115853.png)                                                                              |
| 120mm PWM 4-pin fan                                                  | https://amzn.to/40gyPoK             | 2                          | ![120mm PWM 4-pin fan](/images/Screenshot_20250112_115953.png)                                                                                     |
| Fan Grille 120 mm Dust Filter                                        | https://amzn.to/3DV0Uuw             | 2                          | ![Fan Grille 120 mm Dust Filter](/images/Screenshot_20250112_120214.png)                                                                           |
| IPEX 4 to RP SMA Cable, RP-SMA Antenna to NGFF/M.2 WiFi Network Card | https://amzn.to/3C8Geyp             | 2                          | ![IPEX 4 to RP SMA Cable, RP-SMA Antenna to NGFF/M.2 WiFi Network Card](/images/Screenshot_20250112_120334.png)                                    |
| M4 Spring Washers and Washers                                        | https://amzn.to/3PyqiZC             | 8                          | ![M4 Spring Washers and Washers](/images/Screenshot_20250112_120607.png)                                                                           |
| RP-SMA WiFi Antenna                                                  | https://amzn.to/4fXcnXJ             | 2                          | ![RP-SMA WiFi Antenna](/images/Screenshot_20250112_120722.png)                                                                                     |
| M2 SSD Heatsink                                                      | https://amzn.to/4gPVX4F             | 2 (when two SSDs are used) | ![M2 SSD Heatsink](/images/Screenshot_20250112_141204.png)                                                                                         |
| Iron Wire 1.0 mm                                                     | https://amzn.to/3WE2qHZ             | 1                          | ![Iron Wire 1.0 mm](/images/Screenshot_20250112_145226.png)                                                                                        |
| CPU Heatsink                                                         | I got mine from a local marketplace | 1                          | ![CPU Heatsink](/images/IMG_20250111_193746.jpg) ![CPU Heatsink](/images/IMG_20250111_193710.jpg) ![CPU Heatsink](/images/IMG_20250111_193643.jpg) |
| CPU Thermal Paste                                                    | https://amzn.to/40qAPfr             | 1                          | ![COU Thermal Paste](/images/Screenshot_20250112_153623.png)                                                                                       |
| Heat Shrink Tubing for Electrical Insulation                         | https://amzn.to/40yh7i8             | 8                          | ![Heat Shrink Tubing for Electrical Insulation](/images/Screenshot_20250112_155048.png)                                                            |
| Heat Resistant Tape                                                  | hhttps://amzn.to/4jaZ9tc            | 1                          | ![Heat Resistant Tape](/images/Screenshot_20250112_162531.png)                                                                                     |

## 3D Printed Files

If you don’t have a 3D printer, I recommend [FDM-Druckservice](https://fdm-druckservice.de/produkt/fdm-designer/) for the European region. (I once ordered the Xenomorph head, which you can see on my PS5 in the cover photo, printed using this service.)

![3D View](/images/Screenshot_20250112_105521.png)

I used no special settings for printing with PLA. The infill was set to 15%, the layer height was set to 0.2 mm, and no support was used.

You will need to print the following parts:

- 4x spacer-bottom.stl
- 4x spacer-top.stl
- 1x case-adapter-bottom.stl
- 1x case-adapter-top.stl
- 1x fan-case-big.stl
- 1x fan-case-small.stl
- 1x fan-cover.stl

## Preparations

### Soldering

You need to create the following DIY fan adapter:

![DIY fan adapter](/images/IMG_20241225_231007_794.jpg)

Use the Molex cable extension and the Micro JST MX cable together to create the DIY fan adapter.
Make sure to double-check the wiring. You will have 4 wires:

- GND
- 12V
- Tachometer
- PWM

Do not look at the wire color! Your's might be different! Use following pictures as reference:

![PIN out](/images/IMG_20241225_230612_231~2.jpg)
![PIN out](/images/IMG_20241225_211623_613~2.jpg)

### Cutting

If you are using the same heatsink, you will need to cut the original mounting points:

![Cutting](/images/IMG_20250111_164254_712.jpg)
![Cutting](/images/IMG_20250111_164245_699.jpg)
![Cutting](/images/IMG_20250111_164239_328.jpg)

### 3D Parts

To connect the different parts, you will need to insert the M3 press-in nuts using a soldering iron. Watch your temperatures! You want the thread insert to slide in slowly and not get too hot, or it will simply slide through the plastic.

![thread insert](/images/IMG_20241226_002441_336.jpg)
![thread insert](/images/IMG_20241226_004501_312.jpg)
![thread insert](/images/IMG_20241226_004412_513.jpg)

### SSD Heatsink

Because the SSD is mounted downward, I did not trust securing the heatsink with only the two rubber pieces. I also used heat-resistant tape:

![SSD heatsink](/images/IMG_20241226_003103_649.jpg)
![SSD heatsink](/images/IMG_20241226_162900_319.jpg)

## Installation

I didn't take photos of the disassembly process. Just unscrew everything until you're left with the housing and the motherboard.

1. Remove the CPU fan. It is mounted with four screws and black heatsink tape.
2. Take the RP SMA antenna cable and screw it into the _case-adapter-top.stl_.
3. Use M4x60mm screws, M4 nuts, and M4 washers to connect _case-adapter-bottom.stl_ and _case-adapter-top.stl_ to the UM790 housing. Also, use the four _spacer-top.stl_ and the four _spacer-bottom.stl_ to eliminate any gaps between the 3D-printed parts and the UM790 housing. (Don't be confused by the small heatsink in the pictures. I used it in my first assembly attempt).
   ![Installation](/images/IMG_20241226_005814_328.jpg)
   ![Installation](/images/IMG_20241226_010033_276.jpg)
   ![Installation](/images/IMG_20241226_010644_546.jpg)
   ![Installation](/images/IMG_20241226_010846_593.jpg)
   ![Installation](/images/IMG_20241226_011519_932.jpg)

4. Connect the antenna cable to the Wi-Fi card.
5. Mount the SSD.
   ![Installation](/images/IMG_20241226_163013_717.jpg)
6. To secure the new CPU heatsink, I used 1mm iron wire. Twist the wire so it can be screwed onto the original heatsink mounting points.
   ![Installation](/images/IMG_20241222_135110_430.jpg)
   ![Installation](/images/IMG_20241222_132405_958.jpg)
   ![Installation](/images/IMG_20241222_133011_815.jpg)
7. Place the new heatsink temporarily to measure the needed length of the 1mm iron wire by pulling the wire through the heatsink and repeating the twisting process.
   ![Installation](/images/IMG_20241221_001003_874.jpg)
8. Connect the CPU DIY fan adapter to the motherboard and apply the CPU thermal paste to the copper heatpipe.
   ![Installation](/images/IMG_20241231_184656_385.jpg)
9. Take the new heatsink and screw it into place. Use the original screws and additional washers, along with the 1mm iron wire, to secure the heatsink and prevent it from moving.
   ![Installation](/images/IMG_20250111_172743_460.jpg)
   ![Installation](/images/IMG_20250111_172752_074.jpg)
   ![Installation](/images/IMG_20250111_172801_897.jpg)
10. Take your fans, the fan covers, both _fan-case-small.stl_ and _fan-case-big.stl_, and screw everything together.
    ![Installation](/images/IMG_20241226_000647_469.jpg)
    ![Installation](/images/IMG_20241226_001016_002.jpg)
    ![Installation](/images/IMG_20241226_001046_740.jpg)
    ![Installation](/images/IMG_20241226_000626_787.jpg)
11. For the bottom fan, use the _fan-cover.stl_ to cover the inside of the fan so that no wires can touch the fan blades.
12. To add some space between the bottom fan and the ground, use the original rubber base feet.
    ![Installation](/images/IMG_20241226_170456_535.jpg)
13. Take the _fan-case-small.stl_, connect the DIY fan adapter to the mainboard and the fan. Place the UM790 on top and screw everything together with the M3 screws.
    ![Installation](/images/IMG_20241223_011701_772.jpg)
    ![Installation](/images/IMG_20241223_011859_777.jpg)
14. Take the _fan-case-big.stl_, connect the DIY fan adapter to the fan, and screw everything together as shown in step 13.

## Done

That's it! I hope you like it.

In my first attempts, I used smaller heatsinks. If you want to try it with a smaller heatsink, you can use the _fan-case-small.stl_ part for both the top and bottom.
Here are some pictures of the smaller tower:

![Done](/images/IMG_20241228_155307_800.jpg)
![Done](/images/IMG_20241226_170919_736.jpg)
![Done](/images/IMG_20241226_170910_618.jpg)
