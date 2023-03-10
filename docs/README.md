# Wokwi-Chip-Plotter

## Description

Debug Analog or Digital Signals.

- Plotter `Sample Time` range is 50-10000 µs (default 100 µs).
-  Width of plot is 250 samples.
- `Trigger` modes are Off (`0`) Rising (default) ⬆ and Falling ⬇
- Displays peak volts`Vmax`, and minimum volts `Vmin`
- Displays  Sample Time `^us^` and Capture Time `<ms>`



![image](https://user-images.githubusercontent.com/63488701/224412373-3bae0364-6507-4d62-bd5a-6e0dd84edd14.png)

![image](https://user-images.githubusercontent.com/63488701/224366649-95fd6e82-e9d9-41fa-8d5c-f88310151e6f.png)

## Pin names

| Name | Description                                                  |
| ---- | ------------------------------------------------------------ |
| IN   | Input  configured as ANALOG, also works with digital signals |

## Usage

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
  "dependencies": {
    "chip-plotter": "github:Dlloydev/Wokwi-Chip-Plotter@1.0.4"
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
