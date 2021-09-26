========
Redvault
========


.. image:: https://img.shields.io/pypi/v/redvault.svg
        :target: https://pypi.python.org/pypi/redvault

.. image:: https://img.shields.io/travis/ast0815/redvault.svg
        :target: https://travis-ci.com/ast0815/redvault

.. image:: https://readthedocs.org/projects/redvault/badge/?version=latest
        :target: https://redvault.readthedocs.io/en/latest/?version=latest
        :alt: Documentation Status




Distributed nearline backup system.


* Free software: MIT license
* Documentation: https://redvault.readthedocs.io.


Features
--------

* Use available space on many (remote) disks to backup data.
* Split data into shards for for effective usage of storage space.
* Rule based replication of shards over multiple disks/computers for redundancy.
* Use SSH for remote access.

  * No dedicated server software needed.
  * SSH takes care of access security.

* Use YAML header and tar body for shard format.

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
