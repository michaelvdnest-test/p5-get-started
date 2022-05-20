# p5-get-started

How to use the p5.js JavaScript library


## Preview panel

[live-p5][2] provides a live preview panel of your P5 code.

It enables you to change variable values without reloading the P5 rendering, see the gif below:

![In action](https://github.com/filipesabella/vscode-live-p5/raw/master/image.gif)

## How to use it

- Open your javascript p5 code with a `draw` function
- Type **"live p5"** on the command palette and press enter
- When editing literal values, the preview is updated automatically
- When saving the document, the preview reloads

It enables you to change variable values without reloading the P5 rendering, see the gif below:

## Local server with vscode

Using the [Live Server extension for VS Code][1]
we can easily run a development web server for any local folder.

Instructions:

- Open the VS Code extension manager (CTRL-SHIFT-X / CMD-SHIFT-X)
- Search for and install the [Live Server extension][1].
- Add a p5.js project folder to your VS Code Workspace.
- With your project's index.html or sketch.js file open, start the Live Server using the "Go Live" button in the status bar, or by using ALT-L ALT-O.
- Your sketch should now open in your default browser at location: 127.0.0.1:5500

## p5 extension

[p5.vscode][3] helps you create p5.js projects in Visual Studio Code. It also includes autocompletion, a simple tool to browse and install third-party p5 libraries, and the Live Server extension.

[1]: <https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer> "Live Server Extension"
[2]: <https://marketplace.visualstudio.com/items?itemName=filipesabella.live-p5> "Live p5"
[3]: <https://marketplace.visualstudio.com/items?itemName=samplavigne.p5-vscode> "p5.vscode"


