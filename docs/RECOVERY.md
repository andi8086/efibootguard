# Recovery Mode #

If more than the expected number of environments is detected during boot, the
system stops booting. This can be a problem if the user wants to boot the
system with a memory stick to update a broken installation.

In order to allow external boot devices with other environment configurations,
the Recovery Mode was introduced. If any environment is found on the boot
device, the boot loader will only use environments from this device.
