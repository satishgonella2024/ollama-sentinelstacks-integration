# Ollama-Sentinelstacks Integration

This repository contains configuration and scripts for integrating multiple Ollama models with Sentinelstacks.

## System Configuration

- **CPU**: AMD Ryzen 9 7950X (8 cores allocated to VM)
- **RAM**: 39GB total (36GB available)
- **GPU**: NVIDIA GeForce RTX 4080 SUPER with 16GB VRAM
- **Storage**: 287GB available on main partition

## Getting Started

1. Use the model installation script to add new models
2. Configure the reverse proxy if needed
3. Update your Sentinelstacks configuration

## Available Scripts

- `install-models.sh`: Install recommended models
- `create-custom-models.sh`: Create custom models with specific system prompts
- `monitor-resources.sh`: Monitor GPU and system resource usage

## Configuration Files

- `nginx/`: Example Nginx configuration for routing requests
- `modelfiles/`: Custom Modelfiles for specialized assistants
- `docker-compose.yml`: For running additional UI if needed

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.