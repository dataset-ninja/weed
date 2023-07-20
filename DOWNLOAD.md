Dataset **Weed detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/H/c/1u/SUemHlviy8FJq9LO53oVD886Kzf3cDFyvBYbXluxflQ2tMuj3JPXglafDxMUrOyhaSyj4DJmTVFvx9o2JqgjOY2TyaXa2Cy2ZJV9aCtOMppgg4zIDDCDv0B3P4Y9.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Weed detection', dst_path='~/dtools/datasets/Weed detection.tar')
```
The data in original format can be 🔗[downloaded here](https://github.com/lameski/rgbweeddetection)