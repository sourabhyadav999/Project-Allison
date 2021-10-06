# Project-Allison

Allison is an atempt for creating a Artifical General Intelligence. Allison has two main components Memory and Functions.
Allison's memory is a semantic graph with object at the nodes and the relationships between object as edge weight.

The tasks or Function performed by Allison can be classified into two basic categories:
     1. Non ML related tasks such as opening a camera, hacking into systems, capturing a photo.

     2. ML related tasks, such as understanding the instructions necessary to perform Non ML related tasks, 
       identifying objects in the captured images, verifying Admin and other users (facial recognition)

The starting point of Allison is a NLU network that helps her understand the instructions.
The instructions will not be programmed into the her rather she would have to search the internet for the aforementioned instructions.
The Non ML or ML tasks instructions once performed will be stored in memory along side information, though seperated.

The core will be a execution engine which will be execute the instruction in system's core language.