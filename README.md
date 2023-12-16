This is a trivial fork of kvmd, where functionality of GPIO 2,3,4,5 <-> 18,19,20,21 are swapped.

Now `GP2,3,4,5` is used for SPI communication, whereas PS/2 configurations are controlled via `GP18,19,20,21`.

This allows easier wiring on small form factored Pico boards (like Waveshare's mini RP2040 board) where GP16-25 are not exported via through holes.


Original README below
---

# KVMD
[![CI](https://github.com/pikvm/kvmd/workflows/CI/badge.svg)](https://github.com/pikvm/kvmd/actions?query=workflow%3ACI)
[![Discord](https://img.shields.io/discord/580094191938437144?logo=discord)](https://discord.gg/bpmXfz5)

This repository contains the configuration and code of KVMD, the main PiKVM daemon.
If your request does not relate directly to this codebase, please send it to issues of the [PiKVM](https://github.com/pikvm/pikvm/issues) repository.
