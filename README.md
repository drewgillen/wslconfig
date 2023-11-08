# WSL2 Configuration File for Docker on Windows

## Introduction
This README provides information on the WSL2 configuration file used to fine-tune your Docker environment on Windows. The file is located in the following directory:

**File Location:** `C:\Users\<username>\.wslconfig`

## File Encoding and Line Endings
Ensure that you have the following encoding and line endings set for your `.wslconfig` file:

- **Encoding:** UTF-8
- **Line Endings:** LF (Unix-style line endings)

You can use a text editor that supports UTF-8 encoding and LF line endings to edit this file.

## Configuration Settings

### Memory
The `memory` setting allows you to specify the amount of RAM allocated to your WSL2 environment. You can set the RAM usage in gigabytes. For example, to allocate 4GB of RAM, use the following format:
```yaml

### Memory
The `memory` setting allows you to specify the amount of RAM allocated to your WSL2 environment. You can set the RAM usage in gigabytes. For example, to allocate 4GB of RAM, use the following format:
```yaml
memory=4GB

### Swap
The `swap` setting controls the amount of swap space for your WSL2 environment. Swap space is used as virtual memory when your physical RAM is exhausted. You can set the swap size in gigabytes. For example, to allocate 2GB of swap space, use the following format:
```yaml
swap=2GB

### Processors
The processors setting determines the number of CPU processors or cores allocated to your WSL2 environment. You can specify the number of processors you want to use. For example, to allocate 4 CPU cores, use the following format:
```yaml
processors=4

### Debug Console
The debugConsole setting allows you to enable or disable the WSL debug console when launching Docker containers. You can set it to either true or false. When set to true, the debug console will open when launching Docker containers. To enable the debug console, use the following format:
```yaml
debugConsole=true


