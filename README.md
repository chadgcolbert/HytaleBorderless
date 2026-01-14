# Hytale Borderless
Hytale Borderless is a lightweight Windows utility that allows Hytale to run in a borderless windowed mode.

Because Simon hasn't implemented windows borderless, I can't stream to my friend in discord (Nvidia GPU problems) so I quickly made this program to do it for me and decided I should share. 

📌 Basic Usage

Launch Hytale

Open Hytale Borderless

If Hytale is already running, it will appear in the detected client list

Select the Hytale process

Click Borderless to resize the game to your primary monitor


# Button Overview

Refresh – Refreshes process list obv

Borderless – Does as it says

Restore – Restores the original window style and size


# Before you run the program

Disable fullscreen inside Hytale before using this.

Hytale must be running in windowed mode for borderless mode to work correctly.


# Requirements

Windows 10 / Windows 11

.NET Framework 4.x

Hytale (windowed mode)


# How It Works

Detects the Hytale window process

Removes the window frame using Win32 APIs

Resizes the window to match your primary monitor

No game files are modified.


Because I just fac reset my pc and didnt have VS downloaded, i just used the built in C# compiler in windows, you can lookup how to do it yourself if you don't trust the exe.

# This tool is not affiliated with Riot Games or the Hytale development team.
Use at your own risk. No warranties are provided.
