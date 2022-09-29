### Workflow

- update project code
- update pyproject.toml > increment version
- run ```python -m pip install --upgrade pip```
- run ```python -m pip install --upgrade build```
- run ```python -m pip install --upgrade twine```
- run ```python -m build```
- run ```python -m twine upload --repository testpypi dist/*``` for test environment
- run ```python -m twine upload --skip-existing dist/*```
- use `__token__` as username and the token as password
