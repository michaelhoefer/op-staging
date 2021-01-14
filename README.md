# One Pipeline Staging App
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Config Vars
- `SFDX_BUILDPACK_DEBUG`: If true, instruct the buildpack to display debug information.

- `SFDX_DEV_HUB_AUTH_URL`: Provides the credentials for connecting to the Dev Hub. You can get this value by running `sfdx force:org:display --verbose --json` against your Dev Hub and grabbing the `sfdxAuthUrl`.

- `SFDX_CREATE_PACKAGE_VERSION=true`: Instructs the buildpack to create a new package version from the source. 

- `SFDX_PACKAGE_NAME`: Provides the full name of the package to create and install, used to derive the package id

