![Tejas Vanjari — animated computer vision sketch with three tracked fish](./vision-banner.gif)

**AI grad student at Northeastern · Computer Vision TA · Research Assistant**  
📍 Boston, MA · Open to Spring 2027 applied AI and ML co-ops

[LinkedIn](https://www.linkedin.com/in/tejas-vanjari-p/) · [GitHub](https://github.com/vanjaritejas)

## Hey, I'm Tejas 👋

My projects usually start with a video and a question. Can I count fish when they swim past each other? Can a road-video prototype tell when it has lost sight of the lane? I like building the first version, finding the frames where it breaks, and figuring out what to try next.

At Northeastern, I study AI and help students with assignments and projects as a TA for **EECE/CS 5639 Computer Vision**. I'm also curious about NLP and how to tell when a model's answer holds up.

## 🐟 What I'm working on

**Research Assistant · Northeastern University × MIT Sea Grant**

I'm working on river herring detection and counting from underwater video. When fish overlap, keeping track of individual fish across frames gets harder.

- **Baseline** · I worked with a pipeline that uses YOLO to detect fish and BoT-SORT to track them across frames.
- **What I tried** · I prepared fish image crops and ran a small Vision Transformer experiment to classify them as herring or non-herring.
- **What I'm building next** · A ViT detector that locates fish in full frames. I want to compare it with YOLO on the same footage and see how each detector affects the final count.

## 🚗 Something I built

**Lane and Object Detection for Driver Assistance**

I built a Python prototype that estimates lane boundaries with OpenCV, detects objects with YOLO, and displays a prioritized alert. The most interesting part was debugging glare. It sometimes washed out the lane markings, so I added fallback behavior for frames where the lane estimate was unreliable.

[Explore the project](https://github.com/vanjaritejas/lane-and-object-detection)

## 🧰 Tools I reach for

`Python` · `PyTorch` · `OpenCV` · `YOLO` · `Hugging Face Transformers` · `Linux`

🏃 Away from my laptop, I recently ran a 5K in Cambridge. Next goal is a half marathon.
