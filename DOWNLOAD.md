Dataset **Accurate Nevus Shapes** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/5/f/l5/a3W44c9WSqQPL5YUG6BUFAJ1tU5xGSqfJID77sm6hxKB1bPStoy9zFl3qzWfrCtQ90Z3cRttnvM5tesk9rvMsIAxn6U2kH90bXCL60ViUC3WjJqAXiBfeYl4553p.tar)

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