Welcome to JAXgarden documentation!
=====================================

JAXgarden provides high-performance and hackable neural network model implementations in JAX, leveraging optimized kernals and layers like FlashAttention.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   readme
   modules/index
   contributing
   changelog

Features
--------

- **MultiHeadAttention**: A Flax NNX-compatible implementation with support for different attention backends.

Installation
------------

.. code-block:: bash

   pip install git+https://github.com/ml-gde/jax-layers.git

For development installation:

.. code-block:: bash

   # first, fork the repository to your account.
   # Then, clone it to your machine.
   git clone https://github.com/yourusername/jax-layers.git
   cd jax-layers
   pip install -e ".[dev]"

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search` 