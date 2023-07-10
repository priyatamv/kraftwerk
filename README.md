# Driver coupon recommendation

This data study examines whether a driver will accept the coupon recommended to them in different driving scenarios.

## Description

The goal of the dataset is to understand the factors that affect coupon acceptance by drivers and to develop recommendation models for in-vehicle coupon systems. The dataset provides valuable insights into customer behavior and preferences in relation to coupons in a vehicular context.

## Scope

Analyze various coupon acceptance criteria and provide the observations.

## Getting Started

### Dependencies

* Juypyter note book.

### Analysis
#### Coupon acceptance Bar and Coffe House

* Bar coupon acceptance criteria
    * The proportion of total observations that accepted the Bar coupon is 41.00%. This indicates a significant portion 
      of the drivers accepted the coupon.

    * Drivers who go to a bar less than 3 times have an acceptance rate of 43%, which is higher than the overall 
      proportion. This suggests that drivers who visit bars less frequently are still receptive to the coupo.

    * Drivers who go to a bar more than 3 times have a higher acceptance rate of 54.3%. This indicates that frequent  
      bar-goers are more likely to accept the coupon.

    * Drivers who go to a bar more than once a month and are above the age of 25 have the highest acceptance rate of 
      62%. This group shows a strong inclination towards accepting the coupon, indicating that regular bar visitors are more likely to accept the offer.


* Bar Coupon non-acceptance criteria
    * Drivers below the age of 25 have a lower acceptance rate of 37%. This group appears to be less interested in 
      accepting the coupon, indicating that their bar visit frequency may not be a significant factor in their acceptance decision.

    * Drivers who have no kids, are not widowed, and go to a bar once a month and are over the age of 30 have acceptance 
      rates ranging from 35% to 35.8%. These groups demonstrate a moderate likelihood of accepting the coupon.

* Coffee House coupon acceptance criteria
    * The Proportion of total observations that accepted the Coffee House coupon: 49.86%.This indicates that a 
      significant portion of the drivers accepted the coupon

    * Drivers under the age of 31 who drive alone tend to visit coffee houses more frequently.

    * Drivers under the age of 31 who have friends also tend to visit coffee houses more frequently.

    * Drivers are more likely to visit coffee houses during sunny weather.


* Coffee House coupon non-acceptance criteria
    * Occupation does not significantly affect the acceptance of coffee house coupons

    * Drivers are less likely to visit coffee houses during rainy/snowy weather.

#### Next steps and recommendations

* Target Specific Age Groups: Since age appears to be a significant factor in coupon acceptance, consider tailoring marketing campaigns or offers to different age groups. Focus on drivers under the age of 25 who have a lower acceptance rate for the Bar coupon and drivers under the age of 31 who visit coffee houses more frequently. Create targeted promotions that resonate with these age groups and address their specific preferences and interests.

* Segment Frequent Bar-goers: Identify drivers who go to a bar more than 3 times a month and drivers who visit coffee houses more frequently. These are the segments with higher acceptance rates for both types of coupons. Develop loyalty programs or exclusive offers for these segments to further incentivize their continued patronage.

* Weather-based Promotions: Leverage the observed preferences for different weather conditions. Promote bar visits during pleasant weather and coffee house visits during specific weather conditions. Tailor promotions, themes, or seasonal discounts accordingly to align with drivers' preferences and enhance their experience.

* Personalized Offers: Utilize customer data and preferences to personalize coupon offers. Consider integrating data from other sources, such as occupation or income, to create more targeted and relevant promotions. Leverage customer segmentation strategies to deliver personalized offers based on individual preferences and behaviors.

* Customer Engagement and Feedback: Encourage drivers to provide feedback through surveys or online platforms to gain insights into their preferences and expectations. Actively engage with customers through social media, email marketing, or loyalty programs to foster a sense of community and gather valuable feedback. Use this feedback to continuously improve coupon offerings and better meet customer needs.

* Analyze Overall Market Trends: Monitor broader market trends, competitor strategies, and emerging consumer preferences. Stay updated on industry developments and adapt marketing approaches to stay competitive and address evolving customer demands

## Link to notebook

https://github.com/priyatamv/kraftwerk/blob/main/assignment_5_1_starter/prompt.ipynb

## Authors

Contributors names and contact info

ex. Priyatam Veyyakula

## Version History

* 0.1
    * Initial Release


## Acknowledgments

* [in-vehicle coupon recommendation](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation)