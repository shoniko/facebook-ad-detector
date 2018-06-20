# facebook-ad-detector
A research project to be able to detect Facebook desktop news feed ads visually

## Project structure
**adblock-ai-backend** - docker-compose cluster of a Facebook bot and tensorflow serving server for inference on a trained model and storing submitted screenshots

**facebook-ad-extractor** - scripts to produce synthetic data for trainig and to visualize the produced data (for debugging purposes).

**keras-yolo2** - a keras implementation of YOLOv2

**shoniko.github.com** - a frontend of https://adblock.ai