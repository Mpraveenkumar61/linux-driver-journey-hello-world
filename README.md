# Linux Device Driver Journey 🐧

Learning Linux Kernel Module development from scratch.

## Module 01 — Hello World Kernel Module
- First dynamically loadable kernel module
- Uses `module_init` / `module_exit` hooks
- Prints to kernel log via `printk`

### Build & Run
```bash
make CC=/usr/bin/gcc-15
sudo insmod ldd.ko
sudo dmesg | tail
sudo rmmod ldd
```
