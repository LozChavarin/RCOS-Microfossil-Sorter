# Microfossil Concentrate Fossil Sorter  
#### Olivia Lundelius, John Klingelhofer, Alexis Joseph, Elizabeth Chavarin

## Overview  

In paleontology, microfossil concentrate is a mixture of microfossils (typically from rodents and lizards) and gravel, with each particle being about 2 mm in size.  Microfossils can potentially serve as a source of big data for paleontologists about the locations and environments from which they were collected.  In order to study the microfossils, they must be sorted out from the gravel, which is a very time consuming process.  This project aims to build a machine that automatically sorts microfossils from concentrate, and for that machine’s assembly and software to be made open source and accessible by paleontology laboratories.

## Milestone Goals  
1. Consolidated computer vision program for distinguishing microfossils from gravel  
**Goals:**  
Fix SVM  
Improve color discrimination algorithms, test out new color discrimination techniques  
Make shape-based discrimination function  
Incorporate both functions into a single discrimination program for images of individual microfossils and gravel  
**Stretch:**  
Determine minimum amount of training necessary to have 90%+ accuracy  


2. Set of commandline tools for general users to run computer vision program on images (to be later incorporated with hardware and user interface)  
**Goals:**  
Create tool for training computer vision program with directories for microfossil/gravel images  
Allow for batch processing of images  
Create ability to save/load a training profile  

3. Design prototype of hardware sorter  
**Goals:**  
Identify and acquire hardware necessities, such as camera, arduino, etc.  
Have 3D models of plans of prototype sorter, including necessary electronics  
Assemble prototype sorter and make changes to model and parts as necessary  
Design and assemble second-draft prototype  

4. Create a GUI  
**Goals:**  
Ability to save and load a training profile from within the interface.  
Create a start menu for beginning analysis.  

5. Maintain website and progress blog  
**Goals:**  
Include project and contact information  
Include relevant information about potential usefulness of project and how others can get involved  

6. Data  
**Goals:**  
Gather more training data.  
Generate data from more locales.  



## Overarching Goals  
_Documentation_:  
Write documentation of currently existing functions and commandline tools  
Be written continuously and covering all important functions and general structure of program  
Include less-technical side to documentation for general, non-programmer users of microfossil sorter project  
_Website_:  
Include regular updates to progress of the project  
Include running to-do lists in updates for immediate future  
