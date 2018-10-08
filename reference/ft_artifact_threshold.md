---
layout: default
---

##  FT_ARTIFACT_THRESHOLD

Note that this reference documentation is identical to the help that is displayed in MATLAB when you type "help ft_artifact_threshold".

`<html>``<pre>`
    `<a href=/reference/ft_artifact_threshold>``<font color=green>`FT_ARTIFACT_THRESHOLD`</font>``</a>` scans for trials in which the range, i.e. the minimum, the
    maximum or the range (min-max difference) of the signal in any channel exceeds a
    specified threshold.
 
    Use as
    [cfg, artifact] = ft_artifact_threshold(cfg)
    with the configuration options
    cfg.dataset     = string with the filename
    or
    cfg.headerfile  = string with the filename
    cfg.datafile    = string with the filename
    and optionally
    cfg.headerformat
    cfg.dataformat
 
    Alternatively you can use it as
    [cfg, artifact] = ft_artifact_threshold(cfg, data)
    where the input data is a structure as obtained from `<a href=/reference/ft_preprocessing>``<font color=green>`FT_PREPROCESSING`</font>``</a>`.
 
    In both cases the configuration should also contain
    cfg.trl        = structure that defines the data segments of interest, see `<a href=/reference/ft_definetrial>``<font color=green>`FT_DEFINETRIAL`</font>``</a>`
    cfg.continuous = 'yes' or 'no' whether the file contains continuous data
 
    The following configuration options can be specified
    cfg.artfctdef.threshold.channel   = cell-array with channel labels
    cfg.artfctdef.threshold.bpfilter  = 'no' or 'yes' (default = 'yes')
    cfg.artfctdef.threshold.bpfreq    = [0.3 30]
    cfg.artfctdef.threshold.bpfiltord = 4
 
    It is also possible to use other filter (lpfilter, hpfilter,
    bsfilter, dftfilter or medianfilter) instead of a bpfilter for
    preprocessing, see `<a href=/reference/ft_preprocessing>``<font color=green>`FT_PREPROCESSING`</font>``</a>`
 
    The detection of artifacts is done according to the following settings,
    you should specify at least one of these thresholds
    cfg.artfctdef.threshold.range     = value in uV or T, default  inf
    cfg.artfctdef.threshold.min       = value in uV or T, default -inf
    cfg.artfctdef.threshold.max       = value in uV or T, default  inf
    cfg.artfctdef.threshold.onset     = value in uV or T, default  inf
    cfg.artfctdef.threshold.offset    = value in uV or T, default  inf
 
    When cfg.artfctdef.threshold.range is used, the within-channel peak-to-peak range
    is checked against the specified maximum range (so not the overall range across
    channels). In this case the whole trial will be marked as an artifact.
 
    When cfg.artfctdef.threshold.onset and offset are used, the rising and falling
    flank are thresholded with different values. In case onset and offset are both
    positive, the data will be thresholded above their values. In case both onset and
    offset are negative, the data will be thresholded below their values.
 
    Note that this function does not support artifact- or filterpadding.
 
    The output argument "artifact" is a Nx2 matrix comparable to the
    "trl" matrix of `<a href=/reference/ft_definetrial>``<font color=green>`FT_DEFINETRIAL`</font>``</a>`. The first column of which specifying the
    beginsamples of an artifact period, the second column contains the
    endsamples of the artifactperiods.
 
    To facilitate data-handling and distributed computing you can use
    cfg.inputfile   =  ...
    If you specify one of these (or both) the input data will be read from a *.mat
    file on disk and/or the output data will be written to a *.mat file. These mat
    files should contain only a single variable, corresponding with the
    input/output structure.
 
    See also `<a href=/reference/ft_rejectartifact>``<font color=green>`FT_REJECTARTIFACT`</font>``</a>`, `<a href=/reference/ft_artifact_clip>``<font color=green>`FT_ARTIFACT_CLIP`</font>``</a>`, `<a href=/reference/ft_artifact_ecg>``<font color=green>`FT_ARTIFACT_ECG`</font>``</a>`, `<a href=/reference/ft_artifact_eog>``<font color=green>`FT_ARTIFACT_EOG`</font>``</a>`,
    `<a href=/reference/ft_artifact_jump>``<font color=green>`FT_ARTIFACT_JUMP`</font>``</a>`, `<a href=/reference/ft_artifact_muscle>``<font color=green>`FT_ARTIFACT_MUSCLE`</font>``</a>`, `<a href=/reference/ft_artifact_threshold>``<font color=green>`FT_ARTIFACT_THRESHOLD`</font>``</a>`, `<a href=/reference/ft_artifact_zvalue>``<font color=green>`FT_ARTIFACT_ZVALUE`</font>``</a>`
`</pre>``</html>`
