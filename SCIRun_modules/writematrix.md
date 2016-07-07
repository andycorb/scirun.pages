---
title: WriteMatrix
category: moduledocs
tags: module

---

#WriteMatrix

##Description

###Summary

The WriteMatrix modules saves a persistent representation of a matrix to disk.

###Detailed Description

Upon opening, the GUI defaults to the directory that the user sets for their SCIRUN_DATA environment variable. 

Otherwise, the GUI will default to the directory where the user's SCIRun executable resides. The user can enter the name of a file that the matrix saves to. The file should have a .mat extension. The default file name is MyMatrix. The user may also choose between a Binary or ASCII file format. 