=====
Client
=====
bind_event
===========

Parameters
~~~~~~~~~~~
- eventName (Only event that has been made is onShout)
- eventCallback (A function to call back to.)
- args (A groupid or the required argument by an event.)

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
   
   def callback(x):
      print(x)
      
   rbx.bind_event('onShout', callback, groupid) 
