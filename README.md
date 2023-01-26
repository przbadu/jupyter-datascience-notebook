### How to run this project

1. Install [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers) vscode extension
2. Open devcontainer from the bottom left icon, or using command pallete `cmd + P`
3. Reopen project in devcontainer, by either accepting the prompt that vscode will provide automatically, or by manually by opening dev container command pallete and searching for `Dev Containers: Reopen in Container`
4. This will run project in http://localhost:8888 port

### to generate token run

Open new vscode terminal session and type

```sh
jupyter server list
```

This will give you output like:

```sh
Currently running servers:
http://localhost:8888/?token=c8de56fa... :: /Users/you/notebooks
```

Copy the token from the output, and put it in `Password or token` input field and click on `Login`

And your jupyter notebook is ready. 

Happy machine learning!!