---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Helena, a postdoctoral researcher at the Natural History Museum in London. I'm a planetary scientist, working with meteorites to understand more about the formation and evolution of our Solar System. 

I'm interested in linking the meteorites we have on Earth to their parent body asteroids still in space by linking lab data to telescopic and spacecraft observations. Most of my work is focussed on the meteorites and asteroids that look like at some point in their pasts they were exposed to water, because the questions about where water on Earth came from, and how it is distributed throughout the rest of the solar system have lots of implications for the development of life.

My background
======
I always loved space, and knew that if possible, that was what I wanted to focus on in my career. At school, I did chemistry, physics and maths at A level, with an AS level in biology. I then went on to study an undergraduate degree in [Geophysics](https://www.imperial.ac.uk/study/courses/undergraduate/geophysics-msci/) at [Imperial College London](https://www.imperial.ac.uk/), starting in 2012. I studyed for 4 years and came out with an integrated master's degree. During my time at Imperial I did a project at the Natural History Musuem, my first experience working in a lab, and first time working with meteorites. I realised that working with real samples from space was exactly what I wanted to do, so during the final year of my degree I applied for PhDs in the field of meteoritics. I was lucky enough to be selected to do a PhD which was 'split-site', based at the [planetary materials group](https://www.nhm.ac.uk/our-science/departments-and-staff/earth-sciences/mineral-and-planetary-sciences.html) at the [Natural History Museum](https://www.nhm.ac.uk/), and working closely with the [space instrumentation group](https://www.physics.ox.ac.uk/research/group/space-instrumentation) at [Oxford University](https://www.ox.ac.uk/). 

After my PhD finished in 2020, I spent a year as meteorite curator at the Natural History Museum. During that time I was responsible for the management, organisation and conservation of the 5000 meteorite speimens in the collection. During my time as curator, the [Winchcombe meteorite](https://www.science.org/doi/10.1126/sciadv.abq3925) fell, the first meteorite to fall and be recovered in the UK for 30 years, and I was partly in charge of the intial management and curation efforts.

Following my curation role, I moved back into research and since October 2021 I have been postdoctoral researcher, still based at the Natural History Museum - they can't get rid of me!

My work and research
======
I've got a number of projects that I am currently working on. 
1. I'm looking at the occurance of 'meteorites within meteorites' - certain types of meteorites have a high proportion of small clasts of other meteorite types embedded within them (we call these clasts xenoltihs). I am investigating what they are, where they are and where they might have come from.
1. I've also been investigating an interesting group of anomalous carbonaceous chondrites, including the C2-ungrouped Tagish Lake and Tarda meteorites. These rocks have an unusually heavy oxygen isotopic composition, high magnetite and sulfide abundances and different phyllosilicate compositions from other similar meteorites. I am trying to find more like them, potentially forming a new group of carbonaceous chondrites!
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Techniques
======
I use a variety of instruments and experimental techniques to do my research. Here are the main ones.
1. X-ray diffraction (XRD)
1. Infrared (IR) spectroscopy
1. Thermogravimetric analysis (TGA)

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
