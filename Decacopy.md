# Decacopy

**Threat Type:** PUA, Proxyware


**Damage Potential:** 20% **(LOW)**

**Distribution Potential:** 40% **(MEDIUM)**

**Slowdown Potential:** 40% **(MEDIUM)**

## Short Bio
Decacopy is a potentially unwanted application that behaves as proxyware.

## Technical Details
**File Name:** decacopy-1.2.5.2.exe

**File Size:** 3.69 MB

**MD5 Hash:** aae68e4b8614540ef68134fca3532bf1

**SHA256 Hash:** e85c9eb65c1a2eaa03c64d4a7b30c2b245d42b8c34689af0f90c8fd7068ecde0

**Initial Discovery Date:** Feb 3, 2024

**Affected Operating Systems:** Windows

**Associated Domains:** [www.decacopy.com](https://www.decacopy.com/)

## Behavior Analysis
Walliant is advertised as a lightweight clipboard tool.

It gains persistence on infected systems by adding itself to the start-up programs, creating multiple registry entries and keys, and dropping multiple files in system directories.

It contains the GlobalHop SDK, which creates exit nodes in the infected device; These exit nodes are then sold by GlobalHop Ltd. to companies which provide proxy services to their clients, essentially turning infected machines into exit nodes for proxy services.

Decacopy is usually downloaded by users themselves or bundled along with other programs. 

### [Download Sample](https://mega.nz/file/JXciQAxC#enrxeH9nq5eiMkfs0oxwE91qtVARf6s7Cy5aHD3WsPA)
