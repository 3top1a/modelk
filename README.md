# Model M

![meta/splash.png](meta/splash.png)
<sup><sub>Render may be of an outdated version, the images below are from a CI/CD render and are always up-to-date. Only compatible with nice!nano, other MCUs won't work</sub></sup>
<div style="display: inline-flex; flex-direction: row; align-content: space-around; justify-content: space-evenly;">
  <img src="https://github.com/3top1a/modelk/blob/pcb-artifacts/pcb/autogen/top.png" width="49%" />
  <img src="https://github.com/3top1a/modelk/blob/pcb-artifacts/pcb/autogen/bottom.png" width="49%" />
</div>

The Model K is a custom replacement controller designed to add BLE wireless functionality to classic IBM Model M keyboards. This controller can be hot-swapped into the original keyboard without destroying the original controller.

## Features

<!-- TODO Supported keyboards, M122 not tested yet -->
- Full wireless with BLE (Bluetooth Low Energy)
- Battery powered with power management <!-- TODO Battery life -->
- USB C for drag-and-drop programming, charging and wired use
- [Open source ZMK firmware](https://github.com/3top1a/modelk-zmk), with [CI/CD builds](https://github.com/3top1a/modelk-zmk/actions/workflows/build.yml)
- Three high-frequency user-configurable pins
- Currently only supports the [nice!nano](https://nicekeyboards.com/nice-nano), built on top of the Nordic nRF52840
- All components are THT and easy to solder/repair/replace

