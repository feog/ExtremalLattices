# ExtremalLattices
SAGE code to work with extremal lattices: partial dual, theta series, Fincke-Pohst.

The code was written in SAGE 7.3, and then exported in format ipynb to be rendered in Github. The plots are not rendered though.
The main file is ThetaSeries.ipynb, which computes theta series of high dimensional extremal l-modular lattices, using isobaric polynomials.

However, to obtain all of them, we need small dimensional lattices, and for 14- and 15- modular lattices, we need to check that the lattices are strongly modular (use StronglyModular.ipynb), and then we need the theta series of these lattices (use FinckePohst.ipynb).

Then we compute the secrecy gain of lattices using SecrecyGains.ipynb.

Finally one more 11-modular lattice is found (see AlgebraicLattices.ipynb) for one more point of comparison in secrecy gain.

The file LowerBoundonMaxSecGain is a sage notebook, it contains additional computations, namely: a lower bound on the maximum secrecy gain computed by using Siegel's formula. 
