# tf-facebot
Face generation bot utilizing DCGAN structure with TensorFlow.

## info (and infos)
This program was created for the purposes of my Computer Science final project (it was a bit overkill).

Because it is pointless and not typical to upload large files to GitHub, both the original dataset and the training checkpoints have not been uploaded here. There are several text files, labeled info.txt, within some of the directories left as notes to indicate why some things are missing, or for example how to get the dataset.

## installation instructions
The directories must be set up in a specific order for this to work! From a ~ directory from the project, directory structure is as follows:
1) src
  - face_generation.py
  - both .png outputs and .ckpt savefiles will be saved here
2) input
  - 100k extracted folder with all pictures
  - 100k.txt dataset index
  - models
    - any .ckpt and checkpoint files for loading
