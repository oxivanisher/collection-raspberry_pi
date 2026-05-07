## 2026-05-07
* Autodetect /boot mount and so no longer require the raspberry_pi_boot_dev var

## 2026-04-01 (2)
* Remove redundant become_user: root in all roles

## 2026-04-01
* wifi: add no_log to nmcli PSK task, use systemd_service module
* rpi_swap: use systemd_service module instead of generic service module
* octoprint: use systemd_service module instead of generic service module
* james_on_rpi: security fixes, remove redundant become_user, use systemd_service module
* rpi_configure_radio: use systemd_service module, fix daemon_reload being silently ignored

## 2026-03-27
* Bump for optimized loop output

## 2026-01-15
* Bump for rpi_configure_radio bugfix

## 2026-01-10
* Bump for rpi_configure_radio now also unblocking soft blocked devices with rfkill

## 2025-11-28
* Bump for wifi role for online detection fix

## 2025-11-23
* Ansible 2.5 porting in all roles

## 2025-10-16
* Bump for james_on_rpi role to support mqtt setup

## 2025-10-07
* Bump for flightaware to handle not yet working trixie repository

## 2025-10.05
* Lookup user homes instead of guesstimating
* Install trixie ansible dep for pip

## 2025-10-04
* Ensure switch variable is bool
* Add rpi_avahi role

## 2025-10-03
* Improve trixie support for james

## 2025-09-26
* Bump for hifiberry role to support RPi4

## 2025-09-07
* Bump for james_on_rpi update (use system user) and add more users and changes for cli

## 2025-05-29
* Bump for james_on_rpi update

## 2025-05-21
* Bump for timelapse on calendar bugfix

## 2025-03-13
* Bump for rpi_wifi_usb fix (bootdev var default was wrong)

## 2025-03-10
* Bump for timelapse role (upload every 30 minutes)

## 2025-02-23
* Bump for changed james_on_rpi role

## 2025-02-22
* Bump for changed james_on_rpi role

## 2025-02-14
* Bump for fixed retropi roms role

## 2025-02-08
* Bump for all roles to remove unused tests directory to make linter happy
* Everything is now correctly linted

## 2024-10-02
* Bump for timelapse role (just cleaner ansible)

## 2024-09-29
* Bump for tensorflow role (welcome to 2024)

## 2024-09-27
* Bump for octoprint role (no longer create a oxiscript backup job!)

## 2024-09-08
* Bump for fixed wifi role

## 2024-09-06
* Update timelapse role to use rpicam-apps-lite instead of libcamera-apps-lite

## 2024-08-24
* Update james2 to fix systemd unit file permissions

## 2024-07-11
* Update rpi_tensorflowlite to fix tensorflow repo owner and update readme

## 2024-06-28
* Adding pipeline badge
* Adding supported minimal version for linter

## 2024-05-07
  * Add ansible collection linting
