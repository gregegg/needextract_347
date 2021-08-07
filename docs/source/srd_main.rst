===============================
Software Requirements Document
===============================


Defining a need
-------------------------------

This is where I define the need:

.. user:: Consistent Units
   :id: USER_001

   User must ensure a consistent unit system is used for all inputs


Calling the needextract in the same latex output
---------------------------------------------------

This is where I recall the need with needextract:

.. needextract::
    :filter: id in ['USER_001']
