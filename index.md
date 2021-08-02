## All You Need to Know to Build a Product Knowledge Graph (KDD 2021 Tutorial)

### Slides:
* Overview and Introduction 
* Knowledge Extraction
* Knowledge Cleaning
* Ontology Construction
* Applications
* Conclusion and Future Directions


### Description
Knowledge graphs have been pivotal in supporting downstream applications like search, recommendation, and question answering, among others. Such applications have recently become fundamental components in online retail and e-Commerce platforms, so knowledge graphs have naturally become key enabling technologies in such outlets. Building a high coverage knowledge graph for products is more challenging than generic knowledge graphs. The highly specific and complex domain, the sparsity of training data, along with the constantly evolving taxonomies, can constrain the resulting knowledge graphs. Moreover, the product knowledge graph building process should be very scalable and generalizable, to accommodate the dynamic and constantly growing number of products and product types.
    
In this tutorial we will be presenting best practices and ML innovations in industry towards building a scalable product knowledge graph. Contributions in this domain benefit from the general literature in areas including information extraction and data mining, tailored to address the characteristics of e-Commerce platforms. We will first discuss the efforts for enriching product taxonomies automatically. Product taxonomies address the relationships and hierarchy of the different product types and corresponding attributes. We also cover the information extraction techniques, used to obtain machine-actionable knowledge from the natural and unstructured product profiles. We cover both text-based and multimodal-based extraction techniques, used to utilize product images as additional signals. Industry-based applications require particularly high precision levels, ideally with minimal recall loss. Towards that end, we also cover several contributions utilizing data cleaning and quality control techniques for the extracted product knowledge. 
    
The various approaches for building product knowledge graphs could also be useful for other domains. We take a holistic approach for the covered contributions, addressing the different task formulations, modeling strategies, and utilized architectures. We highlight the corresponding assumptions and use cases, and shed light on how the techniques apply and generalize to other domains. 


### Presenters
* Nasser Zalmout, Applied Scientist @ Amazon (nzalmout@amazon.com)

Nasser Zalmout is an Applied Scientist at Amazon, working on the information extraction effort at the Product Graph team. Nasser received his Ph.D. from New York University, as part of the Global Ph.D. Student Fellowship program. Nasser's research interests are mainly in NLP, covering topics including information extraction, morphological and syntactic modeling, transfer learning, and machine translation, among others. Nasser has many publications in several NLP domains, including 10+ papers in top-tier conferences. 
* Chenwei Zhang, Applied Scientist @ Amazon (cwzhang@amazon.com)

Chenwei Zhang is an Applied Scientist at Amazon working in the Product Graph team. Chenwei finished his PhD at University of Illinois at Chicago. His research interests lie in the fields of data mining and natural language processing. In particular, he is interested in text mining and mining structured information from heterogeneous information sources. Chenwei has 20+ publications in top-tier NLP and data mining conferences. 
* Xian Li, Senior Applied Scientist @ Amazon (xianlee@amazon.com)

Xian Li is a Senior Applied Scientist at Amazon contributing to the knowledge cleaning and data quality control in Amazon Product Knowledge Graph. Before joining Amazon, she was a machine learning scientist at LinkedIn, where she was a major contributor to build LinkedIn's knowledge base of business entities and filed 6 patents. She received her Ph.D. from SUNY Binghamton and her research interests include data cleaning, truth finding in structured and unstructured data sources, data quality, and knowledge management. Xian previously gave a tutorial on fact checking at SIGKDD 2018.
* Yan Liang, Applied Scientist @ Amazon (ynliang@amazon.com)

Yan Liang is an Applied Scientist at Amazon working in the Product Graph team. Her work in the team focuses on addressing generalizability and scalability issues in the information extraction systems. Her research interests include information extraction in NLP and data mining at large scale.
* Xin Luna Dong, Head Scientist at Facebook AR/VR Assistant

Xin Luna Dong is the Head Scientist for Facebook AR/VR Assistant. Prior to joining Facebook, she was a Senior Principal Scientist at Amazon, leading the efforts of constructing Amazon Product Knowledge Graph, and before that one of the major contributors to the Google Knowledge Vault project, and has led the Knowledge-based Trust project, which is called the “Google Truth Machine” by Washington’s Post. She has co-authored books "Machine Knowledge: Creation and Curation of Comprehensive Knowledge Bases" and “Big Data Integration”, was awarded ACM Distinguished Member, and VLDB Early Career Research Contribution Award for “Advancing the state of the art of knowledge fusion”. She serves in the VLDB endowment and PVLDB advisory committee, and is a PC co-chair for WSDM 2022, VLDB 2021, KDD'2020 ADS Invited Talk Series, and Sigmod 2018.
