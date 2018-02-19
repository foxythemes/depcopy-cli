# dep-copy-cli

This is a command line client Dependencies Copy, useful when you need copy dependencies to a specific directory.

## Getting Started

*  Install with npm: `npm install @foxythemes/dep-copy-cli`
*  Run it with `depcopy`

### Initial Setup

Create a JSON file named `dep-copy.json` in the root, this file will saved alls dependencies that will be copied.

## Usage

Add the dependencies that you want to copy specifying the origin path and the destination path

```
  
  Example:
	
	"options": {
    "srcPrefix": "node_modules/",
    "destPrefix": "src/assets/lib/"
  },
  "name-dependecie":{
    "files": {
      "name-depencie-dest/scss" : "name-dependencie-orig/scss/*",
      "name-depencie-dest/dist" : "name-dependencie-orig/dist/*"
    }
  }

  In npm scripts:

  	depcopy

```

## License

Copyright (c) Foxythemes
Licensed under the MIT license.