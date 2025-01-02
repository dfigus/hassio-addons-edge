# EDGE Home Assistant Add-ons by Daniel Figus

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)


## WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of my add-ons:

<https://github.com/dfigus/hassio-addons>

## Installation

Adding this add-ons repository to your Home Assistant instance is pretty easy. In
 the Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/dfigus/hassio-addons-edge
```

[![Opens your Home Assistant instance and show the add add-on repository dialog with the repository URL pre-filled](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)][my-ha-add-repo]

## Add-ons provided by this repository

### &#10003; [Solarflow Control][addon-solarflow-control]

![Latest Version][solarflow-control-version-shield]
![Supports armhf Architecture][solarflow-control-armhf-shield]
![Supports armv7 Architecture][solarflow-control-armv7-shield]
![Supports aarch64 Architecture][solarflow-control-aarch64-shield]
![Supports amd64 Architecture][solarflow-control-amd64-shield]
![Supports i386 Architecture][solarflow-control-i386-shield]

Solarflow Control

[:books: Solarflow Control add-on documentation][addon-doc-solarflow-control]

### &#10003; [TVHeadend][addon-tvheadend]

![Latest Version][tvheadend-version-shield]
![Supports armhf Architecture][tvheadend-armhf-shield]
![Supports armv7 Architecture][tvheadend-armv7-shield]
![Supports aarch64 Architecture][tvheadend-aarch64-shield]
![Supports amd64 Architecture][tvheadend-amd64-shield]
![Supports i386 Architecture][tvheadend-i386-shield]

TV streaming server and recorder

[:books: TVHeadend add-on documentation][addon-doc-tvheadend]

### &#10003; [USB-Test][addon-usb-test]

![Latest Version][usb-test-version-shield]
![Supports armhf Architecture][usb-test-armhf-shield]
![Supports armv7 Architecture][usb-test-armv7-shield]
![Supports aarch64 Architecture][usb-test-aarch64-shield]
![Supports amd64 Architecture][usb-test-amd64-shield]
![Supports i386 Architecture][usb-test-i386-shield]

USB Test

[:books: USB-Test add-on documentation][addon-doc-usb-test]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant [Community Forum][forum].
- You could also [open an issue here][issue] here on GitHub. Note, we use a
 separate GitHub repository for each add-on. Please ensure you are creating
 the issue on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Solarflow Control][solarflow-control-issue]
- [Open an issue for the add-on: TVHeadend][tvheadend-issue]
- [Open an issue for the add-on: USB-Test][usb-test-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## License

MIT License

Copyright (c) 2023-2024 Daniel Figus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-solarflow-control]: https://github.com/dfigus/addon-solarflow-control/tree/6c82a32
[addon-doc-solarflow-control]: https://github.com/dfigus/addon-solarflow-control/blob/6c82a32/README.md
[solarflow-control-issue]: https://github.com/dfigus/addon-solarflow-control/issues
[solarflow-control-version-shield]: https://img.shields.io/badge/version-6c82a32-blue.svg
[solarflow-control-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[solarflow-control-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[solarflow-control-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[solarflow-control-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[solarflow-control-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-tvheadend]: https://github.com/dfigus/addon-tvheadend/tree/5edd497
[addon-doc-tvheadend]: https://github.com/dfigus/addon-tvheadend/blob/5edd497/README.md
[tvheadend-issue]: https://github.com/dfigus/addon-tvheadend/issues
[tvheadend-version-shield]: https://img.shields.io/badge/version-5edd497-blue.svg
[tvheadend-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tvheadend-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tvheadend-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[tvheadend-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tvheadend-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-usb-test]: https://github.com/dfigus/addon-usb-test/tree/744d314
[addon-doc-usb-test]: https://github.com/dfigus/addon-usb-test/blob/744d314/README.md
[usb-test-issue]: https://github.com/dfigus/addon-usb-test/issues
[usb-test-version-shield]: https://img.shields.io/badge/version-744d314-blue.svg
[usb-test-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[usb-test-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[usb-test-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[usb-test-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[usb-test-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[dfigus]: https://github.com/dfigus
[issue]: https://github.com/dfigus/hassio-addons-edge/issues
[license-shield]: https://img.shields.io/github/license/dfigus/hassio-addons-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[my-ha-add-repo]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fdfigus%2Fhassio-addons-edge
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html