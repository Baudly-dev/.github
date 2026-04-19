# Baudly Features

Baudly is a next-generation terminal client built to replace legacy tools like PuTTY. It supports SSH, Serial (UART/RS-232), CAN bus, Telnet, and local shell connections in a modern, tabbed interface.

---

## Multi-Protocol Connections

### SSH
- Password and SSH key-based authentication
- Full xterm.js terminal emulation with ANSI colour support
- Dynamic terminal resize (SIGWINCH)
- Secure credential storage (Windows Credential Manager)

### Serial (UART / RS-232)
- Automatic COM port detection
- Configurable baud rate, data bits, parity, stop bits, and flow control
- Real-time terminal emulation for serial data

### Telnet
- Raw TCP connection with full Telnet IAC protocol negotiation
- Terminal type and window size negotiation
- Full xterm.js terminal emulation

### CAN Bus
- SLCAN and PCAN adapter support
- Standard and extended CAN frame IDs (11-bit / 29-bit)
- Normal and listen-only modes
- Timestamped frame display with DLC and payload

### Local Shell
- Open a terminal running directly on the local machine — no remote connection needed
- Supports Command Prompt, PowerShell, PowerShell Core, WSL, Bash, Zsh, Fish, or any custom shell path
- Auto-detects the system default shell on Windows, Linux, and macOS
- Full PTY emulation with dynamic resize

---

## Session Management

- Save SSH, Serial, and CAN sessions for quick reconnection
- Sessions stored in TOML files under the OS app-data directory
- One-click connect from the session browser

---

## Tab-Based Interface

- Run multiple concurrent sessions in tabs
- Split-pane layout for side-by-side terminals
- Drag tabs between panes and reorder within panes
- Per-session connection status indicators

---

## Macros System

- Create named command/text snippets for repeated inputs
- Organise macros into folders
- Variable substitution: `${host}`, `${user}`, `${cursor}`
- Scope macros to all sessions or specific protocols (SSH, Serial, CAN)
- Optional confirmation dialogs before sending sensitive macros
- Assignable keyboard shortcuts

---

## File Transfer (SFTP)

- Drag-and-drop file uploads over SSH
- Local and remote file browser
- Transfer queue with real-time progress tracking

---

## SSH Tunnel Manager

- Local and remote port forwarding
- View and manage active tunnels from the UI

---

## Security

- Passwords and passphrases never stored in plain text
- Windows Credential Manager integration
- SSH key passphrase support

---

## Platform Support

| Platform | Status |
|---|---|
| Windows (x86-64) | Available |
| macOS | TBC |
| Linux | TBC |
