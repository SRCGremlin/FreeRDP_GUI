# FreeRDP_GUI
A FreeRDP GUI for linux distributions PyGTK3.0 based

# Overview

A simple FreeRDP GUI that allows for connection to four pre-configured presets

Main testing platform is Arch-based distributions however being PyGTK3.0 based it should be somewhat cross-platform compatible.

Run with FreeRDP_runner.py (launches tray icon KDE/ Plasma) or FreeRDP_Main.py to run on its own

Steps:
1. Enter Connection Data - You can progress straight to connect if you don't want to save to a profile
2. Select Profile (1-4)
3. Hit Save Profile (This will lock the file)
4. Hit Connect

## Resolution

Default resolution is set to 1920x1080 however with the fullscreen box ticked it will adjust to the current screen resolution

## Save

Insecure Save function

## Work in Progress

Intend to continue tidying this up, next iteration looking to add a dropdown box and test launching multiple concurrent connections.
