# Wokwi-Chip-Plotter

## Description

Debug Analog or Digital Signals.

- Plotter Timebase range is 50-10000 µs (default 1000 µs). This is the sample period.
-  Width of plot is 255 samples.
- Auto Trigger ON/OFF control (default 1, ON)



![image](https://user-images.githubusercontent.com/63488701/224138800-74a2f6d3-1c6b-4c27-85c0-85e226733559.png)



![image](https://user-images.githubusercontent.com/63488701/224105126-e8875509-201f-4178-91db-3d396103598d.png)

## Pin names

| Name | Description                                                  |
| ---- | ------------------------------------------------------------ |
| IN   | Input  configured as ANALOG, also works with digital signals |

## Usage

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
  "dependencies": {
    "chip-plotter": "github:Dlloydev/Wokwi-Chip-Plotter@1.0.3"
  }
```

Then, add the chip to your circuit by adding a `chip-plotter` item to the `parts` section of `diagram.json`:

```json
  "parts": {
    ...,
    { "type": "chip-plotter", "id": "chip-plotter1" }
  },
```

The actual source code for the chip lives in [src/main.c](https://github.com/Dlloydev/Wokwi-Chip-Plotter/blob/main/src/main.c), and the pins are described in [chip.json](https://github.com/Dlloydev/Wokwi-Chip-Plotter/blob/main/chip.json).

## Example

[![Wokwi_badge](https://user-images.githubusercontent.com/63488701/212449119-a8510897-c860-4545-8c1a-794169547ba1.svg)](https://wokwi.com/projects/358743168189598721) Debug Analog or Digital Signals Example

## License

This project is licensed under the MIT license. See the [LICENSE](https://github.com/Dlloydev/Wokwi-Chip-Analog-Bargraph/blob/main/LICENSE) file for more details.
