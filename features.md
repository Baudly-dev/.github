# Baudly Features

Baudly is a modern terminal client for engineers — SSH, serial, and local connections in a tabbed interface, with macros, file transfer, and cloud sync.

---

## Connections

### SSH · Free & above
- Password and SSH key-based authentication
- Full xterm.js terminal emulation with ANSI colour support
- Dynamic terminal resize (SIGWINCH)
- Credentials stored in the OS keychain (macOS Keychain, Windows Credential Manager, libsecret)

### Serial / UART / RS-232 · Free & above
- Automatic COM port and USB device detection (USB, RS-232, FTDI)
- Configurable baud rate, data bits, parity, stop bits, and flow control
- Real-time terminal emulation

### Local Shell · Free & above
- Open a terminal on the local machine — no remote connection needed
- Supports Command Prompt, PowerShell, PowerShell Core, WSL, Bash, Zsh, Fish, or any custom shell path
- Auto-detects the system default shell on Windows, macOS, and Linux
- Full PTY emulation with dynamic resize

### CAN Bus · Pro & above
- SLCAN and PCAN adapter support
- Standard and extended CAN frame IDs (11-bit / 29-bit)
- Normal and listen-only modes
- Timestamped frame display with DLC and payload
- Live frame table with pause/resume, hex-ID filtering, and a frame-rate counter

### Telnet · Pro & above
- Raw TCP connection with full Telnet IAC protocol negotiation
- Terminal type and window size negotiation
- Full xterm.js terminal emulation

### VNC · Pro & above
- Remote desktop connections over VNC
- View-only mode for safe screen sharing
- Screenshot capture

### Remote File Browser · Pro & above
- Dedicated SFTP/SCP file-browser session — no terminal window needed
- Browse, upload, download, rename, and delete remote files
- Built-in text editor for quick remote file edits

---

## Sessions

- Save SSH, serial, CAN, Telnet, VNC, local, and remote-file-browser sessions for quick reconnection
- Sessions stored locally under the OS app-data directory
- One-click connect from the session browser
- Free plan: up to 5 saved sessions (Serial, SSH, and Local Shell only) · Pro & above: unlimited, all connection types

---

## Tab-Based Interface

- Run multiple concurrent sessions in tabs
- Split-pane layout for side-by-side terminals
- Drag tabs between panes and reorder within panes
- Per-session connection status indicators
- State sync and restore on launch

---

## Macros

- Create named command/text snippets for repeated inputs
- Organise macros into folders in a dockable sidebar
- Variable substitution: `${host}`, `${user}`, `${cursor}`
- Scope macros to all sessions or specific protocols (SSH, serial, CAN, Telnet, local)
- Custom icons, including your own SVG/PNG uploads
- Optional confirmation dialogs before sending sensitive macros
- Assignable keyboard shortcuts
- Import and export your macro library as JSON
- Free plan: up to 5 macros · Pro & above: unlimited

---

## File Transfer

- Drag-and-drop file uploads over SSH, via SFTP or native SCP
- Single-file downloads with a protocol picker
- Remembers the last-used target directory per session
- Real-time transfer progress

---

## Cloud Sync · Pro & above

- Macros and session settings sync automatically across machines

---

---

## Security

- Credentials and key passphrases never stored in plain text
- OS keychain integration: macOS Keychain, Windows Credential Manager, libsecret (Linux)
- SSH private key passphrase support

---

## Platform Support

| Platform | Status |
|---|---|
| Windows 10 & 11 (x64) | Available now |
| macOS 13+ (Apple Silicon & Intel) | Coming soon |
| Linux (AppImage & .deb, x64) | Coming soon |
