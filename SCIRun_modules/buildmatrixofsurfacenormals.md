---
title: BuildMatrixOfSurfaceNormals
category: moduledocs
tags: module

---

#BuildMatrixOfSurfaceNormals

##Description

###Summary

This module calculates area weighted normal vectors per node.

###Detailed Description

For each node in the input surface mesh, find the attached faces, and average the face normal weighted by area for that node. Output a Nx3 DenseMatrix where N is the number of nodes in the input surface mesh. This matrix can be passed to [SwapFieldDataWithMatrixEntries](need_link) to map this data back to a vector field with the same mesh.


