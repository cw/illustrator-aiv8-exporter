# Illustrator AI version 8 Exporter

Exporting AI version 8 from Illustrator is a slow, laborious process&mdash;this script fixes that. The script doesn't waste your time with GUI or settings you'll never use. You just run the script, select a location to export and you have your AIs. The script exports any layer, group or path named with the `.AIv8` extension.

## Credit

This script was forked from [Illustrator SVG Exporter](https://github.com/iconic/illustrator-svg-exporter) and uses the same conventions. 

## Installation

You don't _have_ to install the script to use it (more on that later), but installing the script is by far the best way to use it. All you need to do is drop the `AIv8 Exporter.jsx` file in one of the following directories:

* Windows: `C:\Program Files\Adobe\Adobe lllustratorCC2014\Presets\[language]\Scripts\`
* Mac OS: `/Applications/Adobe lllustrator CC 2014/Presets/[language]/Scripts/`

Note: Make sure to restart Illustrator if you installed the script while the Application is running.

## Running the Script

Once the script is installed, you'll be able to run it by going to `File > Scripts > AIv8 Exporter`. As mentioned, you don't need to install the script. If you want to run it as a one-off, select `File > Scripts > Other Script...` and select the `AIv8 Exporter.jsx` file in the file chooser.

Once you run the script, you'll be prompted to select a location to save the AI files. After a location is set, you're done&mdash;the script does the rest.

## Document Setup

The script doesn't force any setup or organization on you. You can export layers, groups, compound paths or individual paths. Just name the path/layer/group/compound path what you want the file name to be (e.g., my-cool-vector-drawing.AIv8) and the script will prep it for export. You can export nested layers (example: export indiviual assets as well all assets in a parent layer). The exported AIs will be cropped to the bounding box of the path/group/layer.

You can name artboards with a `.AIv8` extension to export AIs to specific dimensions other than the paths' bounding box. All paths within the artboard will be exported, so make sure to clean up any unwanted paths before export.

If you previously named an element for export but now don't want to export for some reason, simply lock it to keep it from being exported.
