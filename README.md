# Shane PSF Reconstruction 

Adaptive optics (AO) systems correct the distortions to the incoming wavefront by using a deformable mirror (DM) and wavefront sensor (WFS). However, such corrections are extremely challenging and necessarily imperfect due to noise limitations, the rapidly evolving atmosphere and other systematic issues. This results in an imperfect point-spread function (PSF), with quasi-static speckles which can evolve over a range of timescales. One potential avenue to address these issues is to develop algorithms which can use telescope telemetry (e.g. WFS data, DM positions, CCD parameters) to model the what the expected PSF distortions are. Machine learning models are a promising way to test this approach. 

Here we present a small dataset of wavefront sensory data (ShaneAO; 3m-Shane telescope at Lick Observaotry) and matched science camera images (from the ShARCS near-infrared instrument) that can be used for PSF reconstruction. The goal of this project is to provide a dataset which can be used to test machine learning algorithms and determine: 1) what is the best approach for modelling PSFs in the presense of diverse atmospheric conditions and inconsistently sampled data and 2) what telemetetry carries a useful signal to determine the PSF shape. Potential learnings can then be transferred to other AO systems on other telescopes. 

At the moment the dataset consists of 5,178 matched wavefront sensor and image pairs, but will be expanded in future after more data is processed. 

**Currently off sick during SPIE, so to get access to the data please contact me at: 'a.chaushev@uci.edu'. Thank you!** 

