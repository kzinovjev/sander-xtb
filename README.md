# sander-xtb
Interface between [sander](https://ambermd.org/AmberTools.php) and [xtb](https://github.com/grimme-lab/xtb) package

Works by reusing the existing interface between sander and [ORCA](https://orcaforum.kofo.mpg.de/index.php) - no modifications to sander or xtb are needed. Just make sure that the "orca" script is in the $PATH and is executable. 

The interface is very basic. It ignores all the variables in &orc namelist except num_threads. the [GFN2](https://pubs.acs.org/doi/10.1021/acs.jctc.8b01176) method is always used.
