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

### &#10003; [TVHeadend][addon-tvheadend]

![Latest Version][tvheadend-version-shield]
![Supports armhf Architecture][tvheadend-armhf-shield]
![Supports armv7 Architecture][tvheadend-armv7-shield]
![Supports aarch64 Architecture][tvheadend-aarch64-shield]
![Supports amd64 Architecture][tvheadend-amd64-shield]
![Supports i386 Architecture][tvheadend-i386-shield]

TV streaming server and recorder.

[:books: TVHeadend add-on documentation][addon-doc-tvheadend]

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

- [Open an issue for the add-on: TVHeadend][tvheadend-issue]

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

[addon-tvheadend]: https://github.com/dfigus/addon-tvheadend/tree/2c2ab22
[addon-doc-tvheadend]: https://github.com/dfigus/addon-tvheadend/blob/2c2ab22/README.md
[tvheadend-issue]: https://github.com/dfigus/addon-tvheadend/issues
[tvheadend-version-shield]: https://img.shields.io/badge/version-2c2ab22-blue.svg
[tvheadend-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tvheadend-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tvheadend-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[tvheadend-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tvheadend-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[dfigus]: https://github.com/dfigus
[issue]: https://github.com/dfigus/hassio-addons-edge/issues
[license-shield]: https://img.shields.io/github/license/dfigus/hassio-addons-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[my-ha-add-repo]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fdfigus%2Fhassio-addons
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html