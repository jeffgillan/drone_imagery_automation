# drone_imagery_automation

## Drone Photogrammetry Processing 

[Automated Metashape workflow on local machine](https://github.com/jeffgillan/automate-metashape), native & docker

[Automated Metashape worfklow on HPC](https://github.com/jeffgillan/metashape_hpc)

[OpenDroneMap](https://github.com/jeffgillan/opendronemap)

[Convert geotiff to COGs and point clouds to COPC (docker)](https://github.com/jeffgillan/cog_copc_generate)

[Pipeline for automated Metashape workflow + COG/COPC conversion](https://github.com/jeffgillan/cog_copc_generate), docker-compose


## Cyber Infrastructure

[Open Forest Observatory](https://openforestobservatory.org/)

[CACAO Open Forest Observatory](https://github.com/open-forest-observatory/cacao-terraform-ofo/tree/main)  

[STAC catalog for Open Forest Observatory](https://github.com/open-forest-observatory/stac)

[Data to Science](https://ps2.d2s.org/)

Script to upload imagery products to Data-to-Science


## Pretrained ML Models

[Notebook for DeepForest](https://github.com/ua-datalab/Geospatial_Workshops/wiki/Image-Object-Detection-%E2%80%90-Deep-Forest)

[Deep Forest](https://deepforest.readthedocs.io/en/v1.5.0/index.html) provides pretrained model to do tree crown object detection. The model started with resnet-50 classification backbone pretrained on ImageNet dataset. Then they estimated the tree crown locations of 30 million trees from Neon Lidar data across the US. They further trained the model on these unsupervised lidar tree crowns. Then final step was training on 10,000 hand-annoted canopy bounding boxes.  

[Notebook for Data-to-Science and Detecto for lettuce ID](https://github.com/jeffgillan/data_to_science_scripts/blob/main/lettuce_detecto.ipynb)

[Notebook for Detecto](https://github.com/ua-datalab/Geospatial_Workshops/wiki/Image-Object-Detection-%E2%80%90-Detecto) 

[Low Altitude Disaster Imagery (LADI)](https://github.com/LADI-Dataset/ladi-overview) dataset and pretrained models.

[GeoAI](https://geoai.gishub.org/)

[Tree Detection Framework](https://github.com/open-forest-observatory/tree-detection-framework)

[SAMGeo](https://samgeo.gishub.org/)

[W.A.L.D.O. Whereabouts Ascertainment for Low-lying Detectable Objects](https://huggingface.co/StephanST/WALDO30)- pretrained model base on YOLO-v8 backbone. Can ID vehicles, people, buildings, bikes. Training dataset is not public. 

[TorchGeo NAIP Foundation Models](https://torchgeo.readthedocs.io/en/stable/api/models.html#naip)

[satlas_pretrain models](https://github.com/allenai/satlaspretrain_models/)

[Tree Detection Framework from Open Forest Observatory](https://github.com/open-forest-observatory/tree-detection-framework)

[VisDrone from Ultralytics YOLO](https://docs.ultralytics.com/datasets/detect/visdrone/)

[Restor Tree Crown Delineation](https://restor-foundation.github.io/tcd/): Consists of a [tree crown dataset](https://huggingface.co/datasets/restor/tcd), [pretrained models](https://huggingface.co/restor) that do semantic segmentation (segformer & unet) and instance segmentation (mask-rcnn). Also has a coded pipeline to train and predict tree crowns. 

[DOTA Dataset](https://captain-whu.github.io/DOTA/index.html)

## Macbook Air Software Stack
* Agisoft Metashape GUI and python module
* Cloudcompare GUI
* QGIS GUI
* Docker desktop and CLI tool
* exiftool CLI tool
* VS Code
* WebODM

  `cd /users/jgillan/Documents/repositories/WebODM`

  `./webodm.sh start`



