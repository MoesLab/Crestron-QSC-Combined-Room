# Crestron + Q-SYS Combined Room — live demo

**[Open the demo](https://moeslab.github.io/Crestron-QSC-Combined-Room/)**

Lakeview Room A and Room B: two Microsoft Teams rooms split by an airwall, run by one Crestron 4-Series processor and a Q-SYS Core. They work alone or combine into one large room. The page is an operations dashboard that runs beside the touch panels and shows what the system is doing.

## What the demo shows

- **Live floor plan** — airwall panels moving, wall sensor state, room state colours (off, on, in meeting, combined), occupancy, cameras, laptop inputs.
- **Two Crestron touch panels** — start or leave a meeting, share a laptop, room power, volume, mic mute, combine and divide with confirmation.
- **Combine rules** — only with the airwall open, never during a meeting; opening the wall asks to combine; closing it divides automatically. Room A is master when combined.
- **Two LED walls** — welcome screen, laptop, meeting with or without shared content; wall B mirrors A when combined.
- **Video routing (DM NVX)** — encoders, multicast addresses, switch, decoders, LED walls and UC engine content inputs, with live subscriptions.
- **Audio (Q-SYS)** — ceiling mic lobes, AEC, USB bridges to the UC engines, speaker zones and the Room Combiner.
- **Message inspector** — every touch panel join, NVX REST call, Q-SYS JSON-RPC message, display command and reply, filterable, with full payloads.

## Planned

Cameras, device health and a one-button room probe; a config editor with presets and wall sensor override; QR code and room bookings.

## System

Crestron 4-Series processor · Crestron Flex UC engines (Teams Rooms) · Crestron touch panels · DM NVX encoders and decoders · Q-SYS Core with ceiling microphones · LED walls · intelligent cameras.

Moe Azizi
