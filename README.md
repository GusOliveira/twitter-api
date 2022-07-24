# twitter-api
api for job interview.

1.Describe which are the main challenges to implement a scraper in social media platforms as Instagram, You Tube and Tik Tock. Give at least 4 examples of challenges, explain why you believe that are an issue and present which methods you would use to handle it. If do you believe there is some challenges that cannot be solved, please provide the reason to support your point of view.
  The challenges of a web scraper in social media are: 
    -Acess: web sites can block the automation of data extraction. To solve this, we can try to talk if the owner of the wesite for permission or find a similar source of data.
    -IP Blocking: This happens when we are calling a large numbers of request in short periods of time. Try to not overload the gates.
    -Captcha: Block loggin from bots with simple tasks for humans. Today we have captcha solvers for bots.
    -web page structure: The pages can have changes in a period of time. If the changes are too big, it can make the scraper useless. To solve this, if the website has an API we should use the API and not the website to get information.
    
2.What do you understand by Data Mining? How this concept can be used to the mission to develop platform the support business to find the best Influencer to increase the ROI of their marketing actions. 
  It's the process to find patterns, correlations and anomalies in large sets of data to try to predict outcomes and events. 
  In order to develop a plataform to increse the ROI of marketing through digital influencers, we have a large set of business and influencers to make correlations and find patterns of the followers.
  We should first check if the followers are the target group of the campaign. After that try to correlate the data of the followers to the business.
  
3.Web scraping tasks. If you already use some of them, please describe the solution you have created. 
  I use a very basic web scraper to get the price of stocks to a data frame and make some grapsh of my investments.
  The website uses a html table for the data. Every stock has a link, I take the website link, loop through the stocks i need and extract the data of each field to a dataframe.
  
4.Explain what HTTP is and how it works. Also, provide a brief description of methods, headers, and cookies in the HTTP context. 
  HTML - HyperText Markup Language. The web browser receive the HTLM document from the server and render the doc into multimedia.
  Methods specifies how to send form-data. We have GET to send form-data as a URL, and POST to post a form-data transaction.
  Headers is a container for introductory content and navigation links. Usually contains one or more heading elements, logo/icon, links.
  Cookies are a small piece of data that servers sends to the user's web browser. They are used for session management, personalization and tracking.
  
5.What do you understand by Proxies Servers and why their important for the web scraping process?  
  They are used to manage proxies and create the apperance of different users accessing the website at the sime time.
  
6.Differentiate Machine Learning, artificial intelligence, and data science.
  Machine Learning: A field of artificial inteligence.
  AI: Simulation of humana inteligence in machines to mimic humans actions.
  Data Science: A field that uses scientific methods, process and algorithms to extract knowledge from unstructured data.
  
7.In the Machine Learning context, what is Feature Engineering? Why this is important for Machine Learning Processing and how the Data Engineering can interfere on that? 
  is the act of converting raw observations into desired features using statistical or machine learning approaches. It is important to improve performance. Data engineers can help make the models more accurate.
  
8.Differentiate the Data Scientist from the Data Engineering?
  Data scientist analyzes data to answer questions and provide metrics to solve business problems. The engineer develops tests and pipelines to maintain and acquire data.
  
9.Imagine that you have been hired as a web scraper developer. On your first day of work you are asked to start a process to develop a data pipeline to create and update a influencers Database from Instagram. As a first step in this process, you are asked to create a simplified logic flowchart that shows the steps in the process of creating this pipeline.
  
  start -> scrap process <-----------|
                |                    |
                |                    |
            API Connection -->  NO ->| 
                |                |
                |                |
               YES               |
                |                |
                |                |   
           extract data          |
                |                |
                |                |
         successfully extracted?-|
                |
                |
               YES
                |
                |
      save the data in CSV --> END
           
