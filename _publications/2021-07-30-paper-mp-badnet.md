---
title: "MP-BADNet: A Backdoor-Attack Detection and Identification Protocol among Multi-Participants in Private Deep Neural Networks"
collection: publications
permalink: /publication/2021-07-30-paper-mp-badnet
excerpt: 'Deep Neural Networks (DNNs) are vulnerable to backdoor attacks where the adversary can inject malicious data during the DNN training. Such kind of attacks is always activated when the input is stamped with a pre-specified trigger which results in a pre-setting prediction of the DNN model. Due to increasing applications of DNNs, it is necessary to detect the backdoors whether the DNN model has been trojaned before implementation. Since the data come from the various data holders during the model training, it is also important to protect the privacy both of input data and models. In this paper, we propose a framework MP-BADNet, the first work on the backdoor attack detection and identification protocol among multi-participants in private deep neural networks. MP-BADNet can not only detect and identify backdoors in the privacy-preserving DNN model, but also achieve privacy preserving of input data and the model in secure multi-party computation (MPC) ways. The implemental results show that the scheme can effectively detect and identify backdoor attacks in the privacy-preserving DNN model.'
date: 2021-07-30
venue: 'ACM TURC 2021: ACM Turing Award Celebration Conference - China ( ACM TURC 2021)'
paperurl: 'https://doi.org/10.1145/3472634.3472660'
citation: 'Chen C, Wei L, Zhang L, et al. MP-BADNet: A Backdoor-Attack Detection and Identification Protocol among Multi-Participants in Private Deep Neural Networks[C]//ACM Turing Award Celebration Conference-China (ACM TURC 2021). 2021: 104-109.'
---
# Abstract
In recent years, machine learning has developed rapidly, and it is widely used in the aspects of work and life, which brings not only convenience but also great security risks. The security and privacy issues have become a stumbling block in the development of machine learning. The training and inference of the machine learning model are based on a large amount of data, which always contains some sensitive information. With the frequent occurrence of data privacy leakage events and the aggravation of the leakage scale annually, how to make sure the security and privacy of data has attracted the attention of the researchers from academy and industry. In this paper we introduce some fundamental concepts such as the adversary model in the privacy preserving of machine learning and summarize the common security threats and privacy threats in the training and inference phase of machine learning, such as privacy leakage of training data, poisoning attack, adversarial attack, privacy attack, etc. Subsequently, we introduce the common security protecting and privacy preserving methods, especially focusing on homomorphic encryption, secure multi-party computation, differential privacy, etc. and compare the typical schemes and applicable scenarios of the three technologies. At the end, the future development trend and research direction of machine learning privacy preserving are prospected.

# Download
DOI: [10.1145/3472634.3472660](https://doi.org/10.1145/3472634.3472660)

[Download paper here](https://chen-congcong.github.io/files/paper/2021-07-30-paper-mp-badnet.pdf)

# Citation
## Recommended citation: <br>
Chen C, Wei L, Zhang L, et al. MP-BADNet: A Backdoor-Attack Detection and Identification Protocol among Multi-Participants in Private Deep Neural Networks[C]//ACM Turing Award Celebration Conference-China (ACM TURC 2021). 2021: 104-109.

## Bibtex
```
@inproceedings{10.1145/3472634.3472660,
author = {Chen, Congcong and Wei, Lifei and Zhang, Lei and Ning, Jianting},
title = {MP-BADNet: A Backdoor-Attack Detection and Identification Protocol among Multi-Participants in Private Deep Neural Networks},
year = {2021},
isbn = {9781450385671},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3472634.3472660},
doi = {10.1145/3472634.3472660},
abstract = {Deep Neural Networks (DNNs) are vulnerable to backdoor attacks where the adversary can inject malicious data during the DNN training. Such kind of attacks is always activated when the input is stamped with a pre-specified trigger which results in a pre-setting prediction of the DNN model. Due to increasing applications of DNNs, it is necessary to detect the backdoors whether the DNN model has been trojaned before implementation. Since the data come from the various data holders during the model training, it is also important to protect the privacy both of input data and models. In this paper, we propose a framework MP-BADNet, the first work on the backdoor attack detection and identification protocol among multi-participants in private deep neural networks. MP-BADNet can not only detect and identify backdoors in the privacy-preserving DNN model, but also achieve privacy preserving of input data and the model in secure multi-party computation (MPC) ways. The implemental results show that the scheme can effectively detect and identify backdoor attacks in the privacy-preserving DNN model.},
booktitle = {ACM Turing Award Celebration Conference - China ( ACM TURC 2021)},
pages = {104–109},
numpages = {6},
keywords = {Deep Neural Networks., Secure Multi-Party Computation, Backdoor Attacks, Privacy-Preserving, Detection and Identification Protocol},
location = {Hefei, China},
series = {ACM TURC 2021}
}

```