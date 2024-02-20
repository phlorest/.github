# Phlorest - a collection of language phylogenies

Phlorest is a curated collection of [phylogenetic trees](https://en.wikipedia.org/wiki/Phylogenetic_tree) of languages
extracted from published research.

Each Phlorest phylogeny is a [CLDF dataset](https://cldf.clld.org), curated with the help of the [phlorest package](https://github.com/phlorest/phlorest).
The CLDF data (in the `cldf` directory of each phylogeny repositoy) contains
- a summary tree
- a set of trees sampled from a posterior distribution (if available)
- metadata about the languages appearing as tips in the trees.

Tree data is stored using a [CLDF TreeTable](https://github.com/cldf/cldf/tree/master/components/trees), language metadata is stored as [CLDF LanguageTable](https://github.com/cldf/cldf/tree/master/components/languages). (See also https://doi.org/10.5281/zenodo.10684787)

You can propose new phylogenies to be included in Phlorest by [opening an issue](https://github.com/phlorest/.github/issues) at https://github.com/phlorest/.github/issues .
