Dataset **Accurate Nevus Shapes** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/W/r/NM/heI3r2mKkV7uqL9HVjyW8o3TJ6uPQ432d12OiVHGPpXp8rJuzqM2QM2gkSX6MuCp5xr53wCx7Xp4vq57Un3WjUi72gFbJ6amFtQzt0rWw1V2DAhxSak0WBk10FL5.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Accurate Nevus Shapes', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/metavision/accurate-nevus-shapessegmentation/download?datasetVersionNumber=1).