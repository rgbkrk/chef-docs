=====================================================
About Configuration Files
=====================================================

.. warning:: |note doc_version_11-4|

|chef| relies on |ruby| files to provide configuration details and settings to various components. The files are written using a |ruby| DSL that specifies each setting and its value. Some values are specified as strings, others as integers, floats, hashes, or arrays. In the following sections, the settings are listed alphabetically, with a description of the setting and (in most cases) the available options and values.

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Config File
     - Description
   * - :doc:`config_rb_chef_server`
     - |config rb chef server|
   * - :doc:`config_rb_client`
     - |config rb client|
   * - :doc:`config_rb_knife`
     - |config rb knife|
   * - :doc:`config_rb_metadata`
     - |config rb metadata|
   * - :doc:`config_rb_solo`
     - |config rb solo|

The following configuration files apply only to |chef 10|:

   * - Config File
     - Description
   * - :doc:`config_rb_server`
     - |config rb server|
   * - :doc:`config_rb_solr`
     - |config rb solr|


.. toctree::
   :hidden:

   config_rb_chef_server
   config_rb_client
   config_rb_knife
   config_rb_knife_optional_settings
   config_rb_metadata
   config_rb_server
   config_rb_solo
   config_rb_solr








