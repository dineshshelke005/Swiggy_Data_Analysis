# Swiggy_Data_Analysis
iNeuron Project - Swiggy Data Analysis, automated EDA &amp; reports, Visualizing the variety of Use Cases along with WordCloud on Textual Data.

# Swiggy Data Analysis Project - (Online Food Ordering & Delivery Platform) 🔥🍁

# Swiggy Data Analysis Project - (Online Food Delivery Platform) 🔥🍁

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/Lokesh-Attarde/Swiggy_Data_Analysis)
  ![GitHub forks](https://img.shields.io/github/forks/Lokesh-Attarde/Swiggy_Data_Analysis)
  [![GitHub contributors](https://img.shields.io/github/contributors/Lokesh-Attarde/Swiggy_Data_Analysis.svg)](https://GitHub.com/Lokesh-Attarde/Swiggy_Data_Analysis/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/154198741-9ba7ddd8-ad79-4e55-9690-f4ae810c54f8.jpg">
</p>

# 📝Problem Statement
Food industries are having important reflection of the economy from past few decades. In this project, we are analyzing the various aspects with different use cases which covers many aspects of Swiggy Food Delivery Service. It helps in not only understanding the meaningful relationships between attributes, but it also allows us to do our own research and come-up with our findings.

Analysis of the following is performed in this Project:

    1. Distribution of 'Rating'.
    2. Area-wise Analysis in terms of 'Rating' and 'Cost_for_Two (₹)' on BTM, HSR, & Koramangala Area.
    3. Analyse "Approx Cost of 2 People" vs "Rating". Find out the relationship between them.
    4. Analyze Affordable/Budgeted and Highest Rated Restaurants of Bangalore.
    5. Top 15 Cheapest & Highest Rated Restaurants with Approx. Cost for 2 People.
    6. Top 15 Expensive & Highest Rated Restaurants with Approx. Cost for 2 People.
    7. Area-wise Cuisines Analysis & Distribution of Cuisines in BTM, HSR, & Koramangala (Bangalore) Restaurants.
    8. Most preferred Cuisines by the Customers.

And many more!!

# ⏳ Dataset
Download the dataset for this project from following Link -
* [Swiggy Data Analysis Dataset](https://github.com/dineshshelke005/Swiggy_Data_Analysis/blob/main/Swiggy%20Bangalore%20Outlet%20Details.csv)

# 📚 Data Analysis
In the datasets we are provided with following columns (Features) of data.

* Shop_Name : Name of the Shop/Restaurants.
* Cuisine : Name of the different Cuisines provided by Restaurants.
* Location : Restaurant Area/Location.
* Rating : Rating given by the Customers out of 5.
* Cost_for_Two (₹) : Approx. Cost of Two people w.r.t. Restaurants.

Out of the 5 features given in the datasets 2 are Continuous and 3 (including the target variable) are Categorical features.

# 🎉 Approach (Architecture):
![Process Flow](https://user-images.githubusercontent.com/84115928/137479294-ccfa21f9-81e1-4de8-8f96-15ddefdec06e.JPG)

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE. 
* Pandas is used for Data Manipulation & Pre-processing.
* Exploratory Data Analysis is automated by dataprep. 
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* WordCloud is used to representing the Text Data.
* GitHub is used as version control system.
![Tools Used](https://user-images.githubusercontent.com/84115928/154200410-86eb19e2-acd5-4669-8b36-ff958363ed2b.JPG)


# 🌱 Some Exciting Glimpse of the Visuals:
![Glimpse 1](https://user-images.githubusercontent.com/84115928/154206516-055a61ba-cf80-48c9-bae5-1b0a98fae6c4.gif)
![Glimpse 2](https://user-images.githubusercontent.com/84115928/154207666-81d7b700-bfd1-4cd0-950c-f521e615ac0e.gif)
![Glimpse 3](https://user-images.githubusercontent.com/84115928/154216904-325c33c5-bace-484b-b4d7-974a5146a3ca.png)

For more details, please go through the Demo given below -
# 🎯 Swiggy Data Analysis Project Video -

https://user-images.githubusercontent.com/84115928/154216541-ab894ba2-7760-47cc-89e2-5275dac3b643.mp4

# 💡 Conclusions

    In this analysis project, we have been analyzed several different use cases for the given dataset t o make better business decisions and help analyze customer trends and satisfaction, which can lead to new and better products and services. It has been found that – 
    •	In BTM Area: Most of the Restaurants has 4.0 to 4.2 Rating and Approx. Cost for Two People lies between 200 to 350. (Max. Cost goes up to 600)
    •	HSR: Most has 4 or above Rating and Approx. Cost for Two People lies between 300 to 400. (Max. Cost goes up to 800)
    •	Koramangala: Most has 4.0 to 4.3 Rating and Approx. Cost for Two People lies between 200 to 350. (Max. Cost goes up to 600)
    With this we can conclude the Most Costly Area is HSR. 

    - We have also analyzed that, we have Total "82" which are the "Budget Restaurants" as well as they are "Affordable". 
    - On top of that, we have found-out, Most of the Affordable/Budgeted Restaurants are having Excellent Rating as well. Like, For Approx. Cost of "200", "150", "250", and "450", the Ratings were "4.8", "4.6", and "4.5" respectively. 
    - This might be because Most of the people prefer Affordable/Budget-Restaurants which also provides good quality of Cuisines. 
    - And On the other hand, there are few Expensive Restaurants who doesn't have that much Rating and they are Expensive too. 
    - Those Restaurants Costs around "600" to "800" for Two People are having the Ratings in between '4.0' to '4.1' which is too less as compared to Affordable/Budgeted Restaurants.

    In addition to that, we have also performed Analysis on the Cuisines w.r.t. different Areas/Location and We have found-out:
    •	In BTM Area, Most of the Restaurants sell "Chinese" which is around '17.1%' followed by "North Indian" & "South Indian" Cuisines which are around '15.2%' & '9.52%'. So, we can also infer that Most of the people are fond of these Cuisines.
    •	In HSR Area, "North Indian" Cuisines are dominated by around '14.3%' followed by "Chinese" & "South Indian" Cuisines '9.52%' & '9.52%' Restaurants respectively.
    •	In Koramangala Area, "Chinese" Cuisines are dominated by around '10.3%' followed by "North Indian" & "South Indian" Cuisines '9.66%' & '7.59%' Restaurants respectively.
    •	Furthermore, we have also been analyzed Cheapest/Expensive & Highest Rated Restaurants with Approx. Cost for 2 People and many more. 

Please Go through [Swiggy Data Analysis - DPR.pptx](https://github.com/Lokesh-Attarde/Swiggy_Data_Analysis/files/8077260/Swiggy.Data.Analysis.-.DPR.pptx) for more info.

# 📖 Documentation

[High Level Documentation](https://github.com/Lokesh-Attarde/Swiggy_Data_Analysis/blob/05d0091a03a0d8b6467df1be21c91af1ac626ad8/Documents/Swiggy%20Data%20Analysis%20-%20HLD.pdf)

[Low Level Documentation](https://github.com/Lokesh-Attarde/Swiggy_Data_Analysis/blob/05d0091a03a0d8b6467df1be21c91af1ac626ad8/Documents/Swiggy%20Data%20Analysis%20-%20LLD.pdf)

[Architecture Documentation](https://github.com/Lokesh-Attarde/Swiggy_Data_Analysis/blob/05d0091a03a0d8b6467df1be21c91af1ac626ad8/Documents/Swiggy%20Data%20Analysis%20-%20Architecture.pdf)

[WireFrame](https://github.com/Lokesh-Attarde/Swiggy_Data_Analysis/blob/05d0091a03a0d8b6467df1be21c91af1ac626ad8/Documents/Swiggy%20Data%20Analysis%20-%20Wireframe.pdf)

[Detail Project Report](https://github.com/Lokesh-Attarde/Swiggy_Data_Analysis/files/8077260/Swiggy.Data.Analysis.-.DPR.pptx)

# 🎉 Help Me Improve
Hello Mr. Reader, if you find any bug or anything else that could add more value in this project then please consider raising it to me I will address them asap.
  
# 📫 Feedback
If you have any feedback, please reach out to me via [LinkedIn](https://www.linkedin.com/in/lokesh-attarde-145086141/)
