# paper-recommendation
 Summary:
 - Exponential growth in data availability of data => it impossible for a normal human being to mine it  
 - Recommender systems alleviate the difficulties related to Big Data and optimize recurrent tasks: filter and present relevant information to make an efficient decision 
 - 1.8 million papers published every year in over 25,000 journals 
 - To simplify the literature review process, recommendation systems connect relevant research papers using citations
 - The recommendation system would be based on the abstract, or other relevant text in the papers ⇒ Abstracts efficiently summarize the context of the paper and provide a clear idea about the direction of the research. 
 - Building a robust paper recommendation system with a context-based approach:
     1. Increases the speed of project completion
     2. Benefits the research community and society as a whole
     3. As well as STEM students since the dataset used is focused on scientific papers
  
  ![methodology](https://github.com/Yasamanne/paper-recommendation/blob/main/img/method.png)


  # 1. Data Collection

    ArXiv Dataset:
      Open access scholarly articles in areas like physics, many subdisciplines of computer science, math, statistics, electrical engineering, quantitative biology, and economics,.... 

      Hosted and maintained by Cornell university
      id: ArXiv ID (can be used to access the paper, see below)
      submitter: Who submitted the paper
      authors: Authors of the paper
      title: Title of the paper
      comments: Additional info, such as number of pages and figures
      journal-ref: Information about the journal the paper was published in
      doi: [https://www.doi.org](Digital Object Identifier)
      abstract: The abstract of the paper
      categories: Categories / tags in the ArXiv system
      versions: A version history
      1.7 M articles
      Subset of data 51k

  # 2. Data Exploration and Cleaning
  
  ![Data Exploration](https://github.com/Yasamanne/paper-recommendation/blob/main/img/eda.png)

  
  ![Data Exploration](https://github.com/Yasamanne/paper-recommendation/blob/main/img/eda2.png)
        

  # 3. Text Processing - steps to clean

  ![Text Processing](https://github.com/Yasamanne/paper-recommendation/blob/main/img/text-process.png)

  
  ![Text Processing](https://github.com/Yasamanne/paper-recommendation/blob/main/img/text-process2.png)

  # 4. Extract Keywords
  
  ![Text Processing](https://github.com/Yasamanne/paper-recommendation/blob/main/img/keywords.png)

  # 5. Modeling - Unsupervised Learning
  
      A. Doc2Vec + KMeans
      
  ![Model](https://github.com/Yasamanne/paper-recommendation/blob/main/img/a-model.png)

      B. Doc2Vec + Cosine Similarity

  ![Model](https://github.com/Yasamanne/paper-recommendation/blob/main/img/b-model.png)

      C. TFIDF + KMeans

  ![Model](https://github.com/Yasamanne/paper-recommendation/blob/main/img/c-model.png)

      D. TFIDF + Cosine Similarity

  ![Model](https://github.com/Yasamanne/paper-recommendation/blob/main/img/d-model.png)

      E. SBERT + KMeans

  ![Model](https://github.com/Yasamanne/paper-recommendation/blob/main/img/e-model.png)
  
      F. SBERT + Cosine Similarity

  ![Model](https://github.com/Yasamanne/paper-recommendation/blob/main/img/f-model.png)

  # 6. Evaluation

  ![Model](https://github.com/Yasamanne/paper-recommendation/blob/main/img/evaluation-kmeans.png)


  
      

