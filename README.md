# HLS_LabC_BLAS
## Vitis BLAS Library

Vitis BLAS Library is an open-sourced Vitis library written in C++ and released under Apache 2.0 license for accelerating linear algebra functions in a variety of use cases.

The main target audience of this library is users who want to accelerate linear algebra functions with FPGA cards. Currently, this library offers three levels of acceleration:

At module level is for the C++ implementation of BLAS functions. These implementations are intended to be used by HLS (High Level Synthesis) users to build FPGA logic for their applications.
The kernel level is for pre-defined kernels that are the C++ implementation of BLAS functions. These implementations are intended to demonstrate how FPGA kernels are defined and how L1 primitive functions can be used by any Vitis users to build their kernels for their applications.
The software APIs level is an implementation of BLAS on top of the XILINX runtime (XRT). It allows software developers to use Vitis BLAS library without writing any runtime functions and hardware configurations.
Check the comprehensive HTML document for more details.

Copyright 2019-2020 Xilinx, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
