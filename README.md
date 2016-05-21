# LDAOpt
LDA using Gibbs sampling with hyperparameter optimization based on [Minka's fixed-point iteration](http://www.msr-waypoint.com/en-us/um/people/minka/papers/dirichlet/minka-dirichlet.pdf) (Equation 55).
The code is a modified version of [GibbsLDA++](http://gibbslda.sourceforge.net/), 
a LDA implementation in C++.

## Usage
The usage is the same as in the original implementation of GibbsLDA++, 
except for alpha and beta values which are not parameters anymore. 
A detailed GibbsLDA++'s usage description can be found on its website under the **Usage** tab.

## Additional Dependencies
[GNU Scientific Library](https://www.gnu.org/software/gsl/)
