=====
User
=====

Block user
===========

Parameters
~~~~~~~~~~~
- User ID

Output
~~~~~~~
- True/False

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   result = rbx.User.block_user("User ID")

Get profile
============

Parameters
~~~~~~~~~~~
- User ID

Output
~~~~~~~
- Dict:
  - username (string)
  - id (number)
  - avatar_url (string)
  - blurb (string)
  - bc (dict):
    - type (string)
    - image_url (string)
  - count (dict):
    - FollowersCount (number)
    - FollowingsCount (number)
    - FriendsCount (number)
  - badges (number)

Example
~~~~~~~~
.. code-block:: python

   import robloxapi
   rbx = robloxapi.client('Cookie')
   profile = rbx.User.getProfile("User ID")


