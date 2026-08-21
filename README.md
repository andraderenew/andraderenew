# Rene Andrade Rey

**Physician & Neuroimaging Researcher**

I build reproducible neuroimaging workflows across structural MRI, task and resting-state fMRI, diffusion MRI, MEG, EEG, and PET.

My work emphasizes transparent processing, quality control, cross-software validation, open science, and technically documented analysis pipelines.

## Featured completed projects

| Modality | Project | Main tools | Repository | Zenodo |
|---|---|---|---|---|
| Diffusion MRI | Preprocessing, DTI, CSD, tractography, SIFT, and quantitative QC | MRtrix3, FSL Eddy | [View project](https://github.com/andraderenew/diffusion-mri_mrtrix3_fsl_single_subject) | [10.5281/zenodo.21629553](https://doi.org/10.5281/zenodo.21629553) |
| Task fMRI | Auditory first-level analysis and cross-software replication | SPM25, FSL FEAT | [View project](https://github.com/andraderenew/fmri-task_spm_firstlevel_auditory) | [10.5281/zenodo.17715105](https://doi.org/10.5281/zenodo.17715105) |
| Resting-state fMRI | Functional connectomics, graph analysis, hubs, and BRAPH-ready exports | Nilearn, NetworkX, FSL, BRAPH-ready outputs | [View project](https://github.com/andraderenew/fmri-rest_fsl-graphs_braph_adhd200-preproc) | [10.5281/zenodo.17715117](https://doi.org/10.5281/zenodo.17715117) |
| MEG | Median-nerve ERFs, dSPM source reconstruction, and time-frequency analysis | Brainstorm, dSPM, Morlet wavelets | [View project](https://github.com/andraderenew/meg_erfs-sources_brainstorm_median-nerve) | [10.5281/zenodo.17715112](https://doi.org/10.5281/zenodo.17715112) |
| EEG | Group-level ERPs, time-frequency power, and exact paired cluster-permutation statistics | EEGLAB, FieldTrip, MATLAB | [View project](https://github.com/andraderenew/eeg_erps-tf_eeglab-fieldtrip_sternberg) | [10.5281/zenodo.21826210](https://doi.org/10.5281/zenodo.21826210) |
| Structural MRI | Tissue segmentation, quality control, global volumes, and VBM preparation | CAT26, SPM25, MATLAB | [View project](https://github.com/andraderenew/structural-mri_cat12_single_subject) | [10.5281/zenodo.21629555](https://doi.org/10.5281/zenodo.21629555) |
| Structural MRI | Cortical reconstruction, morphometry, regional statistics, and Freeview QC | FreeSurfer 7.4.1 | [View project](https://github.com/andraderenew/structural-mri_freesurfer_single_subject) | [10.5281/zenodo.21629557](https://doi.org/10.5281/zenodo.21629557) |
| PET | Dynamic FDG PET, SUVR, PETPVE12 PVC, regional analysis, and PSF sensitivity | FSL MCFLIRT, SPM12, PETPVE12 | [View project](https://github.com/andraderenew/pet_fdg-suvr-pvc_spm-petpve12_openneuro-ds002898) | Pending Zenodo integration repair |

## Completed workflow highlights

### Diffusion MRI — MRtrix3 and FSL

Reproducible single-subject diffusion MRI workflow using public MPI-LEMON data.

- MP-PCA denoising and Gibbs-ringing correction
- Motion, eddy-current, and outlier correction with FSL Eddy
- Diffusion tensor fitting with FA, MD, AD, and RD maps
- Single-shell constrained spherical deconvolution
- Probabilistic iFOD2 whole-brain tractography
- SIFT filtering and track-density imaging
- Automated quality-control figures and quantitative summaries

### Task fMRI — SPM25 and FSL FEAT

Single-subject analysis of the classic SPM Auditory dataset, implemented independently in SPM25 and FSL FEAT.

- Contrast: **Listening > Rest**
- Motion quality control
- First-level GLM
- Statistical maps and cluster tables
- Cross-software comparison

### Resting-state fMRI — Functional connectomics and graph analysis

Ten-subject ADHD-200 preprocessed resting-state workflow using the Schaefer-100 atlas.

- Nuisance regression and temporal filtering
- Subject-level Pearson connectivity matrices
- Fisher-z group averaging
- Minimum-spanning-tree plus 15% density graph construction
- NetworkX graph metrics, communities, hubs, and small-world analysis
- BRAPH-ready matrix and label exports

### MEG — Brainstorm median-nerve analysis

Reproduction of the Brainstorm median-nerve workflow.

- Sensor-level event-related fields
- Early somatosensory topography at approximately 20 ms
- Minimum-norm dSPM source reconstruction
- Morlet time-frequency analysis from 4 to 80 Hz

### EEG — STERN ERPs and time-frequency analysis

Completed group-level analysis of the EEGLAB STERN tutorial study using EEGLAB and FieldTrip.

- 13 participants, 39 condition-specific datasets, 9,678 epochs, and 20,697 events
- ERP and 4–30 Hz time-frequency analysis across 69 common scalp channels
- Primary event-matched contrast: **Memorize − Ignore**
- Positive ERP cluster from 440–552 ms and negative ERP cluster from 632–760 ms
- Negative time-frequency cluster spanning 4–26 Hz and 0.00–1.40 s
- Exact paired cluster tests using all 8,192 possible within-subject permutations
- Subject-level and leave-one-subject-out robustness checks

![Primary EEG time-frequency contrast](https://raw.githubusercontent.com/andraderenew/eeg_erps-tf_eeglab-fieldtrip_sternberg/main/results/figures/stern_tf_Memorize_minus_Ignore_sensor_average.png)

### Structural MRI — CAT26 and SPM25

Single-subject T1-weighted structural MRI workflow.

- Bias-field correction
- Grey matter, white matter, and CSF segmentation
- Spatial normalization and modulation
- CAT quality-control assessment
- Global tissue-volume extraction
- Preparation of smoothed grey matter for VBM

### Structural MRI — FreeSurfer

Single-subject cortical reconstruction and morphometry using OpenNeuro ds000114.

- Complete `recon-all` cortical reconstruction
- Parallel execution with `-openmp 8`
- Subcortical and global volumetric statistics
- Cortical thickness, area, and volume by Desikan–Killiany region
- Coronal, sagittal, and axial Freeview quality-control figures

### PET — FDG SUVR and PETPVE12 partial-volume correction

Completed, quality-controlled single-subject research portfolio demonstration using public OpenNeuro dataset ds002898, subject sub-01.

- 225 dynamic FDG PET frames selected from approximately 30 to 90 minutes
- 2.8 mm isotropic resampling and FSL MCFLIRT motion correction
- Static PET construction, SPM12 tissue segmentation, and PET-to-T1 coregistration
- PETPVE12 Müller–Gärtner partial-volume correction at nominal 4, 5, 6, and 8 mm PSF values
- Bilateral cerebellar-cortex SUVR and Desikan–Killiany regional summaries
- 84 predefined primary grey-matter ROIs; 81 form the post hoc QA robustness subset (GM support >=20 voxels)
- Robust cerebellar-normalized PVC-SUVR PSF CV: median 1.437%, maximum 6.037%
- Robust pre-normalization PVC-activity PSF CV: median 3.029%, maximum 8.587%
- Final workflow validation passed
- Research portfolio demonstration only; not clinical or diagnostic software

## Current methodological comparison

| Modality | Project | Status | Repository |
|---|---|---|---|
| Structural MRI | CAT26/SPM25 versus FreeSurfer on the same OpenNeuro `ds000114` T1-weighted image | Current descriptive cross-method comparison; no population inference or completed region-by-region agreement claim | [View project](https://github.com/andraderenew/structural-mri_cat26-vs-freesurfer_openneuro-ds000114) |

Archived historical scaffolds that have been superseded or discontinued are intentionally omitted from the active portfolio presentation.

## Technical toolkit

**Neuroimaging**

SPM · FSL/FEAT · FreeSurfer · CAT26 · Brainstorm · MRtrix3 · PETPVE12 · BRAPH · EEGLAB · FieldTrip

**Programming and reproducibility**

Python · MATLAB · Bash · Git · BIDS · statistical modelling · scientific visualization

## Research interests

- Structural and functional brain connectivity
- Diffusion MRI and tractography
- Reproducible neuroimaging
- Multimodal integration
- Neuroimaging quality control
- Source imaging
- Graph-theoretical analysis
- Clinical and translational neuroscience

## Research profiles

- [ORCID: 0000-0001-5627-579X](https://orcid.org/0000-0001-5627-579X)
- [Google Scholar](https://scholar.google.es/citations?hl=en&user=Nl3ApFEAAAAJ)
- [LinkedIn](https://www.linkedin.com/in/rene-andrade-rey-5b847b40)

---

Raw neuroimaging data are generally excluded from the repositories. Each completed project documents its data source, processing decisions, software environment, outputs, and limitations.

<!-- profile-refresh: 2026-08-17T14:59:00+02:00 -->
