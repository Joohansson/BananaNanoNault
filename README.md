# BananoNanoNault

![GitHub release (latest by date)](https://img.shields.io/github/v/release/nault/nault)
[![GitHub All Releases](https://img.shields.io/github/downloads/nault/nault/total)](https://github.com/Joohansson/BananoNanoNault/releases/latest)
[![Discord](https://img.shields.io/badge/discord-join%20chat-orange.svg?logo=discord&color=7289DA)](https://discord.nanocenter.org)

BananoNanoNault was made to access Banano secured by a Ledger harware wallet for which accounts are derived from the Nano App (not Banano app). This means the bip39 derivation path used is 44/165 instead of 44/198.

More information about what that means and how to use it is explained in [this medium article](https://nanojson.medium.com/how-to-access-banano-on-a-ledger-hardware-wallet-using-the-nano-app-bf4f0686a13e).

It's a fully client-side signing wallet for sending and receiving [Banano](https://banano.cc) either directly in your browser at [joohansson.github.io/BananoNanoNault](https://joohansson.github.io/BananoNanoNault) or with the [desktop app](https://github.com/Joohansson/BananoNanoNault/releases/latest).
___

## How To Use
It comes in different flavors to suit your need.
#### Desktop App
Available for Windows/Mac/Linux - just head over to the [latest release](https://github.com/Joohansson/BananoNanoNault/releases/latest) and download the version for your OS.

If you want to verify the binary checksum there are plenty of apps to do this. One way is using a powershell or bash terminal:

* **Powershell:** `Get-FileHash -Path '.\BananoNanoNault-Setup-x.x.x-Windows.exe' -Algorithm SHA256`
* **Bash:** `openssl sha256 Nault-x.x.x-Linux.AppImage`

Then compare the output hash with the one listed in the corresponding checksums file that you download.

#### Web App
You can also use Nault from any device on the web at [joohansson.github.io/BananoNanoNault](https://joohansson.github.io/BananoNanoNault).

Both the desktop (recommended) and web version supports the Ledger Nano hardware wallet. For help using it, please refer to [this guide](https://docs.nault.cc/2020/08/04/ledger-guide.html).

A full security guide and other useful articles can be found in the [Nault Docs](https://docs.nault.cc).

## How To Help

Thanks for your interest in contributing! There are many ways to contribute to this project. [Get started here at CONTRIBUTING.md](CONTRIBUTING.md).

If you want to know how to setup the development environment head over to [DEVELOPMENT.md](DEVELOPMENT.md).

## Support

If you are looking for more interactive and quick support compared to creating a new Github issue, you will then find most of the developers in the Nault channel over at the [TNC discord server](https://discord.nanocenter.org/).

## Acknowledgements

Special thanks to the following!

- [NanoVault](https://github.com/cronoh/nanovault) - The original one
- [numtel/nano-webgl-pow](https://github.com/numtel/nano-webgl-pow) - WebGL PoW Implementation
- [jaimehgb/RaiBlocksWebAssemblyPoW](https://github.com/jaimehgb/RaiBlocksWebAssemblyPoW) - CPU PoW Implementation
- [dcposch/blakejs](https://github.com/dcposch/blakejs) - Blake2b Implementation
- [dchest/tweetnacl-js](https://github.com/dchest/tweetnacl-js) - Cryptography Implementation

## Donations

If you have found Nault useful and are feeling generous, you can donate at
`nano_3niceeeyiaa86k58zhaeygxfkuzgffjtwju9ep33z9c8qekmr3iuc95jbqc8`

Thanks a lot!
