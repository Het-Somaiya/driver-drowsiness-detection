# Real-Time Driver Drowsiness Detection

A high-speed Computer Vision system designed for edge deployment, providing immediate auditory alerts based on real-time periorbital monitoring and facial landmark analysis.

## 👁️ Computer Vision Pipeline
- **Facial Landmark Localization:** Utilizes **DLib’s 68-point predictor** for high-precision eye and mouth tracking.
- **EAR (Eye Aspect Ratio):** Implemented mathematical thresholds to detect microsleep events based on eyelid closure duration.
- **OpenCV Integration:** Optimized frame-by-frame processing to maintain a low memory footprint.

## ⚡ Edge Optimization
- **Inference Latency:** Optimized the pipeline to achieve a response time of **<30ms per frame**, critical for life-saving safety alerts.
- **Accuracy:** Achieved **95%+ accuracy** in varied lighting conditions and head poses.
- **Embedded Readiness:** Architected specifically for low-power edge devices (e.g., Raspberry Pi or Jetson Nano).
