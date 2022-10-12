
# GP_Tasks
## Who are we ?
we are a group of Cairo university Facutly of Engineering students how are currently working on their graduation project in the Healthcare Engineering and Management program/Biomedical Engineering
## Team:
- Ola Ayman
- Sandra Adel
- Abdallah Mohamed Galal
- Pierre Amir

## Conda environment

- create an enviroment from a yaml file

```bash
  conda env create -f environment_gp.yml
```

- to update your local env with yaml file

```bash
  conda env update --name myenv --file environment_gp.yml --prune
```

- activate the env (env = env name)

```bash
  conda activate env
```

- export an new yaml file to update the env

```bash
  conda env export > environment_gp.yml

```

## General Task 1 Guidelines:
#### (Getting Familiar with Nibabel)
1) Checking size equality in all three dimensions amomg all dataset cases and performing resizing where necessary.
2) Loading and saving all slices in one stack of images (one case) and its label images in one or all 3 orientations.
3) Showing samples of image and label slice pairs in one stack of images (one case).

## Used Datsets:
- https://www.doc.ic.ac.uk/~rkarim/la_lv_framework/index.html
Left Atrial Wall Dataset (CT)

