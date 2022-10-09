# Importing your own functions in a py file

Here is the directory structure of this demo repository:

```
.
├── README.md  *** <-------- WE ARE HERE
├── Root_Import.ipynb
├── analysis
│   ├── student1
│   │   └── student_Import.ipynb
│   └── subdir_Import.ipynb 
├── data
│   └── README.md
└── scripts
    └── project_test.py
```


There are three examples in here showing you how to import `scripts/project_test.py` at three different locations in this repository.
The .py file with the functions will always be in: `scripts/project_test.py`, the three examples will show you how to import the file from three different locations.

1. [`Root_Import.ipynb`](Root_Import.ipynb)

2. [`analysis/subdir_Import.ipynb`](analysis/subdir_Import.ipynb)

3. [`analysis/student1/student_Import.ipynb`](analysis/student1/student_Import.ipynb)

## Additional Readings

This [video](https://www.youtube.com/watch?v=ZBYDbAQKs3I) is perhaps the best one I've seen about absolute and relative imports!
