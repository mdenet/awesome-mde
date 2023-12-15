# Awesome MDE [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome model-driven engineering (MDE) resources. Originally set up [@iivanoo](https://github.com/iivanoo)'s [Software and Sustainability Group](https://github.com/S2-group) and transferred to [MDENet](https://www.mde-network.org/) in 2023.

## Contents

- [Books and introductory materials](#books-and-introductory-materials)
- [Tools](#tools)

## Books and introductory materials

### Overview books
- [Domain-Specific Languages: Effective modeling, automation, and reuse](https://dsldesign.bitbucket.io/) - A book by Andrzej Wasowski and Thorsten Berger.
- [Model-Driven Software Engineering in Practice](https://link.springer.com/book/10.1007/978-3-031-02549-5) - This book by Marco Brambilla, Jordi Cabot, and Manuel Wimmer provides a good high-level introduction to the field.
  - [Model-Driven Software Engineering in Practice - Introduction](https://www.slideshare.net/mbrambil/modeldriven-software-engineering-in-practice-chapter-1-introduction) - This presentation gives a good summary of the key ideas.
- [Engineering Modeling Languages – Turning Domain  Knowledge into Tools](http://mdebook.irisa.fr/) - A book by Benoit Combemale, Robert B. France, Jean-Marc Jézéquel, Bernhard Rumpe, Jim Steel, and Didier Vojtisek
- [DSL Engineering](http://voelter.de/dslbook/markusvoelter-dslengineering-1.0.pdf) - A book by Markus Völter giving an overview of different approaches and tools for engineering domain-specific (modelling) languages.

### Papers and presentations
- [Foundations of Model-Driven Software Engineering](https://researcher.watson.ibm.com/researcher/files/zurich-jku/mdse-01.pdf) - A presentation by Jochen Kuster.
- [Matters of (Meta-) Modeling](http://msdl.cs.mcgill.ca/people/hv/teaching/MSBDesign/MattersOfMetaModelling.pdf) - A paper by Thomas Kuhne.
- [Model-driven engineering](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.106.9720&rep=rep1&type=pdf) - A paper by D.C. Schimdt.
- [Generative Software Engineering](https://www.se-rwth.de/research/Generative-SE/) - A report by Bernhard Rumpe et al.
- [Domain-Specific Modelling Languages: the need for Modelling Language Engineering](http://msdl.cs.mcgill.ca/people/hv/teaching/MSBDesign/presentations/presentation.ModellingLanguageEngineering.pdf) - A presentation by Hans Vangheluwe.
- [Modelling Languages: (mostly) Concrete (Visual) Syntax](http://msdl.cs.mcgill.ca/people/hv/teaching/MSBDesign/presentations/presentation.DSM-TP.DSLengineering.semantics.pdf) - A presentation by Hans Vangheluwe.
- [Domain-Specific Languages](https://www.slideshare.net/zirrus/domainspecific-langauges) - A presentation by Javier Canovas.
- [Real world DSL - making technical and business people speaking the same language](https://www.slideshare.net/mariofusco/real-world-dsl) - A presentation by Mario Fusco.
- [Domain-Specific Languages: Effective modeling, automation, and reuse](http://dsl.design) - A book by Andrzej Wasowski and Thorsten Berger.
- [Domain-Specific Languages in Practice with JetBrains MPS](https://link.springer.com/book/10.1007%2F978-3-030-73758-0) - An edited volume with different contributions about the JetBrains MPS tool.
- [Globalizing Domain-Specific Languages](https://www.se-rwth.de/publications/Globalizing-Domain-Specific-Languages2.pdf) - A report by B. H. C. Cheng, B. Combemale, R. B. France, J.- M. Jézéquel, B. Rumpe.
- [Design Guidelines for Domain Specific Languages](https://www.se-rwth.de/publications/A-Methodology-for-Retrofitting-Generative-Aspects-in-Existing-Applications.pdf) - A report by G. Karsai, H. Krahn, C. Pinkernell, B. Rumpe, M. Schindler, S. Völkel.
- [Model Transformation](http://msdl.cs.mcgill.ca/people/hv/teaching/MSBDesign/ModelTransformation.pdf) - A presentation by Eugene Syriani and Hans Vangheluwe.
- [Explicitly Modeling Transformations](http://homepages.mcs.vuw.ac.nz/~tk/publications/papers/explicitly-modeling-transformations.pdf) - A paper by Thomas Kuhne, Gergely Mezei, Eugene Syriani, Hans Vangheluwe and Manuel Wimmer.
- [Road to a reactive and incremental model transformation platform: three generations of the VIATRA framework](https://www.researchgate.net/publication/303090660_Road_to_a_reactive_and_incremental_model_transformation_platform_three_generations_of_the_VIATRA_framework) - A paper by Daniel Varro, Gabor Bergmann, Abel Hegedus, Akos Horvath, Istvan Rath and Zoltan Ujhelyi.

## Tools

Below, we list awesome tools for doing MDE. The classification of contributions below is inspired by the MDE Body of Knowledge [[1](https://doi.org/10.1145/3270112.3270121),[2](https://doi.org/10.1007/s10270-019-00746-9)].

- Modeling Languages
  - Language definition
    - Syntax
      - Metamodels
        - [Eclipse Modelling Framework (EMF)](https://www.eclipse.org/modeling/emf/) - The foundational meta-modelling framework in the Eclipse technical space. Used to define meta-models, from which full modelling languages can be built.
          - [EMF Tutorial](https://www.vogella.com/tutorials/EclipseEMF/article.html) - A very good tutorial by Lars Vogel.
          - [EcoreTools](https://www.eclipse.org/ecoretools/) - A graphical editor for creating and managing EMF meta-models.
          - [Emfatic](https://eclipse.org/emfatic) - Textual syntax for Ecore (EMF's meta-modelling language).
        - [metaDepth](http://metadepth.org/) - A metamodelling tool following the multi-level modelling approach.
      - Textual
        - [Xtext](https://www.eclipse.org/Xtext) - A language workbench for creating textual modelling languages and modelling tools.
          - [Xtext 15-minute tutorial](https://www.eclipse.org/Xtext/documentation/102_domainmodelwalkthrough.html) - A short tutorial to get started with Xtext.
        - [MontiCore](https://monticore.github.io/monticore/) - A language workbench for textual languages.
        - [Flexmi](https://eclipse.org/epsilon/flexmi) - Reflective textual syntax for EMF-based models, with XML and YAML flavours.
      - Projectional
        - [Jetbrains MPS](https://www.jetbrains.com/mps/) - A language workbench for projectional languages.
      - Graphical
        - [Sirius](https://www.eclipse.org/sirius/getstarted.html) - A visual language engineering framework.
      - Multi-view modelling
        - [AToMPM](https://atompm.github.io) - A tool for Multi-Paradigm Modeling.
    - Semantics.
      - [GEMOC](https://gemoc.org/studio.html) - A language workbench for modeling language design, implementation and coordination. Especially provides support for executable DSMLs through engines that can execute explicitly specified language semantics.
  - Types of modeling languages
    - General purpose (GPL): UML+OCL, SysML
      - [Papyrus](https://www.eclipse.org/papyrus/) - An open-source UML modelling tool.
    - Domain-specific (DSL): UML Profiles, ADLs, etc
- Model Transformations
  - Model transformation
    - Languages / engines
      - Model-to-model transformation languages
        - [ATL](https://www.eclipse.org/atl/) - An efficient rule-based model transformation language.
        - [Epsilon Transformation Language (ETL)](https://www.eclipse.org/epsilon/doc/etl/) - A hybrid model transformation language. 
        - [MOF Query/View/Transformation (QVT)](https://www.omg.org/spec/QVT/About-QVT/) - The OMG standard for model transformation.
        - [VIATRA - VIsual Automated model TRAnsformations](https://www.eclipse.org/viatra/documentation/tutorial.html) - A tutorial about the VIATRA tool.
        - [The Janus Transformation Language (JTL)](https://jtl.univaq.it/) - Another transformation language.
        - [MoTE - TGG-based Model Transformation Engine](https://www.hpi.uni-potsdam.de/giese/public/mdelab/mdelab-projects/mote-a-tgg-based-model-transformation-engine/) - A graph-transformation based model transformation tool.
        - [Henshin - Graph Transformation Language](https://projects.eclipse.org/projects/modeling.emft.henshin) - A graph-transformation based model transformation tool.
      - Model-to-text transformation languages.
        - [Epsilon Generation Language (EGL)](https://eclipse.org/doc/egl) - A language and tool for model-to-text transformation (aka code generation).
  - Model transformation applications
    - Model differencing and merging
      - [EMFCompare](https://www.slideshare.net/mikaelbarbero/diff-and-merge-with-ease-with-emf-compare) - A tool for comparing models.
        - [Comparison and merge use-cases from practice with EMFCompare](https://youtu.be/Uwq7W7jEdUU) - A tutorial on EMFCompare.
    - Model optimisation / design space exploration. These are tools for searching for optimal models or transformations.
      - [MoMOT](http://martin-fleck.github.io/momot/) - A transformation based optimisation tool.
      - [MDEOptimiser](https://mde-optimiser.github.io/) - A model-based optimisation tool.
      - [Viatra DSE](https://wiki.eclipse.org/VIATRA/DSE) - A transformation based optimisation tool in the ViATRA suite of tools.
    - Model evolution/migration
      - [Edelta](https://github.com/LorenzoBettini/edelta) - A Metamodel Evolution Tool including a textual DSL for model refactoring.
- Model Visualization
  - Layout
    - [Eclipse Layout Kernel (ELK)](https://www.eclipse.org/elk/) - Automatic layout of diagrams.
  - Rendering
    - [Picto](https://eclipse.org/epsilon/doc/picto) - Model visualisation through lazy model-to-text transformation to HTML, Graphviz and PlantUML.
- Model Analysis
  - Structural model analysis
    - Invariant checking
      - [Epsilon Validation Language (EVL)](https://eclipse.org/epsilon/doc/evl) - A language and tool for validating models.
    - Instance generation
    - Metrics calculation
    - Smells detection
  - Behavioural model analysis
    - Pre-postcondition checking
    - Simulation
    - Reachability analysis
    - Temporal model checking
    - Performance
  - Model transformation analysis
    - Correctness (of transformed models, in syntax and semantics)
    - Completeness
    - Functional behaviour (termination, confluence)
    - Performance
- Other
  - Complete Model Management Framework
    - [Epsilon](https://www.eclipse.org/epsilon/) - A set of languages and tools for a wide variety of model-management tasks.
  - Learning Modeling through Gamification
    - [PapyGame](https://www.papygame.com/) - A gamified approach to learning UML and other modelling tools.
      - [Gamification Rule Language - A DSL for gamification rules](https://github.com/antbucc/GRL) - A tool by Antonio Bucchiarone and Stefano Martella.
