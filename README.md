# Day 1

## C2 Workshop requirements

1. Kali Linux VM
2. Setup a Windows 10 VM with at least 25GB of storage (Refer youtube for tutorial)


## Binary Exploitation Workshop requirements

### 1. Kali Linux VM or any Ubuntu machine (Can use the same machine from C2 Workshop)

### 2. Pwntools
```sh
sudo apt-get update
sudo apt-get install python3 python3-pip python3-dev git libssl-dev libffi-dev build-essential
python3 -m pip install --upgrade pip
python3 -m pip install --upgrade pwntools
```

### 3. ROPgadget
```sh
sudo apt install python3-pip
sudo -H python3 -m pip install ROPgadget
```

### 4. GDB
```sh
sudo apt install gdb
```

### 5. Choose one, pwndbg or gef (GDB plugins)

- [pwndbg](https://github.com/pwndbg/pwndbg)
- [gef](https://github.com/hugsy/gef)

### 6. Checksec

```sh
sudo apt install checksec
```

### 7. Ghidra

```sh
sudo apt install ghidra
```

### 8. Any text editor

- Sublime Text
- Vim
- Emacs
