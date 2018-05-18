# tablet-mousepad-disabler
Script is intended to disable the mousepad when in tablet mode for Lenovo ThinkPad Yoga 14 but may work with other devices.

## tabletmode event
Tabletmode events will likely differ between devices. Use `acpi_listen` in terminal to determine while entering/exiting tabletmode.

## mousepad id
Similiar to the tablet event, the mousepad (touchpad) will likely be different per device. Use `xinput list` to determine proper id.
