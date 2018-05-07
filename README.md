# Countdown Python Plugin
Countdown in minutes before switch off

## Parameters
Parameter   | Value                                |
:---        | :---                                 |
**Minutes** | Minutes to countdown. Default is 10. |
**Debug**   | Default is False.                    |

On | Off |
:--- | :---
![On](https://github.com/Xorfor/Domoticz-Countdown/blob/master/images/Countdown_on.PNG) | ![Off](https://github.com/Xorfor/Domoticz-Countdown/blob/master/images/Countdown.PNG) |

## Description
This plugin will start with the specified minutes and countdown. As soon as this plugin passed the count down/wait time, it will switch Off. This status change from On to Off can be used for events. 

You can reset the plugin by sending the 'On' command, or click on the switch.

## Usage
Eg. you want to switch off the lights if no motion is detected in 3 minutes.
![Usage](https://github.com/Xorfor/Domoticz-Countdown/blob/master/images/Knipsel.PNG)
As soon as motion is detected, the Countdown plugin is switched to On, the counter will be switched on/restarted.
