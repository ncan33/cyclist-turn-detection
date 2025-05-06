Automated detection of cyclist hand signals can enhance the experience and safety of road users. For instance, it is standard for self-driving cars to detect car turn signals, but cyclists may be overlooked. Another possible application is vision-based traffic light detection. Overlooking cyclist turn signals may result in missed optimizations in traffic flow. Let's explore the viability of detecting hand signals from cyclists using YOLOv8-Pose.

I used **YOLOv8-Pose** with **ByteTrack** to track cyclists across frames. Pose data was overlaid using **OpenCV**. Position data noise reduction was performed using Savitzky-Golay filtering.

Data is available [here](drive.google.com).
