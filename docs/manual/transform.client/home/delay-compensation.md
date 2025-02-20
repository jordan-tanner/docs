---
sidebar_position: 21
---

import ReactPlayer from 'react-player'

# Delay Compensation

:::tip

Delay compensation is great if you want to align a set of chains - say for a drum kit.

:::

The **transform**.engine offers 16 latency groups, allowing you to group your plugin chains as you wish.

![Delay compensation overview](../../../../static/img/transformclient/delay-compensation-overview.png)

By clicking on the Delay Compensation area on any chain, you will see the reported latency for each
plugin, with an option to add them to one of your 16 latency groups. The **transform**.engine will
then automatically delay your chains to the longest path length.

Once you start grouping chains, you will see the value of plugin latency in that chain plus the
additional amount of latency added to align with the longest chain in that group, all displayed in a
handy graph for comparison!

With the Delay Compensation section closed, on the chain's Delay Compensation area, you can see if
any latency is being added by the system as a result of that chain being in a latency group.

Here's Elliot giving you a quick spin through the UI:
<ReactPlayer controls url="https://youtu.be/VrEc93qH8Bg" />
