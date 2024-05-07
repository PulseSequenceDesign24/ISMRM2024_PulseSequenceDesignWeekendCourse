Ultimate MR Encoding
====================

_Lars Kasper, PhD, Toronto Neuroimaging Facility (ToNI), Department of Psychology, University of Toronto_


Deconstructing the Pulse Sequence Diagram
-----------------------------------------

1. RF
2. Gradients: Trajectories
    - Tilted Hexagonal Grids (T-Hex): 
        - [Grid Generator Code](https://gitlab.ethz.ch/mengel/thex)
        - [Pulseq file](THex_MB3_RF_VERSE_ExampleSequence.seq.seq) for 3 simultaneously excited slices (MB=3), single shot, VERSE RF Pulse
            - [Earlier version of Pulseq file](THex_MB3_LowADC_ExampleSequence) for same T-Hex version (simpler RF pulse and wrong ADC)
        - [SMS-Diffusion T-Hex Connectome Data](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.29953) (Search for Data Availability Statement to find access details)
        - [Holocene Sampling ISMRM24 Abstract](https://submissions.mirasmart.com/ISMRM2024/ViewSubmissionFile.aspx?mode=videoabs&validate=false&sbmID=3352) on generalizations of T-Hex and CAIPIRINHA for non-integer undersampling factors R
    - Julia Reconstruction of non-Cartesian trajectory data (e.g,. spirals): [MRIReco.jl](https://github.com/MagneticResonanceImaging/MRIReco.jl) and [GIRFReco.jl](https://github.com/BRAIN-TO/GIRFReco.jl)
3. Acquisition
4. Beyond Encoding Images: [ISMRM MR Academy on YouTube: MR Fingerprinting (Dan Ma)](https://www.youtube.com/watch?v=zWO09lNGYao&list=PLbkiZxYouIu4koswmke1ZVjZrFLhkCGeb&index=4)

Tools for Assessing Encoding
----------------------------

1. Acquisition Efficiency: Comparison Table and Trajectory Generation [Educational Code related to  chapter 24: _"BOLD fMRI: Physiology and Acquisition strategies"_ (Kâmil Uludağ and Lars Kasper) in book *"Ultra High Field Neuro MRI"*](https://github.com/BRAIN-TO/book-chapter-uhf-neuro-mri)
2. Sensitivity Analysis
3. Information Correlation: Resolution and Point Spread Functions
    - Reconstructions utilizing Signal Correlations: [ISMRM MR Academy on YouTube: Reconstruction Methods for Undersampled Data (Jeff Fessler)](https://www.youtube.com/watch?v=itO5SnNKwdE&list=PLbkiZxYouIu4koswmke1ZVjZrFLhkCGeb)