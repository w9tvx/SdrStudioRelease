# SDRStudio

SDRStudio is a Windows desktop application for building custom control surfaces for FlexRadio stations. It lets you compose task-specific widgets from radio-aware controls, save them to a widget library, and launch them quickly while operating SmartSDR.

SDRStudio is currently alpha software and under active development.

## Download

Download the latest SDRStudio installer from the [Releases page](releases/latest):

```text
SdrStudioSetup-<version>.exe
```

Run the installer and follow the setup prompts.

## Requirements

- Windows 10 or later.
- FlexRadio with SmartSDR for radio operation.
- Internet access during setup if the .NET Desktop Runtime is not already installed.

The installer checks for the required Microsoft .NET 9 Desktop Runtime x86 and downloads it from Microsoft if needed.

## What SDRStudio Does

- Connects to FlexRadio/SmartSDR sessions.
- Builds custom widgets with the Widget Composer.
- Provides radio-aware controls such as meters, buttons, text readouts, numeric controls, selectors, and profile controls.
- Assigns launchable widgets to main-window launcher buttons.
- Imports and exports user widget bundles.
- Includes generated in-app HTML help and a component reference.

## First Run

1. Start SDRStudio from the Start Menu or desktop shortcut.
2. Connect to your FlexRadio from the Radio Connection window.
3. Open the Widget Library.
4. Create or edit widgets in the Widget Composer.
5. Assign widgets to launcher buttons for quick access.

## User Data

SDRStudio stores user preferences and custom widgets under:

```text
%LOCALAPPDATA%\SdrStudio
```

This folder may contain your preferences, launcher layout, window layout, and user-created widgets. Back it up before uninstalling or testing fresh installs if you want to preserve your setup.

## Uninstall

Use Windows Settings:

```text
Settings > Apps > Installed apps > SDRStudio > Uninstall
```

Uninstalling the application removes installed program files. User data under `%LOCALAPPDATA%\SdrStudio` may remain so future installs can keep your settings and widgets.

## Documentation

SDRStudio includes built-in help covering:

- Getting started
- Main window
- Launcher panel
- Widget library
- Widget composer
- Radio connection
- Component reference

Open help from inside the application.

## Author

Created by Ross Dargahi, W9TVX, with assistance from ChatGPT Codex.

Copyright (c) 2026 Ross Dargahi. All rights reserved.


