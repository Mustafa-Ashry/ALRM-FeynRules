This repository contains the following material

1. (ALRM_LO.fr) FeynRules alternative left-right symmetric model (ALRM) files at leading order.

2. (ALRM_LO_hgg_haa.fr) FeynRules alternative left-right symmetric model files at leading order with Higgs-Gamma-Gamma and Higgs-Gluon-Gluon effective vertices.

3. (ALRM_LO.nb) Mathematica notebook which loads the model and performs basic checks .

4. Madgraph UFO, CalcHEP, FeynArts, SHERPA, WHIZARD and ASperge model files (ALRM_LO_UFO, _CH, _FA, _SH, _WO, _MD).

Please cite
1. M. Ashry and S. Khalil, Phenomenological aspects of a TeV-scale alternative left-right model, Phys. Rev. D 91, 015009
2. M. Ashry, MSc Thesis, Cairo University (2015) [https://inspirehep.net/literature/2708563]

Introduction to the Alternative Left-Right Symmetric Model (ALRM)

Model Description

The Alternative Left-Right Symmetric Model (ALRM) is gauged by the Left-Right symmetry group SU(3)C×SU(2)L×SU(2)R×U(1)B-L. The latter B and L being the baryon and lepton numbers. An extra discrete symmetry S is imposed to distinguish between Higgs fields and their dual fields and hence their interactions; causing the absence of the tree-level flavor-changing neutral currents mediated by Higgs bosons.

As in the SM, left-handed fermions compose SU(2)L doublets. Right-handed charged leptons form SU(2)R doublets with corresponding extra particles (scotinos) and right-handed up-quarks form SU(2)R doublets with corresponding extra down-type exotic quarks. Right-handed neutrinos and down-quarks are SU(2)L,R singlets. The Higgs sector composes of an SU(2)L-doublet, an SU(2)R-doublet and a bidoublet.

The electroweak left-right symmetry SU(2)L×SU(2)R×U(1)B-L is spontaneously broken down to the SM electroweak symmetry SU(2)L×U(1)Y, Y being the hypercharge, by the SU(2)R-doublet vev, then the SM electroweak symmetry is spontaneously broken down to the U(1)em through the bidoublet and the SU(2)L-doublet vevs. Accordingly, all fermions and gauge bosons (except of course photon) become massive via Higgs mechanism. The physical gauge sector of the model contains the electroweak gauge bosons (photon, W and Z bosons, whose masses were fixed by the experimental SM values) in addition to two extra gauge bosons (W' and Z' ) correspond to the SU(2)R group, analogous to those of the SU(2)L group. Also the Weinberg angle is fixed here as an input parameter by its experimental value.

Dirac (massive) neutrinos are considered with the mixing MNS matrix implemented in the normal hierarchy. The case of Majorana neutrinos is considered in many other models' files and any type of seesaw mechanisms can be brought to be implemented here easily. Three mixed generations of quarks are considered and hence the general case of the CKM matrix is implemented. In addition, the generic case of nonmanifest left-right symmetry is considered, that is the left and right gauge couplings gL,gR, quark mixing matrices CKML,CKMR and lepton mixing matrices MNSL,MNSR are NOT in general coincident.

The model contains ten physical Higgs bosons: four neutral CP-even higgs bosons, one (the lightest) of which is considered to be the SM-like one with mass fixed to have the value mh=125 GeV. Four charged Higgs bosons and two CP-odd pseudoscalar Higgs bosons. The mass spectra are calculated and the rotation matrices are implemented analytically.

Minimization conditions and spectrum relations are all used to express the whole model parameters and spectra in terms of only five independent (external) parameters: tanbeta, lambda2, lambda3, alpha1, alpha2 and mu3,. As in any two-Higgs doublet model, e.g., MSSM, tanbeta is the ratio between two vevs. The parameters lambda2, lambda3, alpha1, alpha2 are dimensionless potential parameters, while mu3, is a dimension-full potential parameter.

Full analysis of the Higgs sector is presented analytically as in Ref. [2]. The rotation matrices in all cases of scalar, pseudo scalar and charged Higgs are presented in the most general way which is applicable to any other model and to all dimensions.

The effective loop-induced scalar and pseudoscalar higgs-gluon-gluon and higgs-gamma-gamma vertices were implemented at leading order (LO). For the complete gg->gammagamma and pp->gammagamma analysis, Madgraph is used as the Monte Carlo (MC) event generator (EG), then Pythia is used for parton showering (PS), and for matrix element (ME) and PS merging, and also for hadronization and jet matching. Afterward, Delphes is used as a detector simulator, and Madanalysis is used for event file analysis and in recasting the LHC results. Finally, Root is used to produce the histogram figures at [https://feynrules.irmp.ucl.ac.be/wiki/ALRM]
