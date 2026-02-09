# AutoIt 721 Professional Builder Online
**Online Builder (Trial):**  
https://au3maker.itdev721.workers.dev


## Usage Video (YouTube)

A step-by-step usage guide is available on YouTube:

▶ **AutoIt 721 Professional Builder Online – Usage Tutorial**  
https://www.youtube.com/watch?v=kBVP7A9TWKM&feature=youtu.be

The video demonstrates the online builder workflow and basic usage scenarios.


## Introduction

**AutoIt 721 Professional Builder Online** is a build and packaging tool designed to convert **AutoIt scripts (`.au3`)** into **Windows executable files (`.exe`)**, with a strong focus on **source code protection** and **anti-reverse engineering** at build time.

The tool applies extended packing techniques combined with randomization mechanisms to increase analysis complexity, while maintaining a **valid PE structure** and stable execution on Windows systems.

---

## Packed File Example

A successfully protected `.exe` sample built using this tool is publicly available for users to:

- Download and inspect
- Analyze the protection mechanism
- Attempt reverse engineering if they have sufficient skills and tools

**Sample protected file:**

https://www.mediafire.com/file/mytqdxaa2lc3olx/CRACKER-ME_AUTOIT-PROTECTED-2026.exe/file

This sample is provided for demonstration and technical research purposes only.

---

## Key Features

- Build and package AutoIt scripts (`.au3`) into executable files (`.exe`)
- Extended packing algorithm
- Build-time randomization of signatures and internal data
- Preservation of a valid **PE structure**
- Integrated **anti-reverse engineering** mechanisms
- Reduced ability to extract or recover original AutoIt source code

---

## Anti-Reverse Engineering

The tool is designed to **increase the complexity of reverse engineering**, using techniques such as:

- Script data concealment within the executable
- Obfuscation of AutoIt-specific signatures
- Build randomization to prevent pattern-based detection
- Reduced effectiveness of common AutoIt unpacking and decompilation tools

> This project does **not claim absolute security**.  
> Its goal is to **significantly increase the time, cost, and skill level required** to reverse engineer the protected executable.

---

## Online Trial Version

An **online trial version** is provided to allow users to experience the build process and evaluate the tool.

**Online Builder (Trial):**  
https://au3maker.itdev721.workers.dev

### Trial Limitations

- **Expiration**: Generated `.exe` expires 7 days after build
- **Privacy**: Files are processed in memory and are not stored
- **Icons**: Custom `.ico` upload is disabled
- **Plugins**: External libraries are not supported
- **Resources**: No `RC_DATA` injection allowed
- **Security**:
  - Obfuscation is disabled
  - Signature randomization is disabled
- **Architecture**: 32-bit (x86) builds are not supported

The trial version is intended for evaluation purposes and does not represent the full security capabilities of the complete version.

---

## Offline Version (On Request)

An **offline version** is available for developers who require:

- Full privacy
- Local-only build environment
- Protection against source code leakage
- Commercial or internal project usage

### Offline Version Advantages

- Fully local build process
- All security features enabled
- No functional limitations
- Reasonable cost for AutoIt developers

The offline version is provided **upon request**.

---

## Project Ownership

This project is developed and owned by:

**721PC-Net Corporation**

---

## Official Channels

- **Official Facebook Fanpage:**  
  https://www.facebook.com/721PC

---

## Project Goals

- Protect AutoIt source code
- Reduce unauthorized analysis and code leakage
- Provide a stable and secure AutoIt packaging solution
