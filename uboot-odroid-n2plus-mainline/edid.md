This edid files make it possible to get a problematic display working properly.

The edid binary files where taken from:
https://github.com/akatrevorjay/edid-generator

The edid's on this directory can be used with the kernel parameter:

> drm_kms_helper.edid_firmware=HDMI-A-1:edid/{file_name}.bin

Where {file_name} can be one of the files listed on this directory,
eg:

> drm_kms_helper.edid_firmware=HDMI-A-1:edid/1920x1080.bin

Thanks to tobetter for the information he provided here:
https://docs.linuxfactory.or.kr/guides/kmsdrm.html
