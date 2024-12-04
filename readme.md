# Robotic Manipulation MIT 6.4212

My informal HW solutions for MIT 6.4212

## My Mac Setup:

- VSCode with `Docker` and `Dev Container` extensions installed
- `Docker Desktop` installed for Mac with Apple Silicon
- Create docker image specifying platform (since I'm running on M3/ARM64)
`docker build --platform linux/amd64 -t roboticmanipulation <path/to/Dockerfile>`
- `Cmd + shift + P` in VSCode and select `Dev Container: Open Workspace in Container`
- Note that this will use `devcontainer.json` to create container
    - This includes forwarding container port 7000 to host port 7001 since my host machine was already using 7000. This port is used to visualize MeshCat output in browser
- For each DeepNote workspace, I do "Download project" and copy contents over to this repo