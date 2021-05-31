    sysfs: >-
      /sys/devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1
    dev_path: /dev/bus/usb/001/104
    subsystem: usb
    by_id: null
    attributes:
      BUSNUM: '001'
      DEVNAME: /dev/bus/usb/001/104
      DEVNUM: '104'
      DEVPATH: >-
        /devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1
      DEVTYPE: usb_device
      DRIVER: usb
      ID_BUS: usb
      ID_FOR_SEAT: usb-platform-fd500000_pcie-pci-0000_01_00_0-usb-0_1_1
      ID_MODEL: USB_Audio_Device
      ID_MODEL_ENC: USB\x20Audio\x20Device
      ID_MODEL_ID: '0014'
      ID_PATH: 'platform-fd500000.pcie-pci-0000:01:00.0-usb-0:1.1'
      ID_PATH_TAG: platform-fd500000_pcie-pci-0000_01_00_0-usb-0_1_1
      ID_REVISION: '0100'
      ID_SERIAL: C-Media_Electronics_Inc._USB_Audio_Device
      ID_USB_INTERFACES: ':010100:010200:030000:'
      ID_VENDOR: C-Media_Electronics_Inc.
      ID_VENDOR_ENC: C-Media\x20Electronics\x20Inc.
      ID_VENDOR_ID: 0d8c
      MAJOR: '189'
      MINOR: '103'
      PRODUCT: d8c/14/100
      SUBSYSTEM: usb
      TAGS: ':seat:'
      TYPE: 0/0/0
      USEC_INITIALIZED: '6007998869'
  - name: pcmC1D0p
    sysfs: >-
      /sys/devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.0/sound/card1/pcmC1D0p
    dev_path: /dev/snd/pcmC1D0p
    subsystem: sound
    by_id: null
    attributes:
      DEVNAME: /dev/snd/pcmC1D0p
      DEVPATH: >-
        /devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.0/sound/card1/pcmC1D0p
      DEVTYPE: pcm
      MAJOR: '116'
      MINOR: '4'
      SUBSYSTEM: sound
  - name: pcmC1D0c
    sysfs: >-
      /sys/devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.0/sound/card1/pcmC1D0c
    dev_path: /dev/snd/pcmC1D0c
    subsystem: sound
    by_id: null
    attributes:
      DEVNAME: /dev/snd/pcmC1D0c
      DEVPATH: >-
        /devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.0/sound/card1/pcmC1D0c
      DEVTYPE: pcm
      MAJOR: '116'
      MINOR: '5'
      SUBSYSTEM: sound
  - name: controlC1
    sysfs: >-
      /sys/devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.0/sound/card1/controlC1
    dev_path: /dev/snd/controlC1
    subsystem: sound
    by_id: /dev/snd/by-id/usb-C-Media_Electronics_Inc._USB_Audio_Device-00
    attributes:
      DEVLINKS: >-
        /dev/snd/by-id/usb-C-Media_Electronics_Inc._USB_Audio_Device-00
        /dev/snd/by-path/platform-fd500000.pcie-pci-0000:01:00.0-usb-0:1.1:1.0
      DEVNAME: /dev/snd/controlC1
      DEVPATH: >-
        /devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.0/sound/card1/controlC1
      ID_BUS: usb
      ID_MODEL: USB_Audio_Device
      ID_MODEL_ENC: USB\x20Audio\x20Device
      ID_MODEL_ID: '0014'
      ID_PATH: 'platform-fd500000.pcie-pci-0000:01:00.0-usb-0:1.1:1.0'
      ID_PATH_TAG: platform-fd500000_pcie-pci-0000_01_00_0-usb-0_1_1_1_0
      ID_REVISION: '0100'
      ID_SERIAL: C-Media_Electronics_Inc._USB_Audio_Device
      ID_TYPE: audio
      ID_USB_DRIVER: snd-usb-audio
      ID_USB_INTERFACES: ':010100:010200:030000:'
      ID_USB_INTERFACE_NUM: '00'
      ID_VENDOR: C-Media_Electronics_Inc.
      ID_VENDOR_ENC: C-Media\x20Electronics\x20Inc.
      ID_VENDOR_ID: 0d8c
      MAJOR: '116'
      MINOR: '6'
      SUBSYSTEM: sound
      SYSTEMD_USER_WANTS: sound.target
      SYSTEMD_WANTS: sound.target
      TAGS: ':systemd:'
      USEC_INITIALIZED: '6008030203'
  - name: event0
    sysfs: >-
      /sys/devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.3/0003:0D8C:0014.0004/input/input3/event0
    dev_path: /dev/input/event0
    subsystem: input
    by_id: /dev/input/by-id/usb-C-Media_Electronics_Inc._USB_Audio_Device-event-if03
    attributes:
      DEVLINKS: >-
        /dev/input/by-id/usb-C-Media_Electronics_Inc._USB_Audio_Device-event-if03
        /dev/input/by-path/platform-fd500000.pcie-pci-0000:01:00.0-usb-0:1.1:1.3-event
      DEVNAME: /dev/input/event0
      DEVPATH: >-
        /devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.3/0003:0D8C:0014.0004/input/input3/event0
      ID_BUS: usb
      ID_INPUT: '1'
      ID_INPUT_KEY: '1'
      ID_MODEL: USB_Audio_Device
      ID_MODEL_ENC: USB\x20Audio\x20Device
      ID_MODEL_ID: '0014'
      ID_PATH: 'platform-fd500000.pcie-pci-0000:01:00.0-usb-0:1.1:1.3'
      ID_PATH_TAG: platform-fd500000_pcie-pci-0000_01_00_0-usb-0_1_1_1_3
      ID_REVISION: '0100'
      ID_SERIAL: C-Media_Electronics_Inc._USB_Audio_Device
      ID_TYPE: hid
      ID_USB_DRIVER: usbhid
      ID_USB_INTERFACES: ':010100:010200:030000:'
      ID_USB_INTERFACE_NUM: '03'
      ID_VENDOR: C-Media_Electronics_Inc.
      ID_VENDOR_ENC: C-Media\x20Electronics\x20Inc.
      ID_VENDOR_ID: 0d8c
      MAJOR: '13'
      MINOR: '64'
      SUBSYSTEM: input
      TAGS: ':power-switch:'
      USEC_INITIALIZED: '6008085247'
  - name: hidraw0
    sysfs: >-
      /sys/devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.3/0003:0D8C:0014.0004/hidraw/hidraw0
    dev_path: /dev/hidraw0
    subsystem: hidraw
    by_id: null
    attributes:
      DEVNAME: /dev/hidraw0
      DEVPATH: >-
        /devices/platform/scb/fd500000.pcie/pci0000:00/0000:00:00.0/0000:01:00.0/usb1/1-1/1-1.1/1-1.1:1.3/0003:0D8C:0014.0004/hidraw/hidraw0
      MAJOR: '243'
      MINOR: '0'
      SUBSYSTEM: hidraw
