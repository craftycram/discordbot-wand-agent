<p align="center">
  <img src="res/banner.png">
  <a href="https://GitHub.com/craftycram/discordbot-wand-agent/releases/" target="_blank"><img src="https://badge.fury.io/gh/craftycram%2Fdiscordbot-wand-agent.svg"></a>
  <a href="https://GitHub.com/craftycram/discordbot-wand-agent/issues/" target="_blank"><img src="https://img.shields.io/github/issues/craftycram/discordbot-wand-agent.svg"></a>
  <a href="https://discordbot.craftycram.net/" target="_blank"><img src="https://img.shields.io/website-up-down-green-red/https/discordbot.craftycram.net.svg"></a>
  <a href="https://discord.gg/WfXSUSw" target="_blank"><img src="https://img.shields.io/discord/757335944545435798.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2"></a>
</p>

## Introduction

This agent allows you to execute spells on your magic wand to play sounds in discord.  
To use it you will need the agent, an Arduino Nano BLE Sense and the bot on your discord server.

## Requirements
- MacOS or Windows version of the Agent. (download in the releases tab)
- Arduino BLE Sense
- Arduino Firmware Library (download from the repo)
- Arduino IDE
- Discord Account and Guild
- craftycram.net Discord Bot premium tier

## Installation
- Install the agent on your computer
- Install the arduino library to your Arduino IDE
- Flash the firmare to the arduino using the Arduino IDE and the `nano_ble33_sense_accelerometer_continuous` example sketch
- Connect to a channel on your discord server that can be accessed by the bot
- Start the agent
- Select the correct port of your arduino in the dropdown list
- Open the bots webdashboard and login with your discord account
- Execute a spell and enjoy the sounds

## Usage
Just stick your Arduino to your wand with its top side pointing to your left. It should be located near the end on the grip side of your wand, being covered by your hand when holding the wand.

There are currently four spells available:
- alohomora
- wingardium leviosa
- meteolojinx
- finite incantatem

You can take a look at a [spell chart](res/spell-chart.jpg) to see how to perform them.

## Troubleshooting
If you encounter any issues feel free to join [our discord server](https://discord.gg/WfXSUSw) or open a new issue in this repository

## Known-Issues
- gestures need to be repeated multiple times to get recognized
- gestures won't be recognized if not performed the right way
- dashboard signing doesn't work using safari


## Video

[![demo video](https://img.youtube.com/vi/Fh0Q7eCA-5I/0.jpg)](https://www.youtube.com/watch?v=Fh0Q7eCA-5I)

## One Pager

you can read the one pager right [here](res/onepager_discordwand.pdf)