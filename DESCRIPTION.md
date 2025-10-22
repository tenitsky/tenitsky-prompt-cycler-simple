# ComfyUI Prompt Cycler Node

## Overview
This ComfyUI custom node cycles through an infinite number of prompts, making it perfect for batch generation with varied content. It supports both built-in example prompts and custom user-defined prompts.

## Key Features
- **Infinite Prompt Support**: Cycle through any number of custom prompts
- **10 Example Prompts**: Pre-configured with diverse, high-quality prompts
- **Sequential & Random Modes**: Choose how prompts are selected
- **Reset Functionality**: Restart cycle from beginning
- **Seed Control**: Reproducible results
- **Custom Prompts**: Add unlimited custom prompts

## Installation
1. Copy this folder to your ComfyUI `custom_nodes` directory
2. Install dependencies: `pip install -r requirements.txt`
3. Restart ComfyUI

## Usage
1. Add "Prompt Cycler" node to your workflow
2. Connect `prompt` output to your text input node
3. Configure parameters as needed
4. Queue workflow to cycle through prompts

## Parameters
- **Seed**: Random seed (0 = no seed)
- **Cycle Mode**: sequential or random
- **Reset Cycle**: Reset counter to 0
- **Custom Prompts**: Your own prompts (one per line)

## Outputs
- **prompt**: Current prompt string
- **cycle_index**: Current prompt index (0-based)

## Author
Created by **Anton Tenitsky** in 2025.

## License
MIT License - see LICENSE file for details
