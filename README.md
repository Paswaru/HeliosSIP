# HeliosSIP

SIP-to-SSH gateway giving dial-up access to any SSH or Telnet host, for retro PBX networks.

A caller with a modem and a VoIP line reaches a board the way they did in 1992. The gateway is an ordinary SSH or Telnet client to whatever it connects to; nothing Helios-specific crosses the wire.

## Status: pre-release, built in the open

No version has been released and no tag exists. `main` holds releases only; work lands on
`development` through pull requests, and the issues and the estate's project board show what
is being worked on now.

The project is designed feature-first: the developer writes a brief for each feature in
`features/`, and the specifications in `docs/spec/` are derived from those briefs, with every
section naming the features it serves. `CONSTITUTION.md` holds what is specific to this
project; the principles shared across the estate live in the
[HeliosSkills](https://github.com/HeliosBBS/HeliosSkills) plugin.

## The estate

Part of [Helios](https://github.com/HeliosBBS): the [engine](https://github.com/HeliosBBS/HeliosAdvance),
the [Door Kit](https://github.com/HeliosBBS/HeliosDoorKit), the
[door hosting service](https://github.com/HeliosBBS/HeliosDoors), the
[Portal](https://github.com/HeliosBBS/HeliosPortal) and the
[SIP gateway](https://github.com/HeliosBBS/HeliosSIP). Each project's interface to the engine
is a protocol, a wire format, or nothing at all. This one owns its own gateway and consumes SSH or Telnet, nothing more.

## Licence

**GNU Affero General Public License, version 3 only** (not "or later").

