<!-- material/tags { scope: true } -->

---

title:  Save by Open Archive
tags:

- macOS
- Linux
- Windows

---

# Save

tags (as icon):

- Windows
- Mac OS 
- Linux

Technical level requirment: (shown as icon/ tags):

- low

second line of tags (kind of category of the tools??):

- Secure Archiving
- Encryption 
- Media Authentication
- open-source

## Short Intro

Save, developed by OpenArchive, is a privacy-focused mobile application that empowers users to securely verify, share, and archive their mobile media. The app ensures media integrity through SHA-256 hashing, secures uploads with TLS and Tor, and supports metadata and licensing options for proper attribution. Whether a journalist, activist, or content creator, Save is designed to protect digital media while ensuring long-term accessibility and authenticity.

## symptoms

??? [Upload fails due to network restrictions or insecure connection](/internet-shutdown-toolkit/shutdown-framework/docs/shutdown-types.md#Types-of-Shutdown ){ .pg-red }

## Feature

- [X] [Background encryption]("Encryption converts information into a coded format that only someone with the correct key can decode, ensuring security even if the data is intercepted. Unlike a password, which controls access, encryption protects the actual content, making it unreadable without the key, even if access is gained.")
- [X] Media Authentication: Verifies the integrity of your media using [SHA-256 hashing](#){ title="SHA-256 is a cryptographic hash function that converts input data into a fixed 256-bit (64-character) hash. It's deterministic, secure, and widely used for data integrity, password hashing, and blockchain. It ensures pre-image resistance (hard to reverse), collision resistance (unique outputs), and fast computation." } 
- [X] Secure Uploads: Ensures safe media transfer via [TLS](#){ title="TLS (Transport Layer Security) is a cryptographic protocol that secures communication over a network, such as the internet. It ensures data confidentiality, integrity, and authentication by encrypting connections between clients and servers. TLS is commonly used for secure web browsing (e.g., HTTPS).} or Tor.
- [X] Metadata and Licensing: Add Creative Commons licenses and metadata for proper attribution.
- [X] Flexible Archiving: Choose between public archives, private repositories, or personal storage.
- [X] Open Source: Transparent code available for review and contribution.
- [X] User-Friendly Interface: Intuitive design for both beginners and advanced users.
- [ ] Metadata removal 

!!! circle-info "Who makes Save?"
     OpenArchive is a nonprofit committed to helping people easily preserve and organize their media. We develop privacy-first, decentralized, easy-to-use archiving tools and resources.

!!! warning "related risks"

    Ensure the use of Save complies with local laws and regulations. 
    For example, using Tor or archiving sensitive data might be restricted in certain regions.

!!! warning "Known Issues"
    - Requires a stable internet connection for uploads and initial setup.
    - May experience slow uploads over the Tor network depending on regional restrictions.

## Security and testing (about security audits and any usabilty testing)

Save  completed a third-party security audit conducted through support from the Open Tech Fund's (OTF) Red Team Lab.

| Date | Audited by | Platforms audited    | Link      |
| -----|----------|----|-----------|
| July 2023 |  Trail of Bits. |  Android, iOS |[View report](<https://www.open-archive.org/news/save-security-audit>)|

# How to Use

=== "Android"
1. Open the Google Play Store.
2. Search for Save (by OpenArchive).
3. Tap Install.
4. Launch the app and follow on-screen instructions to verify, license, and archive your media.
5. Open the app and capture or upload existing media.
6. Use the built-in verification tool to authenticate files with SHA-256 hashes.
7. Add metadata and licensing information as needed.
8. Choose a destination to securely archive your media.