# Welcome
This repository contains the source code of the UI for NativeScript samples application. The repository does not contain the source code of UI for NativeScript itself. To be able to use the application hosted here, you will need to download the UI for NativeScript plugin for NS and add it manually.

##Overview
The UI for NativeScript samples app resides in the **sdk** folder at root repository level. The folder has a standard NativeScript application structure as described on [NativeScript website](http://docs.nativescript.org/hello-world/hello-world-ns-cli). The source code of the samples resides in the folders named after each component available in **UI for NativeScript**. The currently available components are:

- chart
- sidedrawer

## Adding the UI for NativeScript
As already mentioned, you have to install the **UI for NativeScript** plugin to be able to run the samples app. The following text provides step-by-step instructions on how this is done.

1. Make sure you are using NativeScript 1.2+. To see which version of NativeScript you are currently using, type `tns --version` in the console.
2. Create a NativeScript application and add at least one of the platforms (Android or iOS) if you haven't done so already.
3. Install the plugin by opening the root folder of the samples app and typing the following command: `tns plugin add nativescript-telerik-ui`.

> Currently there are some additional installation steps that need to be taken care of manually. Please follow the instructions provided on the official Telerik UI for NativeScript documentation website: [http://docs.telerik.com/devtools/nativescript-ui/getting-started](http://docs.telerik.com/devtools/nativescript-ui/getting-started)
