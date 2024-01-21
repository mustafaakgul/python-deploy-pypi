## This project goal is to share a package on PyPI.

### Creating Package
* Create a project on GitHub
* Create acc on PyPI - https://pypi.org/account/register/
* Create a project on PyPI - https://pypi.org/manage/projects/
    * cd <YOUR_PROEJECT_PATH> --python-deploy-pypi/repo/
    * pip install setuptools and twine
    * python setup.py sdist
    * twine upload dist/*
        * Enter your credentials on PyPI.org
    * Check your package on PyPI.org --https://pypi.org/project/iot-gaussian/
    * Usage: pip install iot-gaussian

### Updating Project
* After changes in code, update version in setup.py for instance Version : 0.0.2 applying versioning naming convention
* python setup.py sdist
* twine upload dist/*