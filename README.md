# depcopy-cli

This is a command line client Dependencies Copy, useful when you need copy dependencies to a specific directory.

## Getting Started

*  Install with npm: `npm install @foxythemes/depcopy-cli -D`
*  Run it with `depcopy`

### Initial Setup

Create a JSON file named `dep-copy.json` in the root, this file will saved alls dependencies that will be copied.

## Usage

Add the dependencies that you want to copy specifying the destination path.

Example:

```	
  {
    "options": {
      "destPrefix": "src/assets/lib/"
  },
  "name-dependencie":{
    "files": {
      "name-dependencie-dest/scss" : "name-dependencie-orig/scss/*",
      "name-dependencie-dest/dist" : "name-dependencie-orig/dist/*"
      }
    }
  }  

```

In npm scripts:

  depcopy


## License

Copyright (c) FoxyThemes
Licensed under the MIT license.
