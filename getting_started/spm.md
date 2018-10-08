---
layout: default
---

# Integrating with SPM8

## Background

[SPM8](http://www.fil.ion.ucl.ac.uk/spm/software/spm8b/) is the newest version of [SPM software](http://www.fil.ion.ucl.ac.uk/spm/) developed by the Methods Group at the Wellcome Trust Centre for Neuroimaging, Institute of Neurology, University College London, UK and collaborators. SPM8 implements several advanced methods for M/EEG analysi

*  Statistical analysis at both scalp and source level and also analysis of time-frequency images using the General Linear Model (GLM) with thresholding based on Random Field Theory (RFT).

*  Bayesian 3D imaging source reconstruction methods including Multiple Sparse Priors (MSP) and MSP with group constraints.

*  Variational Bayesian dipole fitting, which makes it possible to fit and compare different dipole models for a particular scalp topography. Although dipole fitting is implemented in several packages including Fieldtrip, comparison of different dipole models and optimal selection of the number of dipoles based on model evidence is only available in SPM. 

*  Dynamic Causal Modelling (DCM)- a spatiotemporal network model to estimate effective connectivity in a network of sources. It is an easy to use, but nevertheless very sophisticated tool which makes it possible to model brain's electrical activity with biologically plausible neuronal models, make inferences about physiologically meaningful parameters and compare different models for the same data. DCM is presently available for evoked responses (ERP), steady state responses (a.k.a. power spectra and cross-spectral densities) and induced responses (a.k.a. event-related spectral perturbations, a.k.a. time-frequency images).

The developers of SPM have a formal collaboration with the developers of Fieldtrip on many analysis issues. For example, SPM and Fieldtrip share routines for converting data to Matlab, forward modelling for M/EEG source reconstruction and the SPM8 distribution contains a version of Fieldtrip so that you can combine Fieldtrip and SPM  functions in your custom scripts. SPM and Fieldtrip complement each other well as SPM is geared toward very specific analysis tools as described above whereas Fieldtrip is a more general repository of different methods that can be put together in flexible ways to perform a variety of analyses. In combined SPM8-Fieldtrip the flexibility of Fieldtrip can be complemented by the SPM GUI tools that allow rapid development of simple GUI's and also SPM8's new powerful batching system. Within this framework the power users in a lab
can easily and rapidly develop specialized analysis tools with GUI that can then  also be used by non-proficient Matlab users. Some examples of such tools are available in MEEG toolbox distributed with SPM.
## Practical issues

Up to July 2010 (SPM version 4010) in order to prevent function name clashes SPM called its Fieldtrip functions via intermediate or 'wrapper' functions whose name always started with 'ft_'. Prior to renaming Fieldtrip functions according to the same convention this had the advantage that even if there was a different Fieldtrip version in Matlab path from the one used by SPM, SPM only used its own version and incompatibilities could be avoided. From version 4010 the version of Fieldtrip distributed with SPM is a 'light' version with the same layout and function names as the standalone Fieldtrip but without compat folders, large template files and some less frequently toolboxes (e.g. classification and real time).

Fieldtrip data structures can be converted to SPM EEG files using the *spm_eeg_ft2spm* function.  SPM8 M/EEG data, once loaded with the function *spm_eeg_load* can be converted to Fieldtrip format using the method 'ftraw' (with syntax D.ftraw or ftraw(D)). An additional argument can be supplied to indicate whether the data is memory mapped from the disk (1: default) or loaded into memory (0). Note that not all Fieldtrip functions can properly handle memory mapped data. In order to avoid corrupting the data, ftraw sets a read-only flag on it so in the worst case you might encounter errors in Fieldtrip functions. Please report such errors on SPM or Fieldtrip mailing list as we are interested in fixing them. ftraw(0) is 
safer in this respect but inefficient in its memory use. 

Since SPM8 M\EEG format as well as its predecessor SPM5 format are supported by the fileio toolbox, it is possible to preprocess SPM M\EEG data in Fieldtrip the usual way without the need for SPM installation. SPM M\EEG dataset consists of two files with extensions *.mat and *.dat. The name of *.mat file should be specified in Fieldtrip cfg for the format to be recognized.

The shared infrastructure for head modelling makes it possible to use a head model coregistered with sensors using SPM8 for Fieldtrip methods such as beamforming and obtain results with SPM and Fieldtrip in the same coordinate system. This facilitates comparison and validation of results obtained with SPM using Fieldtrip and *vice versa*.
