# Limitations of AI Self-Detection for Identifying Paraphrased Text

This GitHub repository contains the data used in the paper 
[AI Content Self-Detection for Transformer-based Large Language Models.](https://arxiv.org/abs/2312.172890)

## Overview

The study investigates the effectiveness of AI models in recognizing AI-generated versus human-written text, especially when the text is paraphrased. This has critical implications for academic integrity, plagiarism detection, 
and the use of AI-generated content in general.

## Dataset Summary

The dataset contains short essays (about 1500 characters long) about several topics, including Global Warming, James Webb Telescope, Human Rights in the Digital Age, 
Impact of Social Media on Society, Healthcare Access and Reform, Automation and the Future of Work, etc.

- Total essays: 350
  - AI-Generated (Original): 150 (ChatGPT: 50, Bard: 50, Claude: 50)
  - AI-Generated (Paraphrased): 150 (ChatGPT: 50, Bard: 50, Claude: 50)
  - Human-Written: 50

The data also contains the detection results given by the three AI models (ChatGPT, Bard, Claude) and the AI content detector ZeroGPT.

The official model version available in November 2023 was used for all AI models. More details on the data and the data generation process can be found in the paper.

## Key Findings

- Detection Accuracy:
  - ChatGPT identified AI content in 132 out of 350 cases.
  - Bard was more accurate in detecting human content.
  - Claude showed balanced detection rates for AI and human content.
  - ZeroGPT leaned towards detecting AI content.
- Paraphrasing significantly impacts AI models' detection capabilities.

## Citation

When using this dataset or study, please cite as:

> Antônio Junior Alves Caiado and Michael Hahsler. AI content self-detection for transformer-based large language models. arXiv:2312.17289 [cs.CL], December 2023.

```
@misc{caiado2023ai,
      title={AI Content Self-Detection for Transformer-based Large Language Models},
      author={Antônio Junior Alves Caiado and Michael Hahsler},
      year={2023},
      eprint={2312.17289},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
