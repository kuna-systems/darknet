To build darknet as a python importable pip package, run the following:

`python setup.py sdist bdist_wheel`

This will build the wheel for the package. You can install/reinstall the wheel with this:

`pip install --upgrade --force-reinstall dist/darknet-0.0.1-py3-none-any.whl`

To use the package try this in your python program:

```
import darknet

darknet.performDetect()
```
