<h1> Sales-Analysis </h1>
<br>
<h2> Table of Content </h2>

<ul>
  <li><a href='#overview'>Overview</a></li>
  <li><a href='#motivation'>Motivation</a></li>
  <li><a href='#analysis'>Analysis Highlights</a></li>
  <li><a href='#credits'>Credits</a></li>
  
</ul> 
<br>

<h2 id = 'overview'> Overview </h2>
<p>
This project answers 5 questions regarding the Sales Data (year 2019) of an Electronic Store based out of several cities in the United States of America. 
I have used the Python Libraries Pandas and Matplotlib for answering the following 5 questions :
  <ul>
  <li> What was the best month for sales? How much money was earned in that months?</li>
  <li> What city had the highest number of sales?</li>
  <li> At what time should we display advertisements to maximize the likelihood of customer's buying product?</li>
  <li> What are the products that are most often sold together?</li>
  <li> What product was sold the most? Any insights would be appreciated..</li>
  </ul>

</p>


<br>


<h2 id = 'motivation'> Motivation </h2>
<p>
I started pursuing Post Graduate Program in Data Science Engineering at Great Learning during the pandemic in 2020. After we had covered Numpy Pandas and Visualization using Matplotlib and Seaborn in September 2020, I realised that theory and labs don't have any impact as long as one doesnot have handson experience with real life messy data. So I decided to take on a dataset from kaggle and get my hands dirty! 
<br><br>
This particular category (sales dataset) caught my attention because my first clear understanding (or so I thought back then!) about what objectives that data science achieved came from an article by <a href= 'https://www.nytimes.com/2004/11/14/business/yourmoney/what-walmart-knows-about-customers-habits.html'>New York Times</a>. The idea that Data Science could find the pattern between a hurricane occurance and sale of strawberry Pop-Tarts increasing seven times was very overwhelming at the time! Little did I know this was just the tip of the iceberg.
</p>


<br>


<h2 id = 'analysis'> Analysis Highlights </h2>
<p>
The first part of the process was to combine the raw data which was available to us in 12 csv file for the 12 months into 1 DataFrame. After this, the data had to be cleaned, converted into respective data types and new columns had to be derived from existing columns before proceeding with the analysis.

<br>
<h3> 1) What was the best month for sales? How much money was earned in that months? </h3>
  <p>
    <img src="Images/Analysis_1.png" width=750> <br>
    The highest sales occurs in the month of December. This surely doesnot come as a surprise owing to Christmas and New Year shopping spree.
  </p>
  
<br>

<h3> 2) What city had the highest number of sales? </h3>
  <p>
    <img src="Images/Analysis_2.png" width=750>
  </p>  
 
</p>

<br>

<h3> 3) At what time should we display advertisements to maximize the likelihood of customer's buying product? </h3>
  <p>
    <br> Although this question makes much more sense if we are given the time period of advertisement the client can afford, the peaks seem to appear at 12pm and 7pm. The store saw negligible traffic during the post midnight to early morning period.
    <img src="Images/Analysis_3.png" width=1000, height=400>
  </p>  
 
</p>

<br>

<h3> 4) What are the products that are most often sold together? </h3>
  <p>
    <br> I have answered the question with two groups : <br>
  <ul>
  <li><h4> Top ten groups of Two Products sold Together </h4>
       <img src="Images/Two products bought together.png">
  </li>
    <br>
    <li> <h4>Top ten groups of Three Products sold Together </h4>
      <img src="Images/Three Products bought together.png">
    </li>
  </ul>
    
  
  </p>  

<br>

<h3> 5) What product was sold the most? Any insights would be appreciated.. </h3>
  <p>
    <br> This problem could be tackled by two approaches : <br>
  <ul>
  <li><h4> Total Quantity Ordered </h4>
       <img src="Images/Total Quantity Ordered Each Product.png" >
  </li>
    <br>
  <li><h4> Total Sales </h4>
       <img src="Images/Sales Productwise.png" >
  </li>
    
  </ul>
  
  <br>
  

Interesting point to note that the top five products <br>

     AAA Batteries (4-pack), AA Batteries (4-pack), USB-C Charging Cable, Lightning Charging Cable, WiredHeadphones 

that were sold in highest numbers (quantity)
feature in the bottom five when it comes to total sales! This can be attributed to their relatively marginal
price compared to products like <br>

     Macbook Pro Laptop, iPhone, ThinkPad Laptop 

that top the total sales chart.
  
  </p>  


<br>


<h2 id = 'credits'> Credits </h2>
<p>
<ul>
  <li>I would like to thank my family for supporting my decision to pursue Data Science as career rather than sticking to my degree profession-Mechanical Engineer.</li>
  
 <br>
  
  <li>Next I would like to thank Great Learning for giving quality (both theory and handson) education during the pandemic times. I am sure they had to go to great lengths to provide what was initially promised as an offline course in an online platform.
  </li>
    
 <br>
  
  <li>I thank <a href= 'https://www.linkedin.com/in/namrata-thukral-50550772/'>Namrata Thukral</a> who is a faculty at Great Learning for sparing time out of your busy schedule to review this project and providing valuable insights.
  </li>
 
 <br>
  
  <li>Since this is my first Data Analysis project, I relied on <a href= 'https://www.kaggle.com/'>Kaggle</a> (needs no introduction in the Data Science realm) for acquiring the dataset. Thank you Kaggle for providing such a great platform for Data Science enthusiasts!
  </li>
 
 <br>
  
  <li>Finally I would like to mention Stack Overflow. I was able to solve Part 4) (What are the products that are most often sold together?) by understanding how itertools and counter libraries can be leveraged. To check out the Stack Overflow page click <a href= 'https://stackoverflow.com/questions/52195887/counting-unique-pairs-of-numbers-into-a-python-dictionary'>here</a>.
  </li>
  
  </ul>

 
</p>

