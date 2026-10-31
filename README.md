<a href="https://steitec.net"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/steitec/.github/main/brand/steitec-logo-on-dark.svg">
  <img height="40" alt="steitec" src="https://raw.githubusercontent.com/steitec/.github/main/brand/steitec-logo-on-light.svg">
</picture></a>

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
| [scpi-sim](https://github.com/steitec/scpi-sim) | Simulated SCPI lab instruments over raw TCP, VXI-11 and HiSLIP, with profiles of ten real models (R&S, Keysight, Keithley, Siglent): instruments wired into a bench in YAML, fault injection at runtime, pytest plugin, CI on Linux/Windows/macOS; on [PyPI](https://pypi.org/project/scpi-sim/) and as a Docker image · **[try it in your browser](https://scpi-sim.steitec.net)** |
| [hart-sim](https://github.com/steitec/hart-sim) | Simulated HART field devices (pressure and temperature transmitter) over HART-IP on TCP and UDP: universal and common-practice commands, 4-20 mA loop current with NAMUR NE 43 alarm currents, YAML device profiles, fault injection at runtime, pytest plugin, cross-checked against the Wireshark HART-IP dissector in CI; on [PyPI](https://pypi.org/project/hart-sim/) |
| [modbus-sim](https://github.com/steitec/modbus-sim) | Simulated Modbus devices that behave like real ones: an energy meter whose counters count, a temperature controller that heats to its setpoint, a frequency converter with control word, ramps and fault trip; Modbus TCP, RTU over TCP and serial RTU, 32-bit word orders, scaling and register gaps from YAML profiles, fault injection at runtime (timeouts, exceptions, bad CRC, dropped connections), pytest plugin, cross-checked against pymodbus in CI; on [PyPI](https://pypi.org/project/modbus-sim/) |
| [boot-log-diff](https://github.com/steitec/boot-log-diff) | Compares the serial boot log of an embedded board with a golden log: masks timestamps, addresses and other boot-to-boot noise, ignores driver probe order, compares RAM/CPU/versions, names known faults with a repair diagnosis and writes JUnit/HTML reports for CI; on [PyPI](https://pypi.org/project/boot-log-diff/) |
| [interface-test-kit](https://github.com/steitec/interface-test-kit) | Guided interface test that runs on the embedded PC itself: serial ports including every handshake line, USB test sticks (port, speed, throughput), Ethernet and CAN, one YAML profile per product variant, Y/N prompts for operators and an equipment self-test for worn loopback plugs; on [PyPI](https://pypi.org/project/interface-test-kit/) |
| [test-protocol](https://github.com/steitec/test-protocol) | Turns raw test results (bench and interface test JSON, JUnit XML from pytest or boot-log-diff, CSV incl. German Excel exports) into a printable test protocol for one unit: limits from a TOML file, PASS/FAIL verdict with failed checks on top, SHA-256 of every input for traceability, signature boxes, HTML/PDF in English or German; on [PyPI](https://pypi.org/project/test-protocol/) |
| [scpi-replay](https://github.com/steitec/scpi-replay) | Records the SCPI traffic between test software and a real instrument through a transparent proxy, then replays it: as a stand-in instrument so the test software runs in CI without hardware, or as a regression check against the real instrument or scpi-sim with tolerance rules and JUnit output; pytest fixture included; on [PyPI](https://pypi.org/project/scpi-replay/) |
| [bench-automation](https://github.com/steitec/bench-automation) | End-of-line test station for an embedded PC, with simulated SCPI instruments, fault injection and HTML reports |
| [kiosk-kit](https://github.com/steitec/kiosk-kit) | Unattended touch kiosk for Debian/GNOME: touch-wake display service, update-proof Chromium, Wayland touch calibration |
| [vaultwarden-for-android](https://github.com/steitec/vaultwarden-for-android) | Firefox for Android add-on for self-hosted Vaultwarden, signed by Mozilla |

**Stack:** Python · PyVISA · pyserial · pytest · HART-IP · Linux · systemd · Docker ·
FastAPI · React · TypeScript

📫 Available for freelance work — remote, fixed-price where possible.
