# Taskbar System

**Threat Type:** PUA, Proxyware


**Damage Potential:** 20% **(LOW)**

**Distribution Potential:** 40% **(MEDIUM)**

**Slowdown Potential:** 40% **(MEDIUM)**

## Short Bio
Taskbar System is a potentially unwanted application that behaves as proxyware.

## Technical Details
**File Name:** taskbarsystem.exe

**File Size:** 5.62 MB

**MD5 Hash:** 271c0218165e4be1872c5501d26bfbe5

**SHA256 Hash:** db19e6a6bbb3d65b550cca9367744625f8bfbfa0e51276495e2509b9f491616d

**Initial Discovery Date:** Feb 3, 2024

**Affected Operating Systems:** Windows

**Associated Domains:** [www.taskbarsystem.com](https://www.taskbarsystem.com/)

## Behavior Analysis
Taskbar System is advertised as a tool that lets you adjust and customize the Windows taskbar.

It gains persistence on infected systems by adding itself to the start-up programs, creating multiple registry entries and keys, and dropping multiple files in system directories.

It contains the GlobalHop SDK, which creates exit nodes in the infected device; These exit nodes are then sold by GlobalHop Ltd. to companies which provide proxy services to their clients, essentially turning infected machines into exit nodes for proxy services.

Taskbar System is usually downloaded by users themselves or bundled along with other programs. 

### [Download Sample](https://mega.nz/file/tO1GRb7A#bjQdBb1yIJ4A4U976r1buKBjDWsao1k2irN4JHk-Inc)
