---
title: NES
sidebar: mydoc_sidebar
permalink: hakchi_nes.html
folder: hakchi
---

## NES

### System details  
OS - Linux  
Controller ports - Wii style  
Controller protocol = I²C

### Command line arguments
Per the hakchi wiki:  

Internal emulator of NES Mini has many command line arguments. Seems like some of them are not working but there is full listing of "--help" output:  

```
root@CLOVER:/# /usr/bin/clover-kachikachi --help
+ export MALI_NOCLEAR=1
+ exec kachikachi --fullscreen --sync-guest-with-host --fds-initial-disk-insert-on-keypress --fds-auto-disk-side-switch --fds-disable-host-guest-sync-on-disk-op --keep-aspect-ratio --help
Core needs an UTF-8 C locale, we set it to "en_US.UTF-8" instead of "C".
This is a global side-effect and is subject to change, please don't rely on this.
Kachikachi - v28.0.20160804.dev
===============================
Kachikachi
==========
--help, -h                                                       Print usage and exit.
--command=<file>                                                 Use file as the contents of the command line (one arg     per line).
--log=<file>                                                     Log to file instead of stdout. Defaults to stdout
--ask, -a                                                        Ask for a rom and execute it.
--scale=<1..16>                                                  Specify the initial scale of the window.
--topmost                                                        Do not put window topmost.
--fullscreen                                                     Enable full screen display.
--keep-aspect-ratio                                              Stretch the display while keeping the correct aspect     ratio. (default)
--stretch                                                        Stretch the display to the maximum size available.
--pixel-perfect                                                  Stretch source pixels while keeping an integer target     size.
--mute                                                           Start ROM with mute sound.
--pause-on-lost-focus                                            Pause the emulator when the window loses focus.
--dont-show-debug-infos                                          Disable debug display on screen.
--sync-guest-with-wall                                           Synchronize emulation with wall time.
--sync-guest-with-host                                           Synchronize emulation with host.
--sync-guest-none                                                Don't synchronize emulation, run as fast as possible.
--load-state-slot=<index>, -lss<index>                           Load save state by index.
--load-state-file=<filename>, -lsf<filename>                     Load save state by filename.
--delete-after-load                                              Delete save state after a successful load.
--dim-screen-after=<s>                                           Dim screen after <s> seconds of inactivity.
--volume=<0..100>                                                Set sound volume (default: 100).
--nes-version=[ntsc|pal]                                         Specify the NES version (default is NTSC).
--graphic-filter=<index/name>                                    Specify the graphic filter (refer to code for     values).
--mem-init-pattern=[zero|type_1|type_0]                          Memory initialization pattern.
--fds-auto-disk-side-switch                                      Automatic disk side switch detection
--fds-auto-disk-side-switch-on-keypress                          When a disk side switch is detected, only insert the     other disk side on the next keypress
--fds-initial-disk-insert-delay=<value in frame count>           Set initial disk insertion delay
--fds-initial-disk-insert-on-keypress                            Initial disk insertion on keypress
--fds-bios-file-name=<fds bios file name>                        Specify bios file to load (default to fds_bios.bin)
--fds-disable-host-guest-sync-on-disk-op                         disable host/guest synchronization during disk     operation
--fds-disk-switch-side-delay=<delay in frames>                   Delay in frames between disk ejection and insertion
--delete-previous-record,                                        Delete previous input records (if it exists).
--record-inputs=<filename>,                                      Start or resume the specified input capture.
--replay-inputs=<filename>,                                      Replay the specified input capture and exit.
--input-record-checkpoint-period=<period>,                       Save checkpoints during input recording at the     specified period, in number of guest frames.
--input-record-exit-frame=<frame>,                               Save a checkpoint during input recording at the     specified guest frame and exit.
--input-record-cache=<directory>,                                Enable checkpoint cache during input recording and     set its path the specified directory.
--input-replay-screenshot-period=<period>,                       Take guest screenshots during input replay at the specified period, in number of guest frames.
--input-replay-screenshot-path=<path>,                           The path where replay auto-screenshots will be saved.
--input-replay-screenshot-to-stdout,                             Put the screenshot to stdout (works only with build that have no other outputs.
--input-capture-cut-path=<directory>,                            Set the directory where input capture cuts will be saved.
--input-replay-print-total-duration,                             Print the duration of the input replay.
--save-data-backing-file=<filename>                              Use the specified file for save data (SRAM or FDS writes), specifying an empty filename disable save data management.
--save-on-quit=<filename>                                        Save state to the desired location on quit event.
--save-screenshot-on-quit=<filename>                             Save screenshot to the desired location on quit event.
--enable-crt-scanlines, -sc                                      Enable CRT-like scanlines.
--enable-armet                                                   Enable Armet filter.
--armet-threshold=<t>                                            Armet Detection Threshold (default is 20).
--set-dac-filters=[APU_FDS_14kHz|APU_14kHz_FDS_2kHz|none]        Set DAC filters (default: APU_FDS_14kHz).
--guest-overscan-dimensions=<l,r,t,b>                            Set the number of black PPU pixels on the four screen borders.
--initial-fadein-durations=<t0,t1>                               Set the initial fadein durations in 1/10 of seconds. t0=blackscreen duration, t1=fadein duration.
--ppu-palette=<index/name>                                       Specify the PPU palette (refer to code for values).
--ppu-palette-file=<filename>                                    Specify the .pal palette file.
```
