# Bla Bla

## What we do
Let's intentionally add a toxic dependency to our dependencies 
and then see how Mend handles this.

Try adding at two levels:
- root-level package.json
- sub-project package.json

## Toxic modules to play with
- "vm2": "^3.9.15",
- "minimist": "1.2.3",
- "handlebars": "4.7.3"

The candidates should:
1. ... have a critical-level vulnerability
2. ... this vulnerability should have a known fox
3. ... this fix library should have the same major version as the vulnerable one

