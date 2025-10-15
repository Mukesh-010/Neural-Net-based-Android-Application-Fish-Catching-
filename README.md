# Neural-Net-based-Android-Application-Fish-Catching-

The Application Neural Net based Android Application for Real-Time Fish Catch Identification, Health, and Volume Estimation is used to develop an offline-capable Android application that allows fishermen, inspectors, or buyers to point their phone camera at the catch in maritime domain and instantly:
1.Identify fish species present (from a set of known species)
2.Estimate health/freshness/Quality indicators (based on defined attributes)
3.Count and estimate weight/volume from image/images
4.Store results with geotagging & timestamp for traceability.
5.Can be scaled to other aquatic species (shrimp, crab, etc.).

This Application uses:
1.Offline Application.
2.Instant verification of catch type, quantity, and quality at the source.
3.Empowers fishermen with digital records for better pricing.
4.Aids regulators in enforcing fishing quotas and monitoring sustainability.
5.Improves traceability for exporters and seafood buyers.
6.Can be scaled to other aquatic species (shrimp, crab, etc.).

The tools which are used to develop this product is,

1.Image/Video Capture via phone camera.

2.AI Pipeline (on-device):
  - YOLOv8-Tiny for detection.
  - EfficientNet-Lite for classification (like Species name).
  - CNN model for health detection (Good, Bad, Average).
    
3.Volume & Weight Estimation:
- Use known object (e.g., ruler, crate) for scale.
- Depth sensing via ARCore or dual-camera data.
  
4.Results Display:
- Species list, count, estimated weight, health status.
- Confidence score for each prediction.
  
5.Data Storage:
- Local SQLite DB.
- Optional cloud sync to government/market systems.
