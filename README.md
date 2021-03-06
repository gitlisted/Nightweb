## Introduction

Nightweb is an Android app for anonymous, peer-to-peer social networking. It is written in Clojure and uses I2P and BitTorrent on the backend. Please see [the website](http://nightweb.net) for a general overview, and the [protocol page](http://nightweb.net/protocol.html) for a more in-depth explanation of how it works.

## Contents

- `android` The Android project with platform-specific code, including the UI
- `common` All cross-platform code, including the I2P project and the Nightweb backend
- `graphics` SVG files for all the image resources
- `server` The command line version that you can run on a server to help the network

## Licensing

All source files that originate from this project are dedicated to the public domain. That particularly includes the files in `android/src/clojure/net/nightweb` and `common/clojure/nightweb`, the UI code and backend code respectively. All third-party code in this project remains under their original licenses. I would love pull requests, and will assume that any Clojure contributions are also dedicated to the public domain.
