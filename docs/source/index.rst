Welcome to The "Server-Sent Events Documentation Repository" 0.0.2
===================================

```mermaid
graph LR
A[Client] --> B((EventSource))
B -- Subscribe --> C[Server]
C -- Send events --> B
B -- Event handling --> A




Contents
--------

.. toctree::

   usage
   api
