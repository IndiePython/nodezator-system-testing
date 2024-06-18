
# Nodezator's system testing and its test cases

This repository is part of the [software design document](https://github.com/IndiePython/nodezator-sdd) for the Nodezator app ([repository](https://github.com/IndiePython/nodezator) | [website](https://nodezator.com)). It is used to help manage system testing for Nodezator and to document its test cases.

It consists of a few main documents and several test case documents. Here's a list of the types of such documents and their purposes:

- 01 `README.md` file (this one you are reading), that serves as a table of contents
- 01 [how-to.md](how-to.md) file, that explains how to organize/manage system testing
- 01 `test-cases` folder used to store:
    - 01 [stc-xxxx.md](test-cases/stc-xxxx.md) file (a template for test case documents)
    - several test case documents (`stc-0000.md`, `stc-0001.md`, etc.)


## Test cases: implemented, pending implementation or removed ones

In this section we list test cases. It should contain at least the first of these tables:

- a table listing all test cases implemented, with links to the respective test case documents
- a table listing test cases to be implemented, either soon or eventually
- a table listing removed test cases, so we can keep track of the used UIDs in order not to reuse them

The categories used are loose and arbitrary, for the sole purpose of grouping test cases with common aspects.


### Implemented test cases


| UID | Category | Title |
| --- | --- | --- |
| [0000](test-cases/stc-0000.md) | Instantiation | Instantiate default objects using the context menu |
| [0001](test-cases/stc-0001.md) | Deletion | Delete objects via context menu |
| [0002](test-cases/stc-0002.md) | Selection | Select objects via mouse clicks |
| [0003](test-cases/stc-0003.md) | Selection | Select objects via mouse's box selection |
| [0004](test-cases/stc-0004.md) | Selection | Select objects via keyboard's "select all" operation |
| [0005](test-cases/stc-0005.md) | Selection | Deselect objects by clicking them |
| [0006](test-cases/stc-0006.md) | Selection | Deselect objects by clicking the canvas |
| [0007](test-cases/stc-0007.md) | Selection | Deselect objects via mouse's box selection |
| [0008](test-cases/stc-0008.md) | Selection | Deselect objects via keyboard's "deselect all" operation |
| [0009](test-cases/stc-0009.md) | Deletion | Delete objects via click-selection + key |
| [0010](test-cases/stc-0010.md) | Deletion | Delete objects via box selection + key |
| [0011](test-cases/stc-0011.md) | Deletion | Delete objects via keyboard's "select all" operation + key |


### Planned test cases


| Category | Title |
| --- | --- |
| Connection | Connect a node to another |
| Connection | Connect multiple outputs from a node to other nodes |
| Disconnection | Sever connection between nodes via mouse dragging |
| Disconnection | Sever connection between nodes via output socket context menu |
| Disconnection | Sever connection between nodes via input socket context menu |
| Cycle prevention | Connection forming cycle isn't allowed |
| Graph execution | Execute the graph |
| Graph execution | Execute the graph with a custom standard output stream |
| Variable parameters | Add arguments to a node's positional-variable parameter by creating widgets |
| Variable parameters | Add arguments to a node's positional-variable parameter via connections |
| Variable parameters | Add arguments to a node's positional-variable parameter via widgets and connections |
| Variable parameters | Add arguments to a node's keyword-variable parameter by creating widgets |
| Variable parameters | Add arguments to a node's keyword-variable parameter via connections |
| Variable parameters | Add arguments to a node's keyword-variable parameter via widgets and connections |
| Mode switching | Change node's mode from signature to callable mode |
| Mode switching | Change node's mode from callable to signature mode |
| Mode switching | Change node's mode from expanded to collapsed mode |
| Mode switching | Change node's mode from collapsed to expanded mode |
| Python exporting | Export node layout as equivalent Python code |
