# homelab

Overview of my ever evolving homelab. Devices, Software, Network, and Appliances covered.  homelab adjacent gear also included. Check back as there will be frequent updates.

## core

| Device        | Operating System | Software      | GPU      | NIC(s)                  |
| --------------- | ------------------ | --------------- | ---------- | --------------------------- |
| Supermicro 1U Shallow | FreeBSD Based         | pfSense       | N/A      | 1G, 4 x 10G               |
| Supermicro 1U Deep  | PopOS           | Ollama & WebUI        | 2x P100  | 1G, 2 x 10G               |
| Supermicro 1U | Debian Based          | ProxMox       | N/A      | 1G, 2 x 10G               |
| Supermicro 1U | Debian Based          | ProxMox | N/A      | 1G, 2 x 10G               |
| 45HomeLab HL 15  | Rocky Linux      | Houston       | N/A      | 1G, 2 x 10G               |
| EliteDesk     | Windows 10       | Rufus         | N/A      | 1G, 10G (USB-C adapter) |
| Custom Build  | Ubuntu           | CUDA          | RTX 4090 | 1G 2x10G                  |
| Custom Build  | PopOS            | Ollama & WebUI| RTX 4000 ADA SFF |1G, 2 x 10G  |
| 5N            | Drobo            | BeyondRAID    | N/A      | 2 x 1G                    |

## network

| Manufacturer | Model | Ports | Ethernet | SFP+ |
| --- | --- | --- | --- | --- |
| Netgear | MS510TMX | 10 | 4x 2.5G, 4x 100M - 10G | 2 |
| Netgear | XS512EM | 10 | 10x 100M - 10G | 2 Combo |
| Netgear | XS512EM | 10 | 10x 100M - 10G | 2 Combo |
| Netgear | GS110EMX |10 | 8x 100M - 1G, 2x 10M - 10G | N/A |
| Netgear | Orbi 860 Router | 5 | 1x 10G, 1x 2.5G, 3x 10M - 1G | N/A |
| Netgear | Orbi 860 Satellite | 3 | 3x 10M - 1G | N/A |

## adjacent gear

| Device     | Operating System | Software      | GPU        | NIC(s)    |
| ------------ | ------------------ | --------------- | ------------ | ------------ |
| Tensorbook | Ubuntu 22.04     | Lambda Stack  | 3080 Max-Q | 10G, WiFi  |
| ROG STRIX  | Windows 11       | Rufus         | RTX 3070   | 2.5G, WiFi |
| X1C        | Bambu Lab        | Studio, Handy | N/A        | WiFi       |
| Philips Hue |  Bridge v2.0 | N/A | N/A | 100M, WiFi, Zigbee |



Checkout the [Wiki](https://github.com/tmpearsall/homelab/wiki)
