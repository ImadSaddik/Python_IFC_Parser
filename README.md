# Extracting Information from IFC Files using Python

This repository contains a notebook demonstrating how to extract information from an IFC (Industry Foundation Classes) file using the IfcOpenShell library. The script showcases how to view properties such as area, volume, position, height, and perimeter of specific elements within an IFC file.

## Installation

To run the script, you'll need to install the IfcOpenShell library. You can install it via pip:

```bash
pip install ifcopenshell
```

## Usage

1. **Setup Environment**: First, make sure you have the IfcOpenShell library installed as per the instructions above.

2. **Accessing IFC Files**: This script is designed to work with Google Colab, but you can adapt it to your local environment. It mounts Google Drive to access the IFC file located in the specified directory.

3. **Running the notebook**: Execute the provided notebook in your Python environment. It will load the specified IFC file and extract information about specific elements within the file.

4. **Viewing Information**: The script demonstrates how to extract various properties of specific elements (e.g., walls) within the IFC file, such as area, volume, position, height, and perimeter.

## About IfcOpenShell

IfcOpenShell is a powerful library for reading and extracting information from IFC files dynamically using Python. This notebook provides a basic demonstration of its capabilities, but the library offers much more functionality. Check out the official [documentation](https://blenderbim.org/docs-python/ifcopenshell-python.html) for more examples and advanced usage.

## Video Tutorial

For a detailed walkthrough of the script and its functionality, refer to the accompanying [video tutorial](https://www.youtube.com/watch?v=QMiwabES8WM).