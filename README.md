# MUSIC AND ACOUSTIC ENGINEERING CAPSTONE L01 : ARTIFICIAL MUSIC DETECTION THROUGH MACHINE LEARNING CLASSIFICATORS

### Authors
- Besedova Olga
- Grati Marcello
- Perego Gabriele

### Abstract
This research explores the potential to distinguish between artificially generated music and human-composed music. Various
AI music generators were examined when solving this problem.  
By utilizing classical machine learning classifiers, implemented in Python language, we successfully trained a model that can accurately determine with approximately 90% of accuracy whether an audio track is real or generated by AI.  
Furthermore, with the same level of accuracy, the model can identify the specific AI generator that was used.

### Content
This repository containes 3 different codes focused on testing new way to perform artificial music detection:

- `Capstone_l01_RvF.ipynb` : this model is trained to distinguish between human recorded music and AI generated music
- `Capstone_l01_RvF.ipynb` : this model is trained to classify the music generated by different AI models
- `Noise_test.ipynb` : this code is useful to test model perfromance in different noise scenarios

In order to run this code, the user needs to add this dataset to his google drive folder:

https://drive.google.com/drive/folders/1--JvLlLr_JZeOtfK3jgNJm7_EBBIlxYr?usp=sharing

and then needs to modify the file paths with respect to the postion of the added folder

Es: `/content/drive/My Drive/path/to/folder/Datasets_5/...`

### Paper
To read the research paper, look at: L01_Report.pdf
