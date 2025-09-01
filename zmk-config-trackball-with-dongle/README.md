# ThumbsUp! Trackball, now with dongle!

Borrowed the code from https://github.com/kaihchang/zmk-config-kai-cosmos-dongle
Adjusted the MCU pin and keymap to ThumbsUp! trackball v2.
 

From kai-cosmos:


What's good about ZMK dongles?<br/>
- Almost immediate connection and wake-up from sleep mode.<br/>
- No more dependent from less stable Bluetooth connections.<br/>
- Extended battery life for both splits/peripherals.<br/>
- "Wireless" support for ZMK studio, able to change keymaps on the fly.<br/>

Surely there's something bad?<br/>
- Extra cost for a spare MCU, seeeduino nrf52840 sense in my case here.<br/>
- Takes up an extra USB slot on your device.

Recommend setting CONFIG_PMW3610_REPORT_INTERVAL_MIN to only 8 if MCU is using chip antenna (125Hz) instead of PCB antennae (250Hz).

Todo:
- Dongle ✅
- ZMK Studio ✅
- Scroll layer ✅
- Most frequent transmit (125Hz) ✅
- Built-in cursor acceleration ✅