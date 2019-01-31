https://github.com/kumc-bmi/heron-i2b2-analytics

This repository includes information and programs on a new
direct access model for electronic data stored in an i2b2
database.

This repository has a directory structure loosely based on 
the recommendations in

Wilson et al. Good Enough Practices in Statistical Computing. 
PLoS Comput Biol 13(6): e1005510.

The src folder contains source code for programs in this
repository.

The results folder contains output files produced by programs
in this repository.

The doc folder contains program documentation, informational
handouts, and publications/presentations related to this work.

If you are relatively new to databases, first take a look at 
open_oracle.Rmd. It shows the code needed to get you started.

extract_diabetes_patient_numbers.Rmd shows how to select patients
meeting certain inclusion criteria. It uses diabetes diagnosis
codes as an example.

apply_exclusion.Rmd shows how to take a list of patients
and apply exclusion criteria to get a narrower list.

create_sparse_matrix.Rmd is under development.

explore_hierarchy.Rmd is under development.

extract_medications.Rmd is under development.

extract_using_dbplyr.Rmd is under development.

There are some presentations in the doc folder. These use
ioslides, a presentation system built on top of html and css.
Just double click on the appropriate html file to start the
slide show. There are speaker notes, and you can display 
these by appending ?presentme=true to the end of the url.
See section 4.1.9 of 

https://bookdown.org/yihui/rmarkdown/ioslides-presentation.html

for more details. The presetnations are

mining.html in the doc/mining-talk folder. I gave this
presentation at the April 2018 Frontiers in Biostatistcis
conference. It gives a general overview of how and why you
might want to undertake a data mining project using the
EHR data in i2b2.

searching.html in the doc/searching-talk folder. This
is a very introductory overview on how to identify
records in i2b2 that involve the medication Tamoxifen.

encounters.html is under development.

Note that I am starting a bibliography of key references
in the key-references.bibtex file in the doc folder.
