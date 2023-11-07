# Swin-Transformer-with-TensorFlow

Building a hierarchical representation of the input image by taking patches of small sizes and gradually increasing their size.

Instead of applying Transformer's attention to the entire input as usually done in NLP tasks, attention is calculated locally from non-overlapping shifted windows.

Comprehensive experiments on various vision tasks and model architectures and strong results, e.g. 58.7 box AP and 51.1 mask AP on test-dev on COCO object detection.
