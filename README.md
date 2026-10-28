### Hi, I'm Ralf — test & automation engineer 👋

I spent years repairing embedded PCs and writing the test software that
checked them. Today I build the things around that work, from the test bench
to the server:

- **Test automation** — Python instrument control over SCPI / serial / USB,
  production test sequences with limits and reports
- **Embedded Linux** — Raspberry Pi and panel-PC kiosk systems that boot into
  your app, recover on their own and keep themselves updated
- **Self-hosting** — Docker stacks with reverse proxy and TLS, fail2ban,
  backups, monitoring and push alerts
- **Web tools** — small FastAPI + React apps with a clear scope

#### Selected projects

| Project | What it shows |
|---|---|
| [scpi-sim](https://github.com/steitec/scpi-sim) | Simulated SCPI lab instruments on a raw TCP socket, with profiles of ten real models (R&S, Keysight, Keithley, Siglent): instruments wired into a bench in YAML, fault injection at runtime, pytest plugin, CI on Linux/Windows/macOS; on [PyPI](https://pypi.org/project/scpi-sim/) and as a Docker image |
| [boot-log-diff](https://github.com/steitec/boot-log-diff) | Compares the serial boot log of an embedded board with a golden log: masks timestamps, addresses and other boot-to-boot noise, ignores driver probe order, compares RAM/CPU/versions and flags new errors; on [PyPI](https://pypi.org/project/boot-log-diff/) |
| [interface-test-kit](https://github.com/steitec/interface-test-kit) | Guided interface test that runs on the embedded PC itself: serial ports including every handshake line, USB test sticks (port, speed, throughput), Ethernet and CAN, one YAML profile per product variant, Y/N prompts for operators and an equipment self-test for worn loopback plugs; on [PyPI](https://pypi.org/project/interface-test-kit/) |
| [bench-automation](https://github.com/steitec/bench-automation) | End-of-line test station for an embedded PC, with simulated SCPI instruments, fault injection and HTML reports |
| [kiosk-kit](https://github.com/steitec/kiosk-kit) | Unattended touch kiosk for Debian/GNOME: touch-wake display service, update-proof Chromium, Wayland touch calibration |
| [vaultwarden-for-android](https://github.com/steitec/vaultwarden-for-android) | Firefox for Android add-on for self-hosted Vaultwarden, signed by Mozilla |

**Stack:** Python · PyVISA · pyserial · pytest · Linux · systemd · Docker ·
FastAPI · React · TypeScript

📫 Available for freelance work — remote, fixed-price where possible.
