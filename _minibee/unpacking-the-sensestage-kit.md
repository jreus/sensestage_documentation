---
title: Unpacking the Sense/Stage Kit
summary: A guide on what is in the Sense/Stage kit.
layout: documentation
type: guide
date: 2017-02-06
tags:
    - basics
    - todo
category: introduction
subcategory: getting-started
related:
    - MiniBee
    - Expansion boards
    - Battery charging
    - Battery handling
---


To begin with, you should inspect the contents of your kit. Be able to identify the various parts of the Sense/Stage hardware setup. Your starter kit should include the following:

1. 2 or 5 Minibee boards including headers
2. 3 or 6 Xbee radios (all but one connected to Minibees)
3. a red coordinator board
4. green Xpee expansion boards (2 or 5) including headers
5. green Xpree expansion boards (2 or 5) including headers

You may have also purchased a battery kit, which should include 2 or 5 LiPo batteries and a red USB charging board.

![](/img/minibee-starter-kit-labled.jpg)


# Minibees

These are the small sensor data capture devices that form the core of Sense/Stage. If you're familiar with Arduino, then you're probably already accustomed to the kind of projects such devices can be used for.

Unlike an Arduino, the Minibee has a built-in accelerometer and is ready to start measuring motion right out of the box.

In the future you'll likely want to add additional sensors to capture more phenomena of the physical world.

The standard Sense/Stage kit should have 2 Minibees, a PLUS kit has 5. In addition, for each Minibee you should have a black expansion header.

![](/img/minibee-single-kit.jpg)

# Xbee Radios

While Minibees can operate fine on their own as tiny Arduinos, their real power is in their ability to communicate data wirelessly over a distance.

In order to be able to engage in wireless communication, every Minibee needs to be equipped with a little wireless radio device called an Xbee.

All of your Minibees will come with Xbee radios already attached to them, labled **N** for **NODE**.

You should also have one extra Xbee to use with the coordinator board, labled **C** for **COORDINATOR**.


# The Coordinator Board

The small red board with a mini USB connector on it. This board must also be equipped with an Xbee radio. It will connect to your computer via USB so that your computer can join the wireless conversation with your swarm of Minibees.

> NOTE: A USB mini cable is not included with your Sense/Stage kit!

## Putting the Xbee on the Coordinator Board
Before you can use the coordinator board you need to connect an XBee to it. Your kit is provided with one extra XBee labled "C" for this purpose.

Be very gentle when attaching the Xbee, and make sure you use the correct orientation.

![IMAGE ILLUSTRATING ATTACHING THE XBEE WITH CORRECT ORIENTATION]()

> [More information about the coordinator board](coordinator-board)

# Expansion Boards

Every starter kit comes with expansion boards for adding new sensors and custom circuits to your Minibees. There are two types of expansion boards: the standard **XPree** experimentation board, and the simplified **XPee**.

You should have one XPree and one XPee for each Minibee in your kit.

![](/img/minibee-expansion-kit-small.jpg)

> [More information about the expansion boards](expansion-boards)


# Battery and Charger

If you also purchased a battery kit, you should find included two or five LiPo batteries and a red charger with a USB connector.

> NOTE Make sure to fully charge your batteries before the first use.

> WARNING! LiPo batteries require special handling care. For more information see [this useful link](https://www.sparkfun.com/tutorials/241) from Sparkfun.com.

> [More information about the batteries](battery)