# Python Notes

### Running files (Rest-API)

```
pip install python-dotenv
python rest-client.py
```

### Adding packages for SDK

```
pip install azure-ai-textanalytics==5.3.0
```

### AI Vision

```
pip install azure-ai-vision-imageanalysis==1.0.0b1
```

```python
# import namespaces
from azure.ai.vision.imageanalysis import ImageAnalysisClient
from azure.ai.vision.imageanalysis.models import VisualFeatures
from azure.core.credentials import AzureKeyCredential
```
