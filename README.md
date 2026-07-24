# Rene Andrade Rey

**Physician & Neuroimaging Researcher**

I build reproducible neuroimaging workflows across structural MRI, task and resting-state fMRI, diffusion MRI, MEG, EEG, and PET.

My work emphasizes transparent processing, quality control, cross-software validation, open science, and technically documented analysis pipelines.

## Featured completed projects

| Modality | Project | Main tools | Repository |
|---|---|---|---|
| Task fMRI | Auditory first-level analysis and cross-software replication | SPM25, FSL FEAT | [View project](https://github.com/andraderenew/fmri-task_spm_firstlevel_auditory) |
| MEG | Median-nerve ERFs, source reconstruction, and time-frequency analysis | Brainstorm, dSPM, Morlet wavelets | [View project](https://github.com/andraderenew/meg_erfs-sources_brainstorm_median-nerve) |
| Structural MRI | Tissue segmentation, quality control, global volumes, and VBM preparation | CAT26, SPM25, MATLAB | [View project](https://github.com/andraderenew/structural-mri_cat12_single_subject) |

### Task fMRI — SPM25 and FSL FEAT

Single-subject analysis of the classic SPM Auditory dataset, implemented independently in SPM25 and FSL FEAT.

- Contrast: **Listening > Rest**
- Motion quality control
- First-level GLM
- Statistical maps and cluster tables
- Cross-software comparison
- DOI: [10.5281/zenodo.17715106](https://doi.org/10.5281/zenodo.17715106)

### MEG — Brainstorm median-nerve analysis

Reproduction of the Brainstorm median-nerve workflow.

- Sensor-level event-related fields
- Early somatosensory topography at approximately 20 ms
- Minimum-norm dSPM source reconstruction
- Morlet time-frequency analysis from 4 to 80 Hz
- DOI: [10.5281/zenodo.17715113](https://doi.org/10.5281/zenodo.17715113)

### Structural MRI — CAT26 and SPM25

Single-subject T1-weighted structural MRI workflow.

- Bias-field correction
- Grey matter, white matter, and CSF segmentation
- Spatial normalization and modulation
- CAT quality-control assessment
- Global tissue-volume extraction
- Preparation of smoothed grey matter for VBM

## Current projects

- [FreeSurfer single-subject cortical reconstruction](https://github.com/andraderenew/structural-mri_freesurfer_single_subject)
- [Resting-state functional connectivity and graph analysis](https://github.com/andraderenew/fmri-rest_fsl-graphs_braph_adhd200-preproc)

These repositories are listed as work in progress until their analyses, documentation, and final outputs are complete.

## Technical toolkit

**Neuroimaging**

SPM · FSL/FEAT · FreeSurfer · CAT · Brainstorm · MRtrix3 · BRAPH · EEGLAB · FieldTrip

**Programming and reproducibility**

Python · MATLAB · Bash · Git · BIDS · statistical modelling · scientific visualization

## Research interests

- Structural and functional brain connectivity
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
