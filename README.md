# calippor
Command Line Pipelines Generator

## Which is the structure of params.js?
The structure is similar to your pipeline arguments.

**value**: default value to the field or null
**label**: text to show over the field
**name**: argument
**abrev**: short argument
**default**: default value
**help**: help text
**required**: true/false,

Example:
{"value": null, "label": "--output_directory", "name": "--output_directory", "abrev": "-d", "default": false, "help": "Directory where all the output files will be generated", "required": true},
