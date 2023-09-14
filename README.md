
# SwitchBot

This repository contains code for controlling SwitchBot devices with HomeKit.

## Installation

1. Install Homebridge: https://github.com/homebridge/homebridge
2. Install the SwitchBot plugin:

```
npm install -g @switchbot/homebridge-switchbot
```

3. Configure the plugin in your Homebridge config file:

```json
{
  "platforms": [
    {
      "platform": "SwitchBot",
      "name": "SwitchBot",
      "devices": [
        {
          "name": "My SwitchBot",
          "deviceId": "YOUR_DEVICE_ID"
        }
      ]
    }
  ]
}
```

## Usage

Once the plugin is configured, you can control your SwitchBot devices from HomeKit. For example, to turn on your SwitchBot, you can use the following Siri command:


Hey Siri, turn on the SwitchBot.


## Supported SwitchBot Devices

The following SwitchBot devices are supported by this plugin:

* SwitchBot Humidifier
* SwitchBot Meter
* SwitchBot Meter Plus (US)
* SwitchBot Meter Plus (JP)
* SwitchBot Indoor/Outdoor Thermo-Hygrometer

## Contributing

Contributions are welcome! Please see the [CONTRIBUTING](CONTRIBUTING.md) file for more information.

## License

This project is licensed under the MIT License.


## Additional notes

* You can link to specific lines in the README by appending `#L` followed by the line number to the end of the URL. For example, the following link will open the README at line 20:

```
https://github.com/Dheeraj988/SwitchBot/blob/main/README.md#L20
```
