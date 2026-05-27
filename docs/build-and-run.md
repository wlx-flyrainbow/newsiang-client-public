# Build and Run

This public repository contains the AGPL-covered corresponding source for the
NewSiang desktop client.

## Requirements

- Node.js v20
- npm

## Install

```bash
npm install
npm run prepublish
```

If the micro:bit download is blocked in your network, download
`scratch-microbit.hex.zip` separately and run:

```bash
SCRATCH_MICROBIT_HEX_ZIP=/path/to/scratch-microbit.hex.zip npm run prepublish
```

## Build the web client

```bash
npm run build
```

## Run the web client locally

```bash
npm start
```

## Run the desktop shell

```bash
npm run electron-dev
```

## Auth API

The public client expects an auth and entitlement API. Production service
implementation, user data, payment operations, and deployment details are not
included in this public source export. See `docs/public-api.md` for the
client-facing contract.

## Release version

Package version: 1.0.0
