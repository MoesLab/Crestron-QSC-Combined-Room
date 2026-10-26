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
- **Cameras** — group framing, speaker tracking, presets and privacy; in combined mode, voice switching picks the camera of the room with the active talker.
- **Device health** — 21 devices with status, address, firmware, uptime and temperature, plus alert counts.
- **Room probe** — one button checks pings, Q-SYS link, panels, displays, video routes, speaker zones with pink noise, microphones, echo canceller, cameras and the airwall sensor, then reports pass, warning or fail. Use the fault buttons to see it catch problems.

- **Room configuration** — the processor's JSON config in an editor with four presets (Standard, Event hall, Sensor bypass, Maintenance), validation with clear errors, a review of every change before applying, saved versions and one-click rollback. Settings take effect immediately: wall sensor mode and override, auto-divide, room names, volume limits, camera defaults, auto-off when vacant, guest QR.
- **Guest access** — a QR code per room, also on each LED wall's welcome screen, opening phone control (volume, mic mute, share, report a problem). The token changes after every meeting.
- **Bookings** — today's timeline for both rooms, including a combined booking, with the next meeting on the welcome screens.

## Try this

1. Open the airwall and accept *Combine rooms* on a panel.
2. Start a meeting, share the laptop, and watch the routing, audio and cameras follow.
3. Apply the *Event hall* preset, close and reopen the wall: the rooms now combine on their own.
4. Add a fault in the test tools, then run the room probe.

## System

Crestron 4-Series processor · Crestron Flex UC engines (Teams Rooms) · Crestron touch panels · DM NVX encoders and decoders · Q-SYS Core with ceiling microphones · LED walls · intelligent cameras.

Moe Azizi
