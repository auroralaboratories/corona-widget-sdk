# Sprinkles Widget SDK

The Sprinkles Widget SDK is a collection of common and useful libraries and assets that can be used to build widgets.  Clone this repository to your system and point the _sprinkles-api_ `--static-root` path at the checked-out path (_sprinkles-api_ uses a default path of `/usr/share/sprinkles/assets`).  This will make the contents of this repository available to your widgets through the API endpoint `/static`.

## Quickstart

```
sudo mkdir -p /usr/share/sprinkles
sudo git clone https://github.com/ghetzel/sprinkles-widgets-common.git /usr/share/sprinkles/assets
```
