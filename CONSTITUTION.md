# Constitution

The estate's shared constitution, in the `helios` plugin, is loaded first in every session and
holds the principles: authority from features down, security designed in, multi-node from the
start, the estate and its contracts, the spec rules. This file adds only what is specific to
HeliosSIP, and is loaded right after it, unchanged.

## Role

A caller with a modem and a VoIP line reaches a board the way they did in 1992. The gateway is an ordinary SSH or Telnet client to whatever it connects to; nothing Helios-specific crosses the wire.

It owns its own gateway and consumes SSH or Telnet, nothing more. An interface it owns changes here first, with a version,
before any consumer moves; an interface it consumes is cited by name and version from the
contracts register, never restated.

## How this file is used

Loaded after the shared constitution by every skill, every prompt and every loop iteration. A
change to it is a pull request the developer approves, and nothing else edits it.
