# Legacy Control Panel Restoration Pack

This NTMU pack restores legacy Windows Control Panel features, classic UI elements (Windows 7/Vista-style), and provides WindHawk patches for a complete classic experience on modern Windows.

## Components

- **System Files**: Replaces protected system DLLs, MUIs, and MUNs with legacy versions to restore classic functionality.
- **Registry Keys**: Imports comprehensive registry configurations for Control Panel pages, performance counters, and UI behaviors.
- **WindHawk Mod**: Includes `cpl-reborn.wh.cpp` to patch system processes at runtime for better compatibility and classic behavior.

## Usage

1. **Install NTMU**: Ensure you have the NTMU framework installed.
2. **Apply Pack**: Use NTMU to apply the "Legacy Control Panel Restoration" pack. This will:
   - Replace the necessary system files (with backups).
   - Import all registry keys using TrustedInstaller privileges.
3. **WindHawk Setup**:
   - The pack automatically copies `cpl-reborn.wh.cpp` to `%ProgramData%\Windhawk\ModsSource`.
   - Open WindHawk, find the `cpl-reborn` mod, and compile/enable it.
   - Ensure "exclude system processes" is unchecked in WindHawk advanced settings.

## Optional Components

- **Layout Fixes**: In the `resources\layout-fixes` directory of this pack, you will find batch files (`cpl10.bat`, `cpl7.bat`, etc.) that can be manually executed to fix various Control Panel category layouts.

## Warning

This pack modifies critical system files and registry entries. It is intended for advanced users. Always create a system restore point or backup before applying.
