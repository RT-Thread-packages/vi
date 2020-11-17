# vi

[中文页](README_ZH.md) | English

## 1. Introduction

vi is a well-known text editor under Unix-like platforms. This software package is a port of vi to RT-Thread operating system, derived from the vi editor in busybox, and only implements basic editing functions.

### 1.1. File structure

| Name | Description |
| ---- | ---- |
| vi.c | vi editor source file |

### 1.2 License

vi follows the LGPLv2.1 license, see the `LICENSE` file for details.

### 1.3 Dependency

- RT_Thread DFS
- RT_Thread libc
- RT_Thread optparse package

## 2. How to Obtain

The vi software package needs to enable DFS, libc function and optparse software package.

First enable the DFS function, the specific path is as follows:

    RT-Thread Components --->
        Device virtual file system --->
             [*] Using device virtual file system

Then open the libc function, the specific path is as follows:

    RT-Thread Components --->
        POSIX layer and C standard library --->
             [*] Enable libc APIs from toolchain

Finally, open the optparse package, the specific path is as follows:

     RT-Thread online packages --->
        miscellaneous packages --->
            [*] optparse: a public domain, portable, reentrant, embeddable, getopt-like option parser

## 3. Matters needing attention

- Only use keil and gcc to test, IAR not tested yet

## 4. Contact information

- Maintenance: RT-Thread development team and community developers
- Homepage: <https://github.com/RT-Thread-packages/vi>
