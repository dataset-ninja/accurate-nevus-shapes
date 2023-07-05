Dataset **Accurate nevus shapes** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/f/f/wa/DQUbdfemWn7LKfL8O1GIJIbyJS7ArUnvrfL5RDRdyHGuwK7bIG0HM3TSSWEzYaGJkMpPRI4hHAx5HoT4XOws6I6RM4zjnvB9l6YQd23z7eOg0vZqzVrU67j5AtPU.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Accurate nevus shapes', dst_path='~/dtools/datasets/Accurate nevus shapes.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/metavision/accurate-nevus-shapessegmentation/download?datasetVersionNumber=1)