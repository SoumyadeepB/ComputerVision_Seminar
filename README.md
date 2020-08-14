# UnFlow: Unsupervised Learning of Optical Flow with a Bidirectional Census Loss

The increasing predominance of end-to-end deep learning methods in the field of Computer Vision has necessitated
the need for large quantities of labelled data. However, procuring dense per-pixel ground truth in the optical flow setting, for real
world scenes is difficult, owing to the high setup and infrastructure costs involved, making such data infrequent. To circumvent the
need for ground truth flow, this paper proposes an unsupervised loss based on occlusion-aware bidirectional flow estimation and a
robust census transform. This approach outperforms previous unsupervised deep networks on the KITTI benchmarks by a substantial
margin. It even performs better than existing supervised methods trained only on synthetic datasets. Further fine-tuning allows the
method to achieve competitive optical flow accuracy on the KITTI 2012 and 2015 benchmarks, which enables an optional generic
pre-training of supervised networks for datasets for which limited ground truth data is available.

![UnFlow-CSS](https://user-images.githubusercontent.com/12089275/90125879-0abed200-dd63-11ea-8ed6-78852b3bbc7c.png)


![Network Architecture](https://user-images.githubusercontent.com/12089275/90128330-05638680-dd67-11ea-9f8c-8c37022ba7ed.png)

