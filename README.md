# Interpreting Verbal Irony

This repository represents the code as well as the datasets (e.g., input, annotations, etc.) used in the interpreting verbal irony research. Please check the input jsonlines file **sarcasm_twitter_rte_separate.jsonlines**. 

The input file has the following members.
- serial number (**snum**) appended with ''-i'', where **i** denotes the ith rephrases 
- sarcastic messages (**sarcasm_message**)
- intended (literal) rephrases from the Turkers (**literal_message**). Also appended with the "-i" 
- the nature of incongruity (i.e., explicit or implicit) as annotated (see the paper).

If you use the dataset please cite the following paper,

@inproceedings{ghosh-etal-2020-interpreting,
    title = "Interpreting Verbal Irony: Linguistic Strategies and the Connection to the{T}ype of Semantic Incongruity",
    author = "Ghosh, Debanjan  and
      Musi, Elena  and
      Upasani, Kartikeya and
      Muresan, Smaranda",
    booktitle = "Proceedings of the Society for Computation in Linguistics 2020",
    month = jan,
    year = "2020",
    address = "New York, New York",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.scil-1.10",
    pages = "82--93",
}

