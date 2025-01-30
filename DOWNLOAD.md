Dataset **Indoor Objects Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzIzODdfSW5kb29yIE9iamVjdHMgRGV0ZWN0aW9uL2luZG9vci1vYmplY3RzLWRldGVjdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJPZEIrMjUzdUcwRjdPZER3OU10QlpnNUtTb29pSElQdzFmTHFzMHJzMVA4PSJ9)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Indoor Objects Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/thepbordin/indoor-object-detection/download?datasetVersionNumber=1).