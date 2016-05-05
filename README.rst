PsychENCODE Unified RNAseq Analysis Pipelines
=============================================

This repository contains the pipeline logic used to analyze all RNAseq data in the PsychENCODE. Datasets include:

- `Yale iPSC <https://www.synapse.org/#!Synapse:syn4590910>`_
- `UIC-UChicago BrainGVEX <https://www.synapse.org/#!Synapse:syn4590909>`_
- `UCLA ASD <https://www.synapse.org/#!Synapse:syn4587609>`_
- `Mount Sinai EpiGABA <https://www.synapse.org/#!Synapse:syn4588488>`_
- `CommonMind Consortium <https://www.synapse.org/#!Synapse:syn4923029>`_

These pipelines require the
`ChunkyPipes <https://github.com/djf604/chunky-pipes>`_ pipeline framework and will not run self-contained.
The ChunkyPipes framework
can be easily installed with::

    $ pip install chunkypipes

These pipelines can be installed, configured for the current platform, and run with::

    $ chunky install pipeline-name.py
    $ chunky configure pipeline-name
    $ chunky run pipeline-name [parameters]

For more information on running these pipeline with ChunkyPipes, please refer to the
`ChunkyPipes documentation <http://chunky-pipes.readthedocs.io>`_.

For questions or concerns about these pipelines, please contact Dominic Fitzgerald (dfitzgerald at uchicago dot edu).