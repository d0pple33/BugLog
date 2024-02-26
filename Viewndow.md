# Viewndow

**Threat Type:** PUA, Proxyware


**Damage Potential:** 20% **(LOW)**

**Distribution Potential:** 40% **(MEDIUM)**

**Slowdown Potential:** 40% **(MEDIUM)**

## Short Bio
Viewndow is a potentially unwanted application that behaves as proxyware.

## Technical Details
**File Name:** viewndowlp.exe

**File Size:** 3.95 MB

**MD5 Hash:** 45dc770549a636543076e997f0a30637

**SHA256 Hash:** 9e51f4f0e3b15565d5fcc874888e331f35d0948795e5c46a2ef74bfb3ff9c946

**Initial Discovery Date:** Feb 3, 2024

**Affected Operating Systems:** Windows

**Associated Domains:** https://www.viewndow.com/, https://www.pinaview.com/

## Behavior Analysis
Viewndow is advertised as a tool that lets you pin desired windows.

It gains persistence on infected systems by adding itself to the start-up programs, creating multiple registry entries and keys, and dropping multiple files in system directories.

It contains the GlobalHop SDK, which creates exit nodes in the infected device; These exit nodes are then sold by GlobalHop Ltd. to companies which provide proxy services to their clients, essentially turning infected machines into exit nodes for proxy services.

Viewndow is also distributed under the name Pinaview and is usually downloaded by users themselves or bundled along with other programs. 

### [Download Sample](https://mega.nz/file/sTkwFK7R#PpNzt02UbSSuY8Z7OLgLiK0CLCLe3ZwWN_TELba_mA0)
