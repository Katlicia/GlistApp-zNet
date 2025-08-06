# GlistApp-zNet

This is a usage demo project for the `gipNetcode` plugin, showcasing zNet-based networking functionality in a Glist Engine application.

## 🛠️ Setup Instructions

Before running this GlistApp project, you **must** set up the `gipNetcode` plugin and initialize its submodules to fetch the required zNet dependencies.

### Step 1: Clone `gipNetcode` into your `myglistplugins` directory

```bash
cd path/to/your/myglistplugins
git clone https://github.com/GlistPlugins/gipNetcode.git
```

### Step 2: Initialize and update submodules (for zNet)

```bash
cd gipNetcode
git submodule update --init --recursive
```
> ⚠️ Skipping this step will cause missing zNet dependencies, and the project will not run correctly.

### Step 3: Clone this repository into your 'myglistapps' directory

```bash
cd path/to/your/myglistapps
git clone https://github.com/Katlicia/GlistApp-zNet
```
### Step 4: Open the GlistApp-zNet project and run the CMakeLists file.
This will make your project recognize the gipNetcode plugin.

### Step 5: Build and run!

## Final Notes

This is a prototype for a server that can be used in 3D games. Currently it can run locally and you can test it by starting 2 instances, one as a host, and another as a client.
