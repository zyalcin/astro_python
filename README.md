# astro_python
# Work done for Astronomical calculations using Python. Includes membership classification of NGC 6633, radial velocity graphs and universe expansion models.

#### "classification.ipynb" This project combine data science, data sets, statistical analysis with astronomy. Determining star membership based on 3 characteristics. Starting membership on database: More than 6500 members. 

Step 1: Making parallax cuts based on the GAIA dr3 dataset and using statistical analysis, clear Gaussian cut. Calculated parallax: 2.74725274725 milliarcseconds. 
Final applied parallax cuts: 1.4 and 3.1
Step 2: Making proper motion cuts. Right skewed distribution. Final cut made at 15 PM. value. Cuts match 350 members remain.
Step 3: Making magnitude cuts using photometry. Based on the statistical trends & correspondence to the image itself cut off magnitude set as 17.8

Cuts made using parallax, proper motion and magnitudes reveal that in an area of 3.5’ there are 70 stars that are definitely a member of the open cluster NGC 6633.


#### "galaxy_models.ipynb" This notebook solves for bound, unbound and critical universes using parametric equations and numerical integration and plots the expansion models of the bound, unbound and critical universes. 

#### "radial_velocity.ipynb" This notebook plots the radial velocity of a galaxy, where V is in km/s and R is in kpc.

