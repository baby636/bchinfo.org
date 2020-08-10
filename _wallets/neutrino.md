---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

id: neutrino
title: "Neutrino"
titleshort: "Neutrino"
compat: "mobile android"
level: 2
platform:
  - mobile:
    name: mobile
    os:
      - name: android
        text: "walletneutrino"
        link: "https://play.google.com/store/apps/details?id=cash.bchd.android_neutrino"
        source: "https://github.com/gcash/android-neutrino"
        screenshot: "neutrinowallet.png"
        check:
          control: "checkgoodcontrolfull"
          validation: "checkpassvalidationspvp2p"
          transparency: "checkpasstransparencyopensource"
          environment: "checkpassenvironmentmobile"
          privacy: "checkpassprivacybasic"
          slp: "checkfailslptokens"
        privacycheck:
          privacyaddressreuse: "checkpassprivacyaddressrotation"
          privacydisclosure: "checkpassprivacydisclosurecentralized"
          privacynetwork: "checkpassprivacynetworksupporttorproxy"
---
