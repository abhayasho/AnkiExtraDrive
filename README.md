# Anki BLE Bridge

This is a lightweight Node.js backend that connects to Anki Overdrive cars via Bluetooth Low Energy (BLE), enabling remote control and real-time telemetry through WebSocket. Built from the open-source [Anki-Partydrive](https://github.com/MasterAirscrachDev/Anki-Partydrive) project, this bridge is designed for integration with C# servers, Unity games, or custom clients.

## Features

- ✅ Connects to Anki Overdrive cars via BLE
- ✅ WebSocket server for remote control
- ✅ Supports speed and lane-change commands
- ✅ Broadcasts car telemetry (position, track piece)
- ✅ Easy integration with Unity or C# clients

## Requirements

- Node.js 14+
- Bluetooth Low Energy (BLE) support on host
- Anki Overdrive car powered on (not paired via OS)

## Install

```bash
git clone https://github.com/YOUR_USERNAME/anki-ble-bridge.git
cd anki-ble-bridge
npm install
