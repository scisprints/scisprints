Upcoming
========

[22, 23 Nov 2019] NumPy developer sprint
----------------------------------------

Several NumPy core developers, the BIDS NumPy staff, and possibly some
of the documentation team will be meeting to:

-  refresh the NumPy roadmap
-  discuss DuckArray protocol/dispatching
-  review the dtype refactoring
-  revamp the MacPython/numpy-wheels repo
-  work on reviewing/closing PRs and issues.

and more.

**Notes**: https://github.com/numpy/archive/blob/master/sprints/2019-11-22.md

**Location**: Berkeley Institute for Data Science

[15 Oct 2019] NumPy “Spring Cleaning” sprint
--------------------------------------------

At this virtual sprint, we will close as many PRs and issues as we can.

Past Sprints
============

[10, 11 May 2019] NumPy developer sprint
----------------------------------------

`Meeting
notes <https://github.com/BIDS-numpy/docs/blob/master/meetings/2019-05-10_dev_meetup.md>`__

Several NumPy core developers will be meeting to review the new random
number generation system API, plan the dtype refactoring, and work on
reviewing/closing PRs and issues.

**Agenda**: https://hackmd.io/OtUbEI_4T06noPYtlLp-4w

**Location**: Berkeley Institute for Data Science

[30 Nov, 1 Dec 2018] NumPy developer sprint
-------------------------------------------

`Meeting
notes <https://github.com/BIDS-numpy/docs/blob/master/meetings/2018-11-30-dev-meeting.md>`__

We met and discussed NumPy’s roadmap, low-level NumPy-like libraries,
data type refactoring, and type annotations.

[28 May–2 June 2018] Joint scikit-learn, scikit-image, dask sprint
------------------------------------------------------------------

scikit-learn and scikit-image are two of the major scientific Python
toolbox, enabling data-driven discoveries. The first one proposes simple
yet efficient tools for data mining and data analysis, while the latter
focuses on image processing algorithms. With the flow of data being
processed and analysed, these two libraries face unprecedent scalability
challenges.

One currently under-utilized avenue for solving such scalability
challenge is to leverage the Python library Dask, which provides
flexible parallelized NumPy and Pandas DataFrame, the core numerical
objects used in Scientific Python. Our goal is thus to organize a sprint
bringing together a small number of developers from scikit-learn,
scikit-image, and Dask to experiment and improve the three libraries.

**Repository for ideas**:
`https://github.com/scisprints/2018_05_sklearn_skimage_dask <https://github.com/scisprints/2018_05_sklearn_skimage_dask/issues>`__

**Dates**: May, 28th to June 2nd, 2018

**Location**: Monday: Evans, Tue–Fri: `Berkeley Institute for Data
Science <bids.html>`__

[24, 25 May 2018] NumPy developer sprint
----------------------------------------

NumPy is the fundamental numerical package for scientific computing in
Python. It is a Python library that provides a multidimensional array
object, and an assortment of routines for fast operations on arrays.
While useful on its own, the array object is the core data structure for
many packages in the Python landscape, including Pandas, OpenCV’s python
bindings, and deep learning frameworks such as TensorFlow and PyTorch.

NumPy is managed by a steering committee, and run by a group of
developers who rarely meet in person. The stars have aligned, and a
group of the steering committee/core developers will be in Berkeley for
two days.

We will discuss and maybe even resolve some of the thornier open pull
requests and issues, set some short term goals, and better define deeper
issues that need more community input.

**Dates**: May 24-25, 2018 **Location**: Berkeley Institute for Data
Science

[29 - 30 March, 2018] Matplotlib/GraphXD sprint
-----------------------------------------------

Visualizing the structure of graphs is informative when doing network
analysis, but currently is not well supported by scientific Python
tools. NetworkX is the community standard for representing and analyzing
graphs and, while capable of simple visualization, historically has not
emphasized this feature in order to avoid additional maintenance burden.
Matplotlib, on the other hand, is the predominant plotting library in
the Python ecosystem, but has no official support for graph structures.

At `GraphXD <https://graphxd.github.io/workshop/2018.html%3E>`__ we have
brought together core members of the NetworkX and Matplotlib
communities. At the event sprints, we will work together to improve the
state of graph visualization in Python. Specifically, we aim to:

-  build a small library in Python that utilizes Matplotlib and NetworkX
   for visualizing graph structures, and
-  factor out the visualization components of NetworkX into this new
   library, such that the analytics features of NetworkX remain
   separate.

We plan for this package to continue growing beyond the GraphXD sprint,
and to become a community standard in visualizing graphs with Python.

**Dates**: March, 28th and 29th, 2018 **Location**: Berkeley Institute
for Data Science

[21–22 March 2018] NumPy Enhancement Proposal sprint
----------------------------------------------------

-  `NEP 17 — Split Out Masked
   Arrays <https://numpy.org/neps/nep-0017-split-out-maskedarray.html>`__
-  `NEP 18 — A dispatch mechanism for NumPy’s high level array
   functions <https://numpy.org/neps/nep-0018-array-function-protocol.html>`__
-  `NEP 19 — Random Number Generator
   Policy <https://numpy.org/neps/nep-0019-rng-policy.html>`__
-  `NEP 22 — Duck typing for NumPy arrays – high level
   overview <https://numpy.org/neps/nep-0022-ndarray-duck-typing-overview.html>`__
