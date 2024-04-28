# C# Notes

### Running files (Rest-API)

```
dotnet run
.
```

### Adding packages for SDK

```
dotnet add package Azure.AI.TextAnalytics --version 5.3.0
```

### AI Vision

Studio URL: [https://portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com)

Resource Name: **Azure AI Services**

```
dotnet add package Azure.AI.Vision.ImageAnalysis -v 1.0.0-beta.1
```

```cs
// Import namespaces
using Azure.AI.Vision.ImageAnalysis;

// Authenticate Azure AI Vision client ImageAnalysisClient client = new ImageAnalysisClient( new Uri(aiSvcEndpoint),
new AzureKeyCredential(aiSvcKey));
```

### Azure AI Language service

Studio URL: [https://language.cognitive.azure.com/](https://language.cognitive.azure.com/)

Resource Name: **Language Service**

```
dotnet add package Azure.AI.TextAnalytics --version 5.3.0
```

```cs
// import namespaces
using Azure;
using Azure.AI.TextAnalytics;

// Create client using endpoint and key
AzureKeyCredential credentials = new AzureKeyCredential(aiSvcKey);
Uri endpoint = new Uri(aiSvcEndpoint);
TextAnalyticsClient aiClient = new TextAnalyticsClient(endpoint, credentials);
```

**asas**
