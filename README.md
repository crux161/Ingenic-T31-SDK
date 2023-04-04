# Ingenic-T31 SDK (1.1.1)

This repo will focus on supporting mainly the "Drive-Free 1080p webcam" which is equiped with the Igenic T31 SoC. 

## Ingenic T31 specifications:

## Processors
### XBurst 1 32-bit MIPS core clocked at 1.5GHz with Vector Deep Learning accelerator based on SIMD128, 64KB + 128KB L1/L2 Cache
### RISC-V independent lite core
### System Memory – Built-in 512Mbit (64MB) or 1Gbit (128MB) DDR2
### Storage – Quad SPI flash, NAND flash, SD card I/F
### Display I/F – Supports Smart LCD (SLCD) Display
### Video Encoder – H.264/H.265/MJPEG up to 2592×1920 @ 30fps with multiple streams support
### Camera
MIPI CSI-2 & DVP/BT interfaces
### Supports 5M @ 30fps
Starlight ISP
### Optimizations for low light and surveillance scenarios
### Upgraded 2D / 3D noise reduction
Sharpening enhancement, ROI-AE, advanced WDR, DRC, distortion correction
### Audio – integrated audio codec up to 96Kbps, I2S, 4-channel digital MIC array; echo cancellation
### Networking – GMAC (from specs), RMII (from block diagram)
### USB – 1x USB OTG Interface
### Other Peripherals – WDT, 3x ADC, 2x UART, 3x I2C, 2x SPI, GPIO, 2x SDIO, 4x PWM
### Security – AES/RSA/SHA/TRNG/OTP;  secure boot
### Power Consumption – Minimum: 300 mW (I suppose in idle mode, not deep sleep); typ.: 500mW including DDR (1080p @ 25fps H.265)
### Package – QFN88, BGA 9x9mm
### Process – 22nm

The processor supports fast boot with 200ms stable video output including fast AE (Auto Exposure) / AWB (Auto White Balance) and can be interfaced with WiFi and Bluetooth module.

Ingenic T31 is compatible with USB UVC and UAC and as such, is designed to be integrated into standardized video or audio products. Built-in AI algorithms enable human detection, facial detection/recognition, cry detection, vehicle detection, pets detection.

(https://www.cnx-software.com/2020/04/26/ingenic-t31-ai-video-processor-combines-xburst-1-mips-and-risc-v-lite-cores/?amp=1)
