# amdgpu-fancontrol

Simple bash script to control AMD Radeon graphics cards fan pwm. Adjust temp/pwm values and hysteresis/interval in the script as desired. Other adjustments, such as the correct hwmon path might be required as well.

This script was initially meant as an example. Please don't just run it naively and keep in mind that I'm not responsible for failures.

To monitor multiple cards specify a coma separated list of cards as the first argument. Example: ./amdgpu-fancontrol 0,1,2

## Packages

- Arch Linux (on AUR): https://aur.archlinux.org/packages/amdgpu-fancontrol-git/
