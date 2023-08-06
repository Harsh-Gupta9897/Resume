
# Projects

## Project Table List



### ML Projects

| Computer Vision                                      | NLP/LLM                                       | Data Analytics                            | Traditional ML                      |
|------------------------------------------------------|-----------------------------------------------|------------------------------------------|--------------------------------------|   
| VQVAE as Defense Against Adversarial Attacks         | PrivaLLM & DataGenLLM (OpenSource LLM, QLoRa) | Community Detection (Spectral Clustering)| Naive Bayes Implementation           |
| Person Image Synthesis (Cloth Virtual Try ON)        | PrivaGPT (AI Governance Model for LLMs)       | Color Blindness (BWT Algorithm)          | Classification Module(Multiclass SVM)|
| Human Motion Diffusion Model (Based on Keypoints)    | Text Based Classification (BERT-Based Encoder)| Covid19 Modelling based on CLT & LLN     | Regression and PCA                   |
| DCGAN with ADAIN and ViT Implementation from Scratch | Sentiment Analysis(RNN/LSTM) & Word Embeddings| Recommendation System                    | CLustering(KMeans,Spectral Clustering)|
| Metrics Analysis (CLIP, SWAV,IS) based FIDs          |                                               | Duckworth Lewis Method Implementation    |                                      |

### SDE Projects
|               Title                                    | Date             |
|--------------------------------------------------------|------------------|
| Innogeeks (ERP + Student Management Portal)            | Nov 2020 - Mar 2021 |
| JewelAR (Jewelry Virtual Try ON)                       | Aug 2020 - Feb 2021 |
| SaproIndia (Ecommerce Cum Service Platform)            | Oct 2019 - Dec 2019 |
| STET (Document Verification Portal)                    | Mar 2019 - Apr 2019 |



## ML Projects

### NLP/LLM Projects
1. **PrivaLLM & DataGenLLM (OpenSource LLM, QLoRa, DeepSpeed, ContextLength)**
   - **Description:**
     - Created PrivaLLM, based an open-source Language Model, incorporating QLoRa and DeepSpeed for efficient and optimized language model training.
     - Explored various Context Length increment papers and techniques and also explored the different research papers to speed up the inference and training time.
     - Finetuned various model using QLoRa and also optimized the memory requirement for Open Source LLM such as StableVicuna,XGen_8k, Guanaco,Falcon, OpenLLaMa, LLaMa, MPT ,Raven (RWKV) Based and also read about the various data quality, LLM based papers.
     - Aiming to provide a state-of-the-art solution for privacy-aware large language model applications.
   - **Tech Stack & Techniques::** Transformers, pytorch, QLoRa,DeepSpeed,OpenSource LLM,prompt-engineering,
  
2. **PrivaGPT (AI Governance Model for LLMs)**
   - **Idea:** To provide an AI governance layer to safeguard user data by recognising, assessing, and minimising the PIIs risk posed by Large Language Models. 
   - **Description:**
     - Developed PrivaGPT, an NLP based model, leveraging libraries like spacy and nltk, and utilizing pretrained language models to understand NER of different domains such as General, Medical, Financial and other domain risk.
     - PrivaGPT process: Identify and analyze risks, generate risk scores; Mitigate risks with synthetic prompts, remap to original PIIs; Dashboard presents risk assessment report.
     - **Tech Stack & Techniques::** Transformers, spacy, pytorch, nltk, NER, Bert based Classification.


3. **Product Description/Title-based Classification into Categories (BERT-Based Encoder)**
   - **Description:**
     - Developed an NLP model using pretrained BERT-based model, then finetune it to classify products based on their descriptions or titles into specific categories.
     - Collected and preprocessed a diverse dataset of product descriptions and titles to build a robust classification model.
     - Aimed to automate the categorization process, which can be useful for various e-commerce and inventory management applications.
   - **Tech Stack& Techniques::** Transformers, spacy, pytorch,Bert-Encoder
   - **Link:** https://colab.research.google.com/drive/1wMyGBrxawRXeUcmPhT9px4KwHmrgm1zh#scrollTo=vnEHkNSJi3Ef

4. **Sentiment Analysis (RNN/LSTM)**
   - **Description:**
     - Implemented a Sentiment Analysis system using RNN/LSTM architecture to predict sentiments (positive, negative, neutral) from textual data.
     - Focused on creating a more context-aware sentiment analysis model for a better understanding of users' emotions and opinions.
   - **Tech Stack & Techniques:* RNN, LSTM, Pytorch
   - **Link:** NA

### Deep Learning (Computer Vision )

1. **VQVAE as a Defense Against Adversarial Attacks**
   - **Description:**
     - Explored the use of Variational Quantized Variational Autoencoder (VQVAE) as a defense mechanism against adversarial attacks.
     - Investigated the effectiveness of VQVAE in enhancing robustness to adversarial examples generated by FGSM, I-FGSM, and MI-FGSM attacks.
     - Implemented and evaluated the defense-VAE approach inspired by the Defense-VAE paper to assess its performance against different attack scenarios.
   - **Link:** [VQVAE as Defense Against Adverserial Attacks ](https://github.com/Harsh-Gupta9897/VQVAE_as_Defense_Against_Adversarial_Attack)

2. **Human Motion Diffusion Model**
   - **Description:**
     - Developed a Human Motion Diffusion Model (simMDM) within 10 days based on the latest paper.
     - Utilized a different dataset and experimented with UNet-based architectures to study their impact on generating dance videos from keypoints provided in JSON format.
     - Investigated motion diffusion models and their variations to simulate natural human movement sequences.
   - **Link:** [Human Motion Diffusion Models](https://github.com/Harsh-Gupta9897/HMotion_Diffusion_Model)

3. **Virtual Cloth TryON (Person Image Synthesis)**
   - **Description:**
     - Explored various GANs for cloth and pose synthesis and human generation in that pose.
     - Investigated DCGAN and StyleGAN Encoder Variation for cloth virtual try-on applications.
     - Explored and learn about different possible architecture for cloth tryon based on pose and garment. 
     - Tryout different diffusion and GAN architecture such as PIDM , StyleGAN2 , cvton and also proposed new GAN architecture based on pix2pix to solve the problem.

4. **DCGAN with ADAIN and ViT Implementation from Scratch**
   - **Description:**
     - Conducted an in-depth analysis and implemented the Vision Transformer (ViT) and DCGAN with AdaIN (Adaptive Instance Normalization) from scratch.
     - Examined the architectures' performance on the CIFAR100 dataset to understand their working and capabilities for image generation and classification tasks.
     - All implementations were done in PyTorch based on the nn module, ensuring a solid understanding of the underlying concepts.

5. **Metrics Analysis (CLIP, SWAV,ImageNet(Inecption Score based) FIDs )**
    - **Idea:** Explore different metrics to evaluate images, including FID (Fréchet Inception Distance), CLIP, and SWAV.
    - **Description:**
      - Investigated various image evaluation metrics, starting with FID, but found that it can be manipulated and may not fully capture the quality of images.
      - Conducted experiments with different augmentations to capture diverse features of images and understand their impact on evaluation metrics.
      - Explored and read research papers highlighting the limitations and flaws of image-based metrics, leading to the realization that self-supervised based metrics are more effective for evaluating image-based models.
    - **Link:** [GitHub Repository](https://github.com/Harsh-Gupta9897/)

  

### Traditional ML

<!-- Add your Traditional Machine Learning projects here -->

### Data Analytics Projects

1. **Community Detection Using Spectral Clustering & Louvian Algorithm**
   - **Title:** Community Detection Using Spectral Clustering & Louvian Algorithm
   - **Description:**
     - Explored and implemented Spectral Clustering and Louvain Algorithm for community detection in complex networks.
     - Utilized graph-based algorithms to identify cohesive groups within large datasets.
     - Analyzed real-world network data to uncover underlying community structures.

2. **Duckworth Lewis Method Implementation using (1991-2011) Data**
   - **Title:** Duckworth Lewis Method Implementation using (1991-2011) Data
   - **Description:**
     - Implemented the Duckworth Lewis method to adjust target scores in interrupted cricket matches using historical data from 1991 to 2011.
     - Analyzed match data to determine the impact of interruptions on cricket match outcomes.
     - Validated the accuracy of the method by comparing adjusted target scores with actual results.

3. **Color Blindness using BWT Algorithm (Optimized Algorithm) on 150M length DNA sequence matching with 2-3 missing values in pattern**
   - **Title:** Color Blindness using BWT Algorithm (Optimized Algorithm) on 150M length DNA sequence matching with 2-3 missing values in pattern
   - **Description:**
     - Developed an optimized Burrows-Wheeler Transform (BWT) algorithm to detect color blindness in individuals.
     - Implemented advanced pattern matching techniques to handle 150M length DNA sequences with 2-3 missing values.
     - Conducted extensive tests on diverse datasets to ensure efficiency and accuracy of the algorithm.

4. **Recommendation System using CUR, SVD, PQ Decomposition**
   - **Title:** Recommendation System using CUR, SVD, PQ Decomposition
   - **Description:**
     - Created a recommendation system using CUR (Column Subset Selection), Singular Value Decomposition (SVD), and Product Quantization (PQ) Decomposition.
     - Applied matrix factorization techniques to generate personalized recommendations for users.
     - Evaluated the recommendation system's effectiveness using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

5. **Covid19 Modelling i.e Prediction of Future Cases using Probability Concepts such as CLT and LLN**
   - **Title:** Covid19 Modelling i.e Prediction of Future Cases using Probability Concepts such as CLT and LLN
   - **Description:**
     - Employed probability concepts, like Central Limit Theorem (CLT) and Law of Large Numbers (LLN), to model and predict future Covid19 cases.
     - Analyzed historical Covid19 data to identify trends and patterns.
     - Developed time series forecasting models to predict future case numbers based on historical data.
     - Used SEIR Modelling to forecast the future cases.





## SDE Projects

1. **Innogeeks (ERP + Student Management Portal)**
   - **Date:** Nov 2020 - Mar 2021
   - **Description:**
     - Served as the project's team leader and full-stack developer while managing a team of 5–6 people.
     - Implemented roughly 8–10 modules, each containing several submodules:
       - Scraping coding profiles from popular coding platforms
       - Ranking students, projects, blogs, and articles
       - Mentor-mentee matching & Hackathons management
       - Registration and recruitment functionalities
       - Email generation and automation
       - Backend optimization for improved performance
       - Export-import data module & Dashboard
       - Static and URL-based resume generation modules
     - Aim: To create a portal for helping the students of the technical society to get updates and manage their profiles. Additionally, conducted around 3 consecutive years of recruitment with min 750+ registrations and a recruitment pipeline (with 4 stages) from this portal, automating the entire process from registration to final selection.
   - **Tech Stack:** AWS (RDS, EC2, S3, CloudFront, Git), HTML, Django, Bootstrap, JavaScript
   - **Link:** https://innogeeks.in
 

2. **JewelAR (Jewelry Virtual TryON)**
   - **Date:** Aug 2020 - Feb 2021
   - **Description:**
     - Developed APIs for both iOS and Android apps, while also managing the project's website.
     - Created a vendor dashboard using Django to assist in product and customer management.
     - Planned and discussed various website components and deployed it on AWS.
   - **Tech Stack:** Rest APIs, Swagger UI, Dashboard Customization With Django, DRF (Django Rest Framework), Heroku, AWS, Postman, JWT
   - **Link:** https://www.youtube.com/watch?v=ZvhhY1FJIv0

3. **SaproIndia (Ecommerce Cum Service Platform)**
   - **Date:** Oct 2019 - Dec 2019
   - **Description:**
     - Collaborated with the front-end team to plan and discuss website-related matters.
     - Prepared the entire backend, integrating the Paytm payment gateway and adding authentication components.
     - Deployed the project on DigitalOcean for smooth and reliable hosting.
   - **Tech Stack:** Paytm Payment Gateway, Django, Git, HTML/Bootstrap, JavaScript, DigitalOcean

4. **STET (Document Verification Portal)**
   - **Date:** Mar 2019 - Apr 2019
   - **Description:**
     - Developed a platform for the entrance exam document verification Portal for Sikkim Govt during SIH (Smart India Hackathon).
     - Automated document verification using OCR (Optical Character Recognition).
     - Led a team of 4 members and served as the backend developer, integrating the frontend with the project.
   - **Tech Stack:** Django, HTML

<div align="center">

## :email: Contact

:link: LinkedIn: [harshguptashnd](https://www.linkedin.com/in/harshguptashnd/) / :envelope: Email: [harshguptashnd@gmail.com](mailto:harshguptashnd@gmail.com) / :school: College Email: [harshg@iisc.ac.in](mailto:harshg@iisc.ac.in) / :telephone_receiver: Phone: +91 8534968497 / +91 8650065662 / :octocat: GitHub: [Harsh-Gupta9897](https://github.com/Harsh-Gupta9897)

</div>

