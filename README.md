# db820c-debian-4.14-camera-enable-both-CSI-interfaces
added support for both CSIs to work at a time.tweaked the driver to enable both CCIs corresponding to sensors ov5640 and ov5645.dynamic cci master initialization is done from sensor drivers reading the cci master index from the sensor ports in the device tree
