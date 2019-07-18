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

   import robloxapi;
   rbx = robloxapi.client('Cookie')
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
   
   import robloxapi;
   rbx = robloxapi.Auth.login('Cookie')

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
   import robloxapi;
   rbx = robloxapi.client('Cookie')
   rbx.Auth.RefreshToken()
