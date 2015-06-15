# introduction-to-r-one-day-workshop

# Install R and R Studio
These instructions assume that you have already installed R and RStudio.

R: http://cran.rstudio.com/
Rstudio: http://www.rstudio.com/products/RStudio/

# Windows Operating
If you use Windows, download and install RTools for Windows.
Choose a version that matches your version of R (you can see this when you start
R Studio). 

http://cran.r-project.org/bin/windows/Rtools

# Mac OSX
If you use Mac OSX download and install XQuartz http://xquartz.macosforge.org/landing/

# All operating systems
Open R Studio and paste the following text into the console. This should take
several minutes to complete. Don't worry if the odd package doesn't 
install.

    install.packages("knitr", dep = T)
    install.packages("ProjectTemplate", dep = T)
    install.packages("MASS", dep = T)
    install.packages("psych", dep = T)
    install.packages("stringr", dep = T)
    install.packages("gdata", dep = T)
    install.packages("gtools", dep = T)
    install.packages("xtable", dep = T)
    install.packages("GPArotation", dep = T)
    install.packages("nFactors", dep = T)
    install.packages("vegan", dep = T)
    install.packages("digest", dep = T)
    install.packages("xlsx", dep = T)
    install.packages("readxl", dep = T)
    install.packages("foreign", dep = T)
    install.packages("lattice", dep = T)
    install.packages("ggplot2", dep = T)
    install.packages("lme4", dep = T)
    install.packages("QuantPsyc", dep = T)
    install.packages("sem", dep = T)
    install.packages("lavaan", dep = T)
    install.packages("metafor", dep = T)
    install.packages("boot", dep = T)
    install.packages("car", dep = T)
    install.packages("AER", dep = T)
    install.packages("devtools", dep = T)
    install.packages("DAAG", dep = T)
    install.packages("plyr", dep = T)
    install.packages("tidyr", dep = T)
    install.packages("dplyr", dep = T)
    install.packages("GGally", dep = T)
    install.packages("Rcmdr", dep = T)
    install.packages("lmtest", dep = T)
    install.packages("markdown", dep = T)
    install.packages("bootstrap", dep = T)
    install.packages("hypergeo", dep = T)
    install.packages("Hmisc", dep = T)
    install.packages("lmSupport", dep = T)
    install.packages("perturb", dep = T)
    install.packages("CTT", dep = T)

    library(devtools)
    install_github('jeromyanglim/personalityfacets')
    install_github('leeper/rio')


# R Commander
In the workshop, I will demonstrate the program R Commander.

You can check that the installation above worked by typing the following into the console.

    library(Rcmdr)

You should get an additional R Commander window pop up with menus like Graphs,
Models, etc.

If it does not work, then you may wish to read the installation notes to see
what additional software you may need to install:

http://socserv.mcmaster.ca/jfox/Misc/Rcmdr/installation-notes.html


# Some very optional installations
We will also be using several packages that may require some additional
installation.
 

# Perl
If you are on Windows, there is one function in the Workshop that requires that
you have Perl installed.
https://www.perl.org/get.html

# Mac OSX Operating System
It's probably not required, but you may find it useful to have XCode installed.
http://developer.apple.com/xcode

# Java
If it's not on your system already, you may also wish to install Java.

http://www.oracle.com/technetwork/java/javase/downloads/index.html
 

# LaTeX
I will give a demonstration of using LaTeX with R. If you are particularly
interested in the LaTeX document system, then you probably already have it
installed on your computer. If you've never heard of it, then you probably
shouldn't worry about installing it at this point, but if you are curious and
wish to install it, go to:

http://latex-project.org/ftp.html

Be warned, it is a big download (more than a gigabyte).


