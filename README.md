# hMRI-toolbox_redirect
Redirecting SPM toolbox to another folder.

## PURPOSE
The present hMRI config file redirects towards the full implementation of the toolbox (`tbx_cfg_hmri`) only if present in the Matlab path. The toolbox can therefore be stored in a directory independent from the SPM implementation and synch'd with the main hMRI-Toolbox repository whenever needed. If `tbx_cfg_hmri` is not found in the Matlab path, the hMRI Tools are listed in the SPM Batch GUI but not available. A brief help section provides the user with instructions for hMRI Tools installation.

## USAGE
- Copy this file into a directory in the SPM toolbox directory (e.g. `<path-to-SPM>/toolbox/hMRI-Redirect`). 
- Add the hMRI-Toolbox directory (containing the full implementation of the toolbox) to the Matlab path.
- Restart SPM and the Batch GUI. 

The hMRI Tools will now be available in the `SPM>Tools menu`.

## ACKNOWLEDGMENT
[Cyclotron Research Centre](https://www.gigacrc.uliege.be/) - [University of Liège](https://www.uliege.be/)

Dr Evelyne Balteau (@EvelyneBalteau) - April 2017
