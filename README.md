**Coursework at Harvard Extension (ordered by relevance)**

**AI-Powered Book Recommendation System \- Harvard Extension**

* Architected end-to-end computer vision system analyzing bookshelf photos for personalized recommendations  
* Engineered custom ML pipeline using AWS Rekognition for text detection and book identification  
* Implemented recommendation engine using Gensim and deployed on AWS (Lambda, S3, SageMaker)  
* Developed Flask backend with RESTful APIs and responsive frontend handling image processing  
* Containerized application using Docker and deployed with Nginx on Linux-based DigitalOcean droplets

**Object Detection Using Vision Transformer \- Harvard Extension**

* Implemented a custom Vision Transformer (ViT) with 8 self-attention layers for aircraft detection, achieving 85% IoU on the Caltech 101 dataset  
* Developed a patch-based feature extraction pipeline that divided input images into 7×7 grids for ViT processing  
* Engineered a regression-based bounding box prediction with four spatial parameters for localization accuracy  
* Analyzed intersection-over-union metrics across 20 test samples, using various aircraft orientations and scales

**Image Classification with EfficientNet Fine-Tuning \- Harvard Extension**

* Fine-tuned EfficientNetB0 pre-trained on ImageNet with Stanford Dogs dataset, with \~98% validation accuracy  
* Implemented a two-stage transfer learning approach with frozen backbone followed by fine-tuning  
* Created data augmentation pipelines including rotation, translation, flipping and contrast adjustments to enhance model generalization  
* Conducted model evaluation using precision-recall metrics, achieving \~85% precision across 120 dog breeds

**Feature Extraction \- Harvard Extension**

* Implemented classical feature extraction algorithms including Harris corner detection, HOG, and BRIEF   
* Applied edge detection methods including Canny and Sobel operators with adaptive thresholding  
* Developed Hough transform implementations for straight line detection in complex images  
* Created texture analysis techniques using local entropy measures for image segmentation

**Optical Flow \- Harvard Extension**

* Implemented and compared different optical flow algorithms including Lucas-Kanade and TV-L1 methods  
* Analyzed algorithm performance under varying image conditions including noise, illumination changes, motion  
* Developed visualization techniques to represent motion vector fields for understanding scene dynamics  
* Applied validation metrics to quantitatively evaluate optical flow accuracy using ground truth displacement data

**SQL Library management application \- Harvard Extension**

* Created stored procedures for book borrowing/returning with transaction handling and constraint validation  
* Developed custom views with permission controls to manage user access to sensitive content  
* Handled authentication such that users could only view and borrow their own books  
* Implemented triggers for automated return processing and inventory management  
* Built RESTful API using flask which sends messages to a postgres database using the psycopg2 package

**National Parks Service API Jamstack project \- Harvard Extension**

* Architected static site with Eleventy, integrating with Meilisearch deployed on DigitalOcean  
* Implemented GraphQL for efficient data fetching and content management  
* Created CI/CD pipeline using GitHub Actions for automated testing and deployment  
* Setup static website hosting and serverless functions using Netlify

**Genealogy MEAN (MongoDB, Express, Angular, and Node.js) application \- Harvard Extension**

* Implemented data relationships for family tree and record management  
* Designed NoSQL schema for hierarchical relationship queries and document storage  
* Connected the frontend of Angular to the RESTful ExpressJS backend to the database using Mongoose 

