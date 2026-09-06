* **Python Version**: Python 3.x
* **Permissions**: Administrative / Root access is required to open raw sockets.

---

## 捗 Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/network-sniffer.git
   cd network-sniffer
   ```

2. **Run the Sniffer with Elevated Privileges**:
   ```bash
   sudo python3 sniffer.py
   ```

3. **Stop Sniffing**:
   Press `Ctrl + C` in the terminal to stop packet capture.

---

## 投 Sample Output

```text
Ethernet Frame:
Destination: 00:11:22:33:44:55, Source: 66:77:88:99:AA:BB, Protocol: 8
	 - IPv4 Packet:
		 - Version: 4, Header Length: 20, TTL: 64
			 - Protacol: 6, source: 192.168.1.50, Target: 142.250.190.46
	 - TCP Segment:
		 - Source Port: 54321, Destination: 443
		 - Sequence: 123456789, Acknowledgement: 987654321
		 - Flags:
			 - URG: 0, ACK: 1, PSH: 0, RST: 0, SYN: 0, FIN: 0
		 - Data:
			       ...
```

---

## 糖 License

This project is open-source and available under the [MIT License](LICENSE).
