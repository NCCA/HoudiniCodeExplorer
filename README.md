# Houdini Code Explorer

This is a houdini shelf tool to view the python code used to create houdini nodes. It is useful for understanding how nodes are created and when developing your own tools. 

![](images/Explorer.png)

## Installation

To install this tool first clone this repository into a folder of you choice. This will be the installation location for the tool and must not be deleted.

```bash
git clone https://github.com/NCCA/HoudiniCodeExplorer
```

The package is installed using the houdini hython interpretor so you need to ensure it is active before running the installation. Either open the houdini shell or change to the houdini directory and source the houdini setup script (for example in linux).

```bash
cd /opt/hfs21.0.559/
source setup_houdini_bash
```

Once the houdini environment is active you can install the package by running the following command from the HoudiniCodeExplorer directory:

```bash
./installHouPackage.py
```

This should report output similar to the following:

```
./installHouPackage.py 
{
  "load_package_once": "true",
  "env": [
    {
      "PYTHONPATH": "/home/jmacey/HoudiniCodeExplorer"
    }
  ]
}

 Shelf file created at: /home/jmacey/houdini21.0/toolbar/codeexplorer.shelf
  Contains 1 tools:
    - Code Explorer
```

## Houdini Shelf

You can now find the shelf by clicking on the shelf + icon in the toolbar and selecting "Code Explorer"
