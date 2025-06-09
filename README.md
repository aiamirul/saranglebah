# saranglebah

Master-slave WiFi-based keystroke broadcaster with CLI interface.

## Installation
```bash
pip install saranglebah
```

## Usage

### Master
```bash
saranglebah boss --hamba 192.168.1.100 192.168.1.101
```

### Slave
```bash
saranglebah hamba
```

## Exit
Use `Ctrl + F12` on master to exit the listener.
