# Connectomics Workshop for the CNC Forum: Winter 2025


## Presentation 1: 15 January 2025

Forrest Collman, PhD, Associate Director at the Allen Institute for Brain Science

John Tuthill, PhD, Associate Professor at University of Washington

Sven Dorkenwald, PhD, Shannahan Fellow at the Allen Institute

Bethanny Danskin, PhD, Scientist I at the Allen Institute for Brain Science

## Presentation 2: 19 February 2025

Nuno da Costa, PhD, Associate Investigator at the Allen Institute for Brain Science

Sven Dorkenwald, PhD, Shannahan Fellow at the Allen Institute

Bethanny Danskin, PhD, Scientist I at the Allen Institute for Brain Science


## Non-Programmatic data access

### FlyWire-Codex

[Codex](https://codex.flywire.ai) provides interactive access to the [whole-brain fruit fly connectome](https://www.nature.com/articles/s41586-024-07558-y) created by [FlyWire](flywire.ai). Check out the [FlyWire YouTube channel](https://www.youtube.com/@flywireprinceton4189), which has multiple videos on how to use Codex and its latest features ([workshop video](https://www.youtube.com/watch?v=HrXvgXE1Q6Q)). 

### Neuroglancer

Neuroglancer is a web-based interface to view electron microscopy (EM), cell segmentation data, neuropil, and brain meshes, as well as annotations.

FlyWire (v783): https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5993517542277120

MICrONS (v1300): https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5329535416401920 

Cheatsheet: https://docs.google.com/document/d/1bRGETwCIJEnwK7LseVLNBXwRMDPiHDU5s3eTJviyPvM/edit?usp=sharing

More curated neuroglancer examples for MICrONS available at [the MICrONS Explorer Gallery](https://www.microns-explorer.org/gallery-mm3)

More curated neuroglancer examples for FlyWire available at [the FlyWire Gallery](https://flywire.ai/gallery)

If you are prompted to login: **Use any google profile to login when prompted.**

### MICrONS-DashApps: interactive online analysis

DashApps provide interactive analysis access to datasets that are still being proofread. The links below provide interactive access to the MICrONS dataset.

Browse the data tables, such as cell type classifications with the [Table Viewer](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/table_viewer/?datastack=%22minnie65_public%22).

Query and visualize synaptic connectivity of neurons with the [Connectivity Viewer](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/connectivity/?anno-id=%22%22&id-type=%22root_id%22&mat-version=943&cell-type-table-dropdown=%22%22&datastack=%22minnie65_public%22)


## Programmatic data access 

For this tutorial, we're going to use an online interface to notebooks called Google Colab. Go to the `MICrONS_data_access.ipynb` notebook in [Google Colab](https://colab.research.google.com/github/sdorkenw/MICrONS_workshop_CNC_forum/blob/main/tutorials/MICrONS_data_access.ipynb) (requires GMail or other Google-related account). Google Colab lets you run executable notebooks in the cloud with minimal setup.

Exercises [(on Github)](https://github.com/sdorkenw/MICrONS_workshop_CNC_forum/tree/main/exercises)
* Excercise 1 - Cell-Type Connectivity [Google Colab](https://colab.research.google.com/github/sdorkenw/MICrONS_workshop_CNC_forum/blob/main/exercises/Exercise_1_cell_type_connectivity.ipynb)
* Exercise 2 - Inhibitory Connectivity [Google Colab](https://colab.research.google.com/github/sdorkenw/MICrONS_workshop_CNC_forum/blob/main/exercises/Exercise_2_inhibitory_connectivity.ipynb)
* Exercise 3 - Inhibitory in/out degree [Google Colab](https://colab.research.google.com/github/sdorkenw/MICrONS_workshop_CNC_forum/blob/main/exercises/Exercise_3_inhibitory_in_out_degree.ipynb)

[Additional tools for programmatic access](https://github.com/sdorkenw/MICrONS_workshop_CNC_forum/blob/main/preprocessing/CAVE_quickstart_colab.ipynb)



## Datasets

### MICrONS dataset: Functional connectomics spanning multiple areas of mouse visual cortex

The MICrONS dataset is a large functional connectomics dataset with dense calcium imaging and electron microscopy based cell reconstruction of a millimeter scale volume.
All neurons were automatically reconstructed and all synapses detected.
Subsequent proofreading in this volume yielded reconstructions that include complete dendritic trees for all ~70 thousand neurons as well the local and inter-areal axonal projections of a subset of neurons that map up to thousands of cell-to-cell connections per neuron.
Functional measurements and connectivity can be related for ~12 thousand neurons which were coregistered between the calcium and EM volumes.
In this workshop, we introduce the dataset, as well as both interactive and programmatic tools to analyze it.
The tutorial will contain exercises for hands on work and time to explore the dataset on your own laptop.   

Manuscript describing the dataset: [Functional connectomics spanning multiple areas of mouse visual cortex](https://www.biorxiv.org/content/10.1101/2021.07.28.454025v3.abstract)

#### Further reading relevant to the demonstration

Cell Type Model: [Perisomatic Features Enable Efficient and Dataset Wide Cell-Type Classifications Across Large-Scale Electron Microscopy Volumes](https://www.biorxiv.org/content/10.1101/2022.07.20.499976v2)

Inhibitory Connectivity: [Cell-type-specific inhibitory circuitry from a connectomic census of mouse visual cortex](https://www.biorxiv.org/content/10.1101/2023.01.23.525290v3)

Data Infrastructure: [CAVE: Connectome Annotation Versioning Engine](https://www.biorxiv.org/content/10.1101/2023.07.26.550598v1)

#### Dataset documentation

More complete documentation that includes the above information as well as guides to interacting with meshes, skeletons, and imagery, [can be found online at the MICrONS Tutorial webpages](https://alleninstitute.github.io/microns_tutorial/em_01_background.html).

