# Sega Master System Divide By Three Jailbar Fix

## Goal

1 - Kill the divide-by-three clock divider in the VDP that creates the CPU clock.

The VDP divide-by-three circuit is known to cause jailbars in the analog video signals.

2 - Create a separate clock divider external to the VDP to recreate the CPU clock.

This will keep the CPU clock in sync with the VDP clock.

3 - Combine the divide-by-three mod with the RGB encoder switcher Z80 QSB mod to work with a switchless region mod and dual frequency oscillator (DFO).

## Progress

I am struggling to make a successful clock divider circuit using discrete components. My plan is to reach out for some help in finishing this project.

17-11-2024 - I have made a small breakthrough with this mod so will be activelly working on it again. I will be using a PIC chip now instead of discrete components.

Will populate this repository soon.

Cheers

## Donate

Working on designs to release for free can be both time consuming and expensive. If you like what I do, a small donation will go a long way in helping me continue to serve the modding community as best as I can, with many more free and original guides, designs, and ideas to come.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C7NK7XO)
