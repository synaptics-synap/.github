SyNAP
=====

Synaptics Neural Network Acceleration and Processing
----------------------------------------------------

SyNAP is an acronym for *Synaptics Neural Network Acceleration and Processing*. It originally
started a few years back as a simple Python wrapper around the Verisilicon Acuity toolkit in
order to simply the creation and testing of the AS370 SoC powering the Google Nest smart home
product. Since then it has grown into a full AI framework for various Synaptics SoCs.

SyNAP framework is composed of multiple components

* the SyNAP documentation
  https://syna-synap.github.io/doc
* the SyNAP toolkit for TFLite and ONNX model analysis, compilation and conversion
  https://github.com/syna-synap/toolkit
* the SyNAP runtime for the creation of AI application running on AI-enabled Synaptics SoCs
  - the SyNAP secure driver a.k.a SyKURE
  - the SyNAP C++ API for heterogeneous inference and pre- and post-processing
* forks of OpenSource project optimized for the Synaptics SoCs
