Developed a deepfake detection model capable of classifying videos as either real or fake. The 
preprocessing phase involved splitting videos into frames, detecting faces, cropping 
facial regions, and creating a face-only video dataset. For feature extraction, utilized 
ResNeXt50, MobileNetV2, and EfficientNet-B0 architectures. The classification task 
employed LSTM networks to analyse temporal sequences and classify the videos. This 
comparative analysis identified the most effective feature extractor to be ResNeXt50 for deepfake 
detection.
