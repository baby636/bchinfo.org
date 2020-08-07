---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

id: bitcoincom
title: "Bitcoin.com Wallet"
titleshort: "Bitcoin.com"
compat: "mobile desktop android ios windows mac linux"
level: 3
platform:
  - mobile:
    name: mobile
    default: &DEFAULT
      text: "walletbitcoincom"
      link: "https://bitcoin.com/wallet"
      source: "https://github.com/Bitcoin-Com/Wallet"
      screenshot: "bitcoincomwallet.png"
      check:
        control: "checkgoodcontrolfull"
        validation: "checkfailvalidationcentralized"
        transparency: "checkpasstransparencyopensource"
        environment: "checkpassenvironmentmobile"
        privacy: "checkpassprivacybasic"
        fees: "checkpassfeecontroldynamic"
        slp: "checkpassslptokens"
      privacycheck:
        privacyaddressreuse: "checkpassprivacyaddressrotation"
        privacydisclosure: "checkfailprivacydisclosurecentralized"
        privacynetwork: "checkfailprivacynetworknosupporttor"
    os:
      - name: android
        <<: *DEFAULT
      - name: ios
        <<: *DEFAULT
  - desktop:
    name: desktop
    default: &DEFAULT
      text: "walletbitcoincom"
      link: "https://bitcoin.com/wallet"
      source: "https://github.com/Bitcoin-Com/Wallet"
      screenshot: "bitcoincomwallet.png"
      check:
        control: "checkgoodcontrolfull"
        validation: "checkfailvalidationcentralized"
        transparency: "checkpasstransparencyopensource"
        environment: "checkfailenvironmentdesktop"
        privacy: "checkpassprivacybasic"
        fees: "checkpassfeecontroldynamic"
        slp: "checkfailslptokens"
      privacycheck:
        privacyaddressreuse: "checkpassprivacyaddressrotation"
        privacydisclosure: "checkfailprivacydisclosurecentralized"
        privacynetwork: "checkfailprivacynetworknosupporttor"
    os:
      - name: windows
        <<: *DEFAULT
      - name: mac
        <<: *DEFAULT
      - name: linux
        <<: *DEFAULT
---
