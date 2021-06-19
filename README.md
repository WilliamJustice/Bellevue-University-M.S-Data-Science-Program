  This project is centered on the hospitality industry in the most recent technological booking
atmosphere. Specifically the domain this project falls into the web application-based self-hosting service
industry. A new trend in recent years is for web based services to offer a platform in which private hosts can
allow for customers to utilize their property much in the way a hotel allows guests to stay in theirs. This is a
new medium for the industry and creates a new environment/space which requires increased capitalization
on hidden data.

  The data that will be utilized was found on Kaggle and was scraped from the Airbnb website/app.
The data gathered is from the Seattle, Washington market and will be used only as a sample of all Airbnb
markets. The data was last updated in April of 2021 and dates back to 2008. The data can be found at
https://www.kaggle.com/airbnb/seattle/code. The data is broken down into three datasets which represent
the calendar dataset (likely no use in this research project), the listing dataset (highly critical), and the
reviews dataset (highly critical). Overall, the data represent all bookings, customer reviews, and associated
information.
The reviews dataset is mainly the reviewer data (limited usefulness) and the comments given
(highly critical).
The listing dataset is also highly critical and is broken down into over 90 features detailing
information given from every customer regarding their stay. If one has stayed in an Airbnb these features
are all relatively familiar. Features such as cleanliness, host availability, location score, etc.

  The data that will be utilized was found on Kaggle and was scraped from the Airbnb website/app.
The data gathered is from the Seattle, Washington market and will be used only as a sample of all Airbnb
markets. The data was last updated in April of 2021 and dates back to 2008. The data can be found at
https://www.kaggle.com/airbnb/seattle/code. The data is broken down into three datasets which represent
the calendar dataset (likely no use in this research project), the listing dataset (highly critical), and the
reviews dataset (highly critical). Overall, the data represent all bookings, customer reviews, and associated
information.
The reviews dataset is mainly the reviewer data (limited usefulness) and the comments given
(highly critical).
The listing dataset is also highly critical and is broken down into over 90 features detailing
information given from every customer regarding their stay. If one has stayed in an Airbnb these features
are all relatively familiar. Features such as cleanliness, host availability, location score, etc.

The first method used will be to use an NLP sentiment analysis on customer comments to determine
a quantitative figure for the overall comment. This method is highly important because it shows how
unstructured data can be processed in a valuable way for the project. Next another feature will be added to
represent the “quality” of the accommodation. While doing some quick looks through the data it is obvious
that one feature that is lacking is the quality of the stay. In this context quality represents the physical
datedness of the booking. For example, a booking that was updated within the last few years versus one that
was updated 10+ years ago could receive many of the same customer feedback scores except in this feature.
This feature will need to be engineered based off other related feedback scores. The next feature that will
need be engineered will one that represents location to a popular area. In this project, miles from the
downtown area will be used. This feature alone may help answer the research question regarding
geographical location.
The next step will then be to begin feature analysis to show which features are statistically
significant for modeling. The method for doing this will likely be ANOVA testing to ensure statistical
significance.
The next step will be to determine which models have the best performance for deployment.

With all the data presented it is safe to assume that there is a great deal of error for hosts in
determining the best nightly rate for their accommodation. Given the data on hand it is possible for Airbnb
to quickly recommend a competitive nightly rate which will then increase profits for both the host and
Airbnb. At this point all requirements for the project are already available and only need to be processed.
The ROI of this project is substantial because of the basically zero investment aside from the data science
team funding paired with the opportunity to capitalize on all profits made from bridging the gap of lost
income from over and underpriced bookings going to other stays such as hotels.
