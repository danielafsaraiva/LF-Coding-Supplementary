SUPPLEMENTARY MATERIAL: CODING PARAMETERS
-----------------------------------------------------

This package contains the detailed experimental data and coding parameters used for the Light Field compression and Super-Resolution pipelines presented in the paper.

FILE DESCRIPTIONS:
==================

1. vvc_data.csv
   Coding parameters for the VVC pipeline.
   * Target_Bitrate: The intended bitrate (in bpp) for the experimental point.
   * QP: The Quantization Parameter used for the VTM reference software for VVC.
   * Bitstream_Bytes: The file size of the encoded bitstream.
   * Actual_Bitrate: The resulting bitrate measured in bits per pixel.

2. pleno_data.csv
   Coding parameters for the JPEG Pleno pipeline.
   * Target_Bitrate: The intended bitrate (in bpp) for the experimental point.
   * Lambda: The variable used to control the Rate-Distortion tradeoff in JPEG Pleno 4D-TM.
   * Bitstream_Bytes: The file size of the encoded bitstream.
   * Actual_Bitrate: The resulting bitrate measured in bits per pixel.
