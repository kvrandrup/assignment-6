# assignment-6
Repository for FISH 549 Assignment 6 -- exploring R packages

## Package Title

RTMB

## Location

RTMB can be installed directly with `install.packaged("RTMB")` or through GitHub with `remotes::install_github("https://github.com/kaskr/RTMB", subdir="RTMB")`. 

## Vignettes

This package has both an introduction vignette and an advanced vignette. The advanced vignette goes over my head, even with familiarity to TMB, as it is focued on the `MakeTape` function rather than `MakeADFun`. The introduction vignette gives an overview on the differences between using TMB syntax and RTMB. RTMB requires a familiarity with the use of TMB. 

## Applications

There are no web applications of RTMB that I am aware of. 

## Review

I am personally a huge fan of the RTMB package. The primary purpose of the package is to put TMB operation into a more familiar framework rather than requiring knowledge of c++. I find it much easier to specify my model using R syntax rather than c++ as it is what I am more familiar with. If you are comfortable with R and TMB, this package will be easy to start using. If you have no need to use TMB operation in your models this package will not be of help to you, but if you are someone that needs the background power of TMB but are not comfortable coding in c++, I would highly recommend switching to RTMB. Not only do I believe that his will make your life much easier in the day to day while working on your model, I believe that TMB users are slowly migrating over to RTMB as their primary operation and it is best to keep up with the user base. 

### submission

need to add Mark as a collaborator -- once accepted, tag him in an issue that introduces your assignment and note "I am OK with Mark posting my review to the course website and he can use my name"
