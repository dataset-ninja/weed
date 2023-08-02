Dataset **Weed Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/q/2/Qo/TjVk54bJ4xpUReIe5DwMtw6uHeU5vTGViP5z3n6N96DHVdTMOIsfDW17YjrU5jAYGI033GjVgLaWfUDCaJMK2CKKY6aJ8NvTDkj4zfqhgdQteIlsA7oMMvgDwbxq.tar)

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