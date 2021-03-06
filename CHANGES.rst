CHANGES
=======

Version 1.5.0
-------------
* Now the NAST algorithm trims candidate sequences to that which is bound by the
  beginning and end points of the alignment span; with the the new option
  ``--nast-notrim`` in ``micca msa`` produces the same results of the previous
  version (<=1.4.0);
* Y-scale in ``micca tablebar`` when ``--raw`` fixed;
* "text file busy error" in ``micca msa`` (nast) fixed;
* pandas deprecation warnings fixed;
* documentation updated.

Version 1.4.0
-------------
* No-filter option added to ``micca.api.msa.nast()`` (do not remove positions
  which are gaps in every sequenceces) and to the ``msa`` command
  (``--nast-nofilter`` option);
* documentation improved.

Version 1.3.0
-------------
* Swarm clustering algorithm added to ``micca otu``;
* ``micca.api.otu.denovo_swarm()`` function added;
* micca v1.3.0 includes: VSEARCH v1.9.5, MUSCLE v3.8.31, FastTree v2.1.8, swarm
  v2.1.8;
* documentation updated.

Version 1.2.2
-------------
* Mow micca can generate plots with matplotlib when the ``DISPLAY`` environment
  variable is undefined;
* ``MANIFEST.in``, Dockerfile updated.

Version 1.2.1
-------------
* Dockerfile added;
* Documentation improved.

Version 1.2.0
-------------
* Hits output file option added to ``micca.api.msa.nast()`` (``hits_fn``
  option) and to the ``msa`` command (``--nast-hits`` option);
* setup.py improved.

Version 1.1.0
-------------
* Strand option added in ``classify`` (consensus-based classifier), ``msa``
  (NAST) and ``otu`` (closed-reference and open reference OTU picking protolcols)
  commands. Now these commands search both strand (default) instead the plus
  strand only.

Version 1.0.0
-------------
* micca 1.0.0 includes: VSEARCH v1.9.5, MUSCLE v3.8.31, FastTree v2.1.8.
