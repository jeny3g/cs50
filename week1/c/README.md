## Instructions

In order to be able to run the code, you need to have the following installed:

### **With Docker[](https://cs50.readthedocs.io/code/#with-docker)**

To use VS Code locally with Docker, running a [codespace-like container](https://code.visualstudio.com/docs/remote/containers) on your own computer, even without internet access, and opening a folder like `foo` therein:

1. Download CS50’s latest `.devcontainer.json` file from [raw.githubusercontent.com/cs50/codespace/main/.devcontainer.json](https://raw.githubusercontent.com/cs50/codespace/main/.devcontainer.json), saving it in `foo`. Because the file’s name starts with a dot (i.e., period), it might seem to “disappear” when you download it. But, in a terminal window on Linux or macOS, you should see it with `ls -a`, and at a command prompt in Windows, you should see it with `dir /a`.
2. Download, install, and start [Docker](https://cs50.readthedocs.io/docker/) on your computer.
3. Download and install [VS Code](https://code.visualstudio.com/download) itself on your computer.
4. Install VS Code’s [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.
5. Open VS Code’s [command palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette), as via **Ctrl+Shift+P** on Linux, **⇧⌘P** on macOS, and **Ctrl+Shift+P** on Windows, select **>Remote-Containers - Open Folder in Container…**, and open `foo`.
