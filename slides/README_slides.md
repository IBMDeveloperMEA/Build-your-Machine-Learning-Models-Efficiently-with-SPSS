---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: myst
      format_version: '1.1'
      jupytext_version: 1.1.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---
<!-- 
+++ {"slideshow": {"slide_type": "slide"}}

# Tutorial slides

- Slides are optional (e.g., you may not use them if your presentation is via live coding).
- If the pre-recorded presentations will use slides, we request that you deposit the slides in this folder.

+++ {"slideshow": {"slide_type": "slide"}}

## Use text-based source

- We ask that you use text-based formats for your slides, e.g., markdown 
- This markdown file is an example source for slides using `nbconvert` and Reveal. See the GitHub action '.github/workflows/slides.yml' in this repo so see how this markdown file is converted to a HTML slide show and published on GitHub Pages - https://fawazsiddiqi.github.io/slides_to_pages

+++ {"slideshow": {"slide_type": "subslide"}}

## An example sub-slide

- Another option: you can write your slide content using markdown and use an app for slide design, like [Deckset](https://www.deckset.com) or similar.

+++ {"slideshow": {"slide_type": "slide"}}

## Naming convention and file list

- Use a **naming convention** where each file name starts with a number, reflecting the order of use in the presentation of the tutorial.
- List your slide files in a markdown, with a brief description.


+++ {"slideshow": {"slide_type": "slide"}} 
-->


**🌟 Overview** <br />
In this workshop, you will learn how to graphically build and evaluate machine learning models by using the SPSS Modeler flow feature in IBM® Watson™ Studio. Watson Studio and SPSS Modeler provide us with an interactive environment for quickly building machine learning pipelines that flow data from ingestion to transformation to model building and evaluation, without needing any code.


**🎓 What will you learn?** <br />
– What is SPSS Modeler and how it is used
– How to explore Data Analysis
– What are the different types of algorithms used

**👩‍💻 Who should attend?** <br />
All Developers interested in Artificial Intelligence & Machine Learning are welcome to attend the webinar. This session is for beginners, you don't require any technical skills.

🍉 Register for the live stream and replay on Crowdcast: <br/>
- Register for the live stream or to watch the replay: https://www.crowdcast.io/e/build-ml-models

+++ {"slideshow": {"slide_type": "subslide"}}

**🎈 Prerequisites** <br />
1. Sign up to IBM Cloud using this link: hhttp://ibm.biz/SPSSmod
2. Get a brief intro to Machine Learning: https://www.youtube.com/watch?v=9gGnTQTYNaE
3. Check out the hands-on's step by step guide (this is optional just in case you want to check what we will be doing during the workshop): https://developer.ibm.com/tutorials/build-an-ai-model-visually-with-spss-modeler-flow/

👩‍💻Resources <br />
- GitHub Repository - https://ibm.biz/SPSSmodLab 
- Workshop Slides - http://ibmdevelopermea.github.io/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/
- Survey - https:// ibm.biz/SPSSmodSurvey
- Follow along for the hands-on: https://developer.ibm.com/tutorials/build-an-ai-model-visually-with-spss-modeler-flow/
- Meetup page - https://www.meetup.com/IBM-Cloud-MEA/events/ 

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide1.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide2.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide3.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide4.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide5.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide6.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide7.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide8.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide9.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide10.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide11.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide12.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide13.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide14.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide15.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide16.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide17.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Build-your-Machine-Learning-Models-Efficiently-with-SPSS/blob/main/images/slide_images/Slide18.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}
## License

**Recommend** that slides be shared under a [CC-BY](https://creativecommons.org/licenses/by/4.0/) license.
