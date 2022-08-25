Usage
=====

.. _installation:

Installation
------------

To use PYFBAS, first install it using pip:

.. code-block:: console

   (.venv) $ pip install pyfbad

Importing Libraries
----------------

.. code-block:: console
   
   from pyfbad.data import database as db
   from pyfbad.features import create_feature as cf
   from pyfbad.models import models as md
   from pyfbad.visualization import visualizations as viz

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

