
eclib
=====

The eclib package includes mwrank (for 2-descent on elliptic
curves over Q) and modular symbol code used to create the
elliptic curve database available in sage.

There are three main programs for elliptic cuves in this
distribution:

- mwrank
- point_search
- quartic_points


mwrank
------

To use mwrank, type `mwrank` in the terminal. You will see

    Enter curve:

There are two input formats for curves:

    # Note that there are no spaces
    [a1,a2,a3,a4,a6]
    # or (with spaces)
    a1 a2 a3 a4 a6

Any invalid input causes the program to stop.


point_search
------------

Point search will look for points on elliptic curves up to a
given height. Type `point_search` to begin the program. It
will ask for a series of inputs.

- (real) bound on naive height
- (int) verbosity flag
- (int) option (1) process points found (2) just list #
- (list of ints or rationals) [a1,a2,a3,a4,a6] (or a1 #
- (int) Number of points on the curve to be input (usu#
- (int) Rank bound (serach stops when this is reached)
- (list of triples of ints) known points as [x:y:z] wi#
