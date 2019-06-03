=====
Client
=====

bind_event
===========

Parameters
~~~~~~~~~~~
- eventName 
- eventCallback 
- args 

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   
   def callback(x):
      print(x)
      
   rbx.bind_event('onShout', callback, groupid) 
