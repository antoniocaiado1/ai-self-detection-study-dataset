# Limitations of AI Self-Detection for Identifying Paraphrased Text

This GitHub repository presents the findings of a study, focusing on AI models' self-detection abilities in identifying paraphrased texts. The study evaluates models like ChatGPT, Bard, and Claude against a baseline model, zeroGPT.

## Overview

The research investigates the effectiveness of AI models in recognizing AI-generated versus human-written text, especially when the text is paraphrased. This has critical implications for academic integrity, plagiarism detection, and the use of AI-generated content.

## Dataset Summary

- Total Entries: 350
- Source Distribution: 
  - AI-Generated: 300 (ChatGPT: 100, Bard: 100, Claude: 100, None: 50)
  - Human-Written: 50
- Paraphrasing Distribution: Paraphrased (150), Not Paraphrased (150), N/A (50)
- Topics: Global Warming, James Webb Telescope, Human Rights in the Digital Age, Impact of Social Media on Society, Healthcare Access and Reform, Automation and the Future of Work, etc.

## Key Findings

- Detection Accuracy:
  - ChatGPT identified AI content in 132 out of 350 cases.
  - Bard was more accurate in detecting human content.
  - Claude showed balanced detection rates for AI and human content.
  - ZeroGPT leaned towards detecting AI content.
- Paraphrasing significantly impacts AI models' detection capabilities.

## Citation

When using this dataset or study, please cite:
@misc{caiado2023ai,
      title={AI Content Self-Detection for Transformer-based Large Language Models},
      author={Antônio Junior Alves Caiado and Michael Hahsler},
      year={2023},
      eprint={2312.17289},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
