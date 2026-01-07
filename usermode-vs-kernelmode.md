# User Mode vs Kernel Mode

Windows uses a **two-mode architecture** for stability and security.

## User Mode
- Limited privileges
- Cannot directly access hardware
- Applications run here
- Examples:
  - Chrome
  - Notepad
  - Word

If a user-mode app crashes → OS continues running.

## Kernel Mode
- Full hardware access
- Controls memory, CPU, devices
- Components:
  - Windows Kernel
  - Device Drivers
  - HAL

⚠️ Kernel crash → Blue Screen of Death (BSOD)
