# SSH Botnet Project (Educational Only)

This project demonstrates how multiple SSH clients (bots) can be managed and controlled using Python. It is designed ONLY for ethical, educational, and research use on your own machines/VMs.

## Features

- Manage unlimited SSH bots
- Store bots in JSON (botnet.json)
- Automatic reconnection
- Execute commands on single or all bots
- Run bash scripts remotely
- Local SYN-Flood simulation using scapy
- Clean menu-driven interface
- Detailed colored output

## Requirements

Install dependencies:

pip install pexpect colorama scapy

shell
Copy code

## Usage

python ssh_botnet.py

pgsql
Copy code

Add bots using option 4.

## Supported Actions

| Option | Action |
|--------|--------|
| 1 | List all connected bots |
| 2 | Run command on a single bot |
| 3 | Run command on all bots |
| 4 | Add new SSH bot |
| 5 | Run bash commands on all bots |
| 6 | SYN Flood (LOCAL LAB TEST ONLY) |
| 7 | Save & Exit |

## Notes

- Use **only** on your own systems (VMs, LAN devices).
- Works best with Ubuntu/Kali/Parrot VMs running SSH.
- botnet.json stores credentials for easy reconnection.
- SYN Flood requires admin/root and should be tested ONLY on local isolated machines.

## Disclaimer

This project is strictly for ethical cybersecurity education. Do NOT use it on unauthorized systems.

## License

MIT License
