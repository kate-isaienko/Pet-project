My work will focus on researching data on user interaction with advertising campaigns, their demographics, and behavior. Analyzing the demographic characteristics of users and their income helps to understand their needs better and, accordingly, their behavior. In turn, the research on behavior and interaction with advertising campaigns makes it possible to choose the best marketing strategies for the highest efficiency in working with users.
The work will include segmentation of users by gender, age, and income groups, analysis of the presence or absence of influence of the budget spent on an advertising campaign on its performance indicators, creation of a customer loyalty rating, and research of the behavior of the most loyal of them, as well as loyalty segmentation for use in further advertising campaigns.

The work aims not only to investigate the above aspects but also to provide business recommendations on the best channels and types of advertising campaigns to achieve the highest possible marketing efficiency.

Technologies stack

Power Query: cleaning data and determining the correct data types for each variable;
Excel: descriptive statistics, box plots, correlation analysis;
Google BigQuery (SQL): preparing data for building visualizations, creating age and income categories, creating a ranking list, and aggregating metrics by channels and types of campaigns;
Power BI: data visualization;
Jupyter Notebook (Python): segmentation of customers by loyalty for its further use in marketing strategy.

Dataset description

Demographic Information

CustomerID: Unique identifier for each customer.
Age: Age of the customer.
Gender: Gender of the customer (Male/Female).
Income: Annual income of the customer in USD.

Marketing-specific Variables

CampaignChannel: The channel through which the marketing campaign is delivered (Email, Social Media, SEO, PPC, Referral).
CampaignType: Type of the marketing campaign (Awareness, Consideration, Conversion, Retention).
AdSpend: Amount spent on the marketing campaign in USD.
ClickThroughRate: Rate at which customers click on the marketing content.
ConversionRate: Rate at which clicks convert to desired actions (e.g., purchases).

Customer Engagement Variables

WebsiteVisits: Number of visits to the website.
PagesPerVisit: Average number of pages visited per session.
TimeOnSite: Average time spent on the website per visit (in minutes).
EmailOpens: Number of times marketing emails were opened.
EmailClicks: Number of times links in marketing emails were clicked.

Historical Data

PreviousPurchases: Number of previous purchases made by the customer.
LoyaltyPoints: Number of loyalty points accumulated by the customer.

Target Variable

Conversion: Binary variable indicating whether the customer converted (1) or not (0).
