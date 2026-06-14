# ComfyUI Workflow Collection

A curated collection of ComfyUI workflows known to work with NVIDIA GTX 1050ti, 4VRAM, 8RAM, 16SWAP for various image and video generation tasks.

### Environment

export PYTORCH_CUDA_ALLOC_CONF=expandable_segments:True

### Options

 none

## Workflows

### Text-to-Image
- **z-image-aura_workflow.json** - Text to image workflow using Z Image Turbo models

### Image-to-Image
- **I2I Z IMAGE TURBO FUN UNION CNT.json** - Image-to-image workflow using Z Image Turbo models with ControlNet integration
- **I2I_flux2_klein_image_edit_4b_distilled-latest.json** - Image-to-image workflow using Flux 2 Klein with ControlNet integration

### Video Generation
- **LTXV first last latest v1.json** - Image-to-video workflow using the LTXV distilled model with looping sampler first/last frame capabilities

### Image Processing
- **UPSCALE REMOVE BACKGROUND AND MASK.json** - Upscaling workflow with automated background removal and masking

### Prompt Builder
- **ltxv-prompt-builder.html** - Build prompts for the LTXV workflow.

## Usage

1. Download the desired workflow JSON file
2. Open ComfyUI
3. Load the workflow via File → Load or drag and drop the JSON file into the ComfyUI interface
4. Install missing nodes/models if necessary
5. Adjust parameters as needed for your use case

## Requirements

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) installation
- Required models and custom nodes (varies by workflow)

## Contributing

Feel free to submit your own workflows via pull requests!

## License

See individual workflow files for any specific licensing information.
