======
Group
======

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
   
 
