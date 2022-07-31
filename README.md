# Socket_Oculus_Integration_SDK
Its my Script for the current Oculus Integration SDK


Unity Version 2022.0.0f.1
Oculus Integration SDK Version 39.0


How it works.

I changed on the "Grabbable" Script the "_ActiveTransformer" from private to public, to get access in my CustomSoket script to check if the target Object is grabbed.

![image](https://user-images.githubusercontent.com/104196543/182016195-d14da6cf-18e2-49b3-ac00-96ad8b1bfe79.png)


To create a Socket you have to create an emptyobject with an collider ( Box, Capsle etc. ) and add the custom Socket Script.
The Field for Attach is the place where the object get placed on.
I created an childobject and placed it in Attach.
![image](https://user-images.githubusercontent.com/104196543/182018367-4a991edf-1875-43c1-a220-c83af10f7005.png)

![image](https://user-images.githubusercontent.com/104196543/182018363-aa6606d7-5c98-4d79-8593-051c2a5da559.png)

The HoverMat is for the Hover Instance of the target.

![Batterie_Socket_480](https://user-images.githubusercontent.com/104196543/182018185-2d33487b-edc1-4b24-a9b5-34ca4122d4ae.gif)
