# Environment Setup

Benpigchu works under the WSL(Windows Subsystem for Linux) on a Windows 10 Pro Insider machine.

On WSL we can manually install build utils and qemu on Ubuntu.

Notice that Windows use CRLF as line terminator instead of LF,it should be converted before bash script executed.

Since WSL do not have a graphic interface by default, use `make qemu-nox` instead of `make qemu`. For debugging, `make debug-server` and `make debug-client` is added to makefile to make it possible to open gdb and qemu in two terminal session. Also, it's possible to run gdb outside WSL and attach to the qemu process in WSL.

For vscode user, a `.vscode/launch.json` is provided to enable debugging through vscode debug panel.

If any other problem relative to the environment happens, it will be listed here.