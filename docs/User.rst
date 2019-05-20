=====
User
=====
block_user
===========

Parameters
~~~~~~~~~~~
- ID

Output
~~~~~~~
- True/False

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   result = rbx.User.block_user(id);

getProfile
============

Parameters
~~~~~~~~~~~
- ID

Output
~~~~~~~
* Dict:
   * username (string)
   * id (number)
   * avatar_url (string)
   * blurb (string)
   * bc (dict):
      * type (string)
      * image_url (string)
   * count (dict):
      * FollowersCount (number)
      * FollowingsCount (number)
      * FriendsCount (number)
   * badges (number)

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   profile = rbx.User.getProfile(id);

IdByUsername
=============

Parameters
~~~~~~~~~~~
- Username

Output
~~~~~~~
- Dict:
   - ID

Example
~~~~~~~~

.. code_block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   id = robloxapi.User.IDByUsername(username);

send_message
=============

Parameters
~~~~~~~~~~~
- reciever_id
- subject
- body

Output
~~~~~~~
- Dict (failed or sent)

Example
~~~~~~~~

.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   result = rbx.User.send_message(reciever_id, subject, body);
   
unblock_user
=============

Parameters
~~~~~~~~~~~
- ID

Output
~~~~~~~
- True/False

Example
~~~~~~~~

.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   result = rbx.User.unblock_user(id);

UsernameById
=============

Parameters
~~~~~~~~~~~
- ID

Output
~~~~~~~
- Username

Example
~~~~~~~~

.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   username = robloxapi.User.UsernameById(id)
