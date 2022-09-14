# iograft Rename Files Demo

This repository provides an iograft graph that demonstrates how iograft could be used to automate the renaming of files.

The graph uses ONLY the built-in nodes that come with iograft (as of version 1.3.2), and this repository contains some example image files that are used for the example graph (in the "files" directory).

## Running the Demo

In order to run this demo, first clone or download the repository. Then open the "rename_files.iog" graph file in iograft.

The only value that needs to be set on the graph in order to execute is the `image_directory` graph input. Set this to the "files" directory of this cloned/downloaded repository.

Once the graph is executed, renamed files will be generated in the "renamed" subdirectory of the "files" directory.

Some things to experiment with are:
- Change the `new_name_format` graph input to execute a different renaming.
- Change the `file_expression` graph input to rename a different set of images.
- Run the graph on your own set of images (you will likely need to update the `input_name_format` and `new_name_format` inputs!)
