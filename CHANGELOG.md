# Changelog

This project follows the same versioning guidelines as [nerves_system_rpi3a](https://github.com/nerves-project/nerves_system_rpi3a).  That is, it does NOT follow semantic versioning. The version increases as follows:

1. Major version updates are breaking updates to the build infrastructure.
   These should be very rare.
2. Minor version updates are made for every major Buildroot release. This
   may also include Erlang/OTP and Linux kernel updates. These are made four
   times a year shortly after the Buildroot releases.
3. Patch version updates are made for Buildroot minor releases, Erlang/OTP
   releases, and Linux kernel updates. They're also made to fix bugs and add
   features to the build infrastructure.

## v1.0.2

## v1.0.1

Initial releaseThis is the initial release.  It is simply a fork of [nerves_system_rpi0](https://github.com/nerves-project/nerves_system_rpi0) with the addition of the FBV library for showing the splash screen.