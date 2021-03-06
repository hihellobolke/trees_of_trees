trees_of_trees
==============

Proposal for Version Control using trees of trees

This method involves the use of Object Identifiers to designate every revision of the software code. The inherent nature of Object Identifier allows individual namespace for every object. This concept allows parallel development and multiple control mechanisms. The software tree thus generated by this method may be visualized or stored as graph of graphs type data structure.  Any node in a graph can be a graph by itself.

In this method every "check-out" of the document basically creates a new "branch/fork" and a new object identifier is associated with the checked out code. Since each "check-out" creates a new "branch" file locking is not required. Each merge also creates a new branch and a new object identifier. The checked-out code based may be visualized as a new child "node" of the parent document node. Multiple parallel checkouts create children who are all siblings. This structure is shown diagrammatically as follows:

![alt tag](https://raw.github.com/hihellobolke/trees_of_trees/master/diag1.png)

For more information read the pdf!
