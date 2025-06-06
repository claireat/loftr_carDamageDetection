# loftr_carDamageDetection

Datasets detectron2 trained on:
- archive: https://www.kaggle.com/datasets/lplenka/coco-car-damage-detection-dataset/data
- archive_larger: https://www.kaggle.com/datasets/densus100/car-damage-coco-dataset?resource=download

Directories:
- car_images: contains images used to test detectron2 inference (each subdirectory contains a set of 2 images: before (withoutDent.png) and after (withDent.png))
- before_images: contains all original "before" images
- after_images: contains all original "after" images
- aligned_after_images: contains all "after" images aligned to view of "before" images
- archive: COCO formatted car damage dataset used for training
- archive_larger: COCO formatted car damage dataset used for training (larger)
- predictions: contains 2 subdirectories: aligned_after_preds (aligned after images with damage predictions) and before_preds (before images with damage predictions)