This is the repository for the paper titled: Comparative Analysis of Transformer-Based Models with Marginal Loss Functions for Ontology-Based Query Retrieval", Lima S, Portmann E, Teran L., Human IST institute, University of Fribourgh, 2025
![image](https://github.com/user-attachments/assets/f934d1cf-26a4-4409-b45d-ef4d66bbafee)


Despite the emergence of advanced language models,
transformer-based models with distinct architectures and open-
source availability remain foundational in natural language pro-
cessing. This study selects three representative models—BERT,
RoBERTa, and GPT-2—due to their open-source accessibility and
their representation of bidirectional encoder, optimized encoder,
and autoregressive decoder families, respectively. These models
were combined with ArcFace and FuzzyArcLoss loss functions
for ontology-based query retrieval, focusing on glandular tissue-
related cancers. The research adapts loss functions originally
designed for image verification to text-based tasks, modifying
parameters such as s and m for improved convergence.
Experiments using six NVIDIA DGX A100 GPUs reveal
that bidirectional transformers, particularly BERT with Fuzz-
yArcLoss (au = 0.9) and RoBERTa with FuzzyArcLoss (au =
0.5), achieved the highest retrieval accuracy. GPT-2, as an
autoregressive model, exhibited lower performance across loss
functions, reinforcing the importance of bidirectional context
for effective ontology retrieval. The results highlight that Fuzz-
yArcLoss enhances adaptability compared to static-margin loss
functions, demonstrating its potential for improving seman-
tic search. These findings suggest optimal configurations for
transformer-based architectures in specialized information re-
trieval tasks.
