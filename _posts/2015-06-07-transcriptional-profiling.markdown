---
layout: post
title: Transcriptional profiling of mouse B cell terminal differentiation defines a signature for antibody secreting plasma cells
comments: true
published: true
doi: 10.1038/ni.3154
categories: 
---

Shi et alia perform a series of RNAseq experiments to identify transcriptomic sequences consistent
with antibody-secreting cells (ASCs). BLIMP1-GFP mice are used to provide a marker for sorting ASCs.

I thought I would be interested in the methods but the bioinformatics are relatively straightforward. The `limma` package is deployed heavily. The authors perform an admirable array of isolations and sorts. Inferring information about division generations by membrane dye dilution isn't a new trick but I still like seeing it.

Some factoids:

* More than 70% of the transcripts from bone-marrow plasma cells are immunoglobulin-derived; in
  circulating peripheral B cells, it's more like 2%
* ASCs, despite having distinct origins and anatomical reservoirs, have a shared core expression
  program
