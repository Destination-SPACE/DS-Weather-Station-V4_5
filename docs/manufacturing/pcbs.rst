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

.. _pcbs:

Manufacturing PCBs
==================

To manufacture the Destination Weather Station v4.5, files for JLCPCB have been provided.

Download Files
--------------

JLCPCB handles the manufacturing and assembly of the weather station PCB.

Download the following files from the GitHub repository.

- `Gerbers <https://github.com/Destination-SPACE/DS-Weather-Station-V4_5/blob/main/hardware/destinationWeatherStation_v4-5/manufacturing/jlcpcb_files/jlcpcb_gerbers.zip>`_
- `Bill of materials <https://github.com/Destination-SPACE/DS-Weather-Station-V4_5/blob/main/hardware/destinationWeatherStation_v4-5/manufacturing/jlcpcb_files/jlcpcb_bom.csv>`_
- `Component placement <https://github.com/Destination-SPACE/DS-Weather-Station-V4_5/blob/main/hardware/destinationWeatherStation_v4-5/manufacturing/jlcpcb_files/jlcpcb_cpl.csv>`_


Ordering
--------

1. Go to `JLCPCB.com/quote <https://cart.jlcpcb.com/quote>`_

2. Click **Add gerber file** and upload the ``jlcpcb_gerbers.zip`` file

3. Change the following parameters

   - PCB Qty: Select a quantity
   - PCB Color: Select any color (this may change cost or manufacturing time)
   - Surface Finish: LeadFree HASL
   - PCB Assembly > PCB Type: Standard

.. image:: assets/jlcpcb_parameters.png
      :target: pcbs.html
      
.. image:: assets/jlcpcb_assembly_parameters.png
      :target: pcbs.html

4. Click **Next**

5. Click **Next**

6. Upload the ``jlcpcb_bom.csv`` and ``jlcpcb_cpl.csv`` files.

7. Click **Process BOM & CPL**

8. Click **Next**

   If components are unavailable, make substitutions.

.. image:: assets/jlcpcb_confirm_bom.png
      :target: pcbs.html

9. Click **Next**

.. image:: assets/jlcpcb_confirm_cpl.png
      :target: pcbs.html

10. If asked, select `Research\Education\DIY\Entertainment > Development Board - HS Code 847330` for the product description.

11. Click **Save to Cart**

12. Complete purchase