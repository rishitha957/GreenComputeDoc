Towards Analysing Energy Trends of Source Code

### What is GreenCompute?
GreenCompute is tool, that traverses the source code sections with BFS - (Breadth First Seach), Intel Gadget API, Python (PSutil)

### Features of GreenCompute
Breadth-first search algorithm for traversing a source code repesented as an Abstract Syntax Tree to compute the CPU Utilization of each node (code snippet)

Help developers identify critical energy inefficient areas in source code.

### Uses of GreenCompute
Energy inefiicient code snipptes are discouraged from being written in further software developments.

To help developers mitigate the usage of energy consuming code during new software developments, the developer must be aware of the usage of inefficent APIs and / or code in the project.

With the help of GreenCompute developers can identify the energy consuption in the development phase.

### Working of GreenCompute
The approach followed by GreenCompute is summarized below:

In the current trend we parse the source code with Breadth First Search Alogorithm and we have a tree structure ready.

We then parse the soure code of library to generate Abstract Syntax Tree.

We then extract the CPU utilization metrics of the code snipptes by using Intel Gadget API and Python Psutil API.

GreenCompute, now visually represents the energy trends of our code

### Future of GreenCompute


