# ANSI Highlighter Premium

In the total absence of text editors capable of interpreting ANSI sequences, [ANSI Highlighter](https://niftythoughts.com/#ansi-highlight) harnesses the power of the IntelliJ platform to fulfill the need of rendering ANSI escape sequences in log files from within the convenience of the IDE editor, all while delivering outstanding performance when dealing with large logs.

Plugin available on the JetBrains Marketplace, compatible with all Jetbrains products.

## Supported Features
### Configurable 'ANSI Aware' file extensions:
- Go to Preferences | Editor | File Types
- Under 'Recognized File Types' select 'ANSI Aware'
- Under 'File name patterns' add your custom 'ANSI Aware' file name patterns, *.log is added by default
- Press 'Apply'
### List of supported ANSI codes:
- Reset code (0)
- Bold code (1)
- Italic code (3)
- Single Underline code (4)
- All text foreground color codes (30-37)
- All text high intensity foreground color codes (90-97)
- All text background color codes (40-47)
- All text high intensity background color codes (100-107)
### Customize ANSI colors:
- Go to Preferences | Editor | Colors Scheme | Console Colors
- Expand 'ANSI Colors'
- Customize foreground and background colors as needed
- Press 'Apply'
### Toggle editor display mode:
To toggle between ANSI Highlighter and Plain display modes use one of the following options:
- Click 'Show Plain Mode' from the banner on top of the editor
- Switch between 'Plain' and 'ANSI Highlighter' tabs at the bottom
- Right click on the editor and press 'Switch to Plain/ANSI Highlighter mode'
- Alternatively place the cursor on the editor and use the keyboard shortcut 'ctrl meta A' (customize the shortcut from Preferences>Keymap>ANSI Highlighter Premium if needed)
