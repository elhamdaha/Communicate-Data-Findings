# 2018 Bay Wheels Ride Data Exploration and Visualization
####Udacity's Data Analyst Nanodegree - Project 5
### By Elham Daha

## Dataset
Bay Wheels (previously known as Ford GoBike) is a regional public bike sharing system in the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset used for this exploratory analysis consists of monthly individual trip data from January 2018 to December 2018 in CSV format covering the greater San Francisco Bay area, also available here.

## Project Details
1. Dataset: Ford GoBike
2. Explore the data: Feel free to explore the jupyter notebook where the dataset is visually, and programatically explored.
3. Document the story: organized findings convey a story to present to an audience.
4. Communicate the findings - a slide deck with my findings is prepared for a curious audience.

## Summary of Findings
This project is a win - win situation where a large number of people can benefit from this program:

- Environmentally friendly, budget friendly, and lifetsyle friendly.
- Subscribers (i.e. daily commuters) benefit from a health commuting choice
- Customers (i.e. tourists, students, etc.) have a sustainable, yet flexible option for touring the city.
- Affordable and convenient transportation for the people of all socioeconomic classes

The number of trips peaked around 8-9am and 17-18pm during a day, there were more trips on work days (Mon-Fri) compared to weekends. Summer time was the most popular season of a year, likely due to the weather. The riding trips tend to be shorter on Monday through Friday compared to weekends. It indicates a pretty stable and efficient usage of the bike sharing system on normal work days, while more casual flexible use on weekends.

Renting a bike from theFord GoBike System is a fantastic (healthy and environmentally friendly) way of moving around in the city, both for enjoyment and work. There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and, occasionally around lunch time. Customers are usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area.

## Key Insights for Presentation
Different usage pattern/habit between the two type of riders are seen from the exploration. Subscribers use the system heavily on work days i.e. Monday through Friday whereas customers ride a lot on weekends, especially in the afternoon. Many trips concentrated around 8-9am and 17-18pm on work days for subscribers, yet customers tend to use more in the late afternoon around 17pm Monday to Friday. The efficient/short period of usage for subscribers corresponds to their high concentration on rush hours Monday through Friday, indicating the use is primarily for work commute. The more relaxing and flexible pattern of customer use shows that they're taking advantage of the bike sharing system quite differently from the subscribers, heavily over weekends and in the afternoon, for city tour or leisure purpose probably.

## Files
readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis.

exploration_template.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration.

slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

To view the slide deck, you will need to use the expression (all one line): jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --template output_toggle

output_toggle.tpl - This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project).
