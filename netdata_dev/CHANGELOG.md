# DEV Version
If you don't know what the difference to the non-DEV version is, don't use this...

# Changelog
All notable changes to this project will be documented in this file.

## [2.2.8-DEV5] - 2023-09-19

- Update [Netdata 1.42.4](https://github.com/netdata/netdata/releases/tag/v1.42.4)

## [2.2.8-DEV4] - 2023-09-12
  !!DEV work only with arm64 for now...!!
  fix log variable (enable/disable)
  
## [2.2.8-DEV3] - 2023-09-12
  !!DEV work only with arm64 for now...!!
  Fix ini-file download

## [2.2.8-DEV2] - 2023-09-12
  fix paths and folder creation

## [2.2.8-DEV1] - 2023-09-12
  replace sed with  [ini-file](https://github.com/bitnami/ini-file)
  use /config/netdata as prefix directories (for now prefix everything, later we will reduce this to only the necessary paths)

## [2.2.7] - 2023-09-12

- Update [Netdata 1.42.3](https://github.com/netdata/netdata/releases/tag/v1.42.3)

## [2.2.6] - 2023-09-06

- Update [Netdata 1.42.2](https://github.com/netdata/netdata/releases/tag/v1.42.2)

## [2.2.5-BETA] - 2023-07-20

- Remove NETDATA_CONFIG_PATH as it's currently not working as intended
- Claim via UI does NOT work as we have no easy way to display the random key
- Update [Netdata 1.42.1](https://github.com/netdata/netdata/releases/tag/v1.42.1)

## [2.2.4] - 2023-07-20

- Update [Netdata 1.41.0](https://github.com/netdata/netdata/releases/tag/v1.41.0)

## [2.2.3] - 2023-07-12

- Update [Netdata 1.40.1](https://github.com/netdata/netdata/releases/tag/v1.40.1)

## [2.2.2] - 2023-06-20

- Update Netdata 1.40.0

## [2.2.1] - 2023-05-09

- Update Netdata 1.39.0

## [2.2.0] - 2023-04-28

- Fixed GH CI
- Netdata 1.38.1
- Replaced Maintainer and URLs

## [2.1.1] - 2022-08-29

### Updated

- Bump version of Netdata to 1.34.1

## [2.1.0] - 2022-03-02

### Added

- Connection to cloud
- Cloud support configuration

## [2.0.0] - 2022-02-26

### Added

- docker arguments and labels

### Modified

- Readme and license
- Logo and icon
- Addon name
- Installation guide

## [1.0.0] - 2022-02-25

### Added

- Integration of Netdata
- Add little configuration
- Configuration script
- Retrieve the add-on in the Gamma Software package regitry
- Netdata Logo
- Netdata icon
- Readme
- Documentation


The format of this file is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).