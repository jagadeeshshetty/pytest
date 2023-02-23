# pytest

All about the Pytest framework.

<div align="center">
  <img title="readme-cover" alt="" src="./docs/images/readme-cover-round-corner.png" width=100%>
</div>

## Virtual env setup

### Windows

- Create an virtual env using venv module.
  ```shell
  cd C:\python311
  python.exe -m venv %USERPROFILE%\venvs\frameworkenv
  ```
- Activate the virtual env using 'activate' exe within Scripts dir.

  ```shell
  cd %USERPROFILE%\venvs\frameworkenv\Scripts
  activate

  or

  %USERPROFILE%\venvs\frameworkenv\Scripts\activate
  ```

- Verify the Python version within new virtual env.

  ```shell
  (frameworkenv) C:\Users\jagadeesh\venvs\frameworkenv\Scripts>python --version
  Python 3.11.2
  ```

- Deactivate the virtual env using the deactivate executable.

  ```shell
  (frameworkenv) C:\Users\jagadeesh\venvs\frameworkenv\Scripts> deactivate

  or
  %USERPROFILE%\venvs\frameworkenv\Scripts\deactivate
  ```

### macOS

- Create an virtual env using venv module.
  ```shell
  tbd
  ```
- Activate the virtual env using 'activate' exe within Scripts dir.
  ```shell
  tbd
  ```
- Verify the Python version within new virtual env.

  ```shell
  tbd
  ```

- Deactivate the virtual env using the deactivate executable.
  ```shell
  tbd
  ```

🌟 Make sure to be in venv
`pip install pytest`

### Run pytest

```shell
# less details
pytest
# test_widget.py .

# more details
pytest -v
# test_widget.py::test_widget_functions_as_expected PASSED
```
