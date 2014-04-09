Introduction to the Actor Model of Computation
==============================================

This repository hosts slides and code for a brief introduction to the
Actor Model of Computation.


Slides
------

The slides are generated from the IPython notebook
`Introduction.ipynb`_ (it can be viewed online, but needs to run to
generate the HTML slides).

Code
----

The module that implements a minimal actor language is `tartpy`_.  The
examples and instructions to install are in the IPython notebook `Examples.ipynb`_.

References
----------

This is a list of references mentioned in the slides and examples,
plus some other miscellanea material, in no order, with some comments.

+ **Gul Agha**. *Actors: A Model of Concurrent Computation in 
  Distributed Systems*. Doctoral Dissertation. 1986.
    
  A comprehensive book with good details on patterns. It discusses an
  operational model.

+ **Gul Agha, Ian Mason, Scott Smith, Carolyn Talcott**. *A Foundation
  for Actor Computation*. Journal of Functional Programming,
  January 1993.

  More mathematical, but good discussions on configurations and
  composability.

+ **Carl Hewitt, Peter Bishop and Richard Steiger**. *A Universal
  Modular Actor Formalism for Artificial Intelligence*. IJCAI’73.

+ **Carl Hewitt**. *Actor Model of Computation: Scalable Robust
  Information Systems*. Inconsistency Robustness 2011, Stanford
  University.

  A good overview of many topics, including a very big list of
  references (which is a superset of this list).


.. _Introduction.ipynb: http://nbviewer.ipython.org/github/waltermoreira/actor_model/tree/master/Introduction.ipynb
.. _tartpy: https://github.com/waltermoreira/tartpy
.. _Examples.ipynb: http://nbviewer.ipython.org/github/waltermoreira/actor_model/tree/master/Examples.ipynb
