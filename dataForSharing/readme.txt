A description of the .mat file contents can be found below along with a description of the data. Feel free to use the included data but please cite Jespersen et al., "Diffusion time dependence of microstructural parameters in fixed spinal cord", NeuroImage 2017, (https://doi.org/10.1016/j.neuroimage.2017.08.039).



.mat file contents:

Nexp:
The number of experiments.

x_dim, ydim:
Number of voxels along the spatial x-dimension/y_dimension.

diff_dim:
Number of gradient realizations.

size1:
Total number of data points (x_dim x y_dim x diff_dim).

Delta:
Contains the diffusion time for the experiments.

Res1:
Is the (x_dim x y_dim x diff_dim) data matrix

diffparams:
Struct containing the fields
	
	b_mtx:
	Contains the b-matrices.

	num_dir:
	The number of gradient directions.

	num_A0/num_b:
	The number of b-values.

	eff_b_vals:
	Contains the effective b-value for each b-matrix.

	grad_dirs:
	Gradient directions.



Description: (see https://doi.org/10.1016/j.neuroimage.2017.08.039)

Fixed porcine spinal cord was imaged with a stimulated echo diffusion imaging sequence (EPI) on a 16.4T Bruker Aeon Ascend magnet interfaced with an AVANCE IIIHD console, and equipped with a micro5 probe with gradients capable of producing up to 3000 mT/m in all directions. Spinal cord specimens were obtained from domesticated adult pigs, and the tissues were immersed in 4% PFA roughly 30 minutes post-mortem. The samples were kept in PFA for at least 48h prior to washing with PBS, and placement in a 10 mm NMR tube filled with Fluorinert (Sigma Aldrich, Portugal). The sample was then imaged using a 10 mm birdcage coil tuned for 1H.

Six b=0 images were acquired, as well as six b-value shells from 0.5 to 3 ms/µm2. Each shell was encoded using the nine directions for the 199 DKI scheme (Hansen et al., 2015). Such data sets were acquired for 57 diffusion times ranging from 6 ms to 350 ms with 4 averages each. Across these data sets, the following imaging parameters were kept constant: TE=16 ms, TR=7.5 s, in-plane resolution 140 µm x140 µm, slice thickness = 2.2 mm, and gradient pulse width of 1.15ms. Sample temperature was maintained at 25°C throughout using air flow.
