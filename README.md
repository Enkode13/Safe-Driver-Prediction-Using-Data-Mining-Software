# Safe-Driver-Prediction-Using-Data-Mining-Software
We use two popular data mining softwares, KNIME and RapidMiner, to predict if the driver drives safely or not based on driver and car details.

The RapidMiner workflow has to be copied onto a local repository in order to acces the process.

The Knime project was larger than 25 mb and had to be split into 5 parts using the **split** command in mac.
To re-assamble the part files into one, use the following commands after going into the local directory:

  MAC:
 
  cat KNIME_proj_Part_* > KNIME_project.knwf

  Windows:
  
  copy KNIME_proj_Part_* /b KNIME_project.knwf
