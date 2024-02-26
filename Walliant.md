# Walliant

**Threat Type:** PUA, Proxyware


**Damage Potential:** 20% **(LOW)**

**Distribution Potential:** 40% **(MEDIUM)**

**Slowdown Potential:** 40% **(MEDIUM)**

## Short Bio
Walliant is a potentially unwanted application that behaves as proxyware.

## Technical Details
**File Name:** walliant.exe

**File Size:** 4.01 MB

**MD5 Hash:** 96a2cbe809b25c20ccc7d01e0c76e10e

**SHA256 Hash:** e85c9eb65c1a2eaa03c64d4a7b30c2b245d42b8c34689af0f90c8fd7068ecde0

**Initial Discovery Date:** Feb 3, 2024

**Affected Operating Systems:** Windows

**Associated Domains:** https://www.walliant.com/, https://www.barousel.com/

## Behavior Analysis
Walliant is advertised as a dynamic wallpaper engine.

It gains persistence on infected systems by adding itself to the start-up programs, creating multiple registry entries and keys, and dropping multiple files in system directories.

It contains the GlobalHop SDK, which creates exit nodes in the infected device; These exit nodes are then sold by GlobalHop Ltd. to companies which provide proxy services to their clients, essentially turning infected machines into exit nodes for proxy services.

Walliant is also distributed under the name Barousel and is usually downloaded by users themselves or bundled along with other programs. 

### [Download Sample](https://mega.nz/file/pbcVwBoa#unu98EKnr0bTJk1kx-NojIIQZfiCEVoRcXfjPMpC6qs)
