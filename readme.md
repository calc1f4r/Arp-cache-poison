### 🐋 ARP Cache Poisoning Script

This Python script leverages the power of the scapy library to perform ARP (Address Resolution Protocol) poisoning and packet sniffing on a local network. ARP poisoning is a technique where an attacker intercepts and manipulates network traffic between a victim and a gateway, effectively becoming a "man-in-the-middle." The tool also includes packet sniffing capabilities, allowing users to capture and analyze network traffic for security testing or educational purposes.

#### ⚔ Features

- 🔑 ARP Cache Poisoning: Become a network sorcerer as you magically deceive devices and reroute their traffic through your machine.
- 📝 Packet Sniffing: Unveil the hidden secrets of intercepted packets and delve into the essence of network communication.
- 🎛️ Command-Line Interface: Command your network with simple arguments, effortlessly configuring target IPs and network interfaces.
- 🚄 Multiprocessing: Experience blazing-fast execution as you handle ARP poisoning and packet sniffing in parallel.

#### ⚔ Usage

**Requirements**

```python
pip install scapy termcolor
```

**Basic Usage**

- Specify the victim's IP using the -vIP argument:

```python
sudo python arp_cache_poison.py -vIP <victim_ip_address>
```

- Specify the gateway/router's IP using the -gIP argument:

```python
sudo python arp_cache_poison.py -vIP <victim_ip_address> -gIP <gateway_ip_address>
```

- Optionally enable packet sniffing with the -sniff flag:

```python
sudo python arp_cache_poison.py -vIP <victim_ip_address> -gIP <gateway_ip_address> -sniff
```

- Set the packet count for packet sniffing using the -pc argument:

```python
sudo python arp_cache_poison.py -vIP <victim_ip_address> -gIP <gateway_ip_address> -sniff -pc <packet_count>
```

#### ⚡ Contributions

Contributions are welcome! If you find a bug or have suggestions for improvements, feel free to open an issue or submit a pull request.
