# Traffic-Violation-Dashboard-Analysis

![giphy](https://user-images.githubusercontent.com/83877492/151152512-4c50fd44-8102-4cbb-ac42-7c262c4f595d.gif)


# INTRODUCTION
This dataset contains around 65k+ traffic-related violation records. Each row contains information about a traffic violation that occurred at a particular time. 

Dataset Attribute Information:

- stop_date - Date of violation
- stop_time - Time of violation
- driver_gender - Gender of violators (Male-M, Female-F)
- driver_age - Age of violators
- driver_race - Race of violators
- violation - Category of violation :
1. Speeding
2. Moving Violation (Reckless Driving, Hit and run, Assaulting another driver, pedestrian, improper turns and lane changes, etc)
3. Equipment (Window tint violations, Headlight/taillights out, Loud exhaust, Cracked windshield, etc.)
4. Registration/Plates
5. Seat Belt
6. other (Call for Service, Violation of City/Town Ordinance, Suspicious Person, Motorist Assist/Courtesy, etc.)

- search_conducted - Whether search is conducted in True and False form
- stop_outcome - Result of violation
- is_arrested - Whether a person was arrested in True and False form
- stop_duration - Detained time for violators approx (in minutes)
- drugsrelatedstop - Whether a person was involved in drugs crime (True, False)


![Blue Minimalist Linear Circular Diagram](https://user-images.githubusercontent.com/83877492/151156226-cccbf0f7-ec3f-4652-a801-ae3760df8cdb.png)

# Understanding the Problem 

The goal here is to do an analysis of the traffic violation dataset to see if the tactics used to curb violations has been effective over the years (2005 - 2011). Some of the key important questions I'll be looking into with this analysis include;
- Has the Traffic violation increased or decreased over the years?
- How long does it take for a violator to get flagged down?
- Violation by gender
- If more searches were conducted than not?
- Average age of Offenders
- Traffic violation based on race
- No of violations per hour
- Most frequent violation
- Outcomes of this violations

# Data Preparation

Prepared the dataset using Powerquery editor in PowerBI. Extracted the columns with 90% empty values and also the null values in each column, resolved data inconsistencies and confirmed that every other column was in perfect condition.


# Data Modelling

Using the star schema method to model the data, the 5 dimensions tables created are;
- Date dimension 
- Time dimension
- Offenders attribute dimension
- Violation dimension
- Violation outcome dimension 

# Data Visualization and Analysis

![Screenshot (91)](https://user-images.githubusercontent.com/83877492/151516544-ce30bab7-a61c-41bb-ad8b-1883b372b032.png)

From the first dashboard page, 
- The dataset contains 49.34K observations after removing the null values and empty columns
- Over the years, there was a reduced number of violation in 2005, 2006 came with a rise in violations and then it gradually dropped 2007 - 2011
- Average time it takes to flag down an offender is approximately 0.50 seconds
- January has the highest monthly record of violations
- Average age of offenders is 34 years 
- A total number of 396 drug related arrests were made 
- We have a higher percentage of Male violators than Female violators 
- Violation by race shows that we have more white offenders, followed by blacks and hispanic
- Speeding has the highest record for traffic violation committed
- More vehicles were stopped within the hours of 6am - 4pm, there was less violation in the late evenings and then more violations in the middle of the night. 

![Screenshot (92)](https://user-images.githubusercontent.com/83877492/151535920-a0bac9b2-96a6-46aa-9e38-118c1ce3ad01.png)

The next page shows;
- The age distribution shows that the highest number of violators are between the ages of 20 - 40
- Over 90% of violation neither resulted in searches or arrests and were also non-drug related
- Citation has the highest number of stop outcome

# Conclusion and Recommendation

Traffic violation is quite rampant in cities around the world and it can further lead to severe incidents such as road accidents or car collisions leading to loss of lives and properties. Although, according to the data, there has been a significant decrease in traffic violation over the years, more traffic violation regulations should be put in place. 
- Stricter punishments should be given to extreme and constant violators
- Increased traffic regulation awareness to citizens to keep them informed about the dangers of violating traffic laws
- Cities should have more traffic violation detectors that would easily capture violations committed. 
