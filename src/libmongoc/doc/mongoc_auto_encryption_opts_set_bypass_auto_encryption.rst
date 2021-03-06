:man_page: mongoc_auto_encryption_opts_set_bypass_auto_encryption

mongoc_auto_encryption_opts_set_bypass_auto_encryption()
========================================================

Synopsis
--------

.. code-block:: c

   void
   mongoc_auto_encryption_opts_set_bypass_auto_encryption (
      mongoc_auto_encryption_opts_t *opts, bool bypass_auto_encryption);


Parameters
----------

* ``opts``: The :symbol:`mongoc_auto_encryption_opts_t`
* ``bypass_auto_encryption``: A boolean. If true, a :symbol:`mongoc_client_t` configured with :symbol:`mongoc_client_enable_auto_encryption()` will only perform automatic decryption (not encryption).

See also
--------

* :symbol:`mongoc_client_enable_auto_encryption()`
* The guide for :doc:`Using Client-Side Field Level Encryption <using_client_side_encryption>`
