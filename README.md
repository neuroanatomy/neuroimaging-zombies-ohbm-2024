# neuroimaging-zombies-ohbm-2024
Utilities for a neuroimaging zombies project at OHBM 2024 Hackathon.

Here are the projects we propose for OHBM Brainhack 2024.
But overall, let's keep discussing about the issuue!

## Preprocess a public dataset with your favorite tool and upload the results to GIN

One step towards the reproducibility & replicability of results is to make publicly available the preprocessed data we work with. It also allows us to save resources, avoiding to do several intensive and time-consuming computations each on our own. You can join the effort by publishing your preprocessed public dataset to a public repository hosted on GIN.

The NAAT lab has work in progress in that direction. The GIN reference-preprocessing organization (https://gin.g-node.org/reference-preprocessing) already includes freesurfer 6.0.0 preprocessings of ABIDE 1 & 2. If you wish to contribute, we are happy to add you to the team!

## Work on reference Quality Control

Still in the spirit of reproducibility & replicability of results, let’s make publicly available the quality control of some public datasets. The goal is to be able to reference in our research some public quality control with the methodology and results being shared with everyone.

Depending on which region of interest you are working on, you may need some particular quality control. You can provide a description of your particular needs in the QC (e.g. focus on a specific region, ignorance of certain artifacts, …) along with the methodology you employed and results, so that other researchers can review and/or rely on your work.

Above all, let’s be particularly attentive to our QC methods and exclusion criterions depending on the context, so that we oncly exclude relevant subjects to our work. Sharing our QC methods and results allows us to pick the right QC according to our needs and include the maximum number of subjects in every project. In this way, we maximize the size of the datasets we work with, increase the scope of our results, and respect the implication of families in research.

## Work on the reference pipelines for some well established neuroimaging results

Thinking again of the reproducibility & replicability of results, let’s come up with a reference pipeline that highlights a bench of well established neuroimaging results. In this way, even if one cannot make his dataset publicly available, one can still provide the results of this reference pipeline to show its reliability.

Let’s focus on the most robust neuroimaging findings, e.g. detection of some anatomical changes related to age and sex, detection of the default mode network, detection of the motor/visual cortex, etc. and provide the most simple analysis pipeline able to reproduce those results.
