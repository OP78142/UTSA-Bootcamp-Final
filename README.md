# Predicting Credit Card Transaction Fraud</br>
## Group members: Aaron DeVore, Ariana Garcia, Waynette Burke, Jessica Ermovick</br>
## Project Description</br>
In this project, the Team is attempting to analyze credit card transactions to 
determine predictability of catching fraudulent transactions with greater expediency
than current methods. We will visualize the data to see interesting trends in various 
features of the data and how it relates to the fraudulent transactions as well as attempt to create a predictive model that sufficiently predicts a fraudulent transaction. </br>

## Data Sources
The following data sources were used in preparing visualizations and models for this project:
[Here!](https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions)

## Table of Contents
- [Rationale](#rationale)
- [Extract](#extract)
- [Transform](#transform)
- [Load](#load)
- [Visualizations](#visualizations)
- [Models](#models)
- [Metadata](#metadata)
- [Results](#results)
- [Credits](#credits)
</br>

## Rationale
Credit and Debit card frauds are a growing problem worldwide. As we reach the holiday season, millions of dollars will be fraudulently spent using Credit and Debit cards. In this project, we will attempt to find an efficient model to predict fraud in card transactions. We will also quantify the fraud crisis in an attempt to raise awareness of the trends occurring within this crisis. Target Audience: Banking industry. </br></br>
## Extract
Extraction is being done via an existing historical dataset found [Here](https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions).
Should a banking industry decide to utilize the model, connecting to the banking data via odbc, jdbc, flat files, or even AWS RDS could easily be implemented. At the time of this project, direct access to bank records was not available. The act of accessing credit card information to predict credit card information is the equivalent of stealing the credit card information. To prevent legal issues, the transactions used are generated from a multi-agent virtual world simulation performed by IBM to simulate real-world data. </br>
The data is a set of three comma-separated value files (*.csv files) containing simulated user, card, and transaction data, see Metadata section for details on data.



## Transform
Transformations needed for this data ranged depending on the processes being performed.
### Visualization Transformations
Placeholder text for transformations needed for visualizations (custom codes in tableau, python, etc)

### Models
Placeholder text for transformations needed for model creations (buckets needed, columns dropped, etc)


## Load
Data is loaded into various applications to be processed.
### Tableau Load
Placeholder for Tableau data load details/process
### Jupyter Notebook Load
Placeholder for Jupyter notebook load details/process
### Model Load details and process
Placeholder for Tensorflow data load



## Visualizations
placeholder for Two processes here, Tableau and Python.
### Tableau
placeholder for steps taken and dashboards/viz's made here!
### Jupyter Notebook
placeholder for steps taken and viz's made here!


## Predictive Model Process
placeholder for steps taken for predictive model process here!


## Metadata
## Table Name: sd254_cards.csv</br>
|Column Name                              |Description                              |Data Type          |
|:----------------------------------------|:----------------------------------------|:------------------|
|User                                     |ID field to distinguish card user        |Binary [1|0]       |
|CARD INDEX                               |ID field for each card a User ID owns    |Integer            | 
|Card Type                                |Type of card: Visa, Mastercard, etc      |String             |     
|Card Number                              |Unique card number                       |Big Int            | 
|Expires                                  |Expiration date of card                  |Date MM/YYYY       |  
|CVV                                      |Card Verification Value (3 digit code)   |Integer            |      
|Has Chip                                 |Indicator of presense of chip Y/N- 1/0   |Binary [1|0]       |   
|Cards Issued                             |Number of cards issued for a card number |Integer            | 
|Credit Limit                             |Limit of user- not always equal to card  |Currency USD       | 
|Acct Open Date                           |Date account opened MM/YYYY format       |Date MM/YYYY       | 
|Year PIN last Changed                    |4 digit year of last time PIN was changed|Integer 4 digit Yr | 
|Card on Dark Web                         |Was card number found on dark web Yes/No |Yes/No             |</br>

### Table Name: sd254_users.csv</br>

|Column Name                              |Description                              |Data Type          |
|:----------------------------------------|:----------------------------------------|:------------------|
|Person                                   |Name of Cardholder  -First Last          |String             |
|Current Age                              |Current Age of Cardholder                |Integer            |  
|Retirement Age                           |Age at Retirement-estimated              |Integer            |    
|Birth Year                               |Year of Cardholder Birth                 |Integer 4 digit Yr |  
|Birth Month                              |Month of Cardholder Birth                |Integer 2 digit Mo |  
|Gender                                   |Gender of Cardholder -Female/Male        |String             |  
|Address                                  |Address of Cardholder                    |String             |  
|Apartment                                |Apt # of Cardholder                      |Number             |  
|City                                     |City of Cardholder                       |String             |  
|State                                    |State of Cardholder                      |String             |
|Zipcode                                  |Zipcode of Cardholder                    |Number             |
|Latitude                                 |Latitude of City                         |Decimal            | 
|Longitude                                |Longitude of City                        |Decimal            |
|Per Capita Income - Zipcode              |Per Capita Income of Zipcode             |Currency USD       |
|Yearly Income - Person                   |Yearly Income of Cardholder              |Currency USD       |
|Total Debt                               |Total Debt of Cardholder                 |Currency USD       |
|FICO Score                               |Credit score of Cardholder               |Integer            |
|Num Credit Cards                         |Number of Credit cards issued to person  |Integer            |</br>

### Table Name: credit_card_transactions-ibm_v2.csv</br>
|Column Name              |Description                              |Data Type          |
|:----------------------- |:----------------------------------------|:------------------|
|User                     |ID to describe user                      |Integer            |
|Card                     |ID to describe each card a user owns     |Integer            |
|Year                     |Year of Transaction- 4 digit Yr          |Integer            |
|Month                    |Month of Transaction- 1 or 2 Digits      |Integer            |
|Day                      |Day of Transaction- 1 or 2 Digits        |Integer            |
|Time                     |Time of Transaction- 00:00 format        |Time 00:00         |
|Amount                   |Amount Transaction- US Dollars           |Currency USD       |
|Use Chip                 |Type of transaction (Swipe/Online/Chip)  |String             |
|Merchange Name           |ID describing Merchant/Business          |Big Integer        |
|Merchant City            |City Merchant Business Resides           |String             |
|Merchant State           |State Merchant Business Resides          |String             |
|Zip                      |Zipcode of Merchange                     |Integer            |
|MCC                      |Merchant Category Codes-merchant type    |Integer            |
|Errors?                  |Type of transaction error occurred/null  |String             |
|Is Fraud?                |Is the transaction fraudulent? Yes/No    |String Y/N         |</br>

## Results
placeholder for results here!



## Credits
The collaborators on this project are: 
Aaron Devore https://github.com/OP78142,
Waynette Burke https://github.com/WayBurke,
Ariana Garcia https://github.com/arianajoslyn, and
Jessica Ermovick https://github.com/Jermov </br>

 
