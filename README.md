# Stratifed-Medium Sound Speed Profiling for CPWC Ultrasound Imaging
### Abstract
Coherent plane-wave compounding (CPWC) ultrasound is an important modality enabling ultrafast biomedical imaging. To perform CWPC image reconstruction for a stratified (horizontally layered) medium, one needs to know how the speed of sound (SOS) varies with the propagation depth. Incorrect sound speed and layer thickness assumptions can cause focusing errors, degraded spatial resolution and significant geometrical distortions resulting in poor image reconstruction. We aim to determine the speed of sound and thickness values for each horizontal layer to accurately locate the recorded reflection events to their true locations within the medium. Our CPWC image reconstruction process is based on phase-shift migration (PSM) that requires the user to specify the speed of sound and thickness of each layer in advance. Prior to performing phase-shift migration (one layer at a time, starting from the surface), we first estimate the speed of sound values of a given layer using a cosine similarity metric, based on the data obtained by a multi-element transducer array for two different plane-wave emission angles. Then, we use our speed estimate to identify the layer thickness via end-of-layer boundary detection. A low-cost alternative that obtains reconstructed images with fewer phase shifts (i.e., fewer complex multiplications) using a spectral energy threshold is also proposed in this thesis. Our evaluation results, based on the CPWC imaging simulation of a three-layer medium, show that our sound speed and layer thickness estimates are within 4% of their true values (i.e., those used to generate simulated data). We have also confirmed the accuracy of our speed and layer thickness estimation separately, using two experimental datasets representing two special cases. For speed estimation, we used a CPWC imaging dataset for a constant-speed (i.e., single-layer) medium, yielding estimates within 1% of their true values. For layer thickness estimation, we used a monostatic (i.e., single-element) synthetic-aperture (SA) imaging dataset of the three-layer medium, also yielding estimates within 1% of their true values. Our evaluation results for the low-cost alternative showed a 93% reduction in complex multiplications for the three-layer CPWC imaging dataset and 76% for the three-layer monostatic SA imaging dataset, producing images nearly similar to those obtained using the original PSM methods.

### Thesis Link
http://hdl.handle.net/1828/11925

### IEEE Publication Link
 https://ieeexplore.ieee.org/document/9251457

