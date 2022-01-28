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

Some of the key important questions I'll be looking into with this analysis include;
- Has the Traffic violation increased or decreased over the years?
- How long does it take for a violator to get flagged down?
- Violation by gender
- If more searches were conducted than not?
- Average age of Offenders
- Traffic violation based on race
- No of violations per hour

# Data Preparation

Prepared the dataset using Powerquery editor in PowerBI. Extracted the columns with 90% empty values and also the null values in each column, resolved data inconsistencies and confirmed that every other column was in perfect condition.


# Data Modelling

Using the star schema method to model the data, the 5 dimensions tables created are;
- Date dimension 
- Time dimension
- Offenders attribute dimension
- Violation dimension
- Violation outcome dimension 
