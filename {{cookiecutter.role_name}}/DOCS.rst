{{ cookiecutter.role_name }}
================================================================================

Variables
--------------------------------------------------------------------------------

Variables marked with `M` will be merged with their default values instead of
being overwritten.

.. autoyaml:: defaults/main.yml

.. autoyaml:: vars/main.yml

Examples
--------------------------------------------------------------------------------

.. literalinclude:: tests/site.yml
   :language: yaml
