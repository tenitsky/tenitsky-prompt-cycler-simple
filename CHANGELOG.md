# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed
- Fixed issue where example prompts were not visible in the ComfyUI interface
- Example prompts now show as default values in the custom_prompts field

## [1.0.0] - 2025-10-22

### Added
- Initial release of Prompt Cycler node
- Support for infinite number of custom prompts
- 10 built-in example prompts covering various themes
- Sequential and random cycling modes
- Reset functionality to restart cycle from beginning
- Seed control for reproducible results
- Custom prompts input with multiline support
- Cycle index output for tracking current position

### Features
- **Infinite Prompt Support**: Cycle through any number of custom prompts
- **Example Prompts**: 10 pre-configured high-quality prompts
- **Sequential Cycling**: Automatically cycles through prompts in order
- **Random Mode**: Randomly selects prompts for variety
- **Reset Functionality**: Ability to reset the cycle counter
- **Seed Control**: Reproducible results with seed input
- **Custom Prompts**: Option to provide unlimited custom prompts

### Technical Details
- Built with PyTorch compatibility
- Follows ComfyUI custom node standards
- Proper input/output type definitions
- Comprehensive error handling
- Memory efficient implementation
