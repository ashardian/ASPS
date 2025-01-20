# Advanced Screen Protection Suite

**Comprehensive screen security and sandbox management**

The Advanced Screen Protection Suite is a powerful software designed to provide robust screen security and sandbox management capabilities. This suite is particularly useful for users concerned about unauthorized screen capturing, remote desktop control, and maintaining secure sandbox environments for applications.

## Features

### Security Features

1. **Screen Capture Detection**  
   Detects attempts to capture the screen and alerts the user.

2. **Remote Desktop Control**  
   Monitors and manages remote desktop sessions to prevent unauthorized access.

3. **Screen Capture Blocking**  
   Blocks unauthorized screen capture attempts.

4. **Remote Session Monitor**  
   Monitors remote sessions for suspicious activity.

5. **Sandbox Environment**  
   Provides a secure sandbox environment to run applications safely.

### Active Process Monitoring

- Actively monitors running processes to detect potential threats.  
  Example: Detected process - `smartscreen.exe (PID: 12916)`

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/advanced-screen-protection-suite.git
   ```
2. Navigate to the project directory:
   ```bash
   cd advanced-screen-protection-suite
   ```
3. Run the executable or launch the application from the appropriate folder.

### User Interface Overview
- Each feature in the application has an **Execute** button to activate its functionality.
- A process monitor displays detected threats and monitored processes in real time.

## Requirements

- Windows 10/11
- .NET Framework 4.7 or higher (if using the executable)
- Python 3.8 or higher (if running the script directly)

## Required Libraries

To run the Python script, the following libraries are required:

- `os`
- `psutil`
- `ctypes`
- `platform`
- `sys`
- `tkinter`
- `win32com.client`
- `pywinauto`
- `subprocess`
- `json`
- `winreg`
- `PIL` (Python Imaging Library)
- `base64`
- `io`
- `win32security`
- `win32process`
- `win32con`
- `win32gui`
- `threading`
- `time`
- `traceback`

### Installing Required Libraries

You can install the required libraries using `pip`:

```bash
pip install psutil pywin32 pywinauto pillow
```

## Contribution

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

For any issues or feedback, please open a GitHub issue or contact us directly.
