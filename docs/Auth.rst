=====
Auth
=====

IsUsernameTaken
================

Parameters
~~~~~~~~~~~
- Username

Output
~~~~~~~
- code
- message

Example
~~~~~~~~
.. code-block:: python

   import robloxlib;
   rbx = robloxlib.client('Cookie')
   rbx.Auth.IsUsernameTaken(username)
