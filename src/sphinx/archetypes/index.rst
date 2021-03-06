.. _archetypes:

Project Archetypes
##################

Archetype plugins provide predefined configurations for your build. Like :ref:`format plugins<packaging-formats>`,
archetype plugins can depend on other archetype plugins to extend existing functionality.

Project archetypes are default deployment scripts that try to "do the right thing" for a given type of project.
Because not all projects are created equal, there is no one single archetype for all native packages, but a set
of them for usage.

.. toctree::
   :maxdepth: 1

   Java Command Line Application <java_app/index.rst>
   Java Server Application <java_server/index.rst>
   Akka App [DEPRECATED] <akka_app.rst>
   Configuration Archetypes <misc_archetypes.rst>
   An archetype cheatsheet <cheatsheet.rst>
