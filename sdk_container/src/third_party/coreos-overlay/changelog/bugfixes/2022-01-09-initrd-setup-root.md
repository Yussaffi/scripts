- The rootfs setup in the initrd now runs systemd-tmpfiles on every boot, not only when Ignition runs, to fix a dbus failure due to missing files ([Flatcar#944](https://github.com/flatcar/Flatcar/issues/944))