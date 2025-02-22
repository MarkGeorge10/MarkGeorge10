<p align="center">
  <img src="https://your-hosted-image-url.com/banner.png" alt="Mark Fahim Banner" width="600"/>
</p>

<h1 align="center">Hi, I'm Mark Fahim 👋</h1>
<h3 align="center">Senior Software Engineer | AI Specialist | Master's Student in AI</h3>
<p align="center">Building intelligent systems with a passion for machine learning, algorithms, and mobile development. Currently an AI Research Assistant at Pennsylvania State University.</p>

<h3>About Me</h3>
- 🔭 Working as an <b>AI Research Assistant</b> at Pennsylvania State University.
- 🎓 Pursuing a <b>Master's Degree in Artificial Intelligence</b>.
- 🌱 Enhancing my skills in <b>Algorithms</b> and diving deep into <b>Programming Automatic Calculus</b>.
- 💬 Ask me about <b>Machine Learning, Android Development, Flutter Development</b>.
- 📫 Reach me at <a href="mailto:mark.fouad99@gmail.com">mark.fouad99@gmail.com</a>.

<h3>Achievements</h3>
- 🏆 Developed an ANN-based heart disease prediction system with <b>94% accuracy</b> (up from 84% with Random Forest).
- 🚀 Deployed a scalable AI-driven news platform on AWS, reducing information overload for users.
- 📱 Published <b>10+ mobile apps</b> on Google Play and App Store, serving thousands of users.
- 📊 Delivered actionable insights via PCR Analysis during COVID-19, identifying high-infection regions.

<h3>My Projects</h3>

<h4>Machine Learning Projects</h4>

- **AI-Driven News Intelligence Platform**
  <br/>Used technology: Python, NLP analsis, HPC super computer, NTLK, SCapy<br/>
      This project delivers an automated news aggregation and curation system, combining web scraping, natural language processing (NLP), and user feedback mechanisms to streamline information consumption. The platform integrates two primary data       
       pipelines: (1) a third-party integration with Inoreader API, where a Python-based scraper collects and processes news articles before marking them as read, and (2) a user-configurable RSS feed management system. Users can dynamically add or 
       remove RSS feeds via a Next.js dashboard, with all feed metadata stored in PostgreSQL. The scraper service automatically discovers and processes new content from these feeds, ensuring continuous data ingestion.

  At the core of the platform is an NLP-powered classification engine that filters articles into "Important" or "Not Important" categories. Built using BERT-based models and fine-tuned with user feedback, the system continuously improves its 
       accuracy through iterative retraining. Additionally, the platform incorporates advanced text summarization techniques (e.g., PEGASUS-X) to generate concise, executive-style summaries of each article, complete with keyword extraction and source 
     attribution. These summaries are presented alongside the original content, enabling users to quickly grasp key insights without sifting through lengthy articles.

     The system is designed for scalability and user-centricity. A Next.js dashboard provides an intuitive interface for managing feeds, viewing summaries, and providing feedback on article relevance. Backend services, built with FastAPI and deployed 
     on AWS, ensure high performance and reliability, while Docker containerization simplifies maintenance and scaling. By combining cutting-edge NLP techniques with robust engineering practices, this platform empowers users to stay informed 
     efficiently, reducing information overload while maintaining context and accuracy.

- **Intelligent Mancala game**
  <br/>Used technology: Python, adversarial search algorithms, reinforcement learning techniques<br/>
      Strategic Gameplay: Unleash the power of Minimax & Alpha-Beta Pruning for a tactical gaming experience and real-time Learning: Experience the magic of Q-Learning Reinforcement as the AI dynamically adapts.

- **Medical Basket Analysis**
  <br/>Used technology: Python, Excel, SQL Queries, TFS, Git, Spider, Preprocessing, Data Mining, Machine Learning<br/>
      Finding relations between tests with each other and Did “Vitamin D” trigger other tests or triggered by other tests? From that point, we performed medical test Basket Analysis with FP Growth model with 85% support and 90% confidence.

- **PCR Analysis Project**
 <br/>Used technology:SQL Queries, Excel, DAX, Power BI, TFS, Git, Data visualization<br/>
      IDH company needed to know how many PCR tests were distributed since the start of Covid-19, how many PCR tests were performed in each branch, and how many positive and negative results we have received. Afterwards, we were able to determine the region that had a high rate of infection and determine exactly the needs of each branch. 
      
- **Lipid Medical test**
   <br/>Used technology:Preprocessing, Data Mining, Deep learning, Machine Learning, Python, Excel, SQL Queries, Spider<br/>
  Build a predictable system by using ANN algorithm to predict and evaluate the risk of every patient who has tested positive or negative.

- **Marketing Campaign Response Prediction**
   <br/>Used technology:Preprocessing, Data Mining, Machine Learning, Python, Excel, SQL Queries, TFS, Git, Spider<br/>
    Build a predictable system by using ANN algorithm to predict patient responses by conducting tests in IDH that assisted the company in sending marketing campaigns to the targeted patients to attract them by sending special offers.

- **[Cyclitic Google Capstone Project](https://www.kaggle.com/theoryers/cyclistic-dataset-google-capstone)**
   <br/>Used technology:Preprocessing, R studio, R programming language, Data visualization, Kaggle, Excel<br/>
  The Cyclitic project was a graduation project from Google Data Analytics specialization that talks about a bike sharing company with a fleet of 5824 bicycles and 692 stations across Chicago that requires the study of behavioral differences between casual riders and members. The role of the project was to distinguish ways to have casual riders buy a membership using digital media to increase the company’s profit by converting casual riders to annual members. 

- **[Heart Attack Disease](https://www.kaggle.com/code/theoryers/heart-diseases-prediction-system)**
   <br/>Used technology:Python, Excel, Kaggle, Spider, Preprocessing, Data Mining, Machine Learning, Deep learning<br/>
  This project was a predictable model by Random Forest Decision Trees library with accuracy of 84%. My prediction system was updated by using ANN with accuracy of 94%, to evaluate the risk of every patient who probably has heart disease.


<h4>Backend Projects</h4>

  - **Building News Intelligence Backend with FastAPI and PostgreSQL**
    <br/>Used technology: Python, FASTAPI, Prisma, Github, Git, Supabase, Docker <br/>
    The AI-powered news platform’s backend was built using FastAPI, a high-performance Python framework, to handle API requests, manage data pipelines, and integrate AI models. Its asynchronous capabilities efficiently processed tasks like article          scraping, NLP processing, and content delivery, while RESTful endpoints ensured seamless communication between components. PostgreSQL was chosen for data storage, optimized for structured data like article metadata, RSS feeds, and NLP outputs. The 
    pgvector extension enabled semantic search, and Redis caching improved performance. Docker ensured consistent deployment, and AWS provided scalable infrastructure. Together, FastAPI and PostgreSQL formed a robust, scalable foundation supporting 
    real-time data ingestion, NLP, and user feedback, with room for future enhancements like multi-language support and advanced analytics.

   - **Wedding NestJs Application** 
       <br/>Used technology: Nestjs, Typescript, Prisma, Clickup, Github, Git, Supabase, SQL Queries <br/>
      I have developed a backend application for a wedding mobile app using Prisma and NestJS. Your application 
      deals with user authentication using JWT, manages vendors and their categories, and allows users to create 
     wedding plans based on a specific budget. this application contains:<br/>
      - User Authentication with Using JWT for token-based authentication and authorization, User Profile to allow 
         users to create and update their profiles and Store user-specific data like saved plans, favorites, or past 
          weddings.<br/>
      - Vendor Management Implement CRUD (Create, Read, Update, Delete) operations for vendors, and Categorize vendors for easy navigation and search.<br/>
      - Wedding Planning Create a structured plan object that includes details such as budget, vendors, etc, Implement budget tracking and expense management for the wedding plan, Allow users to add and remove items or tasks from their plans, and Provide recommendations based on the budget and preferences.<br/>
      - Search and Filters Implement search functionality for vendors and categories, and Use filters to refine vendor searches based on location, price range, and services.<br/>
      - Notifications Send notifications for important events like upcoming appointments or tasks, and Allow users to customize their notification preferences.<br/>

- **Davedology Course management system** 
    <br/>Used technology: ASP.net core, SQL Server, video streaming, Github, Git, SQL Queries<br/>
      The Course management backend system designed to elevate the teaching and learning experience. Our 
      platform seamlessly integrates lessons with engaging video content and interactive quizzes, empowering 
      educators and students alike. Teachers enjoy a user-friendly dashboard to effortlessly add lessons and quizzes, 
      while also gaining access to insightful analytics for the quiz section. Elevate your educational journey with our 
      innovative course management solution.


<h4>Front-end Projects</h4>

- [News Intelligence Platform](https://market-pipeline-news.vercel.app/)

<h4>iOS Projects</h4>

- <img src="https://play-lh.googleusercontent.com/hYrkW5rgkT4SOUSCmguYmsnpocQhNlCwoZWPsC6vHOEk7Y2bJuLGfKG-liwKfgdQRg=w480-h960-rw" alt="android" width="40" height="40"/> [AlMokhtabar Patient](https://apps.apple.com/eg/app/almokhtabar-%D8%A7%D9%84%D9%85%D8%AE%D8%AA%D8%A8%D8%B1/id1079320486) 

- <img src="https://play-lh.googleusercontent.com/Q6D4m61-oMLGGAtWTNkUScbxxoKOtI3b69lD6rZQFQEcd-TghkEwYlnOES3gUpejcA=w480-h960-rw" alt="android" width="40" height="40"/> [EchoLab patient](https://apps.apple.com/eg/app/echolab/id1438043859)

- <img src="https://play-lh.googleusercontent.com/Of0yPOBQ27rakUJv5DfNXaKFgXSJD5mYoe6DhIMmTsgJlDo9vp52CvLhpl8ibYwR7NE=w480-h960-rw" alt="android" width="40" height="40"/> [Alborglab  Patient](https://apps.apple.com/us/app/alborglab-%D9%85%D8%B9%D8%A7%D9%85%D9%84-%D8%A7%D9%84%D8%A8%D8%B1%D8%AC/id1452067856) 


<h4>Android Projects</h4>

- <img src="https://play-lh.googleusercontent.com/W-8DrKL9cKiWAnOR-HrpGf8ds0TjPmNcTouWkRBO7opxQBSw_1Mhjyt3yso2N2dtzBM=w480-h960-rw" alt="android" width="40" height="40"/> [Packaging App](https://play.google.com/store/apps/details?id=com.idh.share_box)

- <img src="https://play-lh.googleusercontent.com/n6wcx13vaChjPq9BiP3DniVJ-rrTvQUO5OKtf6V7lvPvwVANlxl46hhSVv2JnJTu6g=w480-h960-rw" alt="android" width="40" height="40"/> [Almokhtabar HC](https://play.google.com/store/apps/details?id=idhcorp.mokhtabar.chemist) 

- <img src="https://play-lh.googleusercontent.com/hYrkW5rgkT4SOUSCmguYmsnpocQhNlCwoZWPsC6vHOEk7Y2bJuLGfKG-liwKfgdQRg=w480-h960-rw" alt="android" width="40" height="40"/> [AlMokhtabar Patient](https://play.google.com/store/apps/details?id=yackeen.idh.almokhtabar.almokhtabar) 

- <img src="https://play-lh.googleusercontent.com/Q6D4m61-oMLGGAtWTNkUScbxxoKOtI3b69lD6rZQFQEcd-TghkEwYlnOES3gUpejcA=w480-h960-rw" alt="android" width="40" height="40"/> [EchoLab patient](https://play.google.com/store/apps/details?id=echolab.idh.PatientApp)

- <img src="https://play-lh.googleusercontent.com/Of0yPOBQ27rakUJv5DfNXaKFgXSJD5mYoe6DhIMmTsgJlDo9vp52CvLhpl8ibYwR7NE=w480-h960-rw" alt="android" width="40" height="40"/> [Alborglab  Patient](https://play.google.com/store/apps/details?id=alborglab.app.lab) 

- <img src="https://play-lh.googleusercontent.com/AsFjcehIilcMtuySheDXSTxFjNiOP5Y53ZXdoVyhFkRmMdWF7QoUCWvIcI2nubFml-8=w480-h960-rw" alt="android" width="40" height="40"/> [Alborglab HC](https://play.google.com/store/apps/details?id=idhcorp.alborg.chemist)

<h4>Flutter Projects</h4>

- <img src="https://play-lh.googleusercontent.com/1NOFCYnfFQstv0Fa2OEaehT2GYZyc4829rIGSvMv2mTWTTqr1TmdpUEWjchYFP6RL_PD=w480-h960-rw" alt="Swiftr" width="40" height="40"/> Swiftr [Android Version](https://play.google.com/store/apps/details?id=se.android.swiftr.swiftr) - [iOS Version](https://apps.apple.com/us/app/swiftr/id1260906262)
  
- <img src="https://github.com/MarkGeorge10/MarkGeorge10/assets/34999954/9a5d2121-af87-4693-9ea0-8dbbac4e4a2b" alt="Rayan" width="40" height="40"/> Rayan [Android Version](https://play.google.com/store/apps/details?id=com.skyvision.rayan) - [iOS Version](https://apps.apple.com/app/rayan-app/id6449189511)
  
- <img src="https://play-lh.googleusercontent.com/_vrwrpVloOtqpbb1fCJGZLWdGD0K37Z28n5_NC1dCIfCRMhCvjJfUd_eEfyhF9bEbPaQ=w480-h960-rw" alt="android" width="40" height="40"/> Organ Live [Android Version](https://play.google.com/store/apps/details?id=com.organ.media.organ_media) - [iOS Version](https://apps.apple.com/app/organ-live-media-foundation/id1663040569) 

-  <img src="https://play-lh.googleusercontent.com/Sp7wIVEkEOcEqlcR_-POPtqhrW6111wIMOPil9h-JHQWWZrDQhMml7rGXIzwWWd60g=w480-h960-rw" alt="Dream Riders" width="40" height="40"/> Dream Riders [Android Version](https://play.google.com/store/apps/details?id=com.dreamrider.dreamriders) - [iOS Version](https://apps.apple.com/us/app/dream-riders/id1629505438)

- <img src="https://play-lh.googleusercontent.com/9YW-L5NiXs9x7umD-MouIYzvKyzUWzG2ZS97Ge_gC96j3Gb3I-jZ_PlDGOoT68uX3Q=w480-h960-rw" alt="android" width="40" height="40"/> SKODA Cars [Android Version](https://play.google.com/store/apps/details?id=com.skoda.skodacar&fbclid=IwAR0Yn7daXTAMjYT2T0V207ya2q6vEzx3AM0hUtbmBHCIlbm3HtCDiwz8XZU) - [iOS Version](https://apps.apple.com/us/app/%C5%A1koda-mc/id1578478791)

- <img src="https://play-lh.googleusercontent.com/U64NmeqS8fh6luh4ItaUYqkwlIuiLd6Xxgkdd4lRESyE42j5IGVx3vlvBzmVATmo6zw=w480-h960-rw" alt="android" width="40" height="40"/> Mr Fix [Android Version](https://play.google.com/store/apps/details?id=com.vadecom.mr_fix) - [iOS Version](https://apps.apple.com/us/app/dream-riders/id1629505438)

- <img src="https://play-lh.googleusercontent.com/kQSt6u5uHbCISbvQpXapPtS_reitScNhww6osj919tBc9WXLDmXNBFZqBGhUaXMS2A=w480-h960-rw" alt="android" width="40" height="40"/> Garage Center [Android Version](https://play.google.com/store/apps/details?id=com.vadecom.garagecenter)

<h4>SharePoint Projects & Power Automate & Power Apps</h4>

  - **Pension Power App** 
  
  - **Summer Vacation Power App**
  
  - **User Creation Workflow**
  
  - **Email Notification System**
  
  - **Intranet IDH**
  
  - **Happy Birthday Automation System**
    <br/>It is a power automate with SharePoint site that contain list of employees' data and validate on date of each employee's birth and send a personal email says Happy Birthday Mr. (…) so we succeed to save effort on internal communication team instead of creating a very long pdf file and send it every month a birthdays list of this month throughout emails.
    
  - **Quality Document Management System**
  <br/>It is a SharePoint & Power Automate is used to manage and organize documents for IDH Quality team.
make a news announcement to all branches and units and automate any kind of document or report approval.
send an email remind to Quality team that document is going to be archived within a month to notify them to update these files.

  - **SAP Management System**
     <br/>It is a team SharePoint site and manage folders, template excel sheets in the document library and this site is built based on user permissions to make each branch to view his only folder and its files inside folder but technical lead can view a group of branches folders and files to lead them and review on their files and archive Our goal is to try to digitize these workflows from manual process to digital flow to make everything under control as possible as we can and can be review, track technical leads and branches.
     

<h3>Skills & Tools</h3>
<p align="center">
  <b>Languages:</b> Python, C#, Swift, Kotlin, Dart, TypeScript, R<br/>
  <b>Frameworks:</b> FastAPI, NestJS, Flutter, React, .NET Core, Next.js<br/>
  <b>AI/ML:</b> TensorFlow, Scikit-Learn, NLTK, BERT, PEGASUS-X, Pandas<br/>
  <b>Databases:</b> PostgreSQL, SQL Server, Supabase, Redis, Oracle<br/>
  <b>DevOps:</b> Docker, AWS, Git, Heroku, Azure<br/>
  <b>Tools:</b> Power BI, Figma, Postman, Selenium<br/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/-Flutter-02569B?logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/-TensorFlow-FF6F61?logo=tensorflow&logoColor=white" alt="TensorFlow"/>
</p>

<h3>Connect with Me</h3>
<p align="center">
  <a href="https://twitter.com/markfouad12"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="30" width="40"/></a>
  <a href="https://linkedin.com/in/mark-george-48410a153/"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40"/></a>
  <a href="https://kaggle.com/theoryers"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="Kaggle" height="30" width="40"/></a>
  <a href="https://medium.com/@mark.fouad99"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="Medium" height="30" width="40"/></a>
</p>

<h3>Let’s Collaborate!</h3>
<p align="center">
  Got a challenging problem or exciting project? Reach me at <a href="mailto:mark.fouad99@gmail.com">mark.fouad99@gmail.com</a> or connect on <a href="https://linkedin.com/in/mark-george-48410a153/">LinkedIn</a>.
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=markgeorge10&show_icons=true&theme=dracula&layout=compact" alt="Top Languages"/>
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=markgeorge10&show_icons=true&theme=dracula" alt="Stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=markgeorge10&theme=dracula" alt="Streak"/>
</p>
