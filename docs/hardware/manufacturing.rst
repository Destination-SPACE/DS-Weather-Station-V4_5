.. Copyright 2026 Destination SPACE Inc.
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

.. _manufacturing:

Manufacturing
=============

To manufacture the Destination Weather Station v4.5, files for JLCPCB have been provided.

To complete the kit, a few additional components will need to be sourced as these will be soldered by the students. These components can be found in the table below.

.. list-table::
   :header-rows: 1

   * - Component
     - Manufacturer
     - Manufacturer Part Number
     - Link

   * - XIAO RP2040
     - Seeed Studio
     - XIAO RP2040
     - https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html

   * - SPDT slide switch
     - C&K
     - OS102011MS2QN1
     - https://www.lcsc.com/product-detail/C221829.html

   * - 128x64 SSD1315 OLED display
     - HS
     - HS96L03W2C03
     - https://www.lcsc.com/product-detail/C5248080.html

   * - 3x AAA Battery holder
     - MYOUNG
     - BH-AAA-B1AJ022
     - https://www.lcsc.com/product-detail/C5290194.html

Ordering
--------

JLCPCB handles the manufacturng and assembly of the weather station PCB.

1. Download the following files.

- `Gerbers <https://github.com/Destination-SPACE/DS-Weather-Station-V4_5/blob/main/hardware/destinationWeatherStation_v4-5/manufacturing/jlcpcb_files/jlcpcb_gerbers.zip>`_
- `Bill of materials <https://github.com/Destination-SPACE/DS-Weather-Station-V4_5/blob/main/hardware/destinationWeatherStation_v4-5/manufacturing/jlcpcb_files/jlcpcb_bom.csv>`_
- `Component placement <https://github.com/Destination-SPACE/DS-Weather-Station-V4_5/blob/main/hardware/destinationWeatherStation_v4-5/manufacturing/jlcpcb_files/jlcpcb_cpl.csv>`_

2. Go to `JLCPCB.com <https://cart.jlcpcb.com/quote>`_

3. Click *Add gerber file* and upload the `jlcpcb_gerbers.zip` file

4. Change the following parameters

   - PCB Qty: Select a quantity
   - PCB Color: Select any color (this may change cost or manufacturing time)
   - Surface Finish: LeadFree HASL
   - PCB Assembly > PCB Type: Standard

5. Click Next

6. Click Next

7. Upload the `jlcpcb_bom.csv` and `jlcpcb_cpl.csv` files.

8. Click Process BOM & CPL

9. Click Next

10. Click Next

10. If asked, select `Research\Education\DIY\Entertainment > Development Board - HS Code 847330` for the product description.

11. Click Save to Cart

12. Complete purchase