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
   
   