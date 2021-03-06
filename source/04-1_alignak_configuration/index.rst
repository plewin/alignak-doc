.. raw:: LaTeX

    \newpage

.. _alignak_configuration/index:

Alignak framework configuration
===============================

.. raw:: LaTeX

    \newpage


The Alignak framework configuration is splitted in two main parts:

   - the core configuration
   - the modules configuration.

All the configurations are stored in the folder */usr/local/etc/alignak/* (or */etc/alignak/*), even the monitoring objects (what is monitored and how it is). Monitoring objects configuration, probably the most important for Alignak's users, is described in  :ref:`the monitored objects dedicated chapter <monitoring_configuration/index>`.

Each main part of the Alignak framework configuration is described in the following chapters :

.. toctree::
   :maxdepth: 1

   core_configuration
   modules_configuration

This chapter gives information about configuring the inter-deamon communication with SSL.

.. toctree::
   :maxdepth: 1

   ssl_certificate

The last chapters give more information about the default installed configuration and some specific objects configuration features.

.. toctree::
   :maxdepth: 1

   default_configuration
   core_configuration_tips.rst
