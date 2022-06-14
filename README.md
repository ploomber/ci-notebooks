## Data Storage Repository
This repository is solely used to store notebooks and related datasets for testing [Soorgeon](https://github.com/ploomber/soorgeon)

## How to upload
1. Go [here](https://github.com/ploomber/soorgeon/blob/main/_kaggle/index.yaml) to fetch the newest addition by public contributors
2. Follow the steps [here](https://github.com/ploomber/soorgeon/blob/main/CONTRIBUTING.md#adding-new-test-notebooks) to download notebooks and dataset, remember to convert .ipynb to .py
3. Your final layout should be a little different and look like this:

```txt
your_download_dir/
    {notebook-name}/
        nb.py
        data.csv
 ```
4. Upload the {notebook-name} directory here
5. Check for potential package requirements, add them [here](https://github.com/ploomber/soorgeon/blob/main/_kaggle/requirements.lock.txt)
6. Finally update [CI](https://github.com/ploomber/soorgeon/blob/main/.github/workflows/ci.yaml) and [test file](https://github.com/ploomber/soorgeon/blob/main/tests/test_sample_notebooks.py)
