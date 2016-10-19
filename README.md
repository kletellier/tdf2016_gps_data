

## Introduction

Data scraped from Tour de France 2016 live tracking website.

## Download

Download the database [here] (http://bit.ly/2e7H2IW)

## Database structure

Database are sqlite 3 database, there are 4 tables :

* riders => all riders profile
* history => all gps points for each rider with many data (speed,latitude,longitude,wind speed,gradient)
* stages => all stages data (start date, starting and arriving town,etc...)
* gps => all gps point for each stages.

Data are only partial, we doesn't have data for each stages, and only few stages has full data.

![schema](https://raw.githubusercontent.com/kletellier/tdf2016_gps_data/master/schema.png)
 