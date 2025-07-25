![GitHub Logo](https://i.imgur.com/DNW11Yt.png)
Picture courtesy of Wackalope#6737

[![GitHub issues](https://img.shields.io/github/issues/RedHawk989/EyeTrackVR?style=plastic)](https://github.com/RedHawk989/EyeTrackVR/issues) [![GitHub forks](https://img.shields.io/github/forks/RedHawk989/EyeTrackVR?style=plastic)](https://github.com/RedHawk989/EyeTrackVR/network) [![GitHub stars](https://img.shields.io/github/stars/RedHawk989/EyeTrackVR?style=plastic)](https://github.com/RedHawk989/EyeTrackVR/stargazers)

- [EyeTrackVR](#eyetrackvr)
      - [This project is in development and is not fully finished](#this-project-is-in-development-and-is-not-fully-finished)
  - [Hardware](#hardware)
  - [About IR Emitter Safety](#about-ir-emitter-safety)
        - [Make sure you are using NON-focused emitters and at around 5ma total power](#make-sure-you-are-using-non-focused-emmiters-and-at-around-5ma-total-power)
  - [Firmware](#firmware)
  - [Headset support](#headset-support)
      - [Contact](#contact)
- [Licenses](#licenses)

# EyeTrackVR

Source First and *affordable* VR eye tracker platform for [VRChat](https://hello.vrchat.com/) via `OSC` and `UDP` protocol.

> [!IMPORTANT]\
> This project is in active development and is not fully finished

## Documentation
Please check out our [documentation site](https://docs.eyetrackvr.dev)

## Hardware

3d files for mounting brackets will be found [here](https://github.com/EyeTrackVR/EyeTrackVR-Hardware)
IR emitter files are also located there. For more info please reference our parts list on our [documentation site](https://docs.eyetrackvr.dev/how_to_build/part_list)

## ESP32 Firmware

Current work has been with our official firmware by `lorow`, found [here](https://github.com/EyeTrackVR/OpenIris).

## Headset support

Any headset that can fit the camera and LEDs can likely be supported, however, mounts may not have been made for it. Please reference to our [parts list](https://docs.eyetrackvr.dev/how_to_build/part_list) for details.


## About IR Emitter Safety

Please *exercise extreme caution* when messing around with IR emitters.
<ins>Once safety testing has been completed links and files will be provided for the emitters</ins>. Please make sure you know what you are doing when assembling the IR emitters.
 <ins>**DO NOT BYPASS (OR NOT DO) ANY SAFETY FEATURES PUT IN PLACE**</ins>. This can result in irreversible bodily harm.
The safety measures were put in place to REDUCE the potential failure risk. All further safety responsibilities are on the user.
This includes visually checking with an IR camera that the brightness is correct and making sure you do not feel warmth.

> [!WARNING]\
> Make sure you are using **NON-focused** emitters and at around ***5ma total power per eye***.

[Effect of infrared radiation on the lens](https://docs.eyetrackvr.dev/safety/effect_of_ir_on_the_lens.pdf)

[Training-library Nir Stds](https://docs.eyetrackvr.dev/safety/training-library_nir_stds_20021011.pdf)

[AN002_Details on photobiological safety of LED light sources](https://docs.eyetrackvr.dev/safety/AN002_Details_on_photobiological_safety_of_LED_light_sources.pdf)

## Contact

Please join our Discord for updates and any questions.

[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/kkXYbVykZX)

## Licenses

***All software is licensed under the Babble Software Distribution License 1.0 unless marked otherwise.***

All documentation, is under the Creative Commons CC-BY-SA-4.0 license***.

<!-- <div align="center">
<img src="./docs/assets/images/licenses/licenses.svg" width="300" alt="Open Licenses" />
</div> -->

[Top](#eyetrackvr)
