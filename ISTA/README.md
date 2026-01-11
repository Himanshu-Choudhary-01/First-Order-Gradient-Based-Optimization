ISTA


This is Iterative Shrinkage Thresholding Algorithm (ISTA) for solving LASSO problem. LASSO problem assumes that signal x be sparse, and this assumption is not wrong. Most natural siggnal can be represented sparse in some domain. For example, natural scenes are sparse in Fourier transform domain or DCT domain. Sometimes the scene itself can be very sparse (e.g. stars at night). <br>

ISTA is a first-order method which is gradient-based so it is simple and efficient. However, its convergence is slow - O(1/k). A fast ISTA (FISTA) is developed for faster convergence, which gives an improved complexity, O(1/(k^2)). <br>

Here we will compare the LASSO problem with ISTA/FISTA to RLS problem with CG. You will see ISTA/FISTA work well on the sparse signal while RLS doesn't. You will see the improved performance of FISTA over ISTA as well.
