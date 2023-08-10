Dataset **Weed Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/4/X/me/1NqGOcndkAb0h0fqcZ7tQMXYCZESjZXpR1Cibq1olwwUe6lVkSEpW2xasr9RJOUC3dghoiYf6TQ5HnsBrp15QYXyxjkqgPBrbvPOyArW2fMUj8vM6us6Ex1DY8kS.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Weed Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://github.com/lameski/rgbweeddetection)