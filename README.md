<div style="display: flex; justify-content: flex-end;">
   <div style="text-align: center;">
   <img src="ferris_magnifying.jpeg" alt="Ferris the crab with magnifying glass" width="150" />
   <h5><i>image credit: Bing image creator</i></h5>
   </div>
</div>

## What does microBioRust aim to do?
This is a Rust crate package designed for microbial genomics and optimised for functions that are much more common and needed in microbial bioinformatics research.


## What will **NOT** be covered by microBioRust?
Workflows and pipelines for end-to-end bioinformatics solutions - microBioRust is a set of enabling tools.


## Why call it microBioRust?
The idea is to bridge across fields.  other languages are out there such as biopython, biojulia, bioC++, bioruby, biojava, bioperl, biosql, biohaskell, biojs, bioPHP, biocaml, bioMake, bioconductor [R programming language] - contains many different libraries.  There is rust-bio, however, no biorust (it is a company selling flowliner).


### Why would microbes have different requirements for bioinformatics, genetics and genomics studies?
Bacteria are arguably the best studied microbes, their DNA and genes are quite different to ours. a microbiology specific parser would be optimised to handle features in these genomes.  the genomes are far shorter than humans, plants and animals and many thousands of them are sequenced, meaning processing thousands of small text files is a requirement.  we have quite a bit of functional information for the genes and the many genomes are available and stored in alternative formats which need parsing.  this is where rust can really shine compared to existing tools in other languages.  we do not want to duplicate where tools already exist, e.g. fasta file parsing in rust-bio.


## What is microbiology?
Microbiology is the study of microscopic organisms, also known as microbes.  they are usually too small to see.
The idea behind this field of biology is an old one, back from when these small organisms were not understood and were all thought to be related based on their size.  microbes can include Viruses, Bacteria, Archaea (like Bacteria but evolved to be distinct, often live in extreme environments), and small Eukaryotes such as yeasts and fungi.  other microbes include several things you may not have heard that much about, like slime molds, phage, prions, algae and protists.


## What about pyo3 to create python-available functionality?
Python's power in ease-of-use and flexibility is excellent, it would be great to leverage rust interop to enhance accessibility to python users down the line.


## Are you looking for open source contributions?
Definitely!  Please see the microBioRust repo for issues.




