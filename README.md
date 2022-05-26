# Beta-VAE
Final Project

preprocess.m-parceltion of the data.

geometric_reformatting.m- geometric_reformatting file which outputs a mat file called fMRI.mat and an h5 file called 100610.h5 into the data folder.

VAE_inference.py-uses the latent variables to generate reconstructed images as mat files. 

backward_reformatting.m-converts the data back into a cifti file.

correlation_sub_vec.m-do corrcoef to the z latent.for each subject find the max correlation.

RESULTS_VAE.py-use the csv file the take the family id of the subjects.

how to use the code:

run preprocess.m

run geometric_reformatting.m

run VAE_inference.py

run backward_reformatting.m

run correlation_sub_vec.m

run VAE_results.py

![image](https://user-images.githubusercontent.com/96918517/170554885-da1e5259-c653-43c7-aee4-9f0f16fe8e8b.png)

