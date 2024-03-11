
# Nodezator's system testing and its test cases

This repository is part of the [software design document](https://github.com/IndiePython/nodezator-sdd) for the Nodezator app ([repository](https://github.com/IndiePython/nodezator) | [website](https://nodezator.com)). It is used to help manage system testing for Nodezator and to document its test cases.

It consists of a few main documents and several test case documents. Here's a list of the types of such documents and their purposes:

- 01 `README.md` file (this one you are reading), that serves as a table of contents
- 01 [how-to.md](how-to.md) file, that explains how to organize/manage system testing
- 01 `test-cases` folder used to store:
    - 01 [stc-xxxx.md](test-cases/stc-xxxx.md) file (a template for test case files)
    - several test case documents (`stc-0000.md`, `stc-0001.md`, etc.)

The main table below lists and links all existing test case files in use. If one of the existing tests is removed, a second table to list removed tests should be placed right after the one below. This list of removed tests in the second table is needed so we can keep track of existing UIDs from them and don't accidentally reuse such UIDs.


| UID  | Title |
| ---- | --- |
| [0000](test-cases/stc-0000.md) | Instantiate default objects using the popup menu |
