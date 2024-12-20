# Modulation Delay

Take what you know about audio delays and apply it to modulation signals! Modulation Delay is a Max For Live device that can affect a modulation signal in the same way a feedbacking delay effect can turn sound into echoes.

Here is an image of a Shaper device modulating Modulation Delay, where it creates echoes of the input.
![How it Looks](images/device.gif)

[Video showing it in action.](https://www.youtube.com/watch?v=YfRTARPEUME)

Send modulation data to its Input, map up to eight destinations, and play with the controls to get interesting to wild results.

* *Dry* - The level of the dry (input) modulation signal in the final output.
* *Send* - The level of the input signal to send to the delay circuit.
* *Rate* - The delay frequency or interval (free or sync'd).
* *Feedback* - The amount of the output signal to mix into the input.

Or try mapping a MIDI controller to Input and have a freestyle jam into an modulation echo chamber. To start, try mapping to a low-pass filter cutoff on a pad sound (e.g. the Wavetable preset named "Spacey Ambient Pad").

The device plots the input signal in grey, the delay signal in light blue, the feedback signal in dark blue, and the output signal in orange.

## Installation

[Download the newest .amxd file from the frozen/ directory](https://github.com/zsteinkamp/m4l-Modulation-Delay/raw/main/frozen/) or clone this repository, and drag the `Modulation Delay.amxd` device into a track in Ableton Live.

Note: If you want to open and edit the non-frozen device, you will need to have [zs.mapper](https://github.com/zsteinkamp/m4l-zs.mapper) installed. [Follow the installation instructions](https://github.com/zsteinkamp/m4l-zs.mapper) there.

## Changelog

* 2024-10-29 [v5](https://github.com/zsteinkamp/m4l-Modulation-Delay/releases/download/v5/ModulationDelay-v5.amxd) - Add non-blocking telemetry ping on load. Does not send any identifying information, only the plugin name, the local computer name, type of computer, and CPU type. I just want to see which plugins are used the most.
* 2024-08-17 [v4](https://github.com/zsteinkamp/m4l-Modulation-Delay/releases/download/v4/Modulation.Delay.v4.amxd) - Support for Live 12's new modulation mode; Visual improvments.
* 2022-12-05 [v3](https://github.com/zsteinkamp/m4l-Modulation-Delay/raw/main/frozen/Modulation%20Delay%20v3.amxd) - Rename to Modulation Delay; Use integer version numbers.
* 2022-11-30 [0.0.2](https://github.com/zsteinkamp/m4l-zs-AutomationDelay/raw/main/frozen/AutomationDelay-0.0.2.amxd) - Added tempo sync option.
* 2022-11-29 [0.0.1](https://github.com/zsteinkamp/m4l-zs-AutomationDelay/raw/main/frozen/AutomationDelay-0.0.1.amxd) - Initial release.

## TODO

* ...

## Contributing

I'd love it if others extended this device. If you would like to contribute, simply fork this repo, make your changes, and open a pull request and I'll have a look.
