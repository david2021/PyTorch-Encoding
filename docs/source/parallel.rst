.. role:: hidden
    :class: hidden-section

Data Parallel
=============

Current PyTorch DataParallel Table is not supporting mutl-gpu loss calculation, which makes the gpu memory usage very in-efficient. We address this issue here by doing CriterionDataParallel. 
The DataParallel compatible with SyncBN will be released later.

.. automodule:: encoding.parallel
.. currentmodule:: encoding.parallel

:hidden:`ModelDataParallel`
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: ModelDataParallel
    :members:

:hidden:`CriterionDataParallel`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: CriterionDataParallel
    :members:

:hidden:`SelfDataParallel`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: SelfDataParallel
    :members:

:hidden:`AllReduce`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: AllReduce
    :members:

:hidden:`Broadcast`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: Broadcast
    :members:

