Imagic
======

###Scripts for IMAGIC-4D

#####plot_mra_class

You may use the following script to plot MRA angle distribution for each class after MSA-CLASS run. Each angle value from each projection is depicted by line on a circle. Such plots can be used to judge if class has incomplete sampling of in-plane rotation angle.

The input parameters are:

* Folder name for output images
* File on which you performed MSA
* File name (*.lis) created by MSA-CL

The output are *.png images in previously selected folder.

---

#####sort_var

You may use the following script to sort you classums by intra-class variance after MSA-CLASS run.

The input parameters are:

* Cycle number (FYI, reminds you iteration #)
* Final number of classes wanted after sorting
* File name (*.lis) created by MSA-CL

The output file has name format: cl(total # of classes)-(cycle #)-sort-var

---
