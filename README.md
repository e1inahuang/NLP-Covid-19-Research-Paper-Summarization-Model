# Text Summarization of Covid-19 Research Papers

## Project Description
The COVID-19 pandemic led to a rapid increase in scientific research covering a wide range of topics, from the virus's effects on human and animal health to its impact on various organs. This wealth of publications, while crucial, poses a significant challenge for researchers and healthcare professionals seeking relevant information due to the vast volume and complex terminology involved. To address this issue, our project proposes utilizing clustering algorithms to efficiently navigate the COVID-19 dataset. By pinpointing the most frequently used professional terms, we aim to group related research papers, making it easier to identify key themes and areas of focus. This method is designed to streamline the search process, enabling users to quickly find pertinent studies without needing to manually review extensive literature. The utility of this tool is not limited to COVID-19 research. It has broader implications for online academic libraries like JSTOR, where it can significantly enhance the ability to locate relevant literature amid thousands of documents. By generating summaries based on key terms, this tool provides a brief yet comprehensive overview of a paper's content, saving time and reducing the effort required for manual summarization. Overall, our project seeks to improve how scientific literature is searched and reviewed. By simplifying the process of finding and summarizing key research findings, we aim to support the swift sharing of vital knowledge and contribute to a more effective and informed scientific community.

#### Executive
Problems we encountered:
- Large quantity of papers
- Diverse research areas
- Overloaded Information
- Need for faster speed research
#### Solution
- Tailored Yearly Insights
- Dynamic Topic Clustering
- At-a-Glance Summaries
- Visual Word Clouds
- Accelerating Research
#### Reference Work Results
![Photo](p2)




## Pre-processing：
#### Data pre-processing
- Step1: Delete NA values
- Step2: Filtering out 2019-2022
- Step3: Filtering out English only articles
#### Deduplication
Use Minhash to identify valid similar titles and delete the similar ones
![Photo](P1)


## Implementation
#### Sentence transformer
- All-mpnet-base-v2 model maps sentences and paragraphs to a 768 dimensional dense vector space and can be used for tasks like clustering or semantic search.
#### Clustering methods
- Attempts
  - KMeans
  - SOM
  - LDA
- Use Mini-Batch KMeans
  - Elbow method
  - t-SNE visualization
  ![Photo](P3)
  




## Result



## References

