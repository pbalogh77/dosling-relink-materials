# Dosling relink materials

Versioned corresponding LGPL library sources and application relink objects for
Dosling. This repository does **not** contain the first-party application source
and does not change the private application's repository visibility.

## iOS 1.0, build 312

[Download the corresponding materials](https://github.com/pbalogh77/dosling-relink-materials/releases/download/ios-1.0-312/dosling-ios-1.0-312-lgpl-relink.tar.gz)

SHA-256: `b97654f38d7b68a39ff32bd6165e41ac11d36d18ee947a5a82ca106ed70a5789`

The download includes the matching unencrypted application, 55 application
objects, a portable relinker, full modified Nuked OPL3 and HQx sources, and the
Dosling scaler runtime/model sources with their notices. The app includes only
the four cleared starter games, not users' imported collections or saves.
No Apple signing keys, provisioning profiles, account tokens or Apple SDK are
included. Obtain your own Apple SDK and lawful signing/provisioning identity.

Follow the included README and app's `Licenses/ios-library-rebuild.txt`.
The relinker reconstructs an **unsigned, separate copy** from the supplied
objects. Rebuild modified libraries and sign/install that copy using your own
identity. These tools do not decrypt a Store executable or change device security.
The original installed app and its data do not need to be removed.

## Permissions and scope

Covered library sources/binaries remain available under their respective
LGPL-2.1-or-later terms; preserve their copyright, licence and modification notices.
Application objects and supplied scripts may be used to reconstruct/relink the
application with modified covered libraries for your own use. Reverse engineering
for debugging those modifications is permitted. This is not a general grant to
redistribute the proprietary first-party app, other people's games or Apple's SDK.
Full component notices and library source licences are included in each version.

Public availability of this material is not Apple approval, GOG authorization or
an assertion that every third-party service has approved Dosling.

## Credits and development

Nuked OPL3: Nuke.YKT and contributors. HQx: Maxim Stepin and Cameron Zemek.
[Dosling scaler](https://github.com/pbalogh77/dosling-scaler) builds on credited
HQx work; the complete corresponding source/model is also included in this kit.
Dosling and these build/relink tools were developed with substantial AI assistance.
See each package's exact source pins and notices rather than assuming all files
have one licence.

Support and material requests: [petya@baloghpetya.com](mailto:petya@baloghpetya.com).
Retain the materials for the specific build you modify; later versions may differ.
