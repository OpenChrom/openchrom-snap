# OpenChrom Snap Package

## Install [![openchrom](https://snapcraft.io/openchrom/badge.svg)](https://snapcraft.io/openchrom)
A pre-built package is available from the Snap store via

    sudo snap install openchrom

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))


To store [Lablicate account](https://account.lablicate.com/) in the system keyring run

    snap connect openchrom:password-manager-service

## Development
For building a package locally run

    snapcraft
    sudo snap install openchrom*.snap --dangerous
