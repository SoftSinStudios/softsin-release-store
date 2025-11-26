# SoftSin Studios — Official Release Store

This repository hosts the **official, cryptographically signed release builds** of the SoftSin Composer Node Suite for ComfyUI.  
All downloadable files in this repository can be independently verified using the SoftSin Studios release-signing key.

The Composer Node Suite serves as the core bridge between human-driven procedural prompting and SoftSin’s broader creative ecosystem.

---

## 🚀 Composer Node Suite
The SoftSin Composer Node Suite is a modular, procedural prompt-building system for **ComfyUI**.  
It enables structured character creation, environments, poses, and scene logic through reusable JSON-driven systems.

**Download the latest signed release:**  
Available in the `composer` directory of this repository.

Every release includes:
- softsin-composer-nodes-x.x.x.zip  
- softsin-composer-nodes-x.x.x.zip.asc (GPG signature)

---

## 🔐 Authenticity & Verification

SoftSin Studios signs every release with our official GPG key.

### Official SoftSin Studios Release Key Fingerprint
4BF1 2AEA 7E09 E837 11F7 0721 4F53 240E 4DA4 BD75

### Public Key
The public key used to verify all releases is included in this repository as:

PUBLIC-KEY.asc

---

## ✔️ How to Verify a Release

1. Import the SoftSin public key:

   gpg --import PUBLIC-KEY.asc

2. Verify the key fingerprint:

   gpg --fingerprint "SoftSin Studios Release"

   Confirm it matches:  
   4BF1 2AEA 7E09 E837 11F7 0721 4F53 240E 4DA4 BD75

3. Verify the downloaded release:

   gpg --verify softsin-composer-nodes-x.x.x.zip.asc softsin-composer-nodes-x.x.x.zip

If GPG reports “Good signature”, the release is authentic and unmodified.

---

## 🌐 SoftSin Ecosystem
For documentation, online tools, demonstrations, and updates, visit:

- Website: https://www.softsinstudios.com  
- Facebook: https://www.facebook.com/softsinstudios  
- YouTube & Instagram: linked on the website

SoftSin Studios builds modular creative tools for the new creative age — ethical, structured, and built for real control.

---

## 📄 About This Repository
This repository serves as the official distribution channel for:
- Current Composer Node Suite release  
- Previous version (for rapid rollback)  
- Corresponding signed .asc files  
- Public authenticity metadata

All other SoftSin tools and web applications are distributed through the website.

---

© SoftSin Studios. All rights reserved.
