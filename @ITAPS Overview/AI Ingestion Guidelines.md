#### Overview

Ingestion and ingestion output needs to be antifragile.  Here are the guidelines:

ITAPS wiki notes should be the central brain of the business, and therefore needs to be in a form that can be fed to AI. 
Please create [[Mermaid]] and post markdown tables of external graphics
PDF should be transformed into markdown through [[docling]]
All graphics need to be embedded .64 in your atomic note use [[PNG2MD]], [[PNG2Clipboard]], and [[MDpng2MDWebp]], other tools
Where possible graphics should be converted into both mermaid and markdown table


#### Perplexity Overview

AI ingestion theory refers to the process of collecting, preparing, and feeding data into artificial intelligence systems for training and operation. This critical step in the AI pipeline faces several challenges and issues:

#### Data Quality and Contamination

One of the primary concerns in AI ingestion is the quality and origin of data:

- AI-generated content is increasingly prevalent on the internet, making it difficult to distinguish between human-created and AI-generated data[1][4].
- Training AI models on their own output or on data contaminated with AI-generated content can lead to a phenomenon called "model collapse"[4].
- Model collapse results in deteriorating quality and diversity of AI outputs over successive generations[4][7].

#### Data Poisoning

Data poisoning is a significant threat to AI systems:

- Attackers can intentionally tamper with training data to affect the outcomes of AI models[13].
- This can lead to biased, inaccurate, or maliciously altered AI behavior[18].
- Poisoning attacks can compromise both the input data and the learning process itself[18].

#### Bias and Fairness

AI ingestion can perpetuate or amplify existing biases:

- If training data is not representative or contains historical biases, AI models can learn and reproduce these biases[6][10].
- This can result in discriminatory outcomes and unfair treatment of certain groups[11].

#### Data Privacy and Security

The ingestion process raises concerns about data protection:

- Handling sensitive or personal data during ingestion requires careful consideration of privacy regulations[9].
- There's a risk of exposing confidential information if proper safeguards are not in place[12].

#### Technical Challenges

AI ingestion faces several technical hurdles:

- Integrating data from diverse sources and formats can be complex[19].
- Ensuring data consistency, accuracy, and timeliness across different ingestion methods (batch, real-time, stream processing) is challenging[19].
- Scalability issues arise when dealing with large volumes of data or real-time processing requirements[19].

#### Ethical Considerations

The ingestion process raises ethical questions:

- There are concerns about the appropriate use of data, especially when it comes to personal information or copyrighted material[11].
- The potential for AI to generate and propagate misinformation or deepfakes is a growing concern[11].

Addressing these issues requires a multifaceted approach, including robust data validation, careful source selection, ethical guidelines, and continuous monitoring of AI systems to ensure their integrity and fairness.

Citations:
[1] https://theweek.com/tech/ai-cannibalization-model-collapse
[2] https://www.komprise.com/glossary_terms/ai-data-ingestion/
[3] https://hdsr.mitpress.mit.edu/pub/1yo82mqa/release/2
[4] https://www.scientificamerican.com/article/ai-generated-data-can-poison-future-ai-models/
[5] https://www.iguazio.com/glossary/data-ingestion/
[6] https://eng.vt.edu/magazine/stories/fall-2023/ai.html
[7] https://www.nytimes.com/interactive/2024/08/26/upshot/ai-synthetic-data.html
[8] https://www.striim.com/blog/what-is-data-ingestion-and-why-this-technology-matters/
[9] https://www.unesco.org/en/artificial-intelligence/recommendation-ethics/cases
[10] https://ovic.vic.gov.au/privacy/resources-for-organisations/artificial-intelligence-and-privacy-issues-and-challenges/
[11] https://provost.wsu.edu/challenges-of-ai/
[12] https://www.ibm.com/think/topics/ai-for-data-integration
[13] https://www.cobalt.io/blog/data-poisoning-attacks-a-new-attack-vector-within-ai
[14] https://www.osmos.io/blog/solving-data-ingestion-using-ai
[15] https://www.montecarlodata.com/blog-data-ingestion/
[16] https://www.linkedin.com/pulse/building-efficient-ai-ingestion-pipeline-data-frank-denneman-qnave
[17] https://fedtechmagazine.com/article/2024/01/unpacking-ai-data-poisoning
[18] https://www.belfercenter.org/publication/AttackingAI
[19] https://www.ibm.com/think/topics/data-ingestion