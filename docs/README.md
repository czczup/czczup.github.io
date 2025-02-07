---
pageClass: home-page
# some data for the components

name: Zhe Chen (陈喆)
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/czczup
  - title: email
    icon: "/icons/email.svg"
    link: 'mailto:wztxy89[at]163.com'
    
cv: /pdf/cv.pdf
bio: Phd Candidate at Nanjing University
email: chenzhe98@smail.nju.edu.cn
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I am a second-year PhD candidate in the Department of Computer Science and Technology at Nanjing University (NJU), supervised by [Prof. Tong Lu](https://cs.nju.edu.cn/lutong/). I started my studies in 2020 through a combined Master's and PhD program, which includes two years for the master's degree and four years for the PhD.

My research interests are vision foundation model, vision-language model, and detection & segmentation.

## News
- [2024-02-27] [InternVL](https://github.com/OpenGVLab/InternVL) (oral) is accepted by CVPR 2024.
- [2024-01-16] [GeoDiffusion](https://kaichen1998.github.io/projects/geodiffusion/), [All-Seeing](https://arxiv.org/pdf/2308.01907.pdf?ref=morioh.com&utm_source=morioh.com), and [BoS](https://openreview.net/pdf?id=lmM4Ecm4HJ) (spotlight) are accepted by ICLR 2024.
- [2023-10-10] [AVSegFormer](https://arxiv.org/abs/2307.01146) is accepted by AAAI 2024.
- [2023-10-24] [InternImage](https://arxiv.org/abs/2211.05778) is is selected as one of [CVPR 2023 Top-10 Influential Papers](https://www.paperdigest.org/2023/09/most-influential-cvpr-papers-2023-09/).
- [2023-09-22] [VisionLLM](https://arxiv.org/abs/2305.11175) is accepted by NeurIPS 2023.
- [2023-07-14] [DDP](https://arxiv.org/abs/2303.17559) is accepted by ICCV 2023.
- [2023-05-10] We release [InternGPT](https://github.com/OpenGVLab/InternChat), which allows you to interact with ChatGPT by clicking, dragging and drawing using a pointing device.
- [2023-04-20] [GPTrans](https://arxiv.org/abs/2305.11424) is accepted by IJCAI 2023.
- [2023-02-28] [InternImage](https://arxiv.org/abs/2211.05778) (highlight) is accepted by CVPR 2023.
- [2023-01-21] [ViT-Adapter](https://arxiv.org/abs/2205.08534) (spotlight) is accepted by ICLR 2023.
- [2023-01-17] Our team wins the champion of [WSDM Cup 2023 Toloka VQA Challenge](https://codalab.lisn.upsaclay.fr/competitions/7434#learn_the_details).
- [2022-11-11] Our InternImage-H created new record of [65.4 box AP](https://paperswithcode.com/sota/object-detection-on-coco) on COCO [test-dev](https://codalab.lisn.upsaclay.fr/competitions/7384#results)!
- [2022-09-19] Our team wins the champions in 7 tracks of [Ego4D ECCV2022 Challenge](https://ego4d-data.org/workshops/eccv22/).
- [2021-12-01] [URST](https://arxiv.org/abs/2103.11784) is accepted by AAAI 2022.
- [2020-12-21] Our team wins the champion of [NAIC 2020 Remote Sensing Semantic Segmentation Task (1,000,000 RMB bonus)](https://cs.nju.edu.cn/b8/d5/c1654a506069/page.htm).
- [2020-05-12] [SiameseCCR](https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/iet-ipr.2019.0618) is accepted by IET Image Processing.


## Education & Experiences

- **Nanjing University, Nanjing, China** <br/>
Sept 2020 - Present

- **Zhejiang University of Science and Technology, Zhejiang, China** <br/>
Sept 2016 - June 2020
  

## Publications

[→ Full list](/projects/)

\* Equal Contribution      # Corresponding Author

<ProjectCard image="/projects/internvl.png" hideBorder=true>

  **InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks**

  **Zhe Chen**, Jiannan Wu, Wenhai Wang, Weijie Su, Guo Chen, Sen Xing, Zhong Muyan, Qinglong Zhang, Xizhou Zhu, Lewei Lu, Bin Li, Ping Luo, Tong Lu, Yu Qiao, Jifeng Dai#

  CVPR oral, 2024

  Introduction: InternVL scales up the ViT to 6B parameters and aligns it with LLM.

  [[Paper](https://arxiv.org/abs/2312.14238)]
  [[BibTex](/bibtex/internvl.txt)]
  [[Code](https://github.com/OpenGVLab/InternVL)]
  [[Poster](/poster/internvl.png)]
  [[中文解读](https://zhuanlan.zhihu.com/p/675877376)]

</ProjectCard>


<ProjectCard image="/projects/internimage.png" hideBorder=true>

  **InternImage: Exploring Large-Scale Vision Foundation Models with Deformable Convolutions**

  Wenhai Wang*, Jifeng Dai*, **Zhe Chen\***, Zhenhang Huang*, Zhiqi Li*, Xizhou Zhu*, Xiaowei Hu, Tong Lu, Lewei Lu, Hongsheng Li, Xiaogang Wang, Yu Qiao#

  CVPR highlight, 2023 | [CVPR 2023 Top-10 Influential Papers](https://www.paperdigest.org/2023/09/most-influential-cvpr-papers-2023-09/)

  Introduction: This work presents a new large-scale CNN-based foundation model, termed InternImage.

  [[Paper](https://arxiv.org/abs/2211.05778)]
  [[BibTex](/bibtex/internimage.txt)]
  [[Code](https://github.com/OpenGVLab/InternImage)]
  [[Poster](/poster/internimage.png)]
  [[中文解读](https://zhuanlan.zhihu.com/p/610772005)]

</ProjectCard>


<ProjectCard image="/projects/vit_adapter.png" hideBorder=true>

  **Vision Transformer Adapter for Dense Predictions**

  **Zhe Chen\***, Yuchen Duan*, Wenhai Wang#, Junjun He, Tong Lu#, Jifeng Dai, Yu Qiao

  ICLR spotlight, 2023

  Introduction: This work present a simple yet powerful adapter for pure ViT, which can remedy the defects of ViT and achieve comparable performance to vision-specific models in dense prediction tasks.

  [[Paper](https://arxiv.org/abs/2205.08534)]
  [[BibTex](/bibtex/vit_adapter.txt)]
  [[Code](https://github.com/czczup/ViT-Adapter)]
  [[Poster](https://iclr.cc/media/PosterPDFs/ICLR%202023/12048.png?t=1680764158.7068026)]
  [[Slides](https://drive.google.com/file/d/1LotIZIEnZzKhsANjBTZs3qcezk9fbVCV/view?usp=share_link)]
  [[中文解读](https://zhuanlan.zhihu.com/p/608272954)]


</ProjectCard>


<ProjectCard image="/projects/bos.png" hideBorder=true>

  **Bounding Box Stability against Feature Dropout Reflects Detector Generalization across Environments**

  Yang Yang, Wenhai Wang, **Zhe Chen**, Jifeng Dai, Liang Zheng

  ICLR spotlight, 2024

  Introduction: A brand-new data-centric problem of estimating the detector performance in an unlabeled test domain.

  [[Paper](https://arxiv.org/abs/2403.13803)]
  [[BibTex](/bibtex/bos.txt)]
  [[Code](https://github.com/YangYangGirl/BoS)]

</ProjectCard>


<ProjectCard image="/projects/geodiffusion.png" hideBorder=true>

  **GeoDiffusion: Text-Prompted Geometric Control for Object Detection Data Generation**

  Kai Chen, Enze Xie, **Zhe Chen**, Lanqing Hong, Zhenguo Li, Dit-Yan Yeung

  ICLR, 2024

  Introduction: GeoDiffusion translates geometric conditions into text prompts, enhancing T2I models for generating detection data, and improves object detector performance.

  [[Paper](https://openreview.net/pdf?id=xBfQZWeDRH)]
  [[BibTex](/bibtex/geodiffusion.txt)]
  [[Code](https://github.com/KaiChen1998/GeoDiffusion)]

</ProjectCard>


<ProjectCard image="/projects/visionllm.png" hideBorder=true>

  **VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks**

  Wenhai Wang*, **Zhe Chen\***, Xiaokang Chen*, Jiannan Wu*, Xizhou Zhu, Gang Zeng, Ping Luo, Tong Lu, Jie Zhou, Yu Qiao, Jifeng Dai#

  NeurIPS, 2023

  Introduction: We present an LLM-based framework for vision-centric tasks, termed VisionLLM.

  [[Paper](https://arxiv.org/abs/2305.11175)]
  [[BibTex](/bibtex/visionllm.txt)]
  [[Code](https://github.com/OpenGVLab/VisionLLM)]
  [[Poster](/poster/visionllm.png)]

</ProjectCard>


<ProjectCard image="/projects/ddp.png" hideBorder=true>

  **DDP: Diffusion Model for Dense Visual Prediction**

  Yuanfeng Ji*, **Zhe Chen\***, Enze Xie#, Lanqing Hong, Xihui Liu, Zhaoqiang Liu, Tong Lu, Zhenguo Li, Ping Luo

  ICCV, 2023

  Introduction: We propose a simple, efficient, yet powerful framework for dense visual predictions based on the conditional diffusion pipeline.

  [[Paper](https://arxiv.org/abs/2303.17559)]
  [[BibTex](/bibtex/ddp.txt)]
  [[Code](https://github.com/JiYuanFeng/DDP)]
  [[Poster](/poster/ddp.png)]

</ProjectCard>

<ProjectCard image="/projects/avsegformer.png" hideBorder=true>

  **AVSegFormer: Audio-Visual Segmentation with Transformer**

  Shengyi Gao, **Zhe Chen**, Guo Chen, Wenhai Wang, Tong Lu#

  AAAI, 2024

  Introduction: This work presents a new framework for AVS tasks that leverages the transformer architecture.

  [[Paper](https://arxiv.org/abs/2307.01146)]
  [[BibTex](/bibtex/avsegformer.txt)]
  [[Code](https://github.com/vvvb-github/AVSegFormer)]
  [[Poster](/poster/avsegformer.png)]

</ProjectCard>

<ProjectCard image="/projects/gptrans.png" hideBorder=true>

  **Graph Propagation Transformer for Graph Representation Learning**

  **Zhe Chen\***, Hao Tan*, Tao Wang, Tianrun Shen, Tong Lu#, Qiuying Peng, Cheng Cheng, Yue Qi

  IJCAI, 2023

  Introduction: This work presents a novel transformer architecture for graph representation learning.

  [[Paper](https://arxiv.org/abs/2305.11424)]
  [[BibTex](/bibtex/gptrans.txt)]
  [[Code](https://github.com/czczup/gptrans)]

</ProjectCard>


<ProjectCard image="/projects/urst.jpg" hideBorder=true>

  **Towards Ultra-Resolution Neural Style Transfer via Thumbnail Instance Normalization**

  **Zhe Chen**, Wenhai Wang#, Enze Xie, Tong Lu#, Ping Luo

  AAAI, 2022

  Introduction: URST is a versatile framework for ultra-high resolution style transfer under limited GPU memory resources.

  [[Paper](https://arxiv.org/abs/2103.11784)]
  [[BibTex](/bibtex/urst.txt)]
  [[Code](https://github.com/czczup/URST)]
  [[Poster](/poster/urst.png)]
  [[中文解读](https://zhuanlan.zhihu.com/p/360193926)]

</ProjectCard>


<ProjectCard image="/projects/siamese_ccr.jpg" hideBorder=true>

  **SiameseCCR: A Novel Method for One-shot and Few-shot Chinese CAPTCHA Recognition using Deep Siamese Network**

  **Zhe Chen**, Weifeng Ma#, Nanfan Xu, Caoting Ji, Yulai Zhang

  IET Image Processing, 2020 (SCI Impact Factor: 2.373)

  Introduction: We proposed a Siamese network-based method for one-shot and few-shot Chinese CAPTCHA Recognition.
  
  [[Paper](/pdf/SiameseCCR.pdf)]
  [[BibTex](/bibtex/siameseccr.txt)]
  [[Code](https://github.com/czczup/SiameseCCR)] 

</ProjectCard>

## Preprints


<ProjectCard image="/projects/fast.png" hideBorder=true>

  **FAST: Faster Arbitrarily-Shaped Text Detector with Minimalist Kernel Representation**

  **Zhe Chen**, Jiahao Wang, Wenhai Wang, Guo Chen, Enze Xie, Ping Luo, Tong Lu#

  Arxiv, 2021

  Introduction: We propose an accurate and efficient scene text detection framework, termed FAST (i.e., faster arbitrarily-shaped text detector).

  [[Paper](https://arxiv.org/abs/2111.02394)]
  [[BibTex](/bibtex/fast.txt)]
  [[Code](https://github.com/czczup/FAST)]

</ProjectCard>


## Technical Reports


<ProjectCard image="/projects/ichat.png" hideBorder=true>

  **InternGPT: Solving Vision-Centric Tasks by Interacting with Chatbots Beyond Language**

  Zhaoyang Liu, Yinan He, Wenhai Wang, Weiyun Wang, Yi Wang, Shoufa Chen, Qinglong Zhang, Yang Yang, Qingyun Li, Jiashuo Yu, Kunchang Li, **Zhe Chen**, Xue Yang, Xizhou Zhu, Yali Wang, Limin Wang, Ping Luo, Jifeng Dai, Yu Qiao

  Technical Report, 2023

  Introduction: InternChat allows you to interact with ChatGPT by clicking, dragging and drawing using a pointing device.

  [[Paper](https://arxiv.org/abs/2305.05662)]
  [[BibTex](/bibtex/ichat.txt)]
  [[Code](https://github.com/OpenGVLab/InternChat)]
  [[中文解读](https://www.zhihu.com/question/570765297/answer/3021584671)]

</ProjectCard>


<ProjectCard image="/projects/wsdm2023.png" hideBorder=true>

  **Champion Solution for the WSDM2023 Toloka VQA Challenge**

  Shengyi Gao, **Zhe Chen**, Guo Chen, Wenhai Wang, Tong Lu#

  Technical Report, 2023

  Introduction: In this report, we present our champion solution to the WSDM2023 Toloka Visual Question Answering (VQA) Challenge.

  [[Paper](https://arxiv.org/abs/2301.09045)]
  [[BibTex](/bibtex/wsdm2023.txt)]
  [[Code](https://github.com/czczup/ViT-Adapter/tree/main/wsdm2023)]
  [[中文解读](https://zhuanlan.zhihu.com/p/611056687)]

</ProjectCard>



<ProjectCard image="/projects/ego4d.png" hideBorder=true>

  **InternVideo-Ego4D: A Pack of Champion Solutions to Ego4D Challenges**

  Guo Chen*, Sen Xing*, **Zhe Chen\***, Yi Wang*, Kunchang Li, Yizhuo Li, Yi Liu, Jiahao Wang, Yin-Dong Zheng, Bingkun Huang, Zhiyu Zhao, Junting Pan, Yifei Huang, Zun Wang, Jiashuo Yu, Yinan He, Hongjie Zhang, Tong Lu, Yali Wang, Limin Wang, Yu Qiao#

  Technical Report, 2022

  Introduction: This work presents our champion solutions to five tracks at Ego4D challenge.

  [[Paper](https://arxiv.org/abs/2211.09529)]
  [[BibTex](/bibtex/ego4d.txt)]
  [[Code](https://github.com/OpenGVLab/ego4d-eccv2022-solutions)]
  [[中文解读](https://mp.weixin.qq.com/s/KsqxA2rp2_2mu6Q73p79fg)]

</ProjectCard>




## Awards & Honors

### Contests
- Toloka Visual Question Answering Challenge, WSDM Cup 2023, 2023, [**1st Place**](https://codalab.lisn.upsaclay.fr/competitions/7434#learn_the_details).
- The 2nd Ego4D Challenge, ECCV Workshop, 2022, [**7 Top-1 Rankings**](https://ego4d-data.org/workshops/eccv22/).
- The 2nd National Artificial Intelligence Challenge (NAIC), Remote Sensing Semantic Segmentation Track, 2020, [**1st Place**](https://cs.nju.edu.cn/b8/d5/c1654a506069/page.htm) **(1,000,000 RMB Bonus)**.
- The 2nd China Gaofen Cup Beautiful Countryside Competition, Remote Sensing Crop Classification Track, 2019, [**3rd Prize**](https://yjs.zust.edu.cn/info/1035/2176.htm) **(5,000 RMB Bonus)**.
- The 9th National Undergraduate E-commerce "Innovation, Creativity and Entrepreneurship" Challenge, Zhejiang Division, 2019, [**1rd Prize**](https://sem.zust.edu.cn/info/1103/1713.htm).
- The 9nd National Undergraduate Service Outsourcing Competition, Captcha Recognition Task, 2018, **2rd Prize**.
### Honors
- Outstanding Graduate of Zhejiang Province
- Zhejiang Provincial Government Scholarship

### Some of My Friends
- [Guo Chen](https://chenguo.netlify.app/), [Zhiqi Li](https://zhiqi-li.github.io/), [Yuanfeng Ji](https://jiyuanfeng.github.io/), [Yang Yang](https://adriayang.netlify.app/), Zhanhao Liang

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
