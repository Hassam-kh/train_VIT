# train_VIT
I have trained VIT transformer on set of images having binary class [0,1] using keras.
dataset_link "https://zenodo.org/record/3784345"
# Remember
download the dataset and them merge them according to class. **Check the CSV provided** For example:
dataset/
├── class_0/
│   ├── TCGA-A6-3809-01Z-00-DX1.c26f03e8-c285-4a66-925d-ae9cba17d7b3.jpg
│   ├── TCGA-A6-3810-01Z-00-DX1.2940ca70-013a-4bc3-ad6a-cf4d9ffa77ce.jpg
│   ├── ...
├── class_1/
│   ├── TCGA-A6-2684-01Z-00-DX1.be127778-e160-4ae3-9e5a-13a16eae2e7a.jpg
│   ├── TCGA-A6-5659-01Z-00-DX1.c671806f-013e-4d99-9841-cda5bd43eff1.jpg
│   ├── ...
