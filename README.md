# Awesome Reticulum

This is a curated list of projects related to the Reticulum network.  
The source code of the list is hosted at [github.com/lorien/awesome-reticulum](https://github.com/lorien/awesome-reticulum)  
Also available at [awesome-reticulum.net](https://awesome-reticulum.net)

## Contents

* [Network Stack](#network-stack)
* [Application-Layer Protocols](#application-layer-protocols)
* [Node Firmware](#node-firmware)
* [Messangers and Browsers](#messangers-and-browsers)
* [Transports and Network Interfaces](#transports-and-network-interfaces)
* [Network Tools](#network-tools)
* [LXMF Bots](#lxmf-bots)
* [NomadNet Applications](#nomadnet-applications)
* [Flasher](#flasher)
* [Micron Markdown Format](#micron-markdown-format)
* [LoRa Tools](#lora-tools)
* [Custom Devices](#custom-devices)
* [Small Utilities and Code Examples](#small-utilities-and-code-examples)
* [Community Discussions](#community-discussions)

## Network Stack

| Project Name | Description |
| :--- | :--- |
| [Reticulum](https://github.com/markqvist/Reticulum) ![GitHub Repo stars](https://img.shields.io/github/stars/markqvist/Reticulum?style=social) | (Markqvist) The cryptography-based networking stack for building unstoppable networks with LoRa, Packet Radio, WiFi and everything in between. |
| [reticulum-zig](https://github.com/ion232/reticulum-zig) ![GitHub Repo stars](https://img.shields.io/github/stars/ion232/reticulum-zig?style=social) | (Ion232) An implementation of Reticulum in Zig targeting operating systems and embedded devices. |
| [microReticulum](https://github.com/attermann/microReticulum) ![GitHub Repo stars](https://img.shields.io/github/stars/attermann/microReticulum?style=social) | (Attermann) Port of Reticulum Network Stack to C++ specifically but not exclusively targeting 32-bit and better MCUs. |
| [ Reticulum-rs](https://github.com/BeechatNetworkSystemsLtd/Reticulum-rs) ![GitHub Repo stars](https://img.shields.io/github/stars/BeechatNetworkSystemsLtd/Reticulum-rs?style=social) | (BeechatNetworkSystemsLtd) Reticulum Networking Stack implementation written in Rust. |
| [Reticulum-Go](https://git.quad4.io/Networks/Reticulum-Go) | (Networks) A Go implementation of the Reticulum Network Stack. |
| [reticulum-network-stack](https://github.com/sergst83/reticulum-network-stack) ![GitHub Repo stars](https://img.shields.io/github/stars/sergst83/reticulum-network-stack?style=social) | (Sergst83) An implementation of Reticulum network stack in Java. |
| [reticulum_ex](https://codeberg.org/int32/reticulum_ex) | (Int32) An implementation of the Reticulum Network Stack in Elixir. This implementation is a work in progress and is definitely not ready for day to day use. |

## Application-Layer Protocols

| Project Name | Description |
| :--- | :--- |
| [markqvist / LXMF](https://github.com/markqvist/LXMF) ![GitHub Repo stars](https://img.shields.io/github/stars/markqvist/LXMF?style=social) | A simple and flexible messaging format and delivery protocol that allows a wide variety of implementations, while using as little bandwidth as possible. |
| [markqvist / LXST](https://github.com/markqvist/LXST) ![GitHub Repo stars](https://img.shields.io/github/stars/markqvist/LXST?style=social) | A simple and flexible real-time streaming format and delivery protocol that allows a wide variety of implementations, while using as little bandwidth as possible. |

## Node Firmware

| Project Name | Description |
| :--- | :--- |
| [RNode_Firmware_CE](https://github.com/liberatedsystems/RNode_Firmware_CE) ![GitHub Repo stars](https://img.shields.io/github/stars/liberatedsystems/RNode_Firmware_CE?style=social) | Community maintained fork of the open firmware which powers RNode. |
| [markqvist / RNode_Firmware](https://github.com/markqvist/RNode_Firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/markqvist/RNode_Firmware?style=social) | An RNode is an open, free and unrestricted digital radio transceiver. It enables anyone to send and receive any kind of data over both short and very long distances. |
| [Micro Reticulum](https://github.com/attermann/microReticulum_Firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/attermann/microReticulum_Firmware?style=social) | Integration of the microReticulum network stack to implement a completely self-contained standalone node on ESP32/NRF52 devices. |
| [DanBeard / RETCON](https://github.com/DanBeard/RETCON) ![GitHub Repo stars](https://img.shields.io/github/stars/DanBeard/RETCON?style=social) | Enables quick creation of pre-configured Raspberry Pi images that automatically form resilient mesh networks once deployed. |
| [strijar / RNS-Gate](https://github.com/strijar/RNS-Gate) ![GitHub Repo stars](https://img.shields.io/github/stars/strijar/RNS-Gate?style=social) | Standalone device for access and routing within the Reticulum Network Stack. |
| [gretel / reticulum-openwrt](https://github.com/gretel/reticulum-openwrt) ![GitHub Repo stars](https://img.shields.io/github/stars/gretel/reticulum-openwrt?style=social) | GitHub workflow for cross-compiling Reticulum Network Stack (RNS) packages for OpenWrt. |
| [RNode Halow firmware](https://github.com/I-AM-ENGINEER/RNode_Halow_Firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/I-AM-ENGINEER/RNode_Halow_Firmware?style=social) | RNode implementation based on the Taixin TXW8301, using the 802.11ah. |
| [RNodeTHV4](https://github.com/jrl290/RNodeTHV4) ![GitHub Repo stars](https://img.shields.io/github/stars/jrl290/RNodeTHV4?style=social) | Standalone Reticulum over LoRa and WiFi Node - Firmware for Heltec V4. |

## Messengers and Browsers

| Project Name | Description |
| :--- | :--- |
| [markqvist / NomadNet](https://github.com/markqvist/NomadNet) ![GitHub Repo stars](https://img.shields.io/github/stars/markqvist/NomadNet?style=social) | Off-grid, resilient mesh communication with strong encryption, forward secrecy and extreme privacy. |
| [markqvist / Sideband](https://github.com/markqvist/Sideband) ![GitHub Repo stars](https://img.shields.io/github/stars/markqvist/Sideband?style=social) | An extensible LXMF messaging and LXST telephony client, situational awareness tracker and remote control and monitoring system for Android, Linux, macOS and Windows. |
| [liamcottle / reticulum-meshchat](https://github.com/liamcottle/reticulum-meshchat) ![GitHub Repo stars](https://img.shields.io/github/stars/liamcottle/reticulum-meshchat?style=social) | A simple mesh network communications app powered by the Reticulum Network Stack. |
| [torlando-tech / columba](https://github.com/torlando-tech/columba) ![GitHub Repo stars](https://img.shields.io/github/stars/torlando-tech/columba?style=social) | A simple messaging app for the Reticulum network on Android using Bluetooth LE over Reticulum. |
| [Ren / Browser](https://git.quad4.io/Ren/Browser) | A browser for the Reticulum Network. Target platforms: Web, Linux, Windows, MacOS, Android, iOS. Built using Flet. |
| [kc1awv / lxst_phone](https://github.com/kc1awv/lxst_phone) ![GitHub Repo stars](https://img.shields.io/github/stars/kc1awv/lxst_phone?style=social) | A peer-to-peer voice calling application built on the Reticulum Network Stack. |
| [fr33n0w / rBrowser](https://github.com/fr33n0w/rBrowser) ![GitHub Repo stars](https://img.shields.io/github/stars/fr33n0w/rBrowser?style=social) | A modern, web-based UI for exploring NomadNet nodes and pages over the Reticulum network. |
| [RNS-Things / MeshChatX](https://git.quad4.io/RNS-Things/MeshChatX) | A heavily customized fork of Reticulum MeshChat; meaningful, stable and tested modifications will be submitted as a PR upstream. |
| [fr33n0w / lxmf-cli](https://github.com/fr33n0w/lxmf-cli) ![GitHub Repo stars](https://img.shields.io/github/stars/fr33n0w/lxmf-cli?style=social) | Feature-rich terminal-based LXMF messaging client for Reticulum. |

## Transports and Network Interfaces

| Project Name | Description |
| :--- | :--- |
| [LFManifesto / ReticulumHF](https://github.com/LFManifesto/ReticulumHF) ![GitHub Repo stars](https://img.shields.io/github/stars/LFManifesto/ReticulumHF?style=social) | Encrypted communication over HF radio using the Reticulum Network Stack and FreeDV digital modes. |
| [torlando-tech / ble-reticulum](https://github.com/torlando-tech/ble-reticulum) ![GitHub Repo stars](https://img.shields.io/github/stars/torlando-tech/ble-reticulum?style=social) | A Bluetooth Low Energy (BLE) interface for Reticulum Network Stack, enabling mesh networking over BLE without additional hardware on Linux devices. |
| [Reticulum-Interfaces / RNS-over-HTTP](https://git.quad4.io/Reticulum-Interfaces/RNS-over-HTTP) | A Reticulum interface that tunnels traffic over standard HTTP/S POST requests, allowing Reticulum to operate on networks where only web traffic is permitted. |
| [BeechatNetworkSystemsLtd / rns-tun-rs](https://github.com/BeechatNetworkSystemsLtd/rns-tun-rs) ![GitHub Repo stars](https://img.shields.io/github/stars/BeechatNetworkSystemsLtd/rns-tun-rs?style=social) | Reticulum TUN adapter. |
| [BeechatNetworkSystemsLtd / rns-vpn-rs](https://github.com/BeechatNetworkSystemsLtd/rns-vpn-rs) ![GitHub Repo stars](https://img.shields.io/github/stars/BeechatNetworkSystemsLtd/rns-vpn-rs?style=social) | Library and application for VPN client over Reticulum mesh network. |
| [BeechatNetworkSystemsLtd / rns-mavlink-rs](https://github.com/BeechatNetworkSystemsLtd/rns-mavlink-rs) ![GitHub Repo stars](https://img.shields.io/github/stars/BeechatNetworkSystemsLtd/rns-mavlink-rs?style=social) | Bridges a flight controller connected via serial port to a QGroundControl ground station over Reticulum mesh network. |
| [RFnexus / reticulum-over-hf](https://github.com/RFnexus/reticulum-over-hf) ![GitHub Repo stars](https://img.shields.io/github/stars/RFnexus/reticulum-over-hf?style=social) | Resources on how to configure Reticulum to work over HF radio. |
| [RFnexus / FreeDVInterface](https://github.com/RFnexus/FreeDVInterface) ![GitHub Repo stars](https://img.shields.io/github/stars/RFnexus/FreeDVInterface?style=social) | A CustomInterface for Reticulum that provides a plug and play, cross-platform sound modem interface for HF radios using the FreeDV API. Supports VOX, serial, and Hamlib PTT. |
| [R2AirVlad / Reticulum-Network-Over-Icom-D-star-Transceivers](https://github.com/R2AirVlad/Reticulum-Network-Over-Icom-D-star-Transceivers) ![GitHub Repo stars](https://img.shields.io/github/stars/R2AirVlad/Reticulum-Network-Over-Icom-D-star-Transceivers?style=social) | Custom RNS interface script enabling transmission and reception of LXMF packets through GMSK modems in Icom transceivers compatible with the D-star standard. |
| [matvik22000 / rns-over-icmp](https://github.com/matvik22000/rns-over-icmp) ![GitHub Repo stars](https://img.shields.io/github/stars/matvik22000/rns-over-icmp?style=social) | Allows using ICMP PING packets as a transport layer for Reticulum, consisting of a client and a server component. |
| [Guide: Reticulum over DNS tunnel](https://github.com/markqvist/Reticulum/discussions/1002) | Guide on how to run Reticulum over a DNS tunnel using Iodine server. |

## Network Tools

| Project Name | Description |
| :--- | :--- |
| [acehoss / rnsh](https://github.com/acehoss/rnsh) ![GitHub Repo stars](https://img.shields.io/github/stars/acehoss/rnsh?style=social) | A utility written in Python that facilitates shell sessions over Reticulum networks, providing a similar experience to SSH. |

## LXMF Bots

| Project Name | Description |
| :--- | :--- |
| [randogoth / lxmf-bot](https://codeberg.org/randogoth/lxmf-bot.git) | Python class to easily develop a simple Telethon style chatbot for the LXMF protocol. |
| [lxmfy / LXMFy](https://github.com/lxmfy/LXMFy) ![GitHub Repo stars](https://img.shields.io/github/stars/lxmfy/LXMFy?style=social) | Easily create LXMF bots for the Reticulum Network with this extensible framework. |
| [lxmfy / ollama-bot](https://github.com/lxmfy/ollama-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/lxmfy/ollama-bot?style=social) | Interact with Ollama LLMs using the LXMFy bot framework. |

## NomadNet Applications

| Project Name | Description |
| :--- | :--- |
| [RNS-Things / rns-page-node](https://git.quad4.io/RNS-Things/rns-page-node) | A simple way to serve pages and files over the Reticulum network. Drop-in replacement for NomadNet nodes that primarily serve pages and files. |
| [fr33n0w / thechatroom](https://github.com/fr33n0w/thechatroom) ![GitHub Repo stars](https://img.shields.io/github/stars/fr33n0w/thechatroom?style=social) | An IRC-style chat room built for Reticulum NomadNet, optimized for MeshChat v2.1+. |
| [gralexey / lxmf-quick-chat](https://github.com/gralexey/lxmf-quick-chat) ![GitHub Repo stars](https://img.shields.io/github/stars/gralexey/lxmf-quick-chat?style=social) | A lightweight chat script for NomadNet nodes. |
| [AutumnSpark1226 / nomadForum](https://codeberg.org/AutumnSpark1226/nomadForum) | A forum application for the NomadNetwork. |

## Flasher

| Project Name | Description |
| :--- | :--- |
| [liamcottle / rnode-flasher](https://github.com/liamcottle/rnode-flasher) ![GitHub Repo stars](https://img.shields.io/github/stars/liamcottle/rnode-flasher?style=social) | A web based firmware flasher for Reticulum / RNode_Firmware. |

## Micron Markdown Format

| Project Name | Description |
| :--- | :--- |
| [randogoth / micron-blog](https://codeberg.org/randogoth/micron-blog.git) | Pelican plug-in and theme for publishing a site in Micron markup format for NomadNet nodes. |
| [randogoth / md2txt](https://codeberg.org/randogoth/md2txt.git) | Transform Markdown into arcane text formats including NomadNet format. |
| [RFnexus / micron-parser-js](https://github.com/RFnexus/micron-parser-js) ![GitHub Repo stars](https://img.shields.io/github/stars/RFnexus/micron-parser-js?style=social) | A JavaScript parser for Micron, a lightweight, terminal-friendly markdown format used in NomadNet and MeshChat. |
| [fr33n0w / micron-composer](https://github.com/fr33n0w/micron-composer) ![GitHub Repo stars](https://img.shields.io/github/stars/fr33n0w/micron-composer?style=social) | A powerful WYSIWYG editor for creating NomadNet-ready .mu pages using the Micron markup language. |

## LoRa Tools

| Project Name | Description |
| :--- | :--- |
| [markqvist / LoRaMon](https://github.com/markqvist/LoRaMon) ![GitHub Repo stars](https://img.shields.io/github/stars/markqvist/LoRaMon?style=social) | Allows you to sniff LoRa networks with an RNode, and dump captured packets to the console or files. |
| [randogoth / lora-transmit](https://codeberg.org/randogoth/lora-transmit.git) | Simple commandline raw LoRa packet transmitter for RNode hardware. |

## Custom Devices

| Project Name | Description |
| :--- | :--- |
| [weltamdraht / ReticulumRasPiRelaySwitch](https://github.com/weltamdraht/ReticulumRasPiRelaySwitch) ![GitHub Repo stars](https://img.shields.io/github/stars/weltamdraht/ReticulumRasPiRelaySwitch?style=social) | Switches electrical devices on or off when an according command is received through Reticulum's LXMF. |

## Small Utilities and Code Examples

| Project Name | Description |
| :--- | :--- |
| [antlas0 / rns_tools](https://github.com/antlas0/rns_tools) ![GitHub Repo stars](https://img.shields.io/github/stars/antlas0/rns_tools?style=social) | A small range of RNS tools driven by curiosity about the Reticulum stack. |
| [SebastianObi / RNS-Tools](https://github.com/SebastianObi/RNS-Tools) ![GitHub Repo stars](https://img.shields.io/github/stars/SebastianObi/RNS-Tools?style=social) | Various small programs and tools which use the Reticulum Network Stack. |
| [SebastianObi / LXMF-Tools](https://github.com/SebastianObi/LXMF-Tools) ![GitHub Repo stars](https://img.shields.io/github/stars/SebastianObi/LXMF-Tools?style=social) | Various small programs and tools which use the LXMF message protocol. |
| [CyberKiska / lxmf-vanity-address-generator-py](https://github.com/CyberKiska/lxmf-vanity-address-generator-py) ![GitHub Repo stars](https://img.shields.io/github/stars/CyberKiska/lxmf-vanity-address-generator-py?style=social) | A simple CLI tool to generate LXMF vanity addresses on the Reticulum network. |
| [SebastianObi / NomadNet-Pages](https://github.com/SebastianObi/NomadNet-Pages) ![GitHub Repo stars](https://img.shields.io/github/stars/SebastianObi/NomadNet-Pages?style=social) | Various small example pages/programs for usage with the NomadNet node server or rns_server_page. |
| [Official RNS Examples](https://reticulum.network/manual/examples.html) | Examples of using RNS in the official documentation. |

## Community Discussions

| Platform | Link |
| :--- | :--- |
| Zulipchat | [reticulum.zulipchat.com](https://reticulum.zulipchat.com) |
| Matrix | [#reticulum:matrix.org](https://app.element.io/#/room/#reticulum:matrix.org) |
