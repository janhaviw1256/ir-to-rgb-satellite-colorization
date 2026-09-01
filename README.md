# IR → RGB Satellite Colorization

Deep learning framework for enhancing and colorizing infrared satellite imagery
into RGB representations while preserving semantic integrity and estimating
pixel-level uncertainty.

-> Project Status-

Currently in development.

-> Objectives-

- Enhance structural details in infrared satellite imagery
- Generate realistic RGB representations
- Preserve semantic and spatial integrity
- Estimate pixel-level confidence/uncertainty
- Evaluate usefulness for downstream vision tasks

-> Planned Pipeline-

Landsat 8/9 IR
      ↓
Preprocessing
      ↓
Enhancement / Super-Resolution
      ↓
IR → RGB Colorization
      ↓
Semantic Constraints
      ↓
Uncertainty Estimation
      ↓
Evaluation

-> Evaluation-

- PSNR
- SSIM
- LPIPS
- FID
- Inference time
- Qualitative visual analysis
- Downstream detection/segmentation performance

-> Project Structure-

data/          Dataset preparation and processing
models/        Neural network architectures
losses/        Training loss functions
training/      Training scripts
evaluation/    Evaluation and metrics
demo/          Interactive demo
notebooks/     Experiments
configs/       Configuration files
outputs/       Selected results 