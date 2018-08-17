*BNN PROJECT*

* 20180803: experiment with VI for BNN (fixed g):
        https://melaniefp.github.io/bnn/20180803_bnn_vi_fixed_g/ACTIVATION=rbf-DIM_U=2.html

* 20180815: learning projection from multiple restarts using PCA + BBVI to infer projected weights.
test log likelihood results for different real datasets and types of initializations:
	- random
	- warm_mr (warm_multiple_restarts) empirical mean and isotropic covariance matrix based on the sets of weights.
	https://melaniefp.github.io/bnn/20180815_vi_pca_diff_init/TYPE=avg_llh_test-INIT=random-DB=boston.html

* 20180816: learning different projections from multiple restarts using BBVI.
    https://melaniefp.github.io/bnn/20180816_vi_diff_proj/TYPE=avg_llh_test-INIT=random-DB=yacht-PROJ=ica.html
