# Створення власних вузлів ([Creating Nodes](https://nodered.org/docs/creating-nodes/))

## Створення першого вузлу 

# Example flows

A packaged node can provide simple example flows that demonstrate how it can be used.

They will appear under the Examples section of the library import menu.

Ideally they should be short, have a comment node to describe the functionality, and not use any other 3rd party nodes that need to be installed.

To create an example, add a flow file to an `examples` directory in your node package. See [Packaging](https://nodered.org/docs/creating-nodes/packaging) for more details.

The name of the flow file will be the menu entry displayed in the menu list. For example:

```
examples\My Great Example.json
```

will display as

```
My Great Example
```