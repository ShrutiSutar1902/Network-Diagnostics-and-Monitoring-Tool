# Network & System Diagnostic Tool

This Python script performs basic network and system diagnostics, including ping tests, DNS resolution, system information, CPU and memory usage, listening ports, and traceroute. It is cross-platform and works on both Windows and Unix-like systems.

---

## Features

1. **Ping Test**  
   Checks connectivity to `google.com` and displays the ping results.

2. **DNS Test**  
   Resolves the IP address of `google.com` to verify DNS functionality.

3. **System Information**  
   Displays OS, architecture, version, and processor details.

4. **CPU & Memory Usage**  
   Shows current CPU usage and available memory.

5. **Listening Ports**  
   Lists all currently listening TCP/UDP ports on the system.

6. **Traceroute**  
   Traces the route to `google.com` to analyze the network path.  
   - Uses `tracert` on Windows.  
   - Uses `traceroute` or `tracepath` on Linux/macOS.

---

## Requirements

- Python 3.6+
- Libraries:
  - `psutil`
  - `platform` (standard)
  - `socket` (standard)
  - `subprocess` (standard)
- Optional system tools for traceroute:
  - Windows: `tracert` (built-in)
  - Linux/macOS: `traceroute` or `tracepath`

Install `psutil` using pip if not already installed:

```bash
pip install psutil
