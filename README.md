# Comfyui-aiai

Comfyui-aiai is a ComfyUI custom node package for AIAI workflows. It provides a unified set of nodes for image generation, image editing, video generation, model API calls, and workflow examples under the `aiai` node categories.

## Repository

- GitHub: https://github.com/aiaiai666/Comfyui-aiai
- Username: aiaiai666
- Email: ihuangke1666@gmail.com

## Features

- AIAI API settings node with the default service endpoint `https://ai.kegeai.top`.
- GPT Image-2 text-to-image and image editing nodes.
- Workflow examples for GPT Image-2, Doubao, Gemini, Grok, Kling, Vidu, Suno, Flux, Qwen, MiniMax, and other supported models.
- Base64 image response handling for supported image nodes, saving generated images into ComfyUI output files for preview.
- Image, video, and LLM API helper nodes grouped under `aiai`.

## Installation

Clone this repository into your ComfyUI `custom_nodes` directory:

```bash
git clone https://github.com/aiaiai666/Comfyui-aiai.git custom_nodes/Comfyui-aiai
```

Install dependencies if your ComfyUI environment does not already include them:

```bash
pip install -r custom_nodes/Comfyui-aiai/requirements.txt
```

Restart ComfyUI after installation.

## Configuration

Use the `aiai API Settings` node to select the AIAI endpoint and set your API key. The plugin uses:

```text
https://ai.kegeai.top
```

You can also provide an API key directly in nodes that expose an `api_key` input.

## Workflows

Example workflows are included in the `workflow` directory. Import the JSON files into ComfyUI to try the packaged node graphs.

## License

See `LICENSE`.
