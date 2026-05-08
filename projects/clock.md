---
layout: page
title: ESP8266 OLED Clock
---

# ESP8266 OLED Clock

A small Wi-Fi-synchronized desk clock built with an ESP8266 D1 Mini and an SSD1306 OLED display.

## Goal

Build a simple desk clock that synchronizes time over Wi-Fi and displays the local Berlin time.

## Hardware

- ESP8266 D1 Mini
- SSD1306 OLED display
- USB power supply
- Breadboard wires

## Current Status

The first working version displays the time correctly after Wi-Fi synchronization.

## Version Log

### v1: Basic Clock

Initial version with Wi-Fi connection, NTP synchronization, and OLED time display.

## Problems Encountered

The first version showed the wrong time because the timezone handling was incorrect.

## What I Learned

NTP provides reference time, but local timezone handling still has to be configured separately.

## Media

Photos and videos will be added here later.