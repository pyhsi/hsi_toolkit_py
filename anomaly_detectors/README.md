# Gatorsense hsitoolkit anomaly detectors Python version
hsi_toolkit_py/anomaly_detectors

Current suite of anomaly detectors:
- rx_anomaly: local anomaly detector, Widowed Reed-Xiaoli anomaly detector uses local mean and covariance to determine pixel to background distance
- gmm_anomaly: global anomaly detector, fits GMM assuming entire image is background computes negative log likelihood of each pixel in the fit model
- md_anomaly: global anomaly detector, Mahalanobis Distance anomaly detector uses global image mean and covariance as background estimates
- cbad_anomaly: global/cluster-based anomaly detector, Cluster Based Anomaly Detection (CBAD)
- csd_anomaly: global anomaly detector, Complementary Subspace Detector


Suite of Anomaly Detectors in progress:
- ssrx_anomaly: local anomaly detector, eliminate leading subspace as background, then use local mean and covariance to determine pixel to background distance
- beta_anomaly: global anomaly detector, fits beta distribution to each band assuming entire image is background computes negative log likelihood of each pixel in the model
- fcbad_anomaly: global/cluster-based anomaly detector, Fuzzy Cluster Based Anomaly Detection (FCBAD)
- !gmrx_anomaly: global/cluster-based anomaly detector, fits GMM assuming entire image is background assigns pixels to highest posterior probability mixture component computes pixel Mahlanobis distance to component mean

Contact: Alina Zare, azare@ufl.edu
