# mFAST
A Matlab toolbox for first arrival time tomography is presented.


We limit our code in the field of ocean bottom seismometer (OBS) survey (Figure 1) based on two factors. First, OBS survey becomes common in the study of deep structure beneath ocean, hence the code is meaningful. Secondly, since OBS is mostly deployed with a large spacing, the computational cost is substantially reduced when compared to the dense receiver case. This makes it possible to run a tomography job in the Matlab setting. For other types of geometry such as the first arrival tomography for near-surface imaging, the computational cost is much large and more efficient code should be chosen.
First arrival seismic tomography is a nonlinear inverse problem.Currently, within our toolbox, only the local linearization method has been implemented. It starts from an initial model and travel time tables. The codes contains the following parts : (1) data structure, (2) model parameterization, (3) ray-tracing, (4) jacobi matrix construction, (5) regularization and smoothing and (6) solving a large scale system of linear equations.
only Matlab is required.
It could also run on Octave.
