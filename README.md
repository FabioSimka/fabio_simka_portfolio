# fabio_simka_portfolio
# About me
Greetings! I'm Fabio Simka, an enthusiastic and outcome-driven professional with a proven track record of utilizing data-driven insights and innovative cloud solutions to foster business growth and transformation. My background in data science, analytics, and cloud architecture enables me to offer a distinctive blend of technical expertise and strategic vision, delivering exceptional value to organizations.

I have a keen commitment to continuous learning and thrive within dynamic, collaborative environments that encourage innovation and growth. My adaptability, critical thinking prowess, and strong communication abilities equip me to effectively collaborate with cross-functional teams, driving impactful results in challenging, fast-paced settings.

I'm thrilled at the opportunity to contribute my expertise to a forward-thinking organization that values innovation and embraces a data-centric approach to decision-making. Please explore my comprehensive portfolio below, highlighting my projects, technical proficiencies, and a detailed overview of my professional journey.

# TL;DR
Who I Am: Passionate and results-driven professional with expertise in data science, analytics, and cloud solutions.

Skills & Expertise: Proficient in Python, R, SQL AWS Cloud Solutions Architecture, and Machine Learning. Strong critical thinking and communication skills.

Key Projects: Utilized neural nets for predictive analysis, implemented AWS Cloud Solutions for data lake management, and facilitated seamless cloud-native transitions. Developed contact book tools and optimized server workloads for high resilience.

Approach: Committed to continuous learning, thrive in collaborative environments, and skilled at translating complex technical concepts to drive tangible business outcomes.

# Projects
To give a comprehensive view of my projects portfolio, I separated the images from the cloud solutions and the codes into pastes. Below you can read a resumed version of the project and use the link to access the image/code for that particular project. 

Project 1: I used a neural net code in a predictive analysis of the probability of a local epidemic hitting a place, according to data extracted from the World Health Organization (WHO). In this predictive analysis, the goal was to identify seasonal patterns of the epidemics, and predict if and when certain locations will have an epidemic on their hands. Specifically, a recurring neural network called Long Short-term Memory (LSTM) was used, with the TensorFlow library, since it is the source of many tools and resources to facilitate machine learning techniques. Technologies and Knowledge: NeuralNet, Python, Machine Learning, Predictive Analysis. Link for project 1: codes/NeuralNet Python

Project 2: Used an AWS Cloud Solutions to solve a problem envolving three different sources of data to make the ingestion, as well the storage of the data in a data lake. It also encompasses the security measures for the data lake, as well as Cloud Solutions to conduct the analysis of that dataset, be it through analytical or machine learning settings. Technolgies and Knowledge: AWS Cloud Solutions Architecture, Critical Thinking. Link for project 2: cloud_solutions/DataLake.jpg

Project 3: Used AWS Cloud solutions for the customer who had a need to run containers on AWS and to use the same orchestration device for both Cloud and on-premises. It was opted for a seamless transition to cloud-native services as demonstrated visually on the file. It was also needed to host a SQL database and to store that generated base with minimum refactoring and resilience to fallovers. Link for project 3:cloud_solutions/AWS Container With Resilience.jpg

Project 4: The elaboration of a contact book tool using Python language to improve organization in a company with a list of clients in constant updates, this code proved effective in maintaining data integrity by using a contact database, with error handling and validation to manage contacts with efficiency, increasing productivity and becoming the foundational project for a learning database. Link to project 4: codes/contact_book

Project 5: In this cloud architecture model, the cliente needed an HTTPS endpoint for data collection, using services that charged per usage and not per time and he was already using an S3 static website hosting. By using that analogy it was opted for cross region data replication and encryption, using different storage classes to save coste, improving data movement, analytics and visualization. Link for project 5: cloud_solutions/HTTPS Endpoint.jpg

Project 6: In this model, the client had a business which many of the server workload was intrincately coupled, in other words, if one part of the server failed, all work would be interrupted. On top of that, the monitoring was made in several different manual spreadsheets and there was much operational overhead, with limited staff which was directly impacting on performance. To solve all those issues, we used decoupling functions with Lambda, so that the system would have high resilience to fallovers of any kind. On top of that it was introduced a central monitorizing with cloudwatch and optimizing cost and reducing operational overhead with serverless cloud services. On top of that, implemented a simple notification system (SNS) to message specific individuals in case of any fail in the system operations. Link for project 6: cloud_solutions/High resilience system.jpg

Project 7: The cliente needed a e-commerce setting with cloud applications maximizing efficiency. So, for the frontend static hosting we used the S3 system, implementing the CloudFront for enhancing content distribution and data delivery. For the backend, we used EC2 instances connected with relational databases to store information of the orders, and ElastiCache for enhancing the performance of the RDS. To process the queues, it was used Amazon SQS for that, and a Lambda function to store the details in the RDS. For the user management of the website, it was used AWS IAM with permissions and access. Using Amazon Pay, the gateway for transaction processing was stablished. For maximum efficiency, an EC2 auto-scalling was using, to adjust the capacity as needed, with Amazon CloudWatch monitoring the integrity of the system. Link for project 7:cloud_solutions/E-commerce architecture.jpg
