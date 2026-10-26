# LAB 7

### Tasks done in lab 7:

**Lab 7A - Laplacian filter**
- Sharpened the moon image with a manual 3x3 Laplacian kernel (`filter2D`) and with Gaussian blur + `cv2.Laplacian`.
- Fixed the final step to `f - lap` in float with clipping, since adding in uint8 wraps values above 255.
- Applied both methods to an RGB image (per channel), and also sharpened only the Y channel in YCrCb to keep the colours clean.

**Lab 7B - Mathematical and statistical filters**
- Added Gaussian, salt & pepper, exponential and uniform noise.
- Applied arithmetic, geometric, harmonic, contraharmonic, median, max/min and midpoint filters.
- Repeated everything on an RGB image by filtering each channel, and compared all filters with PSNR.
