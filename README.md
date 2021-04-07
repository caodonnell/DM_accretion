This repository will (eventually) contain files and scripts related to my research into correlating dark matter accretion and galaxy star formation [(O'Donnell et al., 2021)](https://academic.oup.com/mnras/article/501/1/1253/6006290?guestAccessKey=5ee6716e-d4ac-4555-bc4e-e379e639f4f5).

Currently, this repo houses the isolated host (and associated random) files used in the analysis:
* **SDSS/**: data files derived from SDSS DR16
  * **!notes**: description of the catalog columns for files in this directory
  * **isolated_hosts_10.5_11.0.txt**: catalog of isolated hosts in the stellar mass range 10.5 < \log_{10}(M_*/M_\odot) < 11.0
  * **isolated_hosts_11.0_11.5.txt**: catalog of isolated hosts in the stellar mass range 11.0 < \log_{10}(M_*/M_\odot) < 11.5
  <!--* **isolated_hosts_10.5_11.0.txt**: catalog of isolated hosts in the stellar mass range ![equation](https://latex.codecogs.com/gif.latex?10.5%20%3C%20%5Clog_%7B10%7D%28M_*/M_%5Codot%29%20%3C%2011.0)-->
  <!--* **isolated_hosts_11.0_11.5.txt**: catalog of isolated hosts in the stellar mass range ![equation](https://latex.codecogs.com/gif.latex?11.0%20%3C%20%5Clog_%7B10%7D%28M_*/M_%5Codot%29%20%3C%2011.5)-->

* **UniverseMachine/**: data files dervied from the UniverseMachine (Behroozi et al. 2019)
  * **!notes**: description of the catalog columns for files in this directory
  * Within each snapshot folder:
    * **isolated_hosts_a_10.5_11.0.txt**: catalog (with scale factor $a$) of isolated hosts in the stellar mass range 10.5 < \log_{10}(M_*/M_\odot) < 11.0
    * **isolated_hosts_a_11.0_11.5.txt**: catalog (with scale factor $a$) of isolated hosts in the stellar mass range 11.0 < \log_{10}(M_*/M_\odot) < 11.5

As described in [O'Donnell et al. (2021)](https://academic.oup.com/mnras/article/501/1/1253/6006290?guestAccessKey=5ee6716e-d4ac-4555-bc4e-e379e639f4f5), the mass function of the UniverseMachine differs from the mass function in SDSS (Sec. 3.3.1, including Fig. 10 and Table 1). In our work (and the filenames in this repo), we use SDSS mass values.
	
  
  