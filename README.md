## Steps to run to view the output:

1.1 create a virtual env for macos or linux based

```
  python3 -m venv myvenv
  source myvenv/bin/activate  
```

1.2 for windows:

```
python -m venv virt
python virt/Scripts/activate
```
1.3 use 
```pip freeze```
to see installed dependencies

2. clone the project
3. Install Flask
```
   pip install Flask
```

4. install tensorflow
```
   pip install tensorflow

```
### To work with the ipynb file for the model creation
  * use google colab
  * download my customised datasets from:
    - https://drive.google.com/drive/folders/1REFkQeXGSHHrYbesmlGOl6VqXNCeEEo6?usp=sharing
  * appropriately modify the paths mentioned in the colab file
  * download the file with .h5 file and save it in the project folder

5. Once everything is ready, run the code (in terminal) using
```
  python application.py
```
  * Check for the result at:
    - http://127.0.0.1:5000/
