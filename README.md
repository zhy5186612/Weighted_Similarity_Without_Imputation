# A Weighted Similarity Metric for Community Detection in Sparse Data
This repository contains a notebook and sample data for calculating the weighted similarity metric and its exmaple applications in community detection without inputation in highly sparse data.

## Introduction 

Last updated on 1/12/2025

Many Natural Language Processing (NLP) related applications involves topics and sentiments derived from short documents such as consumer reviews and social media posts. Topics and sentiments of short documents are highly sparse because a short document generally covers a few topics among hundreds of candidates. Imputation of missing data is sometimes hard to justify and also often unpractical in highly sparse data. We developed a method for calculating a weighted similarity for highly sparse data without imputation. This weighted similarity is consist of three components to capture similarities based on both existence and lack of common properties and pattern of missing values. As a case study, we used a community detection algorithm and this weighted similarity to group different shampoo brands based on sparse topic sentiments derived from short consumer reviews. Compared with traditional imputation and similarity measures, the weighted similarity shows better performance in both general community structures and average community qualities. The performance is consistent and robust across metrics and community complexities.

## Team members & Contributors
- Members: Yong Zhang and Eric (Herrison) Gyamfi (@UC Digital Accelorator)

## Contributions
- We welcome contributions through seperate branch or pull request.
- Please create an issue if you have questions.

## Citation

@misc{

      zhang2025weightedsimilaritymetriccommunity,

      title={A Weighted Similarity Metric for Community Detection in Sparse Data}, 
      
      author={Yong Zhang and Eric Herrison Gyamfi},
      
      year={2025},
      
      eprint={2501.07025},
      
      archivePrefix={arXiv},
      
      primaryClass={stat.ME},
      
      url={https://arxiv.org/abs/2501.07025}, 
}

