# 3-D Protein Visualizer with Biopython

## Table of Contents

<ol>
 <li><a href="#introduction">Introduction</a></li>
 <li><a href="#technologies">Technologies</a></li>
 <li><a href="#usage">Usage</a></li>
  <ol>
   <li><a href="#start-the-notebook">Start the notebook</a></li>
   <li><a href="#guided-example">Guided example</a></li>
   <li><a href="#upload-a-photo">Upload a photo</a></li>
   <li><a href="#adjusting-model-sensitivity">Adjusting model sensitivity</a></li>
  </ol>
 <li><a href="#further-reading">Further reading</a></li>
 <li><a href="#author">Author</a></li>
 </ol>
## Table of Contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Usage](#usage)
* [Author](#author)
 
## Introduction <a class="anchor" id="introduction"></a>

This project was primarily inspired by my background in molecular biology. I was excited to explore the biopython library and its uses, so I decided to create a Jupyter Notebook app.

I choose Jupyter Notebooks in part because they provide reasonable widget tooling, so making a GUI is relatively straightforward. The Notebooks are served by Binder, which remedies many of the traditional deployment challenges of Jupyter Notebooks.

While there is a small 10-20 second delay while the server spins up, Binder provides all the interactivity of a traditional Notebook but without much of the fuss.

## Technologies <a class="anchor" id="technologies"></a>
* Python
* Binder
* Jupyter notebooks
* Ipywidgets
* Biopython
* Nglview

## Usage

### Start the notebook <a class="anchor" id="start-the-notebook"></a>

1. Click the badge below to start the notebook.
    - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zachmichael14/protein_viewer/HEAD?labpath=viewer.ipynb)
    - A static version of the notebook will be displayed while the server spins up. 
  
 ![static_notebook.png](img/static_notebook.png)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zachmichael14/protein_viewer/HEAD?labpath=viewer.ipynb)

### GUI reference <a class="anchor" id="gui-usage"></a>

There are several protein representations available, with differnt representation serving different purposes.

# GUI Usage <a class="anchor" id="gui-usage"></a>

While much of the GUI functionality is geared toward creating custom representations, the model representation can most easily be changed by navigating to ```Extra > Quick``` and selecting a representation. 

Note: Representations can stack.

"Cartoon" is typically the default as it's easiest to get a sense of the motifs that make up the protein.

The "contact" view represents distance between amino acids and has become increasingly useful for machine learning computations as these values are independent of model transformations. 

"Spacefill" and "ball-and-stick" are both common representations of molecules in chemistry, though the latter is largely ignored by this GUI as most proteins would be too large to fit on screen if modeled accurately this way.

Simply click the Binder badge above to launch the Notebook.

## Author
### Zachary Seitz
#### Let's connect!
* Find me on [Linkedin](https://linkedin.com/in/zachmichael14).
* Email me at zachmichael14@gmail.com.
* Visit my [resume website](https://zachmichael14.github.io/gh_page/).
