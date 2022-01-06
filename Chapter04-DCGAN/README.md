## Generating Anime Characters using DCGAN

Python 3.6

Steps to set up the project:
1. Create a python3 virtual environment and activate it
2. Install dependencies using "pip install -r requirements.txt"
3. Create essential folders 1. logs 2. results 3. data
4. Download and format the dataset with following instruction:
    1. Install `gallery-dl` package:
        ```bash
        pip install gallery-dl
        ```
    2. Create `data` directory
        ```bash
        mkdir data
        ```
    3. Download images from `danbooru.donmai.us` using `gallery-dl`:
        ```bash
        gallery-dl https://danbooru.donmai.us/posts?tags=face
        ```
5. Train the model by executing python3 run.py
