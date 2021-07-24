# Importing functions in python

There are three examples in here, at three different locations in the directory.
The .py file with the functions will always be in: `test_project/analysis/script/test.py`, the three examples will show you how to import it from three different locations.

1. `test_project/Root_Import.ipynb`

```
from analysis.script import test
test.hello()
```

2. `test_project/analysis/subdir_Import.ipynb`

```
from script import test
test.hello()
```

3. `test_project/analysis/student/student_Import.ipynb`

```
import sys, os
sys.path.insert(0, os.path.abspath('..'))

from script import test
test.hello()
```