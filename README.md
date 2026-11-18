# DRT Converter

Turn a DaVinci Resolve timeline into a Pro Tools session, without an AAF in between.

DRT Converter reads Resolve's native timeline export (`.drt`), consolidates the
audio into Pro Tools-friendly media, and builds the session directly inside
Pro Tools: clips, fades and crossfades, clip gain and volume rides, busses,
markers and track colours.

## Downloads

Get the latest version from the [Releases page](../../releases/latest).

- **DRT Converter** (`.dmg`): the standalone Mac app.
- **DRT Converter Bridge** (`.pkg`): an optional companion panel inside Resolve
  that checks the open timeline, exports the DRT and hands it to the app.

Both are signed and notarized.

## Requirements

- Mac with Apple silicon
- Pro Tools 2025.6 or later, with the scripting server enabled
- DaVinci Resolve Studio for the Bridge panel
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
