## Create Cognitive Services Helper

* Create a file `CognitiveServicesHelper.cs`

* Add the following code:

```csharp
namespace GlobalAzureBLRDemo.Helpers
{
    public class CognitiveServicesHelper
    {
        public string ComputerVisionAPIKey { get; set; } = "<Enter Computer Vision API Key>";
        public string ComputerVisionAPIEndpoint { get; set; } = "<Enter Computer Vision Endpoint>";
    }
}
```

* Enter the Computer Vision API Key and Endpoint you get from your Azure Portal