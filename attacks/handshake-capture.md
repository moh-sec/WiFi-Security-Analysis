# WPA/WPA2 Handshake Capture

Capturing the WPA/WPA2 4-way handshake is one of the most
common techniques used during Wi-Fi penetration testing.

This method does not immediately reveal the Wi-Fi password,
but it allows attackers to perform offline password attacks
at a later stage.

## Attack Overview

The handshake is exchanged when a client connects
to a Wi-Fi network. By capturing this process, it is possible
to analyze the authentication mechanism used by the network.

## High-Level Steps

1. Enable monitor mode on the wireless adapter
2. Identify the target wireless network
3. Monitor and capture wireless traffic
4. Force a connected client to reconnect
5. Capture the WPA/WPA2 handshake

## Why This Attack Is Effective

If the network password is weak or commonly used,
it can potentially be cracked offline once the handshake
is successfully captured.
