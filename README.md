# EyeCloudAI_OpenNCC-NCB

OpenNCC NCB is a Neural Computing Board produced by EyeCloud. Inc, working with Intel® Distribution of OpenVINO™ Toolkit to provide similar functions as the Intel® Neural Compute Stick 2 (Intel® NCS2).

## How to get started

The OpenNCC NCB-USB version can be used the same way as the Intel® Neural Compute Stick 2 (Intel® NCS2), so you can start it following instructions on [Get Started with Intel® Neural Compute Stick 2](https://www.intel.com/content/www/us/en/developer/articles/guide/get-started-with-neural-compute-stick.html) and use resources from the [OpenVINO GitHub Repo](https://github.com/openvinotoolkit/openvino), except one extra step required: after installing the OpenVINO, please download the usb-ma2x8x.mvcmd file for OpenNCC NCB from [here](https://github.com/EyecloudAi/openncc/blob/R22.08.01/SDK/Source/Firmware/fw/usb-ma2x8x.mvcmd) and replace the original .mvcmd file under openvino/inference_engine/lib/intel64/usb-ma2x8x.mvcmd with it.

Regarding the OpenNCC NCB-FFC version, on the software side, it works the same as the USB version; on the hardware side, it is an FFC connector instead of an USB one. Please refer to the OpenNCC NCB-FFC Connector Information documentation under OpenNCC NCB Hardware file in this repo for details.
