
# New York Metropolitan Transportation Authority (MTA): Leveraging Foot-Traffic For Marketing Purposes


![Title (1)](https://user-images.githubusercontent.com/89771282/142501533-d139fb24-9d45-499e-b924-f50fc5862eba.jpg)


## Introduction:
New York Metropolitan Transportation Authority (MTA)  publishes data on a weekly basis. This data does not represent value, Unless it is analyzed and used correctly to serve certain business domain to take advantage of this foot-traffic.

## Abstract:
The project goal would be an identification of the subway stations that have the most crowded,
to help an Ads agency target crowds from busy stations and present their marketing products. For
these, I will analyze the visitors of all stations and identify the busiest stations to target.
As a result, the crowds will be shown and detected based on congestion time.

## Question/need:
The goal of this analysis is to determine crowds of trains stations that can be used positively. Therefore, helping the ads agency in the decision-making and target crowds stations and determine the congestions per day, correlated with congestions time.

* Identify stations that has most congestion.

* Find congestions per day for each station.

* Find the congestions time for each station.

## Objective and Goal:
Take advantage of the stations crowds positively for marketing purposes.
<br />
* Find the congestion on each station.
* Help the ads agency in the decision-making.
* Improving the ads cost and set the cost in accurate way.
* Providing detailed number of visitor by each station.

## Design:
The project utilizes a dataset provided by the MTA that helps in getting information regarding
the stations especially the turnstiles information. Therefore, the design detects congestions based on stations exits, entries. After detecting, the model will generate a graph for spotting congestions, to 
enable the Ads agencies to take action to improve ads operations and pay attention to the busy stations.

## Data:
The dataset contains over 2.7 million observations in the period from August to October of 2021 with 11 columns. A few feature highlights include numbers of entries/exits for each station.

### Data Description:
* MTA Turnstile Data: Data obtained from [MTA Turnstile](http://web.mta.info/developers/turnstile.html).

* Field Description:
<br />


| Field Name  |                Description |
| ----------- | ----------- |
| C/A         | Control Area (e.g., A002)              |
| UNIT        | Remote Unit for a station (e.g., R051) |
| SCP      | Subunit Channel Position represents an specific address for a device (e.g., 02-00)|
| STATION     | Represents the station name the device is located at |
| LINENAME    | Represents all train lines that can be boarded at this station |
| DIVISION    | Represents the Line originally the station belonged to BMT, IRT, or IND |
| DATE        | Represents the date (MM-DD-YY) |
| TIME        | Represents the time (hh:mm:ss) for a scheduled audit event |
| DESC        | Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours) |
| ENTRIES     | The comulative entry register value for a device |
| EXITS       | The cumulative exit register value for a device |
| DAY_OF_WEEK | The day of week represented in categorical format, started from 0 which represent the first day (Monday)|
| DATETIME    | Represent the time and date in the same column |
| ENTRY_DIFF  | The different in the entry based on the previous time period |
| EXIT_DIFF   | The different in the exit based on the previous time period  |
| TOTAL_TRAFFIC | represents the sum of (ENTRY_DIFF, EXIT_DIFF)            |
 

## Tools:
* For carring out the project and explore/prepare the data: Jupyter, Sqllite3, and Python3.
* For data read and write operations: Numpy, and Panda.
* For data visualization: Matplotlib, and Seaborn.


## MVP Goal:
* The goal of this project would be an identification of the subway stations that have the most congestion and crowds, correlated with those who commute every day. And to find how to take this congestion in positive way to serve the ads agency agenda. 

<br />

Easy graphs to detect crowds. Also, helping to take an advantage of crowds by identify the busiest stations based on the graphs.



<br />

For further details on the MVP of this project [click here :)](https://github.com/Hashehri/EDA-MTA/blob/main/MVP.md) 

