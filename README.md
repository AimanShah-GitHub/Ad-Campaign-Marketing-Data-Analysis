# Ad-Campaign-Marketing-Data-Analysis
In this project, we will analyze the significance of the color our client used for his ad campaign and our goal is to suggest a color that yields more clicks per ad.
## Problem Statment
Shawn is a loyal friend, and he needs your help. Shawn just launched a burger bistro in the city of Brisbane. The bistro is open for business, but business is slow. Shawn wants to entice new customers to come and try his tasty burgers. To do this, Shawn will run an online advertising campaign directed at Brisbane residents. Every weekday, between 11:00 a.m. and 1:00 p.m., Shawn will purchase 3,000 ads aimed at hungry locals. Every ad will be viewed by a single Brisbane resident. The text of every ad will read, “Hungry? Try the Best Burger in Brisbane. Come to Shawn’s.” Clicking the text will take potential customers to Shawn’s site. Each displayed ad will cost our friend one cent, but Shawn believes the investment will be worth it.

Shawn is getting ready to execute his ad campaign. However, he runs into a problem. Shawn previews his ad, and its text is blue. Shawn believes that blue is a boring color. He feels that other colors could yield more clicks. Fortunately, Shawn’s advertising software allows him to choose from 30 different colors. Is there a text color that will bring more clicks than blue? Shawn decides to find out. Shawn instigates an experiment. Every weekday for a month, Shawn purchases 3,000 online ads. The text of every ad is assigned to one of 30 possible colors. The advertisements are distributed evenly by color. Thus, 100 ads with the same color are viewed by 100 people every day. For example, 100 people view a blue ad, and another 100 people view a green ad. These numbers add up to 3,000 views that are distributed across the 30 colors. Shawn’s advertising software automatically tracks all daily views. It also records the daily clicks associated with each of the 30 colors. The software stores this data in a table. That table holds the clicks per day and views per day for every specified color. Each table row maps a color to the views and clicks for all analyzed days.

Shawn has carried out his experiment. He obtained ad-click data for all 20 weekdays of the month. That data is organized by color. Now, Shawn wants to know if there is a color that draws significantly more ad clicks than blue. Unfortunately, Shawn doesn’t know how to properly interpret the results. He’s not sure which clicks are meaningful and which clicks have occurred purely randomly. Shawn is brilliant at broiling burgers but has no training in data analysis. This is why Shawn has turned to you for help. Shawn asks you to analyze his table and to compare the counts of daily clicks. He’s searching for a color that draws significantly more ad clicks than blue. Are you willing to help Shawn? If so, he’s promised you free burgers for a year!

## Data Description
We have a csv file as a dataset. Our .csv file is a table stored as text. The table columns are separated by commas. The first line in the file contains the comma separated labels for the columns. The first 99 characters of that line are Color,Click Count: Day 1,View Count: Day 1,Click Count: Day 2,View Count: Day 2,Click Count: Day 3,...

Let’s briefly clarify the column labels:

Column 1: Color– Each row in the column corresponds to one of 30 possible text colors.

Column 2: Click Count: Day 1– The column tallies the times each colored ad was clicked on day 1 of Shawn’s experiment.

Column 3: View Count: Day 1– The column tallies the times each ad was viewed on day 1 of Shawn’s experiment.

The remaining 38 columns contain the clicks per day and views per day for the other 19 days of the experiment.
