# Flight Radar Improvement Progress

## Goal
Create a nicer, more polished version of the existing Seattle flight radar (based on the current index.html).

## Current Status
- Attempt: 3 / 15
- Status: in_progress
- Last updated: 2026-08-01 13:48

## What’s Already Working (from original)
- Dark map centered on Seattle
- Live aircraft from airplanes.live
- Smooth animation between positions after refresh
- Altitude-based plane colors
- Basic HUD with count + time
- Rotating plane icons

## Desired Improvements (priority order)
1. [ ] Faster refresh rate or better inference on plane position to make tracking more realtime.
2. [ ] Better plane popup (show more useful info cleanly)
3. [ ] Show plane trails (last few positions)
4. [ ] Make the HUD more useful (add filters + search)
5. [ ] Improve mobile layout and touch experience
6. [ ] Optional: click plane to follow it

## What Was Tried
-

## Constraints
- Prefer keeping it as a single HTML file if possible
- Keep the dark aesthetic
- Don’t break the smooth animation
- Use only free public APIs (airplanes.live is fine)
- Must still work well on mobile
