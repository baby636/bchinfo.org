---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

id: crescentcash
title: "Crescent Cash"
titleshort: "Crescent<br>Cash"
compat: "desktop windows mac linux mobile android"
level: 2
platform:
  - desktop:
    name: desktop
    default: &DEFAULT
      text: "walletcrescentcash"
      link: "https://crescent.cash"
      source: "https://gitlab.com/pokkst/crescent-cash-desktop"
      screenshot: "crescent.png"
      check:
        control: "checkgoodcontrolfull"
        validation: "checkpassvalidationspvservers"
        transparency: "checkpasstransparencyopensource"
        environment: "checkfailenvironmentdesktop"
        privacy: "checkpassprivacybasic"
        slp: "checkpassslptokens"
      privacycheck:
        privacyaddressreuse: "checkpassprivacyaddressrotation"
        privacydisclosure: "checkpassprivacydisclosurecentralized"
        privacynetwork: "checkpassprivacynetworksupporttorproxy"
    os:
      - name: windows
        <<: *DEFAULT
      - name: mac
        <<: *DEFAULT
      - name: linux
        <<: *DEFAULT
  - mobile:
    name: mobile
    os:
      - name: android
        text: "walletcrescentcash"
        link: "https://play.google.com/store/apps/details?id=app.crescentcash.src"
        source: "https://gitlab.com/pokkst/crescentcash"
        screenshot: "crescent.png"
        check:
          control: "checkgoodcontrolfull"
          validation: "checkpassvalidationspvp2p"
          transparency: "checkpasstransparencyopensource"
          environment: "checkpassenvironmentmobile"
          privacy: "checkpassprivacybasic"
          slp: "checkpassslptokens"
        privacycheck:
          privacyaddressreuse: "checkpassprivacyaddressrotation"
          privacydisclosure: "checkpassprivacydisclosurecentralized"
          privacynetwork: "checkpassprivacynetworksupporttorproxy"
---
