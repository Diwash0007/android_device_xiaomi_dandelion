# Team Win Recovery Project (TWRP)
A custom recovery device-specific tree source code for Redmi 9A.

### How to compile ?
This device tree was tested and is fully compatible with [minimal-manifest-twrp](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp).

1. Set up the build environment following the instructions [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp/blob/twrp-12.1/README.md#getting-started)

2. In the root folder of the fetched repo, clone the device tree:

```bash
git clone https://github.com/Diwash0007/android_device_xiaomi_dandelion.git -b android-11 device/xiaomi/dandelion
```

3. To build:

```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_dandelion-eng
mka recoveryimage
```

# Overview of Redmi 9A:
![dandelion](https://i01.appmifile.com/webfile/globalimg/13/24521DB8-CC5D-6A28-85D2-B8F672404FCA.png "Redmi 9A")

The Redmi 9A, released in 2020, is a budget-friendly smartphone by Xiaomi. It features a 6.53-inch HD+ display, a MediaTek Helio G25 processor, and a 13MP rear camera. With a large 5000mAh battery, it offers extended usage. The phone runs on MIUI based on Android 10, providing a customizable user experience. While it may not have advanced features, it's a solid choice for those seeking an affordable and functional device.

# Device details:
| **Category**               | **Specification**                                           |
|----------------------------|-------------------------------------------------------------|
| **Camera**                 | Rear: 13MP AI Camera, F2.2 / 1.0μm                            |
|                            | Front: 5MP AI Selfie Camera                                   |
| **Processor**              | MediaTek Helio G25                                           |
|                            | - Octa-core processor                                       |
|                            | - 8X Cortex-A53 cores (2.0GHz, 1.5GHz)                       |
|                            | - ARM GE8320 clocked up to 650MHz                           |
| **Operating System**       | MIUI 12 + Android 10                                         |
| **Storage and RAM**        | Configurations: 2GB+32GB, 3GB+32GB                            |
| **Display**                | 16.58cm (6.53) HD+ Display                                   |
|                            | - Resolution: 1600x720 HD+                                  |
|                            | - Brightness: 400nit typ                                     |
|                            | - Contrast: 1500:1, NTSC: 70%                                 |
|                            | - Screen-to-body: 20:9 TFT-IPS                               |
|                            | - Reading mode certified by TÜV Rheinland                    |
| **Dimensions & Weight**    | Height: 164.9mm, Width: 77.07mm, Thickness: 9mm, Weight: 194g |
| **Charging and Battery**   | 5000mAh Built-in rechargeable battery, 10W Fast Charger      |
| **Network & Connectivity** | - Dual SIM (nano SIM + nano SIM + microSD up to 512GB)        |
|                            | - Supports 4G/3G/2G, dual SIM VoLTE HD calling                |
| **Wireless Network**       | - Supports protocols: 802.11a/b/g/n                          |
|                            | - Supports 2.4G Wi-Fi                                        |
|                            | - Supports Bluetooth 5.0                                     |
| **Navigation**             | GPS/A-GPS/GLONASS/Beidou                                      |
| **Multimedia**             | MP4, M4V, MKV, XVID, WAV, AAC, MP3, AMR, FLAC, APE            |
| **Sensors**                | G-sensor, L-Sensor, P-Sensor                                  |
| **Package Contents**       | Redmi 9A, Power adapter, Micro USB cable                      |
|                            | SIM eject tool, User guide, Warranty card                     |

# License:
```
Copyright 2023 Diwash0007

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
