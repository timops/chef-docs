=====================================================
About the |chef repo|
=====================================================

.. warning:: |note doc_version_11-4|

.. include:: ../../includes_repository/includes_repository.rst

Directory Structure
=====================================================
.. include:: ../../includes_repository/includes_repository_directory.rst

The sub-directories in the |chef repo| are:

* ``certificates/``
* ``.chef/``
* ``config/``
* ``cookbooks/``
* ``data_bags/``
* ``environments/``
* ``roles/``

certificates/
-----------------------------------------------------
.. include:: ../../includes_repository/includes_repository_directory_certificates.rst

.. include:: ../../step_repository/step_repository_certificate_generate.rst

.chef/
-----------------------------------------------------
.. include:: ../../includes_repository/includes_repository_directory_chef.rst

config/
-----------------------------------------------------
.. include:: ../../includes_repository/includes_repository_directory_config.rst

The |chef repo| uses two configuration files: ``rake.rb`` (required) and ``knife.rb`` (optional).

rake.rb
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_config/includes_config_rb_rake.rst

.. include:: ../../includes_chef/includes_rake_tasks_included_in_chef_libraries.rst

knife.rb
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_config/includes_config_rb_knife.rst

cookbooks/
-----------------------------------------------------
.. include:: ../../includes_repository/includes_repository_directory_cookbooks.rst

data_bags/
-----------------------------------------------------
.. include:: ../../includes_repository/includes_repository_directory_data_bags.rst

environments/
-----------------------------------------------------
.. include:: ../../includes_repository/includes_repository_directory_environments.rst

roles/
-----------------------------------------------------
.. include:: ../../includes_repository/includes_repository_directory_roles.rst 

chefignore Files
=====================================================
.. include:: ../../includes_repository/includes_repository_directory_chefignore.rst 

Examples
-----------------------------------------------------
The following examples show how to add entries to the ``chefignore`` file.

**Ignore editor swap files**

.. include:: ../../includes_repository/includes_repository_directory_chefignore_swap_files.rst 

**Ignore top-level Subversion data**

.. include:: ../../includes_repository/includes_repository_directory_chefignore_svn.rst 

**Ignore all files in a directory**

.. include:: ../../includes_repository/includes_repository_directory_chefignore_directories.rst 

Many Users, Same Repo
=====================================================
.. include:: ../../includes_repository/includes_repository_many_users_same_repo.rst

Create the |chef repo|
=====================================================
.. include:: ../../includes_repository/includes_repository_create.rst

Clone
-----------------------------------------------------
.. include:: ../../step_repository/step_repository_create_clone.rst

Download
-----------------------------------------------------
.. include:: ../../step_repository/step_repository_create_download.rst

.. toctree::
   :hidden:

   essentials_repository_structure
   essentials_repository_structure_chefignore






