# awesome-edge-ai [![Awesome][awesome-badge]](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/rcmalli/awesome-edge-ai.svg?branch=master)](https://travis-ci.org/rcmalli/awesome-edge-ai)

A curated list of edge devices for AI applications.

## Contents

- [Development Platforms](#development-platforms)
- [Custom Accelerators](#custom-accelerators)
- [Software Libraries](#software-libraries)


### Development Platforms
<!-- Section description (optional). -->

- [Baidu EdgeBoard](http://ai.baidu.com/tech/hardware/deepkit) - Xilinx FPGA based edge computing board.
- [BeagleBone AI](https://beagleboard.org/ai) - Linux Board powered by ARM CPU,TI C66x digital-signal-processor (DSP) cores and embedded-vision-engine (EVE). It has 1GB RAM.
- [Google Coral Dev Board](https://coral.withgoogle.com/products/dev-board/) - It is single board solution which contains ARM CPU and Edge TPU as accelerator with 1GB RAM.
- [Google Coral USB Accelerator](https://coral.withgoogle.com/products/accelerator/) - Edge TPU  accelerator module connects with USB interface. It needs host device.
- [Intel Neural Compute Stick 1](https://software.intel.com/en-us/movidius-ncs) - First generation ASIC chip designed by Movidius that runs as module board via USB interface. It needs host device.
- [Intel Neural Compute Stick 2](https://www.intel.ai/intel-neural-compute-stick-2-smarter-faster-plug-and-play-ai-at-the-edge/) - Second generation module stick which is faster than previous one based TOPS measure. It needs host device.
- [Nvidia Jetson AGX Xavier](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-agx-xavier/) - Most power single board computer from NVIDIA designed for autonomous systems (cars etc.). Contains 512 Cuda core Volta GPU with Tensor Cores and 16 GB RAM.
- [Nvidia Jetson Nano](https://devblogs.nvidia.com/jetson-nano-ai-computing/) - Cost efficient alternative to NVIDIA boards. Performance is equivalent to the TX1. Contains ARM CPU and 128 Cuda core Maxwell GPU and has 4 GB RAM.
- [Nvidia Jetson TX1](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems-dev-kits-modules/?section=jetsonTX1) - Contains ARM CPU and 128 Cuda core Maxwell GPU. `It seems like this board is replaced by Nano.` 
- [Nvidia Jetson TX2](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems-dev-kits-modules/?section=jetsonTX2) - Contains ARM CPU and 256 Cuda core Pascal GPU and has 8 GB/4 GB RAM.
- [OrangePi AI Stick](http://www.orangepi.org/Orange%20Pi%20AI%20Stick%202801/) - ASIC based neural accelerator. It needs host device.
- [Sipeed MAIX Go Suit](https://www.indiegogo.com/projects/sipeed-maix-the-world-first-risc-v-64-ai-module) - Single board computer based on RISC-V AI chip, KPU(Neural Network Processor) and APU(Audio Processor). It contains on-board DVP camera and LCD screen for visual output.
- [SparkFun Edge Development Board](https://www.sparkfun.com/products/15170) - Apollo3 Blue microcontroller based board that contains microphones and 3-axis accelerometer and OV7670 camera interface. Runs on single coin battery. Supports Tensorflow-lite.
- [UP Squared AI Vision X](https://up-shop.org/home/285-up-squared-ai-vision-x-developer-kit.html) - Single board computer contains Intel ATOM CPU and Movidius Myriad as neural accelerator. It has 4 GB RAM.
- [Xnor.ai Solar Powered Module](https://www.xnor.ai/solar-powered-ai/) - Very low power unit which can be running with only using solar panels. `More technical specifications needed.`


### Custom Accelerators
- [Google Edge TPU](https://cloud.google.com/edge-tpu/)
- [Intel Movidius Myriad VPU 2](https://www.movidius.com/myriad2)
- [Intel Movidius Myriad X VPU](https://www.movidius.com/myriadx)
- [Lightspeeur 280-X Neural Accelerators](https://www.gyrfalcontech.ai/solutions/)
- [Sipeed MAIX](https://www.indiegogo.com/projects/sipeed-maix-the-world-first-risc-v-64-ai-module#/)
- [TI Vision AcclerationPac](http://www.ti.com/lit/wp/spry251/spry251.pdf)

### Software Libraries

- [Tensorflow Lite](https://www.tensorflow.org/lite)
- [TinyDNN](https://github.com/tiny-dnn/tiny-dnn)
- [uTensor](https://github.com/uTensor/uTensor)
- [EdgeML](https://github.com/Microsoft/EdgeML)


## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Refik Can MALLI has waived all copyright
and related or neighboring rights to this work. See [LICENSE](LICENSE).


<!-- BADGES -->

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg

