# A Shlaer-Mellor Metamodel created and managed by Leon Starr

Shlaer-Mellor (SM) is a well defined set of execution semantics predating the UML (Unified Modeling Language).
UML is standard graphical notation that, among others, can be used to visualze SM semantics.

These modeling semantics also go under the name: Shlaer-Mellor Executable UML (xUML).

The semantics are described in a book titled [Executable UML: A Foundation for Model Driven Architecture](https://github.com/modelint/shlaer-mellor-metamodel/wiki/Resources).

The goal of this repository is to pull together and document (see [wiki](https://github.com/modelint/shlaer-mellor-metamodel/wiki)) an open source, tool-independent metamodel of the SM semantics.

Feel free to post questions and comments in the [discussions](https://github.com/modelint/shlaer-mellor-metamodel/discussions) section.

[Blueprint MBSE](https://github.com/modelint/blueprint) is an open source ecosystem of python modules centered on this metamodel.

I am using the [flatland diagram generator](https://github.com/modelint/flatland-model-diagram-editor) to produce all of the model diagrams.

A subsubset of these models is now implemented in the Blueprint [makexumlrepo](https://github.com/modelint/make-xuml-repo) module. These are the models that actually work and support model execution. Small tweaks have been made to ensure they
work correctly. Eventually we will bring both those models and the more expansive
set here in this repository in line as single cohesive set. (Or at least hit the
perpetual 99% mark!)

*I think we're at about 80% at the moment - LS 26-7-29*

So if you want to see the working implementation of the models, please see the **makexumlrepo** [model subset](https://github.com/modelint/make-xuml-repo/tree/main/src/make_xuml_repo/metamodel) here.

But if you want to see the entire expanse of what will ultimately be incoporated into the full model repo and want to see full definitions, documentation, resources and such, you've come to the right place.