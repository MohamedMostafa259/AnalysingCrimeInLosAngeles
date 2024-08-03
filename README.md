# AnalysingCrimeInLosAngeles
This project focuses on analyzing crime data from Los Angeles to uncover patterns and trends. By exploring the dataset provided, we aim to identify crime frequency by hour, area, and victim demographics. The analysis includes visualizations of crime incidents over time, by month and day, as well as insights into victim age groups, sex, and descent.

<br>

![Los Angeles Skyline](https://images.unsplash.com/photo-1619083382085-9452906b7157?q=80&w=2064&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

Photo by [Lala Miklós](https://unsplash.com/@lalamiklos024) on [Unsplash](https://unsplash.com).

## Table of Contents
- [Motivation](#motivation)
- [The Data](#the-data)
- [Task](#task)
- [Results](#results)
- [Conclusion](#conclusion)

## Motivation

Los Angeles, California 😎. The City of Angels. Tinseltown. The Entertainment Capital of the World! 

Known for its warm weather, palm trees, sprawling coastline, and Hollywood, along with producing some of the most iconic films and songs. However, as with any highly populated city, it isn't always glamorous and there can be a large volume of crime. That's where we can help!

I've created this notebook to identify patterns in criminal behavior in Los Angeles.

## The Data

[DataCamp](https://app.datacamp.com/) published a single dataset to use. A summary and preview are provided below.

It is a modified version of the original data, which is publicly available from **Los Angeles Open Data**.

### crimes.csv

| Column        | Description                                                                                                                   |
|---------------|-------------------------------------------------------------------------------------------------------------------------------|
| `'DR_NO'`     | Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.                            |
| `'Date Rptd'` | Date reported - MM/DD/YYYY.                                                                                                   |
| `'DATE OCC'`  | Date of occurrence - MM/DD/YYYY.                                                                                              |
| `'TIME OCC'`  | In 24-hour military time.                                                                                                     |
| `'AREA NAME'` | The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for. For example, the 77th Street Division is located at the intersection of South Broadway and 77th Street, serving neighborhoods in South Los Angeles. |
| `'Crm Cd Desc'` | Indicates the crime committed.                                                                                                |
| `'Vict Age'`  | Victim's age in years.                                                                                                        |
| `'Vict Sex'`  | Victim's sex: `F`: Female, `M`: Male, `X`: Unknown.                                                                           |
| `'Vict Descent'` | Victim's descent:<ul><li>`A` - Other Asian</li><li>`B` - Black</li><li>`C` - Chinese</li><li>`D` - Cambodian</li><li>`F` - Filipino</li><li>`G` - Guamanian</li><li>`H` - Hispanic/Latin/Mexican</li><li>`I` - American Indian/Alaskan Native</li><li>`J` - Japanese</li><li>`K` - Korean</li><li>`L` - Laotian</li><li>`O` - Other</li><li>`P` - Pacific Islander</li><li>`S` - Samoan</li><li>`U` - Hawaiian</li><li>`V` - Vietnamese</li><li>`W` - White</li><li>`X` - Unknown</li><li>`Z` - Asian Indian</li> |
| `'Weapon Desc'` | Description of the weapon used (if applicable).                                                                               |
| `'Status Desc'` | Crime status.                                                                                                                 |
| `'LOCATION'`  | Street address of the crime.                                                                                                  |

## Task

-   Where is the majority of crimes happens?
-   which gender of victims is more common in each area?

-   What is the most frequent descent of victims?

-   What is the most frequent gender of the victims?

-   What is the most common age for victims of each gender?
    -   What is the number of crimes committed against victims of different age groups? (age group labels: "0-17", "18-25", "26-34", "35-44", "45-54", "55-64", and "65+")
    
-   What is the most prevalent crime status?

-   Crime Incidents Over Time
-   Do crime incidents increase in certain months?
-   Do crime incidents increase on certain days?
-   Do crime incidents increase at certain hours?

-   Which area has the largest frequency of night crimes (crimes committed between 10pm and 3:59am)?

## Results

### Crime Incidents in Each Area Grouped by Victim's Sex
![Crime Incidents by Area and Sex](https://github.com/MohamedMostafa259/AnalysingCrimeInLosAngeles/blob/b17a8aa729591d076f40a9ce98bf6783d5a62677/visualizations/Crime%20Incidents%20in%20Each%20Area%20Grouped%20by%20Victim's%20Sex.png)

### Crime Incidents by Victim's Origin
![Crime Incidents by Victim's Origin](https://github.com/MohamedMostafa259/AnalysingCrimeInLosAngeles/blob/main/visualizations/Crime%20Incidents%20by%20Victim's%20Origin.png)

### Crime Incidents by Victim's Sex
![Crime Incidents by Victim's Sex](https://github.com/MohamedMostafa259/AnalysingCrimeInLosAngeles/blob/main/visualizations/Crime%20Incidents%20by%20Victim's%20Sex.png)

### Distribution of Victim Ages by Sex
![Victim Age Distribution](path/to/your/image4.png)

### Frequency of Victims by Age Group
![Victims by Age Group](path/to/your/image5.png)

### Frequency of Different Status Descriptions in Crimes
![Crime Status](path/to/your/image6.png)

### Crime Incidents Over Time
![Crime Over Time](path/to/your/image7.png)

### Number of Crime Incidents for Each Month
![Crime by Month](path/to/your/image8.png)

### Number of Crime Incidents for Each Day
![Crime by Day](path/to/your/image9.png)

### Number of Crimes for Each Hour
![Crime by Hour](path/to/your/image10.png)

### Night Crime Incidents in Each Area Grouped by Victim's Sex
![Night Crime by Area and Sex](path/to/your/image11.png)

## Conclusion

This analysis provides insights into the patterns of crime incidents in Los Angeles. By understanding the distribution of crimes across different times, locations, and victim demographics, we can better address and mitigate criminal behavior in the city.