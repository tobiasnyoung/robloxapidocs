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
- True/False

Example
~~~~~~~~
.. code-block:: python

   import robloxlib;
   rbx = robloxlib.client('Cookie')
   rbx.Auth.IsUsernameTaken(username)

login
======

Parameters
~~~~~~~~~~~
- Cookie

Output
~~~~~~~
- Asset
- Auth
- Game
- Group
- Trade
- User

Example
~~~~~~~~
.. code-block:: python
   
   import robloxlib;
   rbx = robloxlib.Auth.login('Cookie')

RefreshToken
=============

Parameters
~~~~~~~~~~~
- None

Output
~~~~~~~
- Cookies

Example
~~~~~~~~
.. code-block:: python
   import robloxlib;
   rbx = robloxlib.client('Cookie')
   rbx.Auth.RefreshToken()
