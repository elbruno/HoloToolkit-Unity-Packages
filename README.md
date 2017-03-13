# HoloToolkit-Unity-Packages
Unity packages created from HoloToolkit Unity repository

Use the HoloToolkit Unity Package in a Unity project

Create a new 3D project in Unity
Now we must import the HoloToolkit package. Select the menu [Assets / Import Package / Custom Package]

![Images/clipboard11](Images/clipboard11.png)

This option will show us the elements of the Unity Package we want to import. For this sample, I will import one package a couple of weeks old to show the correct way of update a package later.
![Images/clipboard12](Images/clipboard12.png)

At this time, Unity is responsible for importing all the elements (this is similar to copy all the files in the Assets directory)
Once imported, you can see all the items in the Assets directory
![Images/clipboard14](Images/clipboard14.png)

We can now begin to work with the HoloToolkit assets in our Unity project
Update a HoloToolkit package in Unity

In this scenario we will perform the same steps to import a package
The important point here, is when there are changes in the package. We will we be warned when we are going to import the package
For example in the picture below you can see changes in the file [Build / Editor / BuildDeployWindow.cs] and new files in [Imput / Plugins / … ]
![Images/clipboard15](Images/clipboard15.png)

This allows us to know the changes which exist between different versions of a package, and also to select the items that we want to use
 

And this is the correct way to work with Unity Packages applied to HoloToolkit.
