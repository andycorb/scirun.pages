---
title: ConvertQuadSurfToTriSurf
category: moduledocs
tags: module

---

#ConvertQuadSurfToTriSurf

##Description

###Summary

This module converts a **QuadSurfField** into a **TriSurfField**.

###Detailed Description

Given a QuadSurfField (or anything that supports the same interface) as input, produce a TriSurfField as output -- each Quad element gets split into 2 Tris. In order to produce consistent splits across faces, it alternates between two different templates for how to do the split.
