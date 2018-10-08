---
layout: default
---

#  FieldTrip workshop in Salzburg

#### Where

The University of Salzburg, with support from the [TINNET-COST Action](http://tinnet.tinnitusresearch.net)

{{:workshop:usalzburg.png?200|}}    {{:workshop:tinnetcost.png?100|}}

#### When

9 - 11 December 2015

#### Who

Nietzsche Lam and Tzvetan Popov will be the lecturers and teachers.

Gaetan Sanchez, Nathan Weisz and Thomas Hartmann are the local organizers.


#### External Applicant Call

Applications for this workshop are now closed. Please check out our other upcoming workshops on [ here](http://fieldtriptoolbox.org/workshop).

## Program

### Wednesday 09 December 2015

Session I
*  **10:00 - 10:15**   Registration, welcome and coffee
*  **10:15 - 11:15**   Lecture: Introduction to MEG and the FieldTrip Toolbox | *Nietzsche Lam*
*  **11:15 - 11:30**   Coffee break
*  **11:30 - 13:30**   Hands-on: Initiation to FieldTrip; Analyzing MEG data (event-related fields)

Session II
*  **13:30 - 14:45**   Lunch
*  **14:45 - 15:45**   Lecture: Introduction to EEG; Comparing EEG with MEG | *Nietzsche Lam*
*  **15:45 - 16:00**   Coffee break
*  **16:00 - 18:00**   Hands-on: Analyzing EEG data
*  **18:00 - 18:30**   Wrap-up-the-day and Summary

### Thursday 10 December 2015

Session III
*  **9:00 - 10:15**    Lecture: Fundamentals of neuronal oscillations and synchrony | *Nietzsche Lam*
*  **10:15- 10:30**    Coffee break
*  **10:30- 12:30**    Hands-On: Time-frequency Analysis of Power
*  **12:30- 13:45**    Lunch

Session IV
*  **13:45 - 14:45**   Lecture: Source reconstruction in FieldTrip | *Tzvetan Popov*
*  **14:45 - 15:00**   Coffee break
*  **15:00 - 17:00**   Hands-on: Source Reconstruction on Oscillatory data (beamformer)
*  **17:00 - 17:30**   Wrap-up-the-day and Summary
*  **19:00 - 23:00**   Social Event

### Friday 11 December 2015

Session V
*  **9:00 - 10:15**    Lecture: Non-parametric permutation techniques | *Tzvetan Popov*
*  **10:15- 10:30**    Coffee break
*  **10:30- 12:30**    Hands-On: Statistical Analyses
*  **12:30- 13:45**    Lunch

Session VI
*  **13:45 - 14:45**   FieldTrip Playground (bring your own data) | *Tzvetan Popov and Nietzsche Lam*
*  **14:45 - 15:00**   Coffee break
*  **15:00 - 17:00**   FieldTrip Playground (bring your own data)
*  **17:00 - 17:30**   Wrap-up-the-day and Closing remarks

## Getting started with the hands-on sessions

For the hands-on sessions you have to start MATLAB. To ensure that everything runs smooth, we will work with a clean and well-tested version of FieldTrip that is distributed on a USB stick, rather than the version you might already have installed. (If you have a FieldTrip version dating from sometime in the last few weeks, that should be fine.) Importantly, the tutorial data does not have to be downloaded but will also be distributed on the USB stick.

 1.  Copy the complete contents of the USB stick to your computer.
 2.  Unzip the fieldtrip-xxxxxxxx.zip file.
 3.  Put Subject01.zip in a directory called 'tutorial'.

`<note warning>`
Depending on the unzip program you are using (e.g. Winrar), the name
of the zip file might also appear as directiory, resulting in
path_to_directory/fieldtrip-xxxxxxxx/fieldtrip-xxxxxxxx, i.e. the
fieldtrip directory in a fieldtrip directory. Please fix that by
moving all files one level up.
`</note>`

After copying all files to your computer and unzipping then, you start MATLAB. To ensure that the right version of fieldtrip is used, and not another version (such as the one included in SPM or EEGLAB), you type in the MATLAB command window

    restoredefaultpath
    cd path_to_directory/fieldtrip-xxxxxxxx
    addpath(pwd)
    ft_defaults

`<note warning>`
Please do NOT use the graphical path management tool from MATLAB. In this hands-on session we'll manage the path from the command line, but in general you are much better off using the startup.m file than the path GUI.

Please do NOT add fieldtrip with all subdirectories, subdirectories will be added automatically when needed, and only when needed.
`</note>`

The restoredefaultpath command clears your path, keeping only the
official MATLAB toolboxes. The addpath(pwd) statement adds the
present working directory, i.e. the directory containing the fieldtrip
main functions. The ft_defaults command ensures that all required
subdirectories are added to the path.

If you get the error "can't find the command ft_defaults" you should check the present working directory.

After installing FieldTrip to your path, you change into the tutorial directory

    cd path_to_directory/tutorial