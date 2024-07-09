# Video-LLM

## General Datasets 💾🌐

The following datasets are used in our training.

| Dataset                                                                                                                                        | Task Domain                             | Scale |
| :--------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------- | :---: |
| WebVid [link](https://github.com/m-bain/webvid)                                                                                                | Video captioning                        |  10M  |
| NExT-QA [link](https://doc-doc.github.io/docs/nextqa.html)                                                                                     | Video QA                                |  5K   |
| DiDemo [link](https://github.com/LisaAnne/TemporalLanguageRelease)                                                                             | Video captioning, temporal localization |  10K  |
| MSRVTT [link](https://www.microsoft.com/en-us/research/publication/msr-vtt-a-large-video-description-dataset-for-bridging-video-and-language/) | Video QA, video captioning              |  10K  |
| MSVD [link](https://www.cs.utexas.edu/users/ml/clamp/videoDescription/)                                                                        | Video QA, video captioning              |  2K   |
| TGIF-QA [link](https://github.com/YunseokJANG/tgif-qa/blob/master/dataset/README.md)                                                           | Video QA                                |  72K  |
| HMDB51 [link](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/)                                                   | Action recognition                      |  7K   |
| UCF101 [link](https://www.crcv.ucf.edu/data/UCF101.php)                                                                                        | Action recognition                      |  13K  |
| VideoInstruct-100K [link](https://huggingface.co/datasets/MBZUAI/VideoInstruct-100K)                                                           | Chat                                    | 100K  |

Other datasets:

| Dataset                                                                                                       | Task Domain        | Scale |
| :------------------------------------------------------------------------------------------------------------ | :----------------- | :---: |
| VideoChatInstruct-11K [link](https://github.com/OpenGVLab/InternVideo/tree/main/Data/instruction_data)        | Chat               |  11K  |
| Valley-webvid2M-Pretrain-703K [link](https://huggingface.co/datasets/luoruipu1/Valley-webvid2M-Pretrain-703K) | Video captioning   | 703K  |
| Valley-Instruct-73k [link](https://huggingface.co/datasets/luoruipu1/Valley-Instruct-73k)                     | Chat               |  73K  |
| Kinetics-400 [link](https://github.com/cvdfoundation/kinetics-dataset)                                        | Action recognition | 650K  |

## Papers
- [06/2023] Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding [[paper]](https://arxiv.org/abs/2306.02858) [[code]](https://github.com/DAMO-NLP-SG/Video-LLaMA)
- [05/2023] VideoChat: Chat-Centric Video Understanding [[paper]](https://arxiv.org/abs/2305.06355) [[code]](https://github.com/OpenGVLab/Ask-Anything)
- [11/2023] VideoChat2 (MVBench: A Comprehensive Multi-modal Video Understanding Benchmark) [[paper]](https://arxiv.org/pdf/2311.17005) [[code]](https://github.com/OpenGVLab/Ask-Anything)
- [06/2023] Video-ChatGPT: Towards Detailed Video Understanding via Large Vision and Language Models [[paper]](https://arxiv.org/abs/2306.05424) [[code]](https://github.com/mbzuai-oryx/Video-ChatGPT)
- [11/2023] Video-LLaVA: Learning United Visual Representation by Alignment Before Projection [[paper]](https://arxiv.org/abs/2311.10122) [[code]](https://github.com/PKU-YuanGroup/Video-LLaVA)
- [06/2024] VideoLLaMA 2: Advancing Spatial-Temporal Modeling and Audio Understanding in Video-LLMs [[paper]](https://arxiv.org/abs/2406.07476) [[code]](https://github.com/DAMO-NLP-SG/VideoLLaMA2)
- [06/2024] LongVA: Long Context Transfer from Language to Vision [[paper]](https://arxiv.org/pdf/2406.16852) [[code]](https://github.com/EvolvingLMMs-Lab/LongVA)
- [06/2024] Video-CCAM: Advancing Video-Language Understanding with Causal Cross-Attention Masks [[code]](https://github.com/QQ-MM/Video-CCAM)
- [06/2024] ShareGPT4Video: Improving Video Understanding and Generation with Better Captions [[paper]](https://arxiv.org/abs/2406.04325v1) [[code]](https://github.com/ShareGPT4Omni/ShareGPT4Video)
- [06/2024] LLaVA-NeXT-Video [[blog]](https://llava-vl.github.io/blog/2024-04-30-llava-next-video/) [[code]](https://github.com/LLaVA-VL/LLaVA-NeXT-Video)
- [05/2024] Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis [[paper]](https://arxiv.org/pdf/2405.21075) [[code]](https://video-mme.github.io/)
- [06/2024] MMBench-Video: A Long-Form Multi-Shot Benchmark for Holistic Video Understanding [[paper]](https://arxiv.org/pdf/2406.14515) [[code]](https://github.com/open-compass/VLMEvalKit)
- [06/2024] Towards Event-oriented Long Video Understanding [[paper]](https://arxiv.org/pdf/2406.14129) [[code]](https://github.com/RUCAIBox/Event-Bench)
