# Pomodorable Timer

A simple, elegant Pomodoro timer built as a single static HTML file. Perfect for productivity tracking with customizable session lengths and sound notifications.

## Quick Start

Open `Pomodoro.html` in your browser — that's it! No installation, no dependencies.

## Features

- **Customizable Durations**: Adjust work, short break, and long break lengths
- **Sound Notifications**: Choose from Beep, Chime, or Bell sounds (or None)
- **Dynamic Favicon**: Browser tab icon updates with session status
- **Session Avatars**: Visual avatars for different session types (work, short break, long break, idle)
- **Cycle Tracking**: Tracks completed work cycles
- **Keyboard Shortcuts**: Press Space to toggle start/pause
- **Persistent Settings**: Your sound choices and volume are saved to localStorage
- **Offline First**: Works completely offline with no external dependencies

## Default Settings

- **Work**: 25 minutes
- **Short Break**: 5 minutes
- **Long Break**: 15 minutes (after 4 work cycles)

## Controls

- **Start**: Begin the current session
- **Pause**: Pause the timer (shows idle avatar)
- **Reset**: Stop and reset to Work session (shows idle avatar)
- **Apply**: Save custom duration settings
- **Preview**: Test your selected sound for a session type

## Customization

Edit the duration inputs at the bottom of the timer, then click "Apply" to update. Changes persist until you modify them again.

## Sound Options

Choose a different sound for each session type:
- Beep (800Hz tone)
- Chime (two-tone bell)
- Bell (rich harmonic bell)
- None (silent)

Adjust the volume slider to control notification loudness.

## Hosting

This is a single-file build perfect for static hosting:
- **Amazon S3**: Upload `Pomodoro.html` and serve via CloudFront
- **GitHub Pages**: Drop the file in a repo
- **Any static host**: Works anywhere

## Technical Details

- **Format**: Single HTML file with embedded CSS and JavaScript
- **No Dependencies**: Pure vanilla JS, no external libraries
- **Browser Support**: Any modern browser (ES6+)
- **Data Storage**: Uses localStorage for user preferences (no server required)

