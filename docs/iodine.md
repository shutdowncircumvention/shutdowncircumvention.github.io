---
tags:
  OS:
    - macOS
    - Linux
    - Windows
  Use Cases:
    - gain internet access
    - DNS
    - Restricted Network
---

# Iodine

## Short Intro
Iodine is a lightweight, open-source DNS tunneling tool that uses DNS queries to transmit data between devices. It works by exploiting the fact that DNS queries can be used to send small amounts of data over the internet without being detected.

## Symptoms
DNS lookups are possible via `dig` or `nslookup`, but other types of network protocols are restricted.

??? info "How to Diagnose"
    Describe the symptoms and diagnostic methods.

??? note "Home WiFi Works XYZ"
    Description or details for **symptoms 2**.

## Free Features

!!! warning "Related Risks"
    Something like "Is VPN legal in your country?"

# How to Use
Here's a simplified overview of how Iodine works:

1. The user creates an account on an Iodine server.
2. The user generates a public key and shares it with the server.
3. The user uses their device to send DNS queries to the Iodine server, which are then transmitted as encrypted data packets.
4. The Iodine server receives these packets and forwards them back to the original sender.

## Security Considerations
While Iodine provides a level of security, it's essential to consider the following:

- **Encryption**: Although Iodine encrypts data packets, it's not ideal for sensitive or high-priority information.
- **Server Compromise**: If an attacker gains access to the Iodine server, they can potentially intercept and decode encrypted data packets.

# How to Install

=== "macOS"
    ### How to Install on macOS
    1. Open the terminal.
    2. Run the following command:
       ```bash
       brew install iodine
       ```
    3. Verify installation:
       ```bash
       iodine --version
       ```

=== "Linux"
    ### How to Install on Linux
    1. Open your terminal.
    2. Search for **iodine**.
    3. Tap **Install**.

=== "Android"
    ### How to Install on Android
    1. Open the Google Play Store.
    2. Search for **Iodine**.
    3. Tap **Install**.
