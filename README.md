# InverseMV: Composing Piano Scores with a Convolutional Video-Music Transformer

This repository contains the code and examples for our paper [InverseMV: Composing Piano Scores with a Convolutional Video-Music Transformer](https://arxiv.org/abs/2112.15320).
Video-Music Transformer (VMT) is an attention-based multi-modal model, which generates piano music for a given video.

## Our Dataset

We release a new dataset composed of over 7 hours of piano scores with
fine alignment between pop music videos and MIDI files.
Our complete InverseMV dataset is available [here](https://drive.google.com/drive/folders/1wI1ojiwOScSGLZ8UwhwhGNVgTh7wFmjM?usp=sharing).

## Demo

Here is an example video fragments from our dataset.
Note that we do not do any post-production.
Each file is made from the original video with a WAVE file converted from the MIDI of the model output.

### Original
The original music of the videos.

https://user-images.githubusercontent.com/11171959/149646574-85840fb5-50bd-449b-bf0e-7c86fd4a2491.mp4

### VMT
The music generated by our VMT model.

https://user-images.githubusercontent.com/11171959/149646588-cd2e97b4-1ad3-4994-aed5-a5fa7f4c2179.mp4

### Seq2Seq
The musics generated by the baseline Seq2Seq model.

https://user-images.githubusercontent.com/11171959/149646580-d8625c5c-1921-4f0d-a3b1-3670a9510073.mp4

## Citation

Please cite our paper if you use InverseMV in your work:

```bibtex
@article{lin2021inversemv,
  title={InverseMV: Composing Piano Scores with a Convolutional Video-Music Transformer},
  author={Lin, Chin-Tung and Yang, Mu},
  journal={arXiv preprint arXiv:2112.15320},
  year={2021}
}
```