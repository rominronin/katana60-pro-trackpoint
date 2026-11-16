# Katana60 Pro Trackpoint

KiCad project for the Katana60 Pro with Trackpoint. A recent revision of the original Katana60, this one adds an often requested trackpoint to the board, and steps away from some of the original design goals.

The trackpoint is optional and requires soldering. Trackpoint support has been developed with a specific make and model in mind: Sprintek SK8707-01-005/008. Some enterprising maker could no doubt make it work with an alternative, salvaged trackpoint unit, but I can offer no support for such endeavours.

* Hot-swap MX sockets
* USB-C
* ATmega32U4
* Sprintek SK8707 trackpoint (PS/2)
* Split or 7u spacebar

Looking for the version without a trackpoint? That's the [Katana60 Pro](https://github.com/rominronin/katana60-pro).

This project started life as the `sprintek` branch of the Katana60 Pro repository, so the history before March 2024 is shared with it.

## Getting the files

The footprint libraries are git submodules, so clone with:

    git clone --recurse-submodules https://github.com/rominronin/katana60-pro-trackpoint.git

## License

MIT, see [LICENSE](LICENSE).
