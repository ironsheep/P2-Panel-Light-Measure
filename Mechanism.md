#  Instrumenting the HUB75 Matrix for measurement

Applying light sensors to our HUB75 Panels so we can directly measure emitted light.  

To recap:
The point of this project is to instrument our HUB75 panel with light sensors so we can directly measure the emitted light from our LEDs.  Our Goal is to identify 16 distinct grey scale values so we can imporove our color presentation of the panels.

We hypothesize that this will force us to move from a simple PWM to a more advanced PWM.

[![License][license-shield]](LICENSE) 


## The hardware

For this project we are using three BH1750 ambient light sensors. These are wired up to a common I2C bus and each BH1750 has its own device enable line.  We want to be able to measure the LED light output unaffected by ambient light aound our testbench so we build a shroud to block out room light from between the RGB Matrix panel and the BH1750 sensor.  We 3D printed the shroud parts and mounted the BH1750's to the new shrouds which are in-turn clipped to the Matrix Panels.

## The fixture design

![Modeling our BH1750 Fixture](images/3d-model.jpg)

**NOTE** the shroud opening is 24mm x 24mm to accommodate P2 (2mm), P3 (3mm), and P4 (4mm) distances between LEDs (as well as other multiples).

![Installing the BH1750](images/installing-bh1750.jpg)

The shroud features M2 screw holes and voids where R,C parts interfere witht he PCB supports.

![Interior design of the shroud](images/theShroud.jpg)



## The fixture with BH1750 installed


![Three assembled](images/sensors-ready.jpg)

The three shrouds are assembled.

![Mounted on panel](images/thePanelMounts.jpg)


...And then clipped onto the panel, now ready for the wiring harness.

---

> If you like my work and/or this has helped you in some way then feel free to help me out for a couple of :coffee:'s or :pizza: slices! 
> 
> [![coffee](https://www.buymeacoffee.com/assets/img/custom_images/black_img.png)](https://www.buymeacoffee.com/ironsheep)

---

## License

Copyright © 2021 Iron Sheep Productions, LLC. All rights reserved.<br />
Licensed under the MIT License. <br>
<br>
Follow these links for more information:

### [Copyright](copyright) | [License](LICENSE)



[maintenance-shield]: https://img.shields.io/badge/maintainer-stephen%40ironsheep%2ebiz-blue.svg?style=for-the-badge

[marketplace-version]: https://vsmarketplacebadge.apphb.com/version-short/ironsheepproductionsllc.spin2.svg

[marketplace-installs]: https://vsmarketplacebadge.apphb.com/installs-short/ironsheepproductionsllc.spin2.svg

[marketplace-rating]: https://vsmarketplacebadge.apphb.com/rating-short/ironsheepproductionsllc.spin2.svg

[license-shield]: https://camo.githubusercontent.com/bc04f96d911ea5f6e3b00e44fc0731ea74c8e1e9/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f69616e74726963682f746578742d646976696465722d726f772e7376673f7374796c653d666f722d7468652d6261646765
