# ComfyUI Workflow Collection

A curated collection of ComfyUI workflows known to work with NVIDIA GTX 1050ti, 4VRAM, 8RAM, 8SWAP for various image and video generation tasks.

### Environment

export PYTORCH_CUDA_ALLOC_CONF=expandable_segments:True

### Options

 none

## Workflows

### Text-to-Image
- **Z_image_turbo.json** - Text to image workflow using Z Image Turbo
- **Flux2_klein_4b_text_to_image.json** - Text to image workflow using Flux2 klein 4b

### Image-to-Image
- **Flux2_klein_image_edit_4b_multi-latest.json** - Image-to-image workflow using Flux 2 Klein 4b

### Video Generation
- **LTXV first last latest v1.json** - Image-to-video workflow using the LTXV 2b distilled model, first/last frame capabilities
- **LTXV latest.json** - Text-to-video workflow using the LTXV 2b distilled model

### Image Processing
- **UPSCALE REMOVE BACKGROUND AND MASK.json** - Upscaling workflow with automated background removal and masking

### Misc Tools
- **angle-prompt-builder.html** - Build prompts for flux/zit.
- **ace-step-prompt-generator.html** - Build prompts for Ace Step 1.5.
- **infograph-studio.html** - Build text prompts for inforgraphs.
- **ltxv-prompt-builder.html** - Build prompts for the LTXV 2b workflow.

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
