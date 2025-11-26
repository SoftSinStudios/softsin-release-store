\# Security Policy — SoftSin Studios



SoftSin Studios distributes all official release builds using \*\*cryptographic signing\*\* to ensure authenticity, integrity, and user safety.



Every downloadable release provided by SoftSin Studios can be independently verified using our public GPG key and the fingerprint shown below. If a file does not verify, \*\*do not trust it\*\*.



---



\## 🔐 Official Release Signing Key



\### SoftSin Studios Release Key Fingerprint

4BF1 2AEA 7E09 E837 11F7 0721 4F53 240E 4DA4 BD75



This fingerprint uniquely identifies the SoftSin Studios signing key used to sign all official releases.



\### Public Key File

The public key is included in this repository as:



PUBLIC-KEY.asc



You may import it into your keyring to validate any SoftSin release.



---



\## ✔️ Verifying a SoftSin Release



To ensure a release is authentic and has not been tampered with:



1\. Import the public key:



&nbsp;  gpg --import PUBLIC-KEY.asc



2\. Verify the fingerprint:



&nbsp;  gpg --fingerprint "SoftSin Studios Release"



&nbsp;  Ensure the fingerprint shown by GPG matches exactly:

&nbsp;  4BF1 2AEA 7E09 E837 11F7 0721 4F53 240E 4DA4 BD75



3\. Verify the release signature:



&nbsp;  gpg --verify <filename>.zip.asc <filename>.zip



A valid SoftSin release will display:



Good signature from "SoftSin Studios Release ..."



If verification fails, the file may be corrupted, tampered with, or not an official release.



---



\## 🛡️ Reporting Security Issues



If you discover a vulnerability, compromised distribution file, or suspicious activity involving a SoftSin release:



Contact:

davidpolensky.com



Please include:

\- The affected file or version

\- Verification results

\- Any reproduction steps or concerns



Do \*\*not\*\* publicly disclose security issues until we have confirmed and mitigated them.



---



\## 📦 Scope of This Policy



This security policy applies to:

\- SoftSin Composer Node Suite (public release)

\- All signed releases in this repository

\- Any future downloadable products distributed by SoftSin Studios



This policy does not apply to:

\- Third-party modifications

\- Re-uploads by users

\- Unsigned or unofficial builds

\- Old versions removed from distribution



Only files accompanied by a valid SoftSin .asc signature are considered official.



---



\## 🔄 Key Rotation



If the signing key is ever rotated, expired, or replaced, a new fingerprint will be published on:

\- This repository

\- The official SoftSin Studios website

\- All official communication channels



Old keys will be revoked and marked accordingly.



---



© SoftSin Studios. All rights reserved.



