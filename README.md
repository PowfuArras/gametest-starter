# Gametest Starter
This is a GameTest behavior for Minecraft: Bedrock Edition pack to be used as a template for you to build your own project that uses the [GameTest Framework](https://learn.microsoft.com/en-us/minecraft/creator/documents/gametestgettingstarted).

## Prerequisites
Before you use this, make sure you have the following prerequisites installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (Node Package Manager)

## Building Your GameTest

To build your GameTest you are going to use typescript. This starter pack includes typescript as a development dependency. Here are the scripts you can use:

- To build your GameTest run:
    ```bash
    npm run build
    ```
    This will run the script to compile your typescript code into javascript code and the output will be placed in the builds directory, which minecraft will run.

- To watch for changes automatically and rebuild when file changes are detected run:
    ```bash
    npm run watch
    ```
    This will start the typescript compiler in watch mode, which will make it convenient to quickly make changes to your code as typescript will automatically recompile your code.

## Usage
1. Apply the behavior pack to a minecraft world. Ensure you have the experiment "Beta APIs" enabled.
2. Write your GameTest scripts in the `scripts/source/` directory.
3. Compile your typescript code and run `/reload` in-game to restart the GameTest Framework without restarting the world.

## Resources
For more information about the GameTest Framework refer to the [Script API Reference Documentation](https://learn.microsoft.com/en-us/minecraft/creator/scriptapi/)