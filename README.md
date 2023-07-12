# AdOptimize: Instagram A/B Testing for Sales and Traffic Boost

This Git repository focuses on A/B testing of Instagram ad campaigns to optimize sales and drive traffic. The goal is to maximize the effectiveness of your advertising efforts on Instagram by experimenting with different variations and strategies.

## Overview:
In today's competitive market, it's crucial to optimize your Instagram ad campaigns for maximum impact. This repository provides a comprehensive framework for conducting A/B tests, allowing you to evaluate the performance of different ad variations and make data-driven decisions.

## Key Features:
- A/B testing framework specifically designed for Instagram ad campaigns.
- Analyze the impact of different ad creatives, copy, targeting options, and more.
- Measure the influence of different strategies on sales, website clicks, search activity, and conversions.
- Utilize statistical analysis to determine the significance of results.
- Boost sales and drive traffic by identifying the most effective advertising approaches.

## Benefits:
- Improve the overall performance of your Instagram ad campaigns.
- Gain valuable insights into customer behavior and preferences.
- Optimize your advertising budget by focusing on strategies with the highest impact.
- Make data-driven decisions to continually refine and enhance your ad campaigns.
- Achieve higher sales conversions and increased website traffic through targeted optimization.

By leveraging the power of A/B testing and data analysis, AdOptimize empowers you to unlock the true potential of your Instagram ad campaigns, resulting in boosted sales and traffic. Enhance your advertising strategies, engage your target audience effectively, and drive your business towards success.


## Project in Detail
### Major Steps in Running A/B Tests

1. **Prerequisites**
    - Objective and Key Metrics
        - Objective is to increase the purchases and Traffic
        - Key Metric
            - Reach / Amount Spent
            - Viewed Content / Amount Spent
            - Purchases/ Amount Spent
    - Product Groups 
        - Control and Treatment

2. **Experimental Design**

    this is the second step where we establish our point to target specific users or all users
    - Users to target
        - Objective is to increase the purchases and Traffic

        - <img src="reports/figures/User&apos;s Path to Purchase.png" alt="ALT_TEXT" width="500" height="370">

        - from the above info we are targeting the users of viewed content
  
3. **Running Experiment**
    
    this is the third step where we establish how long to run the experiment but as basic thumb rule we follow these four things 
    - ramp up plan
    - day of week effect
    - seasonality effect
    - primary & Novelity effect

4. **Results to Decision**

    If we observe the above charts clearly we can get to a conlcusion before getting to conclusion let's see what we found from the above charts
    - The amount spent in Control is 66,818 USD and Treatment is 74,595 USD
    - Performance Metrics
        - Range of Users : for each dollar we spent Control : 39 users and Treatment : 20 users
        - User's Viewed Content : for each dollar we spent Control : 0.866 users and Treatment : 0.749 Users
        - User's Purchased : for each dollar we spent Control : 0.232 users and Treatment : 0.202 Users

    By the above info we can say that Control group is perfoming better compared to the Treatment group

<span style="font-size: small;"><em>
- for more info about theory I highly recommend: [Emma Ding: A/B Testing Fundamentals](https://www.youtube.com/watch?v=VpTlNRUcIDo&t=11s)
- Thanks to [AMAN KHARWAL](https://thecleverprogrammer.com/2022/11/14/a-b-testing-using-python/)
</em></span>
