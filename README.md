SparkFun RTK Everywhere Firmware Binaries
===========================================================

The line of RTK Everywhere products offered by SparkFun all run identical firmware. The [RTK Everywhere firmware](https://github.com/sparkfun/SparkFun_RTK_Everywhere_Firmware) is written for the following products:

<table class="table table-hover table-striped table-bordered">
  <tr align="center">
   <td><a href="https://www.sparkfun.com/products/24672"><img src="https://cdn.sparkfun.com/r/455-455/assets/parts/2/4/9/9/7/GPS-24672-RTK-Torch-Featured2.jpg"></a></td>
   <td><a href="https://www.sparkfun.com/products/24342"><img src="https://cdn.sparkfun.com/r/455-455/assets/parts/2/4/7/0/6/24342-RTK-EVK-Action-6.jpg"></a></td>
     </tr>
  <tr align="center">
    <td><a href="https://www.sparkfun.com/products/24672"><i>SparkFun RTK Torch (GPS-24672)</i></a></td>
    <td><a href="https://www.sparkfun.com/products/24342"><i>SparkFun RTK EVK (GPS-24342)</i></a></td>
  </tr>
  <tr align="center">
    <td><a href="https://docs.sparkfun.com/SparkFun_RTK_Torch/"><i>Hookup Guide</i></a></td>
    <td><a href="https://docs.sparkfun.com/SparkFun_RTK_EVK/"><i>Hookup Guide</i></a></td>
  </tr>
</table>

The [SparkFun RTK Torch](https://www.sparkfun.com/products/24672) is a centimeter-level GNSS receiver. With RTK enabled, these devices can output your location with 8mm horizontal and vertical [*accuracy*](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/accuracy_verification/) at up to 20Hz!

This repo houses the compiled binaries for the RTK Everywhere product line. 

Documentation
--------------

* **[RTK Everywhere Product Manual](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/)** - A detailed guide describing all the various software features of the RTK product line. Essentially it is a manual for the firmware in this repository.

Repository Contents
-------------------

* **/** - Pre-compiled binaries of SparkFun RTK Everywhere firmware, suitable for loading (see [Updating Firmware](https://docs.sparkfun.com/SparkFun_RTK_Firmware/firmware_update/)). 
* **/STM32_LoRa** - Pre-compiled binaries for the STM32WLE5 that controls the LoRa radio in the RTK Torch. See [Updating STM32 Firmware](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/firmware_update_stm32/).
* **/Uploader_GUI** - A link to the [RTK Uploader Repo](https://github.com/sparkfun/SparkFun_RTK_Firmware_Uploader) which contains the GUI for updating the ESP32 firmware on RTK units. See [Updating Firmware From GUI](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/firmware_update_esp32/#updating-firmware-using-the-uploader-gui).
* **/u-blox_Update_GUI** - A python and Windows executable GUI for updating the firmware on the u-blox modules within the RTK device (ZED-F9x and NEO-D9S primarily but all u-blox GNSS products are supported). See [Updating u-blox Firmware](https://docs.sparkfun.com/SparkFun_RTK_Everywhere_Firmware/firmware_update_ublox/).
* **/ZED Firmware** - Copies of Binaries from u-blox for loading onto ZED-F9x

License Information
-------------------

This product is _**open source**_!  Please see the [LICENSE.md](./LICENSE.md) for more details.

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
