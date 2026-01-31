# Evil Twin Attack (Wi-Fi Fake Access Point)

An Evil Twin attack is when an attacker creates a fake Wi-Fi access point
that mimics a legitimate network. The goal is to trick users into connecting
to the fake network, which allows the attacker to intercept traffic
or capture sensitive information.

This attack is commonly used in public places
where users tend to connect to open or familiar networks.

## Attack Overview

The attacker creates a fake access point with the same name (SSID)
as the target network. Once a user connects, the attacker can:

- Intercept network traffic
- Perform Man-in-the-Middle (MITM) attacks
- Capture credentials or sensitive data

## High-Level Steps

1. Create a fake access point with the same SSID as the target network
2. Deauthenticate connected clients from the real network
3. Wait for clients to connect to the fake network
4. Monitor and capture traffic

## Why This Attack Works

Users often connect to networks by name only,
and they may not verify the authenticity of the access point.
If the fake AP has a stronger signal or the same SSID
users may connect automatically.
