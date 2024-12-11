This set is available in Zenodo 10.5281/zenodo.2452870
The original data given in /data/raw and used in the article have been obtained from an old version using matlab. 
They should be approximately the same as the ones given in pipeline-2. 


fMRI of rats under anesthesia
=============================

This is the set of data concerning experiments to evaluate the influence of anesthetics on rats during resting state functional magnetic resonance imaging (rs-fMRI). 
Available data corresponds to the time series extracted from rs-fMRI on brain areas defined in an atlas. 
Data were collected from March 2016 to June 2016 in the Grenoble Institute of Neurosciences (GIN), Grenoble, France.  
See publication for details. 

Authors: G. J.-P. C. Becq (a), T. Habet (b), N. Collomb (b, c), M. Faucher (a, b), C. Delon-Martin (b), V. Coizet (b), S. Achard (a), E. L. Barbier (b, c)
Institutions: (a) Univ. Grenoble Alpes, CNRS, Gipsa-lab, F-38000, Grenoble, France; (b) Univ. Grenoble Alpes, Inserm, U1216, Grenoble Institut Neurosciences, GIN, F-38000 Grenoble, France; (c) Univ. Grenoble Alpes, Inserm, UMS017, CNRS, US3552, CHU Grenoble Alpes, IRMaGe, F-38000 Grenoble, France
Copyright: for the database inherited from the copyrights of the repository. codes are given as it under a CeCILL-B license. 
Date: 2019-05-07 

Contents data.zip
=================

data are given in this archive. 

/data/raw/ raw data in .csv format
/data/cD1/ filtered data at the cD1 wavelet scale, see publication for detail,  same format as raw. 
/data/cD2/ ... cD2 ...
/data/cD3/ ... cD3 ...
/data/cD4/ ... cD4 ...
/data/cD5/ ... cD5 ...
/data/cD6/ ... cD6 ...
/data/cD7/ ... cD7 ...
/data/cA7/ ... cA7 ...
/data/coreg/ .txt file, one per trial, parameters obtained after coregistration made with SPM12, see publication for detail.  
/data/i_select/ .csv files, one per trial, containing validations of samples from framewise displacement on coregistration files, see publication for details.   
/data/area.csv: data concerning areas in the atlas. 
/data/cbf.csv: cerebral blood flow values. 
/data/trial.csv: data concerning trials. 

contents code.zip
=================

Publication codes are given in this archive. Codes are given as they are. All codes are distributed under a CeCILL-B license agreement. 
Code has been developed with these dependencies: 
python 3.6.5
jupyter 1.0.0
pandas 0.23.4
numpy 1.15.4
scipy 1.1.0
matplotlib 3.0.2
igraph 0.7.1

/code/tools.py: tools to manage data and plot figures. 
/code/waveslim_rats.py: function for wavelet computations.  
/code/0 - Wavelet decomposition.ipynb: compute wavelet details and approximations. 
/code/1 - FD distributions.ipynb: notebook for plotting figures 
/code/2 - Spectral.ipynb: ... same as above... 
/code/3 - SV.ipynb: ... same as above...
/code/4 - C + significant correlations.ipynb: ... same as above...
/code/5 - CBF + BOLD + FCS.ipynb: ... same as above...
/code/6 - C + FCS + ranked FCS + Graphs.ipynb: ... same as above...
/code/7 - C vs size area.ipynb: ... same as above...











