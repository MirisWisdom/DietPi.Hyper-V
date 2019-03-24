<html>
	<p align="center">
		<img src="https://user-images.githubusercontent.com/10241434/52020486-654f5f00-252c-11e9-9659-afb0b66c5931.png" alt="DietPi">
	</p>
	<p align="center">
		<b>Hyper-V images releases for DietPi!</b>
		<br><br>
		optimised • compatible • untouched
		<br><br>
		<a href="https://dietpi.com">
            DietPi Website
        </a>
		•
		<a href="https://github.com/Fourdee/DietPi.git">
            DietPi GitHub
        </a>
	</p>
	<hr>
	<p align="center">
        VHDX images for DietPi, fully compatible with Microsoft Hyper-V.
		<br><br>
		<a href="https://github.com/yumiris/DietPi.Hyper-V/releases/latest">
            Download Latest VHDX
        </a>
	</p>
    <hr>
	<p align="center">
		<img src="https://user-images.githubusercontent.com/10241434/54876749-e4d41d00-4e4f-11e9-9433-fe7dc77a1703.png" alt="Hyper-V Screenshot">
	</p>
</html>

## Introduction

DietPi is an extremely lightweight Debian-based OS. With images starting at
400MB, that's 3x lighter than "Raspbian Lite". It is highly optimized for
minimal CPU and RAM resource usage, ensuring your SBC always runs at its maximum
potential. The programs use lightweight Whiptail menus. You'll spend less time
staring at the command line, and more time enjoying DietPi.

DietPi makes self-hosting incredibly easy and straightforward, making it a
superb candidate for running as a virtualised server image in home labs. It is
available on common VM software such as VMware and VirtualBox, but it is not
(yet) available on Hyper-V.

The DietPi.Hyper-V project aims to release DietPi images that are compatible
with Hyper-V with minimal modifications. This way, Hyper-V users can experience
the true essence of DietPi: *optimised, simplified, for everyone*.

## Features

- fully compatible with Microsoft Hyper-V
- minimal modifications to the DietPi installation
- optimised file size (~200MB when compressed!)
- images are compressed, signed and released on GitHub

## Releases

| Release                                                                 | Date       | Hash                                                                       |
| ----------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------- |
| [`v6.22`](https://github.com/yumiris/DietPi.Hyper-V/releases/tag/v6.22) | 2019-03-24 | `SHA256: CD0D43D7E799387278E5865E9C9237E8CFFCBF5C418D061DBD4E67B1E437266E` |
| [`v6.20`](https://github.com/yumiris/DietPi.Hyper-V/releases/tag/v6.20) | 2019-01-31 | `SHA256: 0D0267701B1D894DB4513F4C3A6C7D04D981CC77661C413B7DAC13424A9AB783` |

## Disclaimer

This project is NOT officially supported by the DietPi team, nor is the team
affiliated with it. This is a spin-off project which aims to formally support
Hyper-V as a hypervisor for running DietPi.

Please rely on this project's issues page for errors/bugs directly related to
Hyper-V, and the official DietPi GitHub or forums for DietPi-specific issues. If
uncertain, report the issues here. Any issues that are related to DietPi itself
will be relayed to the official team.

## Attributions

- DietPi: Daniel Knight (Fourdee)
- Hyper-V: Microsoft Corporation