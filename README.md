# TWRP Device configuration for Motorola Moto One Power

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core 1.8 GHz Kryo 260
CHIPSET | Qualcomm SDM636 Snapdragon 636
GPU     | Adreno 509
Memory  | 4GB
Shipped Android Version | 8.1 (Oreo)
Storage | 64GB
Battery | 5000 mAh
Dimensions | 156 x 76 x 8.98 mm
Display | 1080 x 2246 pixels, 6.2" IPS LCD
Rear Camera  | 16 MP (f/1.8) + 5 MP (f/2.2), (PDAF, dual pixel)
Front Camera | 12 MP (f/2.2)

![Device Picture](https://i-cdn.phonearena.com//images/phones/73027-xlarge/Motorola-One-Power-5.jpg)

### Kernel Source
Check here: https://github.com/ixmoe/android_kernel_motorola_sdm660

### How to compile

```sh
. build/envsetup.sh
lunch omni_chef-eng
make -j4 recoveryimage
```
### Copyright
 ```
  /*
  *  Copyright (C) 2013-17 The OmniROM Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
