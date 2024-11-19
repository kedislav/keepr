# Pentesting Inventory Management Made Easy

`keepr` aims to simplify the bookkeeping aspect of pentesting, and centralize it into a simple YAML file you can easily read, edit and share.

## Functionality

`keepr` works with a set of subcommands;

- `init <name> [description]`: initializes an inventory with an optional description.
- `add <name>[/<target>]`: add a target into the inventory file.
- `show <name>[/<target>]`: show information about the inventory or a specific target.

## To-Do:

`keepr` will implement the functionality to:

- `import`: import your `nmap` scan exports or other scan files for easy inventory tracking.
- `visualize`: visualize your inventory and all of the targets inside it in your web-browser via a graph.
