# saranglebah

Master-slave WiFi-based keystroke broadcaster with CLI interface.

## Installation
```bash
pip install .
```

## Usage

### Master
```bash
saranglebah master --slaves 192.168.1.100 192.168.1.101
```

### Slave
```bash
saranglebah slave
```

## Exit
Use `Ctrl + F12` on master to exit the listener.
