.. _response:

========
Response
========

Overview
========

.. automodule:: dimod.response

.. currentmodule:: dimod
.. autoclass:: Response
   :members: samples_matrix, data_vectors

Methods
=======

Viewing a Response
------------------

.. autosummary::
   :toctree: generated/

   Response.samples
   Response.data

Constructing or updating a Response
-----------------------------------

.. autosummary::
   :toctree: generated/

   Response.from_dicts
   Response.from_futures
   Response.from_matrix
   Response.from_pandas
   Response.update

Transformations
---------------

.. autosummary::
   :toctree: generated/

   Response.change_vartype
   Response.relabel_variables

Copy
----

.. autosummary::
   :toctree: generated/

   Response.copy

Done
----

.. autosummary::
   :toctree: generated/

   Response.done