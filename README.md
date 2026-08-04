# Linux/Unix System (linuxunix)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
