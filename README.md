## Introduction

This project provides an application template for the [frida-il2cpp-bridge](https://github.com/vfsfitvnm/frida-il2cpp-bridge) library, which is an excellent library that enables hooking of IL2CPP applications. The template includes environment configuration and code compilation commands, as well as explanations of some common issues that beginners may encounter.

## Cloning the Repository

You can start by cloning or forking this repository:

```PowerShell
git clone https://github.com/ChuJiani/frida-il2cpp-bridge-template.git
```

## Installing Dependencies

To install all dependencies, run the following command with yarn:

```PowerShell
yarn install
```

## Compiling the Source Code

Compile the target hook script with the predefined command:

> checking the `package.json` file for details

```PowerShell
yarn run build
```

The compiled script will be located in `output/hook.js`.

> The `watch` command is a continuous version of the `build` command, which continuously monitors changes to source files and compiles them in real-time. When combined with frida's `auto-reload` functionality, it provides a seamless debugging experience.

## Developing the Script

Refer to the wiki and discussions of [frida-il2pp-bridge]("https://github.com/vfsfitvnm/frida-il2cpp-bridge/wiki") to develop the script.

## Using the Script

Refer to the [Frida documentation](https://frida.re/docs/frida-cli/) for guidance on using the script.
