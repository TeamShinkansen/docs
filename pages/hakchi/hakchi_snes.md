---
title: SNES
sidebar: mydoc_sidebar
permalink: hakchi_snes.html
folder: hakchi
---

## SNES

### System details  
OS - Linux  
Controller ports - Wii style  
Controller protocol = I²C

### Command line arguments
Per the hakchi wiki:  

Internal emulator of SNES Mini has many command line arguments. Seems like some of them are not working but there is full listing of "--help" output:  

```
root@CLOVER:~# canoe-shvc
Usage: canoe-shvc [options]
where options are:
--version                             Show version then exit
-output-dir DIRECTORY                 Specify where output files are written
-help                                 Display this help screen
-re 07                                Resume state and play all .inputs in turn.
-resume FILENAME.break                Load an emulator state snapshot from specified file
-replay FILENAME.inputs               Process recorded user inputs in the specified file
-replay-all                           Continue processing all .input files in sequential order
-rollback-mode MODE                   Start in rollback mode (0=Idle 1=Record 2=Replay)
-rollback-snapshot-period FRAMES      Save a rollback snapshot every N frames (60 for 1 second)
-rollback-input-dir DIRECTORY         Specify where rollback files are read from
-rollback-output-dir DIRECTORY        Specify where rollback files are written
-rollback-discard-data                Discard input rollback data when starting recording instead of appending to it
-during SECONDS                       Exit after given guest seconds elapsed
-during-frames FRAMES                 Exit after given guest ticks
--save-screenshot-on-quit PATH        Save host screenshot before exiting
--volume PERCENT                      Set the master volume
-no-audio                             Do not open nor output audio
-boost-fx FACTOR                      Multiply SuperFX clock speed
-no-lowlatency                        Render in a separate thread, to accommodate "slow" titles.
-lowlatency                           Render on the main thread to reduce input latency.
-no-cpurender                         Use the old GPU code for rendering
-cpurender                            Use the CPU for rendering
-filter INTEGER                       Activate a post-process graphics filter (0=None 1=OpenGL 2=Scanlines 3=CRT)
-magfilter INTEGER                    Specifies the magnification filter (0=Nearest 1=Linear 2=HorizontalLinear 3=AntiAliasedNearest). The default is nearest with -filter 1 and linear with -filter 2 or -filter 3.
--wait-transition-fd EVENTFD          Specifies the event fd to read before drawing the first frame.
--start-transition-fd EVENTFD         Specifies the event fd write to when starting the exit to menu transition.
--finish-transition-fd EVENTFD        Specifies the event fd to write when the exit to menu transition is finished.
--transition-to-menu-sprite FILENAME  Specifies the menu transition sprite sheet to use.
--transition-to-menu-at-exit          Plays the transition animation when exiting.
--transition-from-menu                Plays the transition animation before starting.
-fp INTEGER                           Activate Flash/Patterns compensation filter (0=None, 1=VcPhoto 2-5=Armet:Additive,Blend,MonoAdditive 100=auto)
-glFinish                             Graphics option to reduces latency on mali400, but may degrade framerate
-no-glFinish                          Opposite of the above option, which became default as of 1.9.1201
-render-soft                          Use SDL software renderer.
-show-minimized                       Create window in background
--use-decorative-frame PATH           Show a decorative frame using the given file, minus the extension
--decorative-frame-hue                Automatically tint the decorative frame, using the game's output
--decorative-frame-saturation         Automatically desaturate decorative frame, using the game's output
--decorative-frame-luminosity         Automatically change the decorative frame's luminosity, using the game's output
--pixel-perfect                       Render the screen using square pixels
--rollback-ui PATH                    Load the rollback UI from this folder
-record-next                          Save next state snapshot and inputs on exit
--save-on-quit FILENAME               Save state snapshot on exit in given filename
-use-state-saver                      Use StateSaver instead of QuickSave
--sram-file FILENAME.sfrom            Path to save the SRAM to when it's modified
-exit-on-sram-file-load-error         Exit if loading the SRAM file (--sram-file) failed
--enable-sram-file-hash               Output a .hash file for SRAM files (standalone and save state)
--load-time-path FILENAME.sfrom       Path to load the playtime
--save-time-path FILENAME.sfrom       Path to save the playtime
-rom FILENAME.sfrom                   The game to emulate
```
