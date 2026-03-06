Internal Network Validator & Security Auditor
 
 _Overview_
A Python-based security utility designed to automate the process of network auditing and data sanitization. This tool identifies high-risk open ports (like FTP and SSH) and masks internal IP addresses to comply with data privacy standards.

_ Key Features_
Port Audit Module: Scans a defined list of ports and flags "OPEN" statuses for administrative review.
IP Masking: Automatically sanitizes IP logs by masking the host octets, useful for sharing logs without exposing network topology.
Modular Design: Written in clean, modular Python for easy integration into larger SOC automation workflows.

_How It Works_
The script evaluates internal network traffic patterns and applies a masking logic (`XXX.XXX.*.*`) to protect internal infrastructure details.
 
 _Usage_
1. Clone the repository: `git clone https://github.com/manisha2580/Internal-Network-Validator.git`
2. Run the auditor: `python main.py`

_Future Roadmap_
- [ ] Add support for CIDR notation validation.
- [ ] Integrate Nmap library for real-time scanning.
- [ ] Export audit results to JSON or CSV format.
