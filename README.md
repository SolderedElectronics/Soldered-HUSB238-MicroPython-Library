# Soldered HUSB238 MicroPython Library

> **Note:** this board is not yet released.

This library drives boards built around the HUSB238 USB-C Power Delivery sink controller, letting a microcontroller query and request a specific PD voltage/current profile from a USB-C PD charger over I2C (fixed address 0x08). Supports reading source capability (5V/9V/12V/15V/18V/20V PDOs), requesting a specific voltage, and reading attach/PD-response status.

## How to install

---

After [**installing the mpremote package**](https://docs.micropython.org/en/latest/reference/mpremote.html), install the library on your board using the following command:

```sh
  mpremote mip install github:SolderedElectronics/Soldered-HUSB238-MicroPython-Library
```
Or, if you're running a Windows OS:

```sh
  python -m mpremote mip install github:SolderedElectronics/Soldered-HUSB238-MicroPython-Library
```

### Repository Contents

- **husb238.py** - MicroPython driver class
- **package.json** - mip install manifest
- **/Examples** - basic reading and voltage-request examples

### Hardware design

You can find hardware design for this board in the HUSB238 hardware repository.

### Documentation

Access library documentation [here](https://docs.soldered.com).

### About Soldered

![Soldered Logo](https://raw.githubusercontent.com/SolderedElectronics/Soldered-Generic-Arduino-Library/dev/extras/Soldered-logo-color.png)

At Soldered, we design and manufacture a wide selection of electronic products to help you turn your ideas into acts and bring you one step closer to your final project. Our products are intented for makers and crafted in-house by our experienced team in Osijek, Croatia. We believe that sharing is a crucial element for improvement and innovation, and we work hard to stay connected with all our makers regardless of their skill or experience level. Therefore, all our products are open-source. Finally, we always have your back. If you face any problem concerning either your shopping experience or your electronics project, our team will help you deal with it, offering efficient customer service and cost-free technical support anytime. Some of those might be useful for you:

- [Web Store](https://www.soldered.com/shop)
- [Tutorials & Projects](https://soldered.com/learn)
- [Documentation](https://docs.soldered.com)

### Open-source license

Soldered invests vast amounts of time into hardware & software for these products, which are all open-source. Please support future development by buying one of our products.

Check license details in the LICENSE file. Long story short, use these open-source files for any purpose you want to, as long as you apply the same open-source licence to it and disclose the original source. No warranty - all designs in this repository are distributed in the hope that they will be useful, but without any warranty. They are provided "AS IS", therefore without warranty of any kind, either expressed or implied. The entire quality and performance of what you do with the contents of this repository are your responsibility. In no event, Soldered (TAVU) will be liable for your damages, losses, including any general, special, incidental or consequential damage arising out of the use or inability to use the contents of this repository.

## Have fun!

And thank you from your fellow makers at Soldered Electronics.
