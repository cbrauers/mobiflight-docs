---
title: Arduino Leonardo
description: Details on MobiFlight incompatibility with the Arduino Leonardo
---

> [!IMPORTANT]
> This board is unsupported. Consider a [Mega 2560 Pro Mini](../../arduino-mega-2560-pro-mini/) instead.

The Arduino Leonardo is an Arduino board based on the ATmega32U4 microcontroller.
Despite its physical resemblance to the Arduino Uno, it is more closely related to the [Arduino Micro](../../arduino-micro),
another unsupported board.


{{< cards >}}

{{< card title="Arduino Leonardo" subtitle="ATmega32U4 microcontroller" tag="Unsupported" tagType="error" image="card-images/boards/arduino-uno.png" method="Resize" options="600x q80 webp" >}}

{{</ cards >}}

While it is sometimes possible to install MobiFlight Pro Micro firmware on the Arduino Leonardo,
this should not be taken as a sign of support. The MobiFlight Pro Micro firmware was not designed
or tested with the Arduino Leonardo in mind, so attempting to use it on the Leonardo board may
lead to issues, including but not limited to missing pins.