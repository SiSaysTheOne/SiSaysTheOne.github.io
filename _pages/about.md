---
permalink: /
title: "Portfolio Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page for my academic portfolio. It may become something else in the future! 

For now, you'll find: 
- My contact information (on the left side of this page)
- My research papers
- My porject work (including senior design)
- Reflections on my academic experience
- My resume (and CV?)

# Career Objective
//todo Career Objective

Todo list
===
- The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header.
- For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. 
  - At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. 
  - The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).
- Many people use a git client to create files on their local computer and then push them to GitHub's servers.  
- For those users that need more advanced functionality, the template also supports the following popular tools:
  - [MathJax](https://www.mathjax.org/) for mathematical equations
  - [Mermaid](https://mermaid.js.org/) for diagraming
  - [Plotly](https://plotly.com/javascript/) for plotting

Post-install message from rubyzip:
RubyZip 3.0 is coming!
**********************

The public API of some Rubyzip classes has been modernized to use named
parameters for optional arguments. Please check your usage of the
following classes:
  * `Zip::File`
  * `Zip::Entry`
  * `Zip::InputStream`
  * `Zip::OutputStream`
  * `Zip::DOSTime`

<!-- Run your test suite with the `RUBYZIP_V3_API_WARN` environment
variable set to see warnings about usage of the old API. This will
help you to identify any changes that you need to make to your code.
See https://github.com/rubyzip/rubyzip/wiki/Updating-to-version-3.x for
more information.

Please ensure that your Gemfiles and .gemspecs are suitably restrictive
to avoid an unexpected breakage when 3.0 is released (e.g. ~> 2.3.0).
See https://github.com/rubyzip/rubyzip for details. The Changelog also
lists other enhancements and bugfixes that have been implemented since
version 2.3.0. -->