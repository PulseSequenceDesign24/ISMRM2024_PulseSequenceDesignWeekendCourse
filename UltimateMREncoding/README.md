Ultimate MR Encoding
====================

_Lars Kasper, PhD, Toronto Neuroimaging Facility (ToNI), Department of Psychology, University of Toronto_


Deconstructing the Pulse Sequence Diagram
-----------------------------------------

1. RF
2. Gradients: Trajectories
    - Tilted Hexagonal Grids (T-Hex): [Grid Generator Code](https://gitlab.ethz.ch/mengel/thex) and [SMS-Diffusion T-Hex Connectome Data](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.29953) (Search for Data Availability Statement to find access details)
    - Julia Reconstruction of non-Cartesian trajectory data (e.g,. spirals): [MRIReco.jl](https://github.com/MagneticResonanceImaging/MRIReco.jl) and [GIRFReco.jl](https://github.com/BRAIN-TO/GIRFReco.jl)
3. Acquisition
4. Beyond Encoding Images: [ISMRM MR Academy on YouTube: MR Fingerprinting (Dan Ma)](https://www.youtube.com/watch?v=zWO09lNGYao&list=PLbkiZxYouIu4koswmke1ZVjZrFLhkCGeb&index=4)

Tools for Assessing Encoding
----------------------------

- Acquisition Efficiency: Comparison Table and Trajectory Generation [Educational Code related to  chapter 24: _"BOLD fMRI: Physiology and Acquisition strategies"_ (Kâmil Uludağ and Lars Kasper) in book *"Ultra High Field Neuro MRI"*](https://github.com/BRAIN-TO/book-chapter-uhf-neuro-mri)
- Sensitivity Analysis
- Point Spread Function (Resolution Limits)

[ISMRM MR Academy on YouTube: Reconstruction Methods for Undersampled Data (Jeff Fessler)](https://www.youtube.com/watch?v=itO5SnNKwdE&list=PLbkiZxYouIu4koswmke1ZVjZrFLhkCGeb)