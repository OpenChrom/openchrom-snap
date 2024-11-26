# OpenChrom Snap Package

## Install [![openchrom](https://snapcraft.io/openchrom/badge.svg)](https://snapcraft.io/openchrom)

    sudo snap install openchrom

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))


To store [Lablicate account](https://account.lablicate.com/) in the system keyring run

    snap connect openchrom:password-manager-service

## Development

    snapcraft
    sudo snap install openchrom*.snap --dangerous
