# P2-Panel-Light-Measure
Using BH1750s to measure HUB75 Panel output - running on the Parallax P2 Processor

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE) 

The point of this project is to instrument our HUB75 panel with light sensors so we can directly measure the emitted light from our LEDs.  Our Goal is to identify 16 distinct grey scale value so we can imporove our color presentation of the panels.

We hypothesize that this will force us to move from a simple PWM to a more advanced PWM.

All of the driving of the panel, the measuring of the light values and reporting will take place on the Propeller 2 development hardware.

![ready to wire](images/ready4wiring.jpg)
**Fig 1 - Our panel waiting for wiring harness**

See also [Fixture Mechanical Design](Mechanism.md)

## The project


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
