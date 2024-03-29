# PoseAnnotation

Free tool to create your custom HUMAN POSE ANNOTATION data sets for Machine Learning/Computer Vision Applications!

## Set Up and Installing Requirements
git clone this repo to your local machine

```
git clone https://github.com/moonbeam5115/PoseAnnotation.git
```

```
cd PoseAnnotation
```

Set up virtual environment:  
(Conda)  
```
conda create --prefix ./env python=3.7
```

Activate conda environment:  
```
conda activate ./env
```

Install requirements: 
```
pip3 install -r requirements.txt
```

## Getting Started
Place images you wish to annotate inside the imgs folder  

Start program:  
```
python main.py
```

Left Click on image to add joint annotation

Press "e" to undo previous joint annotation

Press "enter" to save results and go to next image -- Results are saved to the RESULTS Directory

Press "escape" to exit program

<div align="center">
  <img src=https://github.com/moonbeam5115/PoseAnnotation/blob/main/imgs/Lu_sitting_annotated.png />
</div>

## Future Functionality

Create functionality to return to previous image  
Allow user to skip occluded joints

## Support Future Projects  
If this project helped your research or other work in any way, consider donating to my Patreon to support other ongoing Computer Vision/Machine Learning/Data Science projects. 

Head over to:  
Patreon.com/supermanecuavoley
