# c264-magic-cart 44-pin

![GitHub release (latest by date)](https://img.shields.io/github/v/release/SukkoPera/c264-magic-cart-44pin)
![GitHub Release Date](https://img.shields.io/github/release-date/SukkoPera/c264-magic-cart-44pin?color=blue&label=last%20release)
![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/SukkoPera/c264-magic-cart-44pin/latest?color=orange)

c264-magic-cart is a cartridge for the Commodore 264 series of computers - Commodore 16, 116 and Plus/4.

![Board](https://raw.githubusercontent.com/SukkoPera/c264-magic-cart-44pin/main/img/render-top.png)

## Summary
This is a 44-pin variant of [the original project by Marko Šolajić](https://github.com/msolajic/c264-magic-cart).

This version is still aimed at the C16/C116/Plus4 and it **requires** the usage of a [Plus4MultiExpander](https://github.com/SukkoPera/Plus4MultiExpander) or something similar. It is NOT compatible with the C64/C128.

Isn't Open Hardware great?

## Usage
The project was migrated to KiCad, during which the nice graphics were lost. Apart from that and changing the connector, I only made minor modifications, mostly to switch to standard KiCad footprints.

The only significant difference is the introduction of JP4 and JP5 in order to run the cartridge from the C2 slot. This is experimental and untested, so just set them both to center-left in order to run from the C1 slot as the original project does.

If you plan to use this at the same time as the EPROM slot on [TCBM2SD](https://github.com/SukkoPera/tcbm2sd-44pin), you will probably need an updated JED file for the latter, which is yet unreleased at the time of writing, so please check again later.

Please refer to [the original project](https://github.com/msolajic/c264-magic-cart) for GAL files, documentation, instructions, etc.

## Releases
If you want to get this board produced, you are recommended to get [the latest release](https://github.com/SukkoPera/c264-magic-cart-44pin/releases) rather than the current git version, as the latter might be under development and is not guaranteed to be working.

Every release is accompanied by its Bill Of Materials (BOM) file and any relevant notes about it, which you are recommended to read carefully.

## License
The original c264-magic-cart is Open Hardware licensed under the [CERN OHL v. 1.2](https://spdx.org/licenses/CERN-OHL-1.2.html), released by Marko Šolajić in 2021.

This 44-pin version is copyright &copy; SukkoPera 2026 and is licensed under the same license.

## Thanks
- Marko for his amazing work.
- Tadeusz Klimaszewski for coming up with the idea of porting this project to the 44-pin connector and testing it.
