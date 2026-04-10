# Commencement

Previous versions of *ANTLR* possessed the capability of automatically generating *ASTs* from input files. However, in its latest version (that is version 4, at the time of writing this documentation), this automatic generation feature no longer exists. Fortunately, *ANTLRv4* provides the necessary tools to build our own *AST* generator. The techniques used to achieve these syntax trees are detailed in this chapter.

## Updating the Grammar & Tree Walking

For implementing the *AST* generation, we will be leveraging the tree-walking feature of *ANTLR*. To properly make use of this feature, it will be necessary to first update our DFM grammar, clean up all generated files and re-generate everything.

--TBC