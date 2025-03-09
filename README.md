# Highlight Text Extractor

> A fork of [pyhighlight-ocr](https://github.com/zirkelc/pyhighlight-ocr) with enhanced highlight detection capabilities.

## About This Fork

This fork adds a new feature to the original text extraction tool: **automatic detection of highlights in any color**. While the original implementation required manually specifying HSV color ranges for each highlight color, this fork can detect highlighted text regardless of color using adaptive saturation thresholding combined with text detection algorithms.

### Key Improvements

- **Color-agnostic highlight detection**: Automatically detects highlighted text of any color
- **Reduced configuration**: No need to specify exact HSV color ranges
- **Adaptive thresholding**: Adjusts to different document conditions automatically

## Original Project

Full credit for the original implementation goes to [zirkelc](https://github.com/zirkelc). This fork builds upon their excellent work in text extraction and highlight detection.
