# DRT Converter

Get a DaVinci Resolve timeline into Pro Tools accurately, starting from Resolve's
native timeline export (`.drt`) and not from Resolve's AAF.

The `.drt` carries more than Resolve's own AAF export does, including sub-frame
source positions and reel names. DRT Converter reads it directly, consolidates
the audio into Pro Tools-friendly media, and delivers clips, fades and
crossfades, clip gain and volume rides, busses, markers and track colours.

## Two ways to deliver

- **Build the session in Pro Tools.** With Pro Tools on the same Mac, the app
  creates the session for you.
- **Export an AAF.** No Pro Tools needed. Write an AAF with linked or embedded
  media and hand it to whoever is doing the sound work.

## Downloads

Get the latest version from the [Releases page](../../releases/latest).

- **DRT Converter** (`.dmg`): the standalone Mac app.
- **DRT Converter Bridge** (`.pkg`): an optional companion panel inside Resolve
  that checks the open timeline, exports the DRT and hands it to the app.

Both are signed and notarized.

## Requirements

- Apple silicon Mac, macOS 11 or later
- DaVinci Resolve, to export the `.drt`. The Bridge panel needs Resolve Studio.
- Pro Tools 2025.6 or later with the scripting server enabled, only if you want
  the session built directly in Pro Tools. AAF export works without it.
- Tested with DaVinci Resolve 21.2 and Pro Tools 2026.4

## Reporting a problem

Open an [issue](../../issues) and include your Resolve and Pro Tools versions,
plus the build log from the app.

Please do not attach timelines, sessions or media from a production. Describe
the problem, or reproduce it with test media.

## About

Built by Justin Yates, a working feature film editor. Free to use.

DRT Converter is an independent tool. It is not affiliated with, endorsed by or
supported by Blackmagic Design or Avid. DaVinci Resolve and Pro Tools are
trademarks of their respective owners.
