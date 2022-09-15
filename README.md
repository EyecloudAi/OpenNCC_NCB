# EyeCloudAI_OpenNCC-NCB

OpenNCC NCB is a Neural Computing Board produced by EyeCloud. Inc, working with Intel® Distribution of OpenVINO™ Toolkit to provide similar functions as the Intel® Neural Compute Stick 2 (Intel® NCS2).

## Where to buy
OpenNCC NCB will soon be available on [Crowd Supply](https://www.crowdsupply.com/eyecloud/openncc-ncb).

## How to get started

On the software side, OpenNCC NCB can be used the same way as the Intel® Neural Compute Stick 2 (Intel® NCS2), so you can start it following instructions on [Get Started with Intel® Neural Compute Stick 2](https://www.intel.com/content/www/us/en/developer/articles/guide/get-started-with-neural-compute-stick.html) and use resources from the [OpenVINO GitHub Repo](https://github.com/openvinotoolkit/openvino), except one extra step required: after installing the OpenVINO, please download the usb-ma2x8x.mvcmd file for OpenNCC NCB from [here](https://github.com/EyecloudAi/openncc/blob/R22.08.01/SDK/Source/Firmware/fw/usb-ma2x8x.mvcmd) and replace the original .mvcmd file under openvino/inference_engine/lib/intel64/usb-ma2x8x.mvcmd with it.

On the hardware side, differences between the USB version and FFC version are the connector types: One is USB-C and the other is FFC. For details, please refer to the documents under OpenNCC NCB Hardware file in this repo.
