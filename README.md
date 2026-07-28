# Rene Andrade Rey

**Physician & Neuroimaging Researcher**

I build reproducible neuroimaging workflows across structural MRI, task and resting-state fMRI, diffusion MRI, MEG, EEG, and PET.

My work emphasizes transparent processing, quality control, cross-software validation, open science, and technically documented analysis pipelines.

## Featured completed projects

| Modality | Project | Main tools | Repository | Zenodo |
|---|---|---|---|---|
| Diffusion MRI | Preprocessing, DTI, CSD, tractography, SIFT, and quantitative QC | MRtrix3, FSL Eddy | [View project](https://github.com/andraderenew/diffusion-mri_mrtrix3_fsl_single_subject) | [10.5281/zenodo.21650417](https://doi.org/10.5281/zenodo.21650417) |
| Task fMRI | Auditory first-level analysis and cross-software replication | SPM25, FSL FEAT | [View project](https://github.com/andraderenew/fmri-task_spm_firstlevel_auditory) | [10.5281/zenodo.21650414](https://doi.org/10.5281/zenodo.21650414) |
| Resting-state fMRI | Functional connectomics, graph analysis, hubs, and BRAPH-ready exports | Nilearn, NetworkX, FSL, BRAPH-ready outputs | [View project](https://github.com/andraderenew/fmri-rest_fsl-graphs_braph_adhd200-preproc) | [10.5281/zenodo.21650416](https://doi.org/10.5281/zenodo.21650416) |
| MEG | Median-nerve ERFs, dSPM source reconstruction, and time-frequency analysis | Brainstorm, dSPM, Morlet wavelets | [View project](https://github.com/andraderenew/meg_erfs-sources_brainstorm_median-nerve) | [10.5281/zenodo.21650415](https://doi.org/10.5281/zenodo.21650415) |
| Structural MRI | Tissue segmentation, quality control, global volumes, and VBM preparation | CAT26, SPM25, MATLAB | [View project](https://github.com/andraderenew/structural-mri_cat12_single_subject) | [10.5281/zenodo.21650422](https://doi.org/10.5281/zenodo.21650422) |
| Structural MRI | Cortical reconstruction, morphometry, regional statistics, and Freeview QC | FreeSurfer 7.4.1 | [View project](https://github.com/andraderenew/structural-mri_freesurfer_single_subject) | [10.5281/zenodo.21650423](https://doi.org/10.5281/zenodo.21650423) |

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

## Portfolio scaffolds

These repositories are archived and citable, but their current README files describe planned workflows rather than completed scientific analyses.

| Modality | Planned workflow | Repository | Zenodo |
|---|---|---|---|
| Diffusion MRI | FSL DTIFIT tutorial with optional TOPUP/EDDY, FA/MD maps, and ROI summaries | [View project](https://github.com/andraderenew/dti_fsl-dtifit_tutorial) | [10.5281/zenodo.21650517](https://doi.org/10.5281/zenodo.21650517) |
| Structural MRI | CAT12 versus FreeSurfer morphometry agreement on OASIS-1 | [View project](https://github.com/andraderenew/structural-mri_cat12-vs-freesurfer_oasis1) | [10.5281/zenodo.21650518](https://doi.org/10.5281/zenodo.21650518) |
| EEG | ERPs and time-frequency analysis with EEGLAB and FieldTrip | [View project](https://github.com/andraderenew/eeg_erps-tf_eeglab-fieldtrip_sternberg) | [10.5281/zenodo.21650530](https://doi.org/10.5281/zenodo.21650530) |
| EEG | LORETA/eLORETA source imaging and Brainstorm PTE/dPTE connectivity | [View project](https://github.com/andraderenew/eeg_sources-connectivity_loreta-brainstorm_pte) | [10.5281/zenodo.21650521](https://doi.org/10.5281/zenodo.21650521) |

## Technical toolkit

**Neuroimaging**

SPM · FSL/FEAT · FreeSurfer · CAT · Brainstorm · MRtrix3 · BRAPH · EEGLAB · FieldTrip

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