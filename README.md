# <img src="docs/images/h2rsvlm_logo-removebg-preview.png" style="vertical-align: -10px;" :height="50px" width="50px"> H<sup>2</sup>RSVLM：Towards Helpful and Honest Remote Sensing Large Vision Language Model

[![arXiv](https://img.shields.io/badge/arXiv-2403.20213-b31b1b.svg)](https://arxiv.org/abs/2403.20213) 

[[Project Page](https://fitzpchao.github.io/h2rsvlm_page/)] [[Paper](https://arxiv.org/abs/2403.20213)] [[HF Demo🤗](https://huggingface.co/spaces/FitzPC/H2RSVLM)] [[Model🤗](https://huggingface.co/FitzPC/H2RSVLM)] [[Dataset🤗](https://huggingface.co/datasets/FitzPC/HqDC-1.4M)]


<!-- <div style="display: flex; justify-content: center;" align="center">
<center>
<img src="doc/images/h2rsvlm_logo.png" style="width: 200 px;">
</div> -->
<div style="display: flex; justify-content: center;">
  <img src="docs/images/h2rsvlm_logo.png" style="height: 300px;">
</div>

## News
- **2024.3.28** Paper available on [ArXiv](https://arxiv.org/abs/2403.20213).

## TODO
- [ ] Release inference code and checkpoints of H<sup>2</sup>RSVLM.
- [ ] Release all data in this work.
- [ ] Release the training code of H<sup>2</sup>RSVLM.

<!-- ## Contents

- [Install](#install)
- [Models](#models)
- [Demo](#demo)
- [Data](#data)
- [Evaluation](#evaluation)
- [Training](#training) -->


## Citation
```bibtex
@misc{pang2024h2rsvlm,
        title={H2RSVLM: Towards Helpful and Honest Remote Sensing Large Vision Language Model}, 
        author={Chao Pang and Jiang Wu and Jiayu Li and Yi Liu and Jiaxing Sun and Weijia Li and Xingxing Weng and Shuai Wang and Litong Feng and Gui-Song Xia and Conghui He},
        year={2024},
        eprint={2403.20213},
        archivePrefix={arXiv},
        primaryClass={cs.CV}
```

## Acknowledgement
We gratefully acknowledge these wonderful works：
- [Vicuna](https://github.com/lm-sys/FastChat#vicuna-weights)
- [LLaVA](https://github.com/haotian-liu/LLaVA)
- [ShareGPT4V](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V)
- [LLaMA](https://github.com/facebookresearch/llama)

## License

![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg) ![Data License](https://img.shields.io/badge/Data%20License-CC%20By%20NC%204.0-red.svg) **Usage and License Notices**: The data and checkpoint is intended and licensed for research use only. They are also restricted to uses that follow the license agreement of LLaMA, Vicuna and Gemini. The dataset is CC BY NC 4.0 (allowing only non-commercial use) and models trained using the dataset should not be used outside of research purposes.