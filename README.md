# Linux/Unix System (linuxunix)
A topic catalog of system-level APIs and interfaces available across Linux/Unix-like operating systems. Includes kernel system calls, POSIX standards, inter-process communication mechanisms (D-Bus, Netlink), virtual filesystems (procfs, sysfs), event-notification facilities (epoll, inotify), device management (udev, systemd), and userspace security interfaces.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/linuxunix/refs/heads/main/apis.yml)

## Scope
- **Type:** Topic
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:
 - Kernel, Linux, Operating System, System, Unix, POSIX

## Timestamps
- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### System Calls API
Low-level interface between user-space applications and the Linux kernel providing access to process management, file I/O, memory, networking, signals, and IPC primitives.

**Human URL:** [https://man7.org/linux/man-pages/man2/syscalls.2.html](https://man7.org/linux/man-pages/man2/syscalls.2.html)

#### Tags:
 - Kernel, Low-Level, Syscalls

#### Properties
- [Documentation](https://man7.org/linux/man-pages/dir_section_2.html)
- [Reference](https://www.kernel.org/doc/html/latest/userspace-api/index.html)

### POSIX API
Portable Operating System Interface standards for Unix-like systems, defining a consistent application programming interface across platforms.

**Human URL:** [https://pubs.opengroup.org/onlinepubs/9699919799/](https://pubs.opengroup.org/onlinepubs/9699919799/)

#### Tags:
 - POSIX, Standards, Portability

#### Properties
- [Documentation](https://pubs.opengroup.org/onlinepubs/9699919799/)
- [Specification](https://standards.ieee.org/ieee/1003.1/7101/)

### D-Bus API
Inter-process communication and remote procedure call mechanism widely used on Linux desktop and system services.

**Human URL:** [https://www.freedesktop.org/wiki/Software/dbus/](https://www.freedesktop.org/wiki/Software/dbus/)

#### Tags:
 - IPC, Messaging, Desktop

#### Properties
- [Documentation](https://dbus.freedesktop.org/doc/dbus-specification.html)
- [Source Code](https://gitlab.freedesktop.org/dbus/dbus)

### Netlink API
Socket-based interface for communication between the kernel and user space, particularly for networking and device subsystems.

**Human URL:** [https://man7.org/linux/man-pages/man7/netlink.7.html](https://man7.org/linux/man-pages/man7/netlink.7.html)

#### Tags:
 - Networking, Kernel, Sockets

#### Properties
- [Documentation](https://man7.org/linux/man-pages/man7/netlink.7.html)
- [Reference](https://www.kernel.org/doc/html/latest/userspace-api/netlink/intro.html)

### procfs API
Virtual filesystem providing process and system information through a hierarchical file-based interface.

**Human URL:** [https://man7.org/linux/man-pages/man5/proc.5.html](https://man7.org/linux/man-pages/man5/proc.5.html)

#### Tags:
 - Filesystem, Process, Monitoring

#### Properties
- [Documentation](https://man7.org/linux/man-pages/man5/proc.5.html)
- [Reference](https://www.kernel.org/doc/html/latest/filesystems/proc.html)

### sysfs API
Virtual filesystem for kernel objects and device information presented under /sys.

**Human URL:** [https://man7.org/linux/man-pages/man5/sysfs.5.html](https://man7.org/linux/man-pages/man5/sysfs.5.html)

#### Tags:
 - Filesystem, Kernel, Devices

#### Properties
- [Documentation](https://man7.org/linux/man-pages/man5/sysfs.5.html)
- [Reference](https://www.kernel.org/doc/html/latest/filesystems/sysfs.html)

### inotify API
Linux kernel subsystem for monitoring filesystem events such as file creation, deletion, and modification.

**Human URL:** [https://man7.org/linux/man-pages/man7/inotify.7.html](https://man7.org/linux/man-pages/man7/inotify.7.html)

#### Tags:
 - Filesystem, Monitoring, Events

#### Properties
- [Documentation](https://man7.org/linux/man-pages/man7/inotify.7.html)

### epoll API
I/O event notification facility for scalable monitoring of large numbers of file descriptors.

**Human URL:** [https://man7.org/linux/man-pages/man7/epoll.7.html](https://man7.org/linux/man-pages/man7/epoll.7.html)

#### Tags:
 - I/O, Events, Performance

#### Properties
- [Documentation](https://man7.org/linux/man-pages/man7/epoll.7.html)

### udev API
Device manager for the Linux kernel handling device nodes and hotplug events in /dev.

**Human URL:** [https://www.freedesktop.org/software/systemd/man/udev.html](https://www.freedesktop.org/software/systemd/man/udev.html)

#### Tags:
 - Devices, Hardware, Hotplug

#### Properties
- [Documentation](https://www.freedesktop.org/software/systemd/man/udev.html)
- [Source Code](https://github.com/systemd/systemd/tree/main/src/udev)

### systemd API
System and service manager exposing a D-Bus interface for managing services, sockets, devices, mounts, and timers.

**Human URL:** [https://www.freedesktop.org/wiki/Software/systemd/](https://www.freedesktop.org/wiki/Software/systemd/)

#### Tags:
 - Init, Service Management, System

#### Properties
- [Documentation](https://www.freedesktop.org/software/systemd/man/)
- [Reference](https://www.freedesktop.org/wiki/Software/systemd/dbus/)
- [Source Code](https://github.com/systemd/systemd)

## Common Properties
- [Kernel.org](https://www.kernel.org/)
- [Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)
- [Linux man-pages](https://man7.org/linux/man-pages/)

## Maintainers
**FN:** Kin Lane
**Email:** kin@apievangelist.com
