# neuroimaging-zombies-ohbm-2024
Join our Mattermost channel at [brainhack.org](https://mattermost.brainhack.org/brainhack/channels/neuroimaging-zombies), and check these slides to learn more about the project at [osf.io](https://osf.io/fvqn7/).

Neuroimaging zombies are published results which no one knows if they are  true or false, dead or alive: they  just stick around so that people who believe in them can still cite them! We would rather like to see living neuroimaging results: results that can be replicated if sensible choices of population and methods are used. Living results can be reproduced: using the same data and the same approach/code, we should be able to get the same results. Even more, living results can be replicated: using reasonably similar data and reasonably similar approach/code, we should be able to get a reasonably similar result.

The aim of this project is to devise a strategy for killing neuroimaging zombies, and also for preventing your own results from turning into zombies!
Open data is our main weapon against neuroimaging zombies, and we would like to make it shine. We would like to use open, public data to its full extent. Through a community effort, our aim will be to provide **reference preprocessing** for all open data, for all the main tools used in neuroimaging and their different versions. We would like this preprocessing to be available on a public server, accessible to everyone: Never again you should need to process public data yourself! We should then be able to start creating **reference quality control** for this data, following a standardised procedure. Finally, we would like to provide **reference statistical analysis pipelines** necessary to reproducing and replicating the core results of neuroimaging. This will be a set of core living neuroimaging results to which new living neuroimaging results should be progressively added. A living neuroimaging result will look like a code repo: with versioning and automatic testing, which will serve as a constant check of its vital signs.

Join us and let’s work together on some of these projects:

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
