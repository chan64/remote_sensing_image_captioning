# Remote Sensing Image Captioning

Remote sensing Image Captioning is a special case of Image Captioning which solves the difficulties in processing the remote sensing images. Issues may arise due to translation, rotation and viewpoint of images and maintaining semantic consistency in the generated captions. This method of describing a remote sensing scene in the form of sentences plays an important role in a number of fields, such as image retrieval, scene classification and as a vision companion. A Domain-driven approach is developed, in which the domain probabilities are used for captioning the remote sensing images. This approach concentrates on the domain- based information available in the images. A new dataset, called UAVIC dataset is created for images captured using Unmanned Aerial Vehicle (UAV), which covers wide range of land having multiple terrains and gives a better view of the landscapes. The proposed domain driven approach is applied to UCM and UAVIC dataset and the quality of resulting captions are evaluated using BLEU scores. 

### Requirements
- Google Collab and Drive 
- if running offline, 
  - Python 
  - Jupyter notebook

### Installation

Place the .ipynb files in Google Drive and run in Google Collab after creating the below directory structure in Drive.

```bash
.
├── Description
│   ├── testall.txt
│   └── trainnew.txt
├── Features
│   ├── dataset_one_hot_combined.pkl
│   ├── domain_features.pkl
│   └── features_resnet152_combined.pkl
├── model
│   └── results
├── classify_domain.ipynb
├── sample-lstm2\ (1).ipynb
└── sample-lstm2.ipynb
```


### Contributions

Special thanks to Team Dhaksha for providing us with raw images for the dataset. DHAKSHA is an End-to End solution provider in the field of UAS/UAV Technology from Concept Design to Manufacturing & After-market operational support services, viz.,
Please do check them out at https://www.teamdhaksha.com/.



