# Phosphor

A mini PC gaming setup that turns an AZW Green G3 into a controller-navigated console for the living room. Built because PCs have way more capability than locked-down consoles, especially with Microsoft restricting their ecosystem. This runs Linux with full desktop access and a massive game library while staying smaller than an Xbox.

## Why This Project

I had a spare AZW Green G3 mini PC sitting around and wanted to make use of it. Modern consoles are getting more locked down, but a PC running Linux gives you access to Steam, emulators, indie games, and a full desktop when you need it. The goal is to get all that working with just a controller from the couch.

## Hardware

- **Mini PC:** AZW Green G3
- **CPU:** Intel Celeron N5100 (4 cores, up to 2.8GHz)
- **RAM:** 8GB
- **Graphics:** Intel UHD Graphics (Jasper Lake)
- **Storage:** 640GB (expandable, has a ~100gb m.2 and 512gb ssd)
- **OS:** Zorin OS 18 Core (X11)
- **Controller:** Xbox Series X Controller

## What It Does

- Full desktop navigation with Xbox controller (no keyboard/mouse needed)
- Unified game library through EmulationStation Desktop Edition
- Steam games (native Linux + Proton compatibility layer)
- Retro emulation (NES, SNES, PS1, N64, Dreamcast, etc.)
- Local multiplayer support for games like Portal 2
- Auto-start controller mapping on login
- On-screen keyboard for typing without physical keyboard

## Performance Expectations

The Celeron N5100 is not a powerhouse but it handles:
- **Retro emulation:** NES through PS1/N64/Dreamcast runs great
- **Indie/older Steam games:** Works well for 2D games and older 3D titles
- **Light modern games:** Low settings on less demanding titles
- **NOT for:** AAA gaming, high graphics settings, anything post-2015 that's graphically intensive

## Current Setup Status

- [x] Zorin OS installed and configured
- [x] Switched to X11 for controller compatibility
- [x] antimicrox installed (controller to keyboard/mouse mapping)
- [x] Xbox Series X Controller detected and working
- [ ] Controller button mappings (fully) configured
- [ ] EmulationStation-DE installed and themed
- [ ] Steam library integrated
- [ ] Auto-start antimicrox on boot
- [ ] On-screen keyboard setup for controller login
- [ ] Decide on ESDE auto-start behavior

## Possible Challenges

Getting full PC capability with only a controller is harder than it sounds. You need:
- Desktop navigation without a mouse
- Typing without a keyboard (on-screen keyboard required)
- Game-specific controller profiles so buttons work right
- Auto-switching between desktop mode and game mode
- Making it all seamless enough that you never need to plug in a keyboard

## Goals

**Phase 1:** Basic controller navigation and ES-DE frontend
**Phase 2:** Steam integration and game library setup
**Phase 3:** Multiple controller support for local co-op
**Phase 4:** Auto-start configuration and on-screen keyboard
**Phase 5:** Custom ES-DE theming to match the dark system theme

## Why Linux Instead of Windows

- Better performance on low-end hardware
- Free and open source
- No forced updates or telemetry
- Better controller support through Steam Input
- Access to both native Linux games and Windows games via Proton
- Can tweak anything without Microsoft getting in the way
