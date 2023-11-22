# Deprecation Notice
This add-on is no longer maintained. A good alternative (which i myself am using) is [Felipecrs netdata-hass-addon](https://github.com/felipecrs/netdata-hass-addon).  
If you used the Dev version, make sure to remove the existing netdata folder inside the config folder.

## Forked from [Gamma-Software](https://github.com/Gamma-Software/netdata-homeassistant-addon)
## It appears that Gamma-Software(Valentine Rudloff) no longer maintains his Repository  
## I will TRY to keep this updated as long as my free time allows

<p align="center"><a href="https://netdata.cloud"><img src="https://user-images.githubusercontent.com/1153921/95268672-a3665100-07ec-11eb-8078-db619486d6ad.png" alt="Netdata" width="300" /></a></p>

<h3 align="center">Netdata is high-fidelity infrastructure monitoring and troubleshooting.<br />Open-source, free, preconfigured, opinionated, and always real-time.</h3>
<br />

<img src="https://user-images.githubusercontent.com/1153921/95269366-1b814680-07ee-11eb-8ff4-c1b0b8758499.png" alt="---" style="max-width: 100%;" />

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]
![Github CI][ci]

# About

Netdata's **distributed, real-time monitoring Agent** collects thousands of metrics from systems, hardware, containers,
and applications with zero configuration. It runs permanently on all your physical/virtual servers, containers, cloud
deployments, and edge/IoT devices, and is perfectly safe to install on your systems mid-incident without any
preparation.

For more information you can visit the [official website](https://netdata.cloud) or the [documentation](https://docs.netdata.cloud) or the [Github page](https://github.com/netdata/netdata/blob/master/README.md).

Netdata is licensed under the GNU General Public License v3.0 [Netdata License](https://github.com/netdata/netdata/blob/master/LICENSE)

Here is an example of a Netdata dashboard:

![netdata charts](image/screenshot.png)

# Installation

The Netdata Addon is not available in the Home Assistant default Addon. To install this Addon you'll need to:

1. Go to the *Configuration* section
2. Go to the *Addon, Backup & Supervisor* section
3. Click on the *add-on store* lower-right button
4. Click on the 3 dots icon on the top-right corner
5. Click on *Repositories*
6. Add this repository: https://github.com/cryorig/netdata-homeassistant-addon
7. Search for the "Netdata" add-on
8. Start the "Netdata" add-on
9. Check the logs of the "Netdata" add-on to see if everything went well

![netdata installation](image/installation.gif)

## Support

Got questions or Problems?  
[Open a new issue][issue]

## Contributing

This is an active open-source project. We are always open to people who want to use the code or contribute to it.

TODO: We have set up a separate document containing our [contribution guidelines](.github/CONTRIBUTING.md)  
In the mean time: [Open a new issue if you have Questions.][issue]

Thank you for being involved! :heart_eyes:

## Compatible and tested platforms

This addon is tested on the following platforms: (State from 27042023 Gamma-Software Repository)

* Raspberry Pi 4
* MacBook Pro 13' 2011
* Asus Zenbook 14'

If you tested it on your own system and it works for you, please [Open a new issue here][issue] so I can add it to the tested list.

## Authors & contributors

The original setup of this repository is by [Valentin Rudloff][valentin].
Current Maintainer of this Fork: [CryoRig]

For a full list of all authors and contributors,
check [the original contributor's page][contributors_gamma] as well as [the contributor's page of this Fork][contributors_cryorig].

## License

Copyright (c) 2021-2022 Valentin Rudloff

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


[valentin]: https://github.com/Gamma-Software
[cryorig]: https://github.com/cryorig
[contributors_gamma]: https://github.com/Gamma-Software/netdata-homeassistant-addon/graphs/contributors
[contributors_cryorig]: https://github.com/cryorig/netdata-homeassistant-addon/graphs/contributors
[issue]: https://github.com/cryorig/netdata-homeassistant-addon/issues
[contact]: cryorig@gmx.at

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

[ci]: https://github.com/cryorig/netdata-homeassistant-addon/actions/workflows/builder.yaml/badge.svg
