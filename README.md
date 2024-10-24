# BSS-CFFMA: Cross-Domain Feature Fusion and Multi-Attention Speech Enhancement Network based on Self-Supervised Embedding

Speech self-supervised learning (SSL) represents has achieved state-of-the-art (SOTA) performance in multiple downstream tasks. However, its application in speech enhancement (SE) tasks remains immature, offering opportunities for improvement. In this study, we introduce a novel cross-domainnfeature fusion and multi -attention speech enhancement network, termed BSS-CFFMA, which leverages self-supervised embeddings. BSS-CFFMA comprises a multi-scale cross-domainfeature fusion (MSCFF) block and a residual hybrid multiattention (RHMA) block. The MSCFF block effectively integrates cross-domain features, facilitating the extraction of richacoustic information. The RHMA block, serving as the primary enhancement module, utilizes three distinct attention modules to capture diverse attention representations and estimate high quality speech signals.
We evaluate the performance of the BSS-CFFMA model through comparative and ablation studies on the VoiceBankDEMAND and WHAMR! dataset, achieving SOTA results.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

## Installation

### Dependencies
- torch==1.11.0
- torchaudio==0.11.0
- fairseq==0.12.2
- numpy==1.22.4
- numba==0.57.0
- pesq==0.0.3
- pstoi

To install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

## Usage

### Dateset and Data processing

Provide examples on how to use the project.

### Pre-trained model

Explain how to configure the project if necessary.

### Running

Instructions on how to run the project and any commands needed.

## Contributing

### Contributing Guidelines

Guidelines for contributing to the project.

### License

This project is licensed under the [License Name]. See the [LICENSE](LICENSE) file for details.

## Authors

- [Author Name](link to author's GitHub or website)

## Additional Information

### Feedback

Provide feedback channels or link to a FAQ section if available.

### Future Plans

Outline any future updates or features planned for the project.



Installation

# noisy speech

![img1](img/noisy.png) 

# enhance speech

![img2](img/enhance.png)

# clean speech

![img2](img/clean.png)

