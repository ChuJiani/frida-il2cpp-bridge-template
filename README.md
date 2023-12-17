## Introduction

This project provides an application template for the [frida-il2cpp-bridge](https://github.com/vfsfitvnm/frida-il2cpp-bridge) library, which is an excellent library that enables hooking of IL2CPP applications. The template includes environment configuration and code compilation commands, as well as explanations of some common issues that beginners may encounter.

## Get Start

You can start by cloning this repository:

```bash
git clone https://github.com/ChuJiani/frida-il2cpp-bridge-template.git
```

Run the following command to install dependencies:

```bash
npm install
```

Compile the example script with the predefined `build` command, which is defined in `package.json`.

```bash
npm run build
```

The compiled script will be located in `output/hook.js`, and can be correctly loaded and run by frida.

You can also use `watch` command, which continuously monitors changes to source files and compiles them in real-time. This is useful when combined with frida's `auto-reload` functionality.

## Further Development

Refer to the `wiki` and `discussions` of [frida-il2pp-bridge]("https://github.com/vfsfitvnm/frida-il2cpp-bridge/wiki") to develop the script.
