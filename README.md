
#  DataOpticon 2020: R Package Validation 

Author: Ellis Hughes

twitter: @ellis_hughes

<!-- badges: start -->
<!-- badges: end -->

This is the respository for the DataOpticon 2020 presentation `R Package Validation`.


[Slides](https://thebioengineer.github.io/dataOpticon_2020)

[Sample Package](https://www.github.com/thebioengineer/dataOpticon_2020/sample_package/ValidateMe)


The focus of this presentation is to present an approach to simplify the process of validation of R packages. 
My motivation and development of this approach comes from developing an internal package that needed validation.
The current process required at least three word documents that needed to be updated, approved, and version at every step.
If anything changed, most everything had to be rewritten. 
In addition, by separating the validation process from the package development, duplication of effort was rampant. 

In an effort to reduce overhead and increase speed of development, I distilled the elements required of validation and reproduced it as part of the package development process.

Using packages that are already instrumental in modern package development, users can create all the documention necessary for a validation:

- Rmarkdown is used to write out the specifications, test cases, and generate the final validation document.
- Roxygen2 is used to track authorship and ownership of specifications, functions, test cases, and test case code.
- testthat is used to exectute the test case code and record results

I would like to thank my team at Fred Hutch for helping develop this idea and the code to generate the validation.
  - Marie Vendettuoli
  - Anthony Williams
  - Jimmy Fulp 
  - Bharathi Lakshminarayanan
  - Rafael Kuttner
  - Alicia Sato
  - Shannon Grant
  - Paul Stutzman
  - Kate Ostbye


