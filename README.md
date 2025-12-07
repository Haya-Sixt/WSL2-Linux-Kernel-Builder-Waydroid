# WSL2-Linux-Kernel-Builder
![kernel-build](https://github.com/beghem/WSL2-Linux-Kernel-Builder/actions/workflows/build.yml/badge.svg)

USB (usbip), USB-CAN, WayDroid and Kasm support for WSL2 Kernel.

+ Download one of the [Kernels](https://github.com/Haya-Sixt/WSL2-Linux-Kernel-Builder/actions) (click the latest workflow run)
+ Create a `.wslconfig` file on `/mnt/c/Users/<user>/` and add a reference to the created image with the following.[^1]
    ```ini
    [wsl2]
    kernel=c:\\users\\<user>\\linux-msft-wsl-6.6.y-can-usbip-wd-ksm
    ```

[^1]: [usbipd-win](https://github.com/dorssel/usbipd-win)
