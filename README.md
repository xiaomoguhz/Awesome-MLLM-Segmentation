# Awesome-MLLM-Segmentation

**If you find this project helpful, please consider giving it a star ⭐.**

## Contents

<!-- vim-markdown-toc GitLab -->
- [Awesome-MLLM-Segmentation](#awesome-mllm-segmentation)
  - [Contents](#contents)
  - [Image Segmentation](#image-segmentation)
    - [Referring Expression Segmentation](#referring-expression-segmentation)
    - [Open-Vocabulary Semantic Segmentation](#open-vocabulary-semantic-segmentation)
  - [Video Segmentation](#video-segmentation)
  - [Feedback](#feedback)

<!-- vim-markdown-toc -->

## Image Segmentation

### Referring Expression Segmentation

1. <span id = "1001">**[LISA]**</span> | **CVPR'24** | LISA: Reasoning Segmentation via Large Language Model | [`[pdf]`](https://arxiv.org/abs/2308.00692) | [`[code]`](https://github.com/dvlab-research/LISA)
2. <span id = "1002">**[GLaMM]**</span> | **CVPR'24** | GLaMM: Pixel Grounding Large Multimodal Model | [`[pdf]`](https://arxiv.org/abs/2311.03356) | [`[code]`](https://github.com/mbzuai-oryx/groundingLMM)
3. <span id = "1003">**[PixelLM]**</span> | **CVPR'24** | PixelLM: Pixel Reasoning with Large Multimodal Model | [`[pdf]`](https://arxiv.org/abs/2312.02228) | [`[code]`](https://github.com/MaverickRen/PixelLM)
4. <span id = "1004">**[GSVA]**</span> | **CVPR'24** | GSVA: Generalized Segmentation via Multimodal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2312.10103) | [`[code]`](https://github.com/LeapLabTHU/GSVA)
5. <span id = "1005">**[AnyRef]**</span> | **CVPR'24** | Multi-modal Instruction Tuned LLMs with Fine-grained Visual Perception | [`[pdf]`](https://arxiv.org/abs/2403.02969) | [`[code]`](https://github.com/jwh97nn/AnyRef)
6. <span id = "1006">**[GROUNDHOG]**</span> | **CVPR'24** | GROUNDHOG: Grounding Large Language Models to Holistic Segmentation | [`[pdf]`](https://arxiv.org/abs/2402.16846) | [`[code]`](https://groundhog-mllm.github.io)
7. <span id = "1007">**[NExT-Chat]**</span> | **ICML'24** | NExT-Chat: An LMM for Chat, Detection and Segmentation | [`[pdf]`](https://arxiv.org/abs/2311.04498) | [`[code]`](https://github.com/NExT-ChatV/NExT-Chat)
8. <span id = "1008">**[PSALM]**</span> | **ECCV'24** | PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model | [`[pdf]`](https://arxiv.org/abs/2403.14598) | [`[code]`](https://github.com/zamling/PSALM)
9. <span id = "1009">**[SAM4MLLM]**</span> | **ECCV'24** | SAM4MLLM: Enhance Multi-Modal Large Language Model for Referring Expression Segmentation | [`[pdf]`](https://arxiv.org/abs/2409.10542) | [`[code]`](https://github.com/AI-Application-and-Integration-Lab/SAM4MLLM)
10. <span id = "1010">**[CoReS]**</span> | **ECCV'24** | CoReS: Orchestrating the Dance of Reasoning and Segmentation | [`[pdf]`](https://arxiv.org/abs/2404.05673) | [`[code]`](https://github.com/baoxiaoyi/CoReS)
11. <span id = "1011">**[VISA]**</span> | **ECCV'24** | VISA: Reasoning Video Object Segmentation via Large Language Models | [`[pdf]`](https://arxiv.org/abs/2407.11325) | [`[code]`](https://github.com/cilinyan/VISA)
12. <span id = "1012">**[OMG-LLaVA]**</span> | **NeurIPS'24** | OMG-LLaVA: Bridging Image-level, Object-level, Pixel-level Reasoning and Understanding | [`[pdf]`](https://arxiv.org/abs/2406.19389) | [`[code]`](https://github.com/lxtGH/OMG-Seg)
13. <span id = "1013">**[VITRON ]**</span> | **NeurIPS'24** | Vitron: A Unified Pixel-level Vision LLM for Understanding, Generating, Segmenting, Editing | [`[pdf]`](https://arxiv.org/abs/2412.19806) | [`[code]`](https://github.com/SkyworkAI/Vitron)
14. <span id = "1014">**[VisionLLM v2]**</span> | **NeurIPS'24** | VisionLLM v2: An End-to-End Generalist Multimodal Large Language Model for Hundreds of Vision-Language Tasks | [`[pdf]`](https://arxiv.org/abs/2406.08394) | [`[code]`](https://github.com/OpenGVLab/VisionLLM)
15. <span id = "1015">**[VLTP]**</span> | **WACV'25** | VLTP: Vision-Language Guided Token Pruning for Task-Oriented Segmentation | [`[pdf]`](https://arxiv.org/abs/2409.08464) | [`[code]`](https://github.com/HanningChen/VLTP/tree/main)
16. <span id = "1016">**[LaVASeg]**</span> | **ArXiv'2403** | Empowering Segmentation Ability to Multi-modal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2403.14141)
17. <span id = "1017">**[LaSagnA]**</span> | **ArXiv'2404** | LaSagnA: Language-based Segmentation Assistant for Complex Queries | [`[pdf]`](https://arxiv.org/abs/2404.08506) | [`[code]`](https://github.com/congvvc/LaSagnA)
18. <span id = "1018">**[F-LMM]**</span> | **CVPR'25** | F-LMM: Grounding Frozen Large Multimodal Models | [`[pdf]`](https://arxiv.org/abs/2406.05821) | [`[code]`](https://github.com/wusize/F-LMM)
19. <span id = "1019">**[SETOKIM]**</span> | **ICLR'25** | Towards Semantic Equivalence of Tokenization in Multimodal LLM | [`[pdf]`](https://arxiv.org/abs/2406.05127) | [`[code]`](https://github.com/ChocoWu/SeTok)
20. <span id = "1020">**[u-LLaVA]**</span> | **ArXiv'2408** | u-LLaVA: Unifying Multi-Modal Tasks via Large Language Model | [`[pdf]`](https://arxiv.org/abs/2311.05348) | [`[code]`](https://github.com/OPPOMKLab/u-LLaVA)
21. <span id = "1021">**[UnifiedMLLM]**</span> | **ArXiv'2408** | UnifiedMLLM: Enabling Unified Representation for Multi-modal Multi-tasks With Large Language Model | [`[pdf]`](https://arxiv.org/abs/2408.02503) | [`[code]`](https://github.com/lzw-lzw/UnifiedMLLM)
22. <span id = "1022">**[DIFFLMM]**</span> | **ArXiv'2410** | Emerging Pixel Grounding in Large Multimodal Models Without Grounding Supervision | [`[pdf]`](https://arxiv.org/abs/2410.08209) | [`[code]`](https://github.com/Shengcao-Cao/groundLMM)
23. <span id = "1023">**[SegLLM]**</span> | **ICLR'25** | SegLLM: Multi-round Reasoning Segmentation | [`[pdf]`](https://arxiv.org/pdf/2410.18923) | [`[code]`](https://github.com/berkeley-hipie/segllm)
24. <span id = "1024">**[HyperSeg]**</span> | **ArXiv'2411** | HyperSeg: Towards Universal Visual Segmentation with Large Language Model| [`[pdf]`](https://arxiv.org/abs/2411.17606) | [`[code]`](https://github.com/congvvc/HyperSeg)
25. <span id = "1025">**[InstructSeg]**</span> | **ArXiv'2412** | InstructSeg: Unifying Instructed Visual Segmentation with Multi-modal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2412.14006) | [`[code]`](https://github.com/congvvc/InstructSeg)
26. <span id = "1026">**[PRIMA]**</span> | **ArXiv'2412** | PRIMA: Multi-Image Vision-Language Models for Reasoning Segmentation | [`[pdf]`](https://arxiv.org/abs/2412.15209) | [`[code]`](https://plan-lab.github.io/projects/prima/)
27. <span id = "1027">**[GeoGround]**</span> | **ArXiv'2411** | GeoGround: A Unified Large Vision-Language Model for Remote Sensing Visual Grounding | [`[pdf]`](https://arxiv.org/abs/2411.11904) | [`[code]`](https://github.com/zytx121/GeoGround)
28. <span id = "1028">**[RSUniVLM]**</span> | **ArXiv'2412** | RSUniVLM: A Unified Vision Language Model for Remote Sensing via Granularity-oriented Mixture of Experts | [`[pdf]`](https://arxiv.org/abs/2412.05679) | [`[code]`](https://github.com/xuliu-cyber/RSUniVLM)
29. <span id = "1029">**[Text4Seg]**</span> | **ICLR'25** | Text4Seg: Reimagining Image Segmentation as Text Generation | [`[pdf]`](https://arxiv.org/abs/2410.09855) | [`[code]`](https://github.com/mc-lan/Text4Seg)
30. <span id = "1030">**[Sa2VA]**</span> | **ArXiv'2501** | Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of Images and Videos | [`[pdf]`](https://arxiv.org/abs/2501.04001) | [`[code]`](https://github.com/magic-research/Sa2VA)
31. <span id = "1031">**[MIRAS]**</span> | **ArXiv'2502** | Pixel-Level Reasoning Segmentation via Multi-turn Conversations | [`[pdf]`](https://arxiv.org/abs/2502.09447) | [`[code]`](https://github.com/ccccai239/PixelRIST)
32. <span id = "1032">**[GeoPix]**</span> | **ArXiv'2501** | GeoPix: Multi-Modal Large Language Model for Pixel-level Image Understanding in Remote Sensing | [`[pdf]`](https://arxiv.org/abs/2501.06828)
33. <span id = "1033">**[UFO]**</span> | **ArXiv'2503** | UFO: A Unified Approach to Fine-grained Visual Perception via Open-ended Language Interface | [`[pdf]`](https://arxiv.org/abs/2503.01342) | [`[code]`](https://github.com/nnnth/UFO)
34. <span id = "1034">**[GroundingSuite]**</span> | **ArXiv'2503** | GroundingSuite: Measuring Complex Multi-Granular Pixel Grounding | [`[pdf]`](https://arxiv.org/abs/2503.10596) | [`[code]`](https://github.com/hustvl/GroundingSuite)
35. <span id = "1035">**[HiMTok]**</span> | **ArXiv'2503** | HiMTok: Learning Hierarchical Mask Tokens for Image Segmentation with Large Multimodal Model | [`[pdf]`](https://arxiv.org/abs/2503.13026) | [`[code]`](https://github.com/yayafengzi/LMM-HiMTok)
36. <span id = "1036">**[Seg-Zero]**</span> | **ArXiv'2503** | Seg-Zero: Reasoning-Chain Guided Segmentation via Cognitive Reinforcement | [`[pdf]`](https://arxiv.org/abs/2503.06520) | [`[code]`](https://github.com/dvlab-research/Seg-Zero)
37. <span id = "1037">**[POPEN]**</span> | **CVPR'25** | POPEN: Preference-Based Optimization and Ensemble for LVLM-Based Reasoning Segmentation | [`[pdf]`](https://arxiv.org/abs/2504.00640) | [`[code]`](https://lanyunzhu.site/POPEN)
38. <span id = "1038">**[MMSA]**</span> | **ICLR'25** | MMR: A Large-scale Benchmark Dataset for Multi-target and Multi-granularity Reasoning Segmentation | [`[pdf]`](https://arxiv.org/abs/2503.13881) | [`[code]`](https://github.com/jdg900/MMR)
39. <span id = "1039">**[SegEarth-R1]**</span> | **ArXiv'2504** | SegEarth-R1: Geospatial Pixel Reasoning via Large Language Model | [`[pdf]`](https://arxiv.org/abs/2504.09644) | [`[code]`](https://github.com/earth-insights/SegEarth-R1)
40. <span id = "1040">**[Pixel-SAIL]**</span> | **ArXiv'2504** | Pixel-SAIL: Single Transformer For Pixel-Grounded Understanding | [`[pdf]`](https://arxiv.org/abs/2504.10465) | [`[code]`](https://github.com/magic-research/Sa2VA)
41. <span id = "1041">**[Ground-V]**</span> | **CVPR'25** | Ground-V: Teaching VLMs to Ground Complex Instructions in Pixels | [`[pdf]`](https://arxiv.org/abs/2505.13788)
42. <span id = "1042">**[VistaLLM]**</span> | **CVPR'24** | Jack of All Tasks, Master of Many: Designing General-purpose Coarse-to-Fine Vision-Language Model | [`[pdf]`](https://arxiv.org/abs/2312.12423)
43. <span id = "1043">**[SegAgent]**</span> | **CVPR'25** | SegAgent: Exploring Pixel Understanding Capabilities in MLLMs by Imitating Human Annotator Trajectories | [`[pdf]`](https://arxiv.org/abs/2503.08625) | [`[code]`](https://github.com/aim-uofa/SegAgent)
44. <span id = "1044">**[ALTo]**</span> | **ArXiv'2505** | ALTo: Adaptive-Length Tokenizer for Autoregressive Mask Generation | [`[pdf]`](https://arxiv.org/abs/2505.16495) | [`[code]`](https://github.com/yayafengzi/ALToLLM)
45. <span id = "1045">**[SAM-R1]**</span> | **ArXiv'2505** | SAM-R1: Leveraging SAM for Reward Feedback in Multimodal Segmentation via Reinforcement Learning | [`[pdf]`](https://arxiv.org/abs/2505.22596)
46. <span id = "1046">**[RSVP]**</span> | **ACL'25** | RSVP: Reasoning Segmentation via Visual Prompting and Multi-modal Chain-of-Thought | [`[pdf]`](https://www.arxiv.org/abs/2506.04277)
47. <span id = "1047">**[VRS-HQ]**</span> | **CVPR'25** | The Devil is in Temporal Token: High Quality Video Reasoning Segmentation | [`[pdf]`](https://arxiv.org/abs/2501.08549) | [`[code]`](https://github.com/SitongGong/VRS-HQ)
48. <span id = "1048">**[VisionReasoner]**</span> | **Arxiv'2505** | VisionReasoner: Unified Visual Perception and Reasoning via Reinforcement Learning | [`[pdf]`](https://arxiv.org/abs/2505.12081) | [`[code]`](https://github.com/dvlab-research/VisionReasoner)
49. <span id = "1049">**[PixelThink]**</span> | **Arxiv'2505** | PixelThink: Towards Efficient Chain-of-Pixel Reasoning | [`[pdf]`](https://arxiv.org/abs/2505.23727) | [`[code]`](https://github.com/songw-zju/PixelThink)
50. <span id = "1050">**[Seg-R1]**</span> | **Arxiv'2506** | Seg-R1: Segmentation Can Be Surprisingly Simple with Reinforcement Learning | [`[pdf]`](https://www.arxiv.org/abs/2506.22624) | [`[code]`](https://github.com/geshang777/Seg-R1)
51. <span id = "1051">**[HRSeg]**</span> | **Arxiv'2507** | HRSeg: High-Resolution Visual Perception and Enhancement for Reasoning Segmentation | [`[pdf]`](https://www.arxiv.org/abs/2507.12883) | [`[code]`](https://github.com/WeihuangLin/HRSeg)

### Open-Vocabulary Semantic Segmentation

1. <span id = "2001">**[PSALM]**</span> | **ECCV'24** | PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model | [`[pdf]`](https://arxiv.org/abs/2403.14598) | [`[code]`](https://github.com/zamling/PSALM)
2. <span id = "2002">**[LLMFormer]**</span> | **IJCV'24** | LLMFormer: Large Language Model for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://link-springer-com.remotexs.ntu.edu.sg/article/10.1007/s11263-024-02171-y)
3. <span id = "2003">**[LaSagnA]**</span> | **ArXiv'2404** | LaSagnA: Language-based Segmentation Assistant for Complex Queries | [`[pdf]`](https://arxiv.org/abs/2404.08506) | [`[code]`](https://github.com/congvvc/LaSagnA)
4. <span id = "2004">**[HyperSeg]**</span> | **ArXiv'2411** | HyperSeg: Towards Universal Visual Segmentation with Large Language Model| [`[pdf]`](https://arxiv.org/abs/2411.17606) | [`[code]`](https://github.com/congvvc/HyperSeg)
5. <span id = "2005">**[Text4Seg]**</span> | **ICLR'25** | Text4Seg: Reimagining Image Segmentation as Text Generation | [`[pdf]`](https://arxiv.org/abs/2410.09855) | [`[code]`](https://github.com/mc-lan/Text4Seg)
6. <span id = "2006">**[HiMTok]**</span> | **ArXiv'2503** | HiMTok: Learning Hierarchical Mask Tokens for Image Segmentation with Large Multimodal Model | [`[pdf]`](https://arxiv.org/abs/2503.13026) | [`[code]`](https://github.com/yayafengzi/LMM-HiMTok)
7. <span id = "2007">**[ALTo]**</span> | **ArXiv'2505** | ALTo: Adaptive-Length Tokenizer for Autoregressive Mask Generation | [`[pdf]`](https://arxiv.org/abs/2505.16495) | [`[code]`](https://github.com/yayafengzi/ALToLLM)

## Video Segmentation

1. <span id = "3001">**[VISA]**</span> | **ECCV'24** | VISA: Reasoning Video Object Segmentation via Large Language Models | [`[pdf]`](https://arxiv.org/abs/2407.11325) | [`[code]`](https://github.com/cilinyan/VISA)
2. <span id = "3002">**[VideoLISA]**</span> | **NeurIPS'24** | One Token to Seg Them All: Language Instructed Reasoning Segmentation in Videos | [`[pdf]`](https://arxiv.org/abs/2409.19603) | [`[code]`](https://github.com/showlab/VideoLISA)
3. <span id = "3003">**[VITRON ]**</span> | **NeurIPS'24** | Vitron: A Unified Pixel-level Vision LLM for Understanding, Generating, Segmenting, Editing | [`[pdf]`](https://arxiv.org/abs/2412.19806) | [`[code]`](https://github.com/SkyworkAI/Vitron)
4. <span id = "3004">**[ViLLa]**</span> | **ArXiv'2407** | ViLLa: Video Reasoning Segmentation with Large Language Model | [`[pdf]`](https://arxiv.org/abs/2407.14500) | [`[code]`](https://github.com/rkzheng99/ViLLa)
5. <span id = "3005">**[HyperSeg]**</span> | **ArXiv'2411** | HyperSeg: Towards Universal Visual Segmentation with Large Language Model| [`[pdf]`](https://arxiv.org/abs/2411.17606) | [`[code]`](https://github.com/congvvc/HyperSeg)
6. <span id = "3006">**[InstructSeg]**</span> | **ArXiv'2412** | InstructSeg: Unifying Instructed Visual Segmentation with Multi-modal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2412.14006) | [`[code]`](https://github.com/congvvc/InstructSeg)
7. <span id = "3007">**[Sa2VA]**</span> | **ArXiv'2501** | Sa2VA: Marrying SAM2 with LLaVA for Dense Grounded Understanding of Images and Videos | [`[pdf]`](https://arxiv.org/abs/2501.04001) | [`[code]`](https://github.com/magic-research/Sa2VA)
8. <span id = "3008">**[VRS-HQ]**</span> | **CVPR'25** | The Devil is in Temporal Token: High Quality Video Reasoning Segmentation | [`[pdf]`](https://arxiv.org/abs/2501.08549) | [`[code]`](https://github.com/SitongGong/VRS-HQ)
9. <span id = "3009">**[GLUS]**</span> | **CVPR'25** | GLUS: Global-Local Reasoning Unified into A Single Large Language Model for Video Segmentation | [`[pdf]`](https://arxiv.org/abs/2504.07962) | [`[code]`](https://github.com/GLUS-video/GLUS)
10. <span id = "3010">**[DeSa2VA]**</span> | **arXiv'2506** | Decoupled Seg Tokens Make Stronger Reasoning Video Segmenter and Grounder | [`[pdf]`](https://arxiv.org/abs/2506.22880) | [`[code]`](https://github.com/longmalongma/DeSa2VA)

## Feedback

If you have any suggestions or find missing papers, please feel free to reach out at `lanm0002@e.ntu.edu.sg`.

