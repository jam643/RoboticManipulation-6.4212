# Robotic Manipulation MIT 6.4212

My informal HW solutions for MIT 6.4212 for Fall 2023

## Running Notebooks

### Locally on my Mac:

- VSCode with `Docker` and `Dev Container` extensions installed
- `Docker Desktop` installed for Mac with Apple Silicon
- `Cmd + shift + P` in VSCode and select `Dev Container: Open Workspace in Container`
- Note that this will use `devcontainer.json` to create container
    - Specifies `--platform=linux/amd64` when building image since I'm running on Mac M3 ARM64 but image is designed for AMD64, this enforces emulation
    - This includes forwarding container port 7000 to host port 7001 since my host machine was already using 7000. This port is used to visualize MeshCat output in browser
- For each DeepNote workspace, I do "Download project" and copy contents over to this repo

### In Github Codespace

- In github repo, go to `Code` -> `Codespaces` `+` to create codespace in browser
- Once it's startup, you can run notebooks in cloud