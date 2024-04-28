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

Studio URL: [https://portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com)

Resource Name: **Azure AI Services**

```
pip install azure-ai-vision-imageanalysis==1.0.0b1
```

```python
# import namespaces
from azure.ai.vision.imageanalysis import ImageAnalysisClient
from azure.ai.vision.imageanalysis.models import VisualFeatures
from azure.core.credentials import AzureKeyCredential

# Authenticate Azure AI Vision client
cv_client = ImageAnalysisClient(
    endpoint=ai_endpoint,
    credential=AzureKeyCredential(ai_key)
)
```

### Azure AI Language service

Studio URL: [https://language.cognitive.azure.com/](https://language.cognitive.azure.com/)

Resource Name: **Language Service**

```
pip install azure-ai-textanalytics==5.3.0
pip install python-dotenv
```

```python
# import namespaces
from azure.core.credentials import AzureKeyCredential
from azure.ai.textanalytics import TextAnalyticsClient

# Create client using endpoint and key
credential = AzureKeyCredential(ai_key)
ai_client = TextAnalyticsClient(endpoint=ai_endpoint, credential=credential)
```

**asas**
