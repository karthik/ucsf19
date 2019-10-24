
# [Open Code](https://calendars.library.ucsf.edu/event/5671671)

October 24, 2019. 3:30 - 5pm

This workshop is part of a series on [Reproducibility for Biomedical Researchers](https://courses.ucsf.edu/course/view.php?id=6933) hosted by the UCSF library.

### Slides

![Imgur](https://i.imgur.com/4OiMlC8.png)

This repositories contains slides and links to various resources mentioned during the workshop. For any questions or clarifications please file an issue.


## Resources

[The National Academy of Sciences report on Reproducibility and Replicability in Science](https://www.nap.edu/catalog/25303/reproducibility-and-replicability-in-science)  Free PDF available for download.

[My talk on research compendia in R from Rstudio Conference in January 2019 (includes video, slides, and a bunch of resources)](https://github.com/karthik/rstudio2019#how-to-make-your-data-analysis-notebooks-more-reproducible)


[Docker - An introduction to Docker for reproducible research, with examples from the R environment.](https://https://arxiv.org/abs/1410.0846)


https://github.com/pypa/pipenv

### Git and GitHub

[Ten Simple Rules for Taking Advantage of Git and GitHub](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004947)

[Coordinate releases between GitHub and Zenodo](https://guides.github.com/activities/citable-code/)

### Research compendia

- [Packaging Data Analytical Work Reproducibly Using R (and Friends)](https://www.tandfonline.com/doi/abs/10.1080/00031305.2017.1375986) ([OA preprint](https://peerj.com/preprints/3192/)). A practical introduction to setting up a research compendium in R. 

[Examples of research compendia on GitHub (Python)](https://github.com/researchcompendia?language=python)

[Examples of research compendia on GitHub (R)](https://github.com/researchcompendia?language=R)

[Browse the Research Compendium topic on GitHub](https://github.com/benmarwick?tab=repositories&type=source)


**Examples of Research Compendia on GitHub**
Below are a few links to real world examples of research compendia in R. To have a minimal compendium, all you really need is a valid [`DESCRIPTION`](https://github.com/boettiger-lab/pomdp-intro/blob/master/DESCRIPTION) file containing a handful of fields such as type, name, version and dependencies. See Marwick et al 2017 for a detailed description of the different types of compendia.

**Small**
- [Code and data associated with Duffy, James, and Longworth Applied and Environmental Microbiology paper describing the ecology, virulence, and phylogeny of a brood parasite of Daphnia, Blastulidium paedophthorum;](https://github.com/duffymeg/BroodParasiteDescription)
 
**Medium**
- [Resolving the measurement uncertainty paradox in ecological management](https://github.com/boettiger-lab/pomdp-intro)

**Large**

- [Non-parametric Bayesian Inference for Conservation Decisions ](https://github.com/cboettig/nonparametric-bayes)

- Find various other compendia on [Github](https://github.com/topics/research-compendium) and [Zenodo](https://zenodo.org/communities/research-compendium?page=1&size=20) using the `research-compendium` tag.

**Software packages related to research compendia**

📦 [`rrtools`](https://github.com/benmarwick/rrtools)  by Ben Marwick (also the author of the packaging data analysis paper mentioned above) *extends functions in `devtools` and provides instructions, templates, and functions to make a basic compendium suitable for doing reproducible research with R.* 
	- Also see 📦 [workflowr](https://jdblischak.github.io/workflowr/) by John Blischak and the [task view](https://github.com/jdblischak/ctv-project-workflows) on R-based data analysis projects maintained by John Blischak, Anna Krystalli, Ben Marwick, Daniel Nüst.
- 📦 [`usethis`](https://github.com/r-lib/usethis) *Many of the major function in `rrtools` are imported from `usethis.` A savvy user can get by setting up and maintaining a compendium purely with `usethis` functions.*
- 📦 [`goodpractice`](https://github.com/MangoTheCat/goodpractice) - Designed to help you build more robust packages, the package does a deep dive on your package contents and provide advice on syntax pitfalls to avoid, code formatting suggestions, and helps you improve overall package structure.
- The 📦 [`rticles`](https://github.com/rstudio/rticles) package by JJ has numerous journal templates and together with Rstudio addins like word [`countaddin` ](https://github.com/benmarwick/wordcountaddin)and [`citr`](https://github.com/crsh/citr) + [`knitcitations`](https://github.com/cboettig/knitcitations).


### Computational environments: Binder and friends

- [My Binder](https://mybinder.org/) is a free binderhub deployment that turns any Git repo into a collection of interactive notebooks. Now with better R support!
- For instructions on how to set this up for your R project, see [my notes here](https://github.com/karthik/rstudio2019/blob/master/binder-notes.md)
- [Introducing Binder 2.0 — share your interactive research environment](https://elifesciences.org/labs/8653a61d/introducing-binder-2-0-share-your-interactive-research-environment) Paper describing the architecture of Binder in case you were interested in what was happening under the hood
- 🎥 [A talk about Binder at Scipy 2018](https://www.youtube.com/watch?v=KcC0W5LP9GM). Also see [conference proceedings PDF](http://conference.scipy.org/proceedings/scipy2018/pdfs/project_jupyter.pdf).
- [`repo2docker`](https://github.com/jupyter/repo2docker) A Python module that will turn any repo (or local folder) into a Docker Image.  

**Other hosted Binder hubs**

- [Pangeo binder](https://binder.pangeo.io/) *Pangeo encourages everyone to use it.*
- [gesis](https://notebooks.gesis.org/)
- [Syzgy](http://syzygy.ca/) *Binder + JupyterHub for Compute Canada*