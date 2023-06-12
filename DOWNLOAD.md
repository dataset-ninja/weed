Dataset **Weed** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/7/L/Iz/nopJghEeZgZP4xHyLRvTDz12fwRFdWJSjboLVoYvWHoOpQY5cdAGZIxnp8XwKSUeMHPo7oiId0ljhUEuoM0LuzL4nf09BKHMx1CWXvWqjA5p5zW8X7D03lwqpSXK.tar)

As an alternative, it can be downloaded with ```dataset-tools``` package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Weed', dst_path='~/dtools/datasets/Weed.tar')
```
The data in original format can be 🔗[downloaded here](https://github.com/lameski/rgbweeddetection/archive/refs/heads/master.zip)
