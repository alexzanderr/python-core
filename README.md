# python-core
powerful python package available on PyPI

# requires python 3.7+ installed 
```bash
pip install python-core
```


# example of code
```python
# usual imports from core package

# modules
from core.__audio import *
from core.__datetime import *
from core.__json import *
from core.__numbers import *
from core.__path import *
from core.__random import *
from core.__selenium import *
from core.__winapi import *
from core.__zip import *

# packages
from core.__collections import *
from core.gui import *
from core.sounds import *

# __$name are modules with names that already exist in python, so i needed to came with a convention
# these modules are an upgraded version wrapped around built-in modules

# modules (continued)
from core.aesthetics import *
from core.algorithms import *
from core.animations import *
from core.backtracking import *
from core.development import *
from core.download import *
from core.drive import *
from core.exceptions import *
from core.image import *
from core.pdf import *
from core.romania import *
from core.session import *
from core.statistics import *
from core.symbols import *
from core.system import *
from core.weather import *

# these are all the modules and packages included in 'python-core' package


# just a simple example
if __name__ == "__main__":
    # from core.__numbers
    print(fixed_set_precision_str(2.123456, 2))
```

**output**
```
2.123
```



```
thank you for your time!
```
