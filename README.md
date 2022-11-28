Small Bash script which is useful if after suspending your distro the USB ports no longer recognize what was attached to them.
- Copy this script in: <code>/lib/systemd/system-sleep/</code>
- Execute: <code>chmod +x resetAllUsbDevices</code>
This is should resolve this issue.
