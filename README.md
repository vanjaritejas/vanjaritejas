# Tejas Vanjari

**AI graduate student at Northeastern University · Computer Vision TA · Research Assistant**

Boston, MA · Seeking a Spring 2027 co-op in applied AI or machine learning

[LinkedIn](https://www.linkedin.com/in/tejas-vanjari-p/) · [GitHub](https://github.com/vanjaritejas)

## About me

I'm a master's student at Northeastern University. My current work focuses on computer vision, especially what happens after a model detects something in a frame. In my herring research, detections need to become tracks and reliable counts. In my road-video project, they help determine which alert to display.

I'm also a teaching assistant for **EECE/CS 5639 Computer Vision**, where I support students with assignments and course projects. I'm interested in natural language processing as well, particularly how to evaluate a model's answers.

## Research experience

### Research Assistant · Northeastern University × MIT Sea Grant

I contribute to a project that uses underwater video to detect, track, and count river herring. One challenge is that fish can overlap during busy passages, making it harder to follow individuals across frames.

- **Baseline** — I worked with a pipeline that uses YOLO to detect fish and BoT-SORT to associate detections across frames for counting.
- **My contribution** — I prepared fish image crops and ran an initial Vision Transformer experiment to classify cropped images as herring or non-herring.
- **Current work** — I'm developing the ViT detection stage so it can locate fish in full video frames. The next step is to compare the YOLO and ViT detectors on the same footage, using the same tracking setup to evaluate detection quality and counting error.

## Featured project

### Lane and Object Detection for Driver Assistance

I built a Python prototype that processes road video and overlays lane boundaries, object detections, and a prioritized warning. I split it into three stages so I could test each part separately.

1. **Lane detection** — Use OpenCV to isolate white and yellow markings in the road region, then estimate lane boundaries with Hough lines.
2. **Object detection** — Use YOLO to detect objects and group them by where they appear relative to the vehicle's path.
3. **Alert logic** — Use object position and estimated proximity to decide which warning to display.

Glare was a failure case I had to handle. When it washed out the lane markings, the lane estimate could become unreliable, so I added fallback behavior for those frames.

[View the project on GitHub](https://github.com/vanjaritejas/lane-and-object-detection)

## Tools I use

Python · PyTorch · OpenCV · Ultralytics YOLO · Hugging Face Transformers · Linux

## Outside of work

I recently ran a 5K in Cambridge, and my next running goal is a half marathon.
