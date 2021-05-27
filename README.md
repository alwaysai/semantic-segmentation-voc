# Semantic Segmentation VOC
Perform [Semantic Segmentation](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#semantic-segmentation) on a series of images using a model trained on the [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/) dataset.

## Requirements
* [alwaysAI account](https://alwaysai.co/auth?register=true)
* [alwaysAI Development Tools](https://alwaysai.co/docs/get_started/development_computer_setup.html)

## Usage
Once the alwaysAI tools are installed on your development machine (or edge device if developing directly on it) you can install and run the app with the following CLI commands:

To perform initial configuration of the app:
```
aai app configure
```

To prepare the runtime environment and install app dependencies:
```
aai app install
```

To start the app:
```
aai app start
```

Different images can be used by updating the files in the *images/* directory. Note that when developing for a remote device, removing images in the local *images/* directory won't remove images from the device. They can be removed using the `aai app shell` command and deleting them from the *images/* directory on the remote device.

To change the computer vision model, the engine and accelerator, and add additional dependencies read [this guide](https://alwaysai.co/docs/application_development/configuration_and_packaging.html).

## Support
* [Documentation](https://alwaysai.co/docs/)
* [Community Discord](https://discord.gg/z3t9pea)
* Email: support@alwaysai.co
