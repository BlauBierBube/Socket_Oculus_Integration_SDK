# Socket_Oculus_Integration_SDK
Its my Script for the current Oculus Integration SDK


Unity Version 2022.0.0f.1
Oculus Integration SDK Version 39.0


How it works.

I changed on the "Grabbable" Script the "_ActiveTransformer" from private to public, to get access in my CustomSoket script to check if the target Object is grabbed.

![image](https://user-images.githubusercontent.com/104196543/182016195-d14da6cf-18e2-49b3-ac00-96ad8b1bfe79.png)


To create a Socket you have to create an emptyobject with an collider ( Box, Capsle etc. ) and add the custom Socket Script.
The Field for Attach is the place where the object get placed on.
The HoverMat is for the Hover Instance of the target.

