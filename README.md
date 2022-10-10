# Unicorn_Companies_Analysis

# Cleaning and Analyzing data in Power query and Power BI
# Introduction
This is my first project while working at my previous job place. I analyzed a dataset from kaggle about unicorn companies around the world. A unicorn company, or unicorn startup, is a private company with a valuation of over $1 billion. As of June 2022, there are over 1,000 unicorns around the world. Popular former unicorns include Airbnb, Meta, and Google. Variants include a decacorn, valued at over $10 billion, and a hectocorn, valued at over $100 billion. The dataset contained 1061 unicorns and 10 columns which included information about company, valuation, date joined, country, city, industry, select founder, year founded, funding and financial stage.
# Data Cleaning
After importing my data into power query, I checked for duplicates(found none),the validity of my data using column distribution, quality and profiling and removed columns not neccessary for my analysis. I also made sure my columns were in the right data type.
# Data Preprocessing
I noticed the select investors column contained many investors together so i split them using the "split by delimiter function"(since i needed the each investor).
# Data Analysis & Visualizations
1. More than half of the unicorns come from United States. The United States is the best to start if ambitious
![uni-5](https://user-images.githubusercontent.com/115374063/194786970-5e72bce6-d1e7-4631-855c-547cee415c8d.png)
2. Bytedance has the highest return on investment (ROI) with 40% more than thr other unicorns folloewd by Shein company.![uni-6](https://user-images.githubusercontent.com/115374063/194787089-024473ee-8c68-419c-8cfa-13dd0ab59b3e.png)
3. 5-6 years is the most frequent duration required to achieve the hallowed unicorn, with an overall meedian of 6 years across industries in the last decade.![uni-2](https://user-images.githubusercontent.com/115374063/194787200-50ecbfa4-bc52-4060-8fa6-abba401a0d9f.png)
4. Internet related industries like Fintech, AI e.t.c, have the most potential to scale![uni-8](https://user-images.githubusercontent.com/115374063/194787311-29122679-a030-453e-ad55-60622c117560.png)
5. San Francisco and New York are gthe best places to spot a unicorn in the world, with almost 25%of all the global unicorns. They can be regarded to as *Industry Hubs*![uni-7](https://user-images.githubusercontent.com/115374063/194787415-890f8ce3-5db4-44b7-9417-be5e731aafa6.png)
6. The Past 5 years have been awesome for valuations with a huge growth in 2021![uni-3](https://user-images.githubusercontent.com/115374063/194787476-6836e99c-4119-430a-b959-95cb65ce3b37.png)
[view the dashboard here](https://user-images.githubusercontent.com/115374063/194786711-e7901387-5943-474f-a11a-2a211bc9ead6.png)
