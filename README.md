# SoSmartRoom
An intelligent and highly customisable room specific home control system for the Raspberry Pi 4 and other low power computers programmed in Svelte

## IMPORTANT
While SoSmartRoom is usable by everyone, setting it up and customising it REQUIRES knowledge of JavaScript and other frameworks. SoSmartRoom is also designed to be one room control only, i.e. one server and control unit per room.

## Features
* Modern, touch screen friendly interface
* Accessable both through web and on device touch screen.
* Firebase authentication
* Public accessablity through a provider of your choice which can be enabled to allow your friends to access your smart devices and give you a headache. Equipped with basic Firebase authentication and rate limiting to restrict potential attackers.
* Spotify status through Spotify module, shows now playing and album art.
* Inventory system for clothing and other items in room

## Standard interfaces
SSR comes with some interfaces built in, including basic door lock control and light control.
This was made for my specific setup, but you can easily extend it to add your devices.
* IOT Light Bulbs (RGBW)
* RSTP IP Security Cameras with or without PT(Z)
* Individually addressable RGBW strips (extends lightb module)

## What you need
* This was developed and tested on a Raspberry Pi 4 4GB with a touchscreen running Raspberry Pi OS, with a Tapo smart plug, a TP-Link Kasa smart bulb, Nanoleaf pannels and a cheap Tuya individually addressable RGB LED strip.


## Development
`npm run dev`
