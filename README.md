# Rediscovery of CNN's Versatility for Text-based Encoding of Raw Electronic Health Records

CHIL 2023 (Oral)

[Rediscovery of CNN's Versatility for Text-based Encoding of Raw Electronic Health Records](https://arxiv.org/abs/2303.08290)  
Eunbyeol Cho*, Minjae Lee*, Kyunghoon Hur, Jiyoun Kim, Jinsung Yoon, Edward Choi  

<em>The code will be available soon here.</em>

### Abstract
Making the most use of abundant information in electronic health records (EHR) is rapidly becoming an important topic in the medical domain.
Recent work presented a promising framework that embeds entire features in raw EHR data regardless of its form and medical code standards.
The framework, however, only focuses on encoding EHR with minimal preprocessing and fails to consider how to learn efficient EHR representation in terms of computation and memory usage.
In this paper, we search for a versatile encoder not only reducing the large data into a manageable size but also well preserving the core information of patients to perform diverse clinical tasks. 
We found that hierarchically structured Convolutional Neural Network (CNN) often outperforms the state-of-the-art model on diverse tasks such as reconstruction, prediction, and generation, even with fewer parameters and less training time.
Moreover, it turns out that making use of the inherent hierarchy of EHR data can boost the performance of any kind of backbone models and clinical tasks performed.
Through extensive experiments, we present concrete evidence to generalize our research findings into real-world practice.
We give a clear guideline on building the encoder based on the research findings captured while exploring numerous settings.
