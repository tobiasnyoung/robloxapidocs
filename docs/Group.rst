======
Group
======

demote
=======

Parameters
~~~~~~~~~~~
- Group ID
- User ID

Output
~~~~~~~
- ranked
- reason
- oldRole
- newRole

Example
~~~~~~~~
.. code-block:: python

   import robloxlib;
   rbx = robloxlib.client('Cookie')
   rbx.Group.demote('groupid','id')

getGroup
=========

Parameters
~~~~~~~~~~~
- Group ID

Output
~~~~~~~
- Dict
   - id
   - name
   - description
   - owner
      - userId
      - username
      - buildersClubMembershipType
   - shout
   - memberCount
   - isBuildersClubOnly
   - hasClan (always return false)
   - publicEntryAllowed

Example
~~~~~~~~
.. code-block:: python

   import robloxlib; 
   rbx = robloxlib.client('Cookie')
   rbx.Group.getGroup(id)
   
getGroupRoles
==============

Parameters
~~~~~~~~~~~
- Group ID

Output
~~~~~~~
- Dict
   - groupId
   - roles
      - id
      - name
      - rank
      - memberCount

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie')
   rbx.Group.getGroupRoles(id)
   
getWall
========

Parameters
~~~~~~~~~~~
- Group ID

Output
~~~~~~~
- Dict
   - previousPageCursor
   - nextPageCursor
   - data
      - id
      - poster
         - user
            - userId
            - username
            - buildersClubMembershipType
         - role
            - id
            - name
            - rank
            - memberCount
      - body
      - created
      - updated

Example
~~~~~~~~
.. code-block:: python

   import robloxlib;
   rbx = robloxlib.client('Cookie')
   rbx.Group.getWall(id)

groupPayout
============

Parameters
~~~~~~~~~~~
- Group ID
- User ID
- Amount

Output
~~~~~~~
- True/False

Example
~~~~~~~~
.. code-block:: python

   import robloxlib;
   rbx = robloxlib.client('Cookie')
   rbx.Group.groupPayout('groupid','id','amount')
   
groupSearch
============

Parameters
~~~~~~~~~~~
- Name
- Max Rows

Output
~~~~~~~
- Keyword
- MaxRows

Example
~~~~~~~~
.. code-block:: python

   import robloxlib;
   rbx = robloxlib.client('Cookie')
   rbx.Group.groupSearch('keyword', 'maxrows')
