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

add_proxy
===========

Parameters
~~~~~~~~~~~
- ip 
- port 

Example
~~~~~~~~
.. code-block:: python

   import robloxapi;
   rbx = robloxapi.client('Cookie');
      
   rbx.add_proxy('ip', 'port') #will send all requests with ths proxy 
