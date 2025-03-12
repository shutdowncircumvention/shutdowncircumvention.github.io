<!-- material/tags { scope: true } -->

---

title: Tella
tags:

- macOS
- Linux
- Windows

---

# Tella

tags as icon:

- iOS
- Android

Technical level requirment: (shown as icon/ tags):

- low

second line of tags (kind of category of the tools??):

- encryption of news material
- information provider tool

## Short Intro

Tella is an application that functions as a File Manager, Camera, and Recorder. It automatically encrypts photos, videos, and audio recordings when they are captured. Users can also import existing files into Tella for encryption.

The app includes features such as the ability to change its icon, and files stored within Tella are not accessible through the phone’s default gallery or file manager. 

This helps protect sensitive content, such as documentation of human rights violations or news material, in situations where devices may be searched. During internet shutdowns, Tella can be used to archive files securely until connectivity is restored and the content can be shared.

## symptoms

??? [Full shutdown](/internet-shutdown-toolkit/shutdown-framework/docs/shutdown-types.md#Types-of-Shutdown ){ .pg-red }

??? note "no DNS but XYZ"
describe
<details>
<summary>how to diagnose</summary>

</details>
??? note "home wifi works XYZ"
    Description or details for **symptoms 2**.

## Feature

- [X] [Background encryption]("Encryption converts information into a coded format that only someone with the correct key can decode, ensuring security even if the data is intercepted. Unlike a password, which controls access, encryption protects the actual content, making it unreadable without the key, even if access is gained.")
- [X] Hide App icon on home screen
- [ ] Metadata Removal
- [X] [Metadata](#){ title="tooltip of why metadata is important" } Removal

  - [ ] On Settings > Security users have the option to Preserve or delete the file's metadata when importing Photos and Videos to Tella. EXIF metadata of files migth include data about when the file was created, camera settings or location of the device.
- [ ] Camera silent mode

  * [X] in Android
  * [ ] in iOS
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
- [ ]## Something like is it tested?
- [X] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt

  * [X] In hac habitasse platea dictumst
  * [X] In scelerisque nibh non dolor mollis congue sed et metus
  * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque

!!! circle-info "Who makes Tella?"

    Tella is developed and maintained by Horizontal, a human rights non-profit. In addition to developing Tella, Horizontal develops other privacy and security tools, and trains activists, journalists, and human rights defenders in digital security.

## <span style="color:red">I think we can have some icons of "non-profit" and "for profit"/ "open-source", anything related to how 'ethical' the tool is, with inapplicable ones greyed out, for each tool </span>.

Who makes Tella?
Tella is developed and maintained by Horizontal, a human rights non-profit. In addition to developing Tella, Horizontal develops other privacy and security tools, and trains activists, journalists, and human rights defenders in digital security.

!!! warning "related risks"

    If the user loses their lock, it is not possible to regain access to Tella and the files stored inside the app. The user has to uninstall and reinstall Tella, and all files will be lost. 

## Security and testing (about security audits and any usabilty testing)

Tella regularly ask independent security firms to audit our code to ensure it is robust and secure.

| Date | Audited by | Platforms audited    | Link      |
| -----|----------|----|-----------|
| May 2024 | Subgraph Technologies, Inc. |  Android, iOS, Tella Web |[View report](</assets/2024.05.18 - Subgraph - Updated Report.pdf>)|
| May 2023 | Subgraph Technologies, Inc. | Android, iOS, Tella Web |[View report](</assets/2023.05 - Tella security audit - Final report.pdf>)|

# How to USE

=== "MacOS"
[Tutorial on Tella official site to download and install](https://tella-app.org/get-started-android#download-and-install-tella)
[Video Tutorial](https://tella-app.org/get-started-ios#download-and-install-tella)

=== "Android"
[Tutorial on Tella official site to download and install](https://tella-app.org/get-started-ios#download-and-install-tella)
[Video Tutorial](https://tella-app.org/get-started-ios#download-and-install-tella)


# How to Install

=== "MacOS"
### How to Install on MacOS
1. Open the terminal.
2. Run the following command:
```bash brew install tool-name ```
3. Verify installation:
```bash tool-name --version ```

=== "Android"
