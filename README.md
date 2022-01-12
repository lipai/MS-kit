# MS-kit
### A simple tool for batch setting in, and batch export data (POSCAR or xyz format) from Materials Studio Visualizer
A batch setting means setting properties for all structures in the given folder.
A batch export means exporting all structures in the given folder.

More versions can be downloaded from http://home.ustc.edu.cn/~lipai/tutorials/software.html#materials-studio-batch-setting-tool

![image](https://user-images.githubusercontent.com/13411486/149045708-318c7318-65fd-4780-bd20-7338edc3044c.png)｛"width"="50px"}
There are four parts in the panel.
The top part highlighted with red circle is the "Work Path" which gives the Materials studio folder.
The left part highlighted with blue square is batch setting part for setting the lattice, Atom style and background color.
The green square part is for exporting files.
The right down part outputs operational information.

For both batch setting and export data, you need firstly input "Work Path".

#### how to get "Work Path"
![image](https://user-images.githubusercontent.com/13411486/149046406-bf9863a6-dbbc-4dab-b227-589f226229c5.png)
![image](https://user-images.githubusercontent.com/13411486/149046424-06d31112-b820-4538-b2b4-d1102b586778.png)
Copy the "Location" path and paste into the "Work Path" textbox.

#### how to do batch setting
First, close all structure windows.
![image](https://user-images.githubusercontent.com/13411486/149046807-26c04a44-51f7-4447-a44c-a091dc7ce533.png)
Second, do the setting for Lattice/Atom, and click Apply.
For the "Element" in Atom setting, if the input text is "All", the atom setting will be applied onto all atoms.
![image](https://user-images.githubusercontent.com/13411486/149046854-d8ed8c2a-606a-4639-81a4-8111636f138f.png)
Finally, reopen the structure windows.
![image](https://user-images.githubusercontent.com/13411486/149047211-dbe02578-e4cf-4a26-80a3-912347a9681e.png)
![image](https://user-images.githubusercontent.com/13411486/149047226-3846aca7-378d-4a94-8c6e-f391245e9b5a.png)

#### how to do batch exporting
The export part is independent of the batch setting part.
After the "Work Path" is given, you may input the Export Path in which the exported files will be located.
The default Export Path is the Desktop folder.
Then choose the file format, and click save.

