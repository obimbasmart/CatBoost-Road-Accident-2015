# CatBoost-Road-Accident-2015
A data science collaborative project on Road accidents in UK, 2015  - CatBoost Team

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/road_accident_image.jpg?raw=true)

## Problem statement: 
A safe road system aims to eliminate fatal and serious injuries for all road users. It does so through a holistic view of the road system that first anticipates human mistakes and second keeps impact energy on the human body at tolerable levels. Safety is imperative of the designers and owners of the transportation system.

Making a commitment to zero deaths means addressing every aspect of accident risks through five elements which include safe road users, safe vehicles, safe speeds, safe roads, post-crash care.

The key focus of a safe system is to reduce death and serious injuries through design that accommodates human mistakes and injury tolerance.

However, the United Kingdom road safety deviates from the ideal safe road system. By less consideration of the five elements, UK records high number of accident cases which cause serious injuries on road users.

This inefficiency of the United Kingdom road safety system is clearly seen in 2015 where there was a total of 140,056 accident cases affecting over 180,000 persons with slight to fatal injuries. This means that on an average there was 15,000 casualties in a month. This claim is based on the UK_Traffic_Accidents_2015.csv data.

The aim of this project is to understand the major factors that contributed to road accidents in UK. One needs to know when, where, and why they happen.

## Exploratory Data Analysis:
Raising speed limits increases the number of casualties, but a slight look into the data shows that Low Speed limit of 30km/hr resulted in more casualties as against vehicles on high speed as shown below:

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/casualties_by_speed.png?raw=true)

It will be interesting to know if cars on high speed caused more fatal accidents than those on low speed. The resulting image below shows that, 30km/hr speed led to more serious accident than other speed limits.

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/speed_on_severity.png?raw=true)

However, it was observed that 75% of the accident occurred as a result of the single carriageway(a road with one, two or more lanes arranged within a one carriageway with no central reservation to separate opposing flows of traffic) which led to more casualties. This could been an head-on collision with the vehicle coming in the opposite direction. The graph below validates the fact

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/casualties_by_road_type.png?casualties_by_road_type.pngraw=true)

Today most accidents occur at junctions. Analysis on the uk road accidents - 2015, revealed that junction details contributed to the massive number of accidents and casualties. 60% of the accidents occured at junctions and this led to more casualties.

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/casualites_by_junction_details.png?raw=true)

Considering the conditions of the road surface, we could deduce that 72.5% of the accidents on UK, 2015, occurred on a Dry road while Wet, damp, Frost, ice and other factors contributed to 27.5%. This shows that road surface condition isn't the major cause of road accidents in UK, 2015

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/accident_by_surface_condition.png?raw=true)

The fact is that bad weather significantly increases the chance of a car accident. Conditions such as fog, rain, sleet, snow, and ice not only hamper visibility but it can also affect the performance of your vehicle. But this wasn't the case regarding the Uk road accidents data. Majority of the accidents occured on a Good weather condition. If we are to see the relationship between weather condition and accident severity, we'd see that weather conditions is not directly proportionl to the degree of fatality and number of casualties. Could there be other factors that played in ?

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/analysis_on_weather_condition.png?raw=true)
![download](https://user-images.githubusercontent.com/67028610/155322949-f6324b98-3de8-409a-9939-3250b424c753.png)

Light conditions are known to affect the number of vehicle accidents and fatalities but the relationship between light conditions and accident severity is not fully understood as more accidents occured during the day and most were slight

![alt text](https://github.com/Smartify-Tech/CatBoost-Road-Accident-2015/blob/main/images/light_conditions.png?raw=true)

Urban areas tend to have more car accidents than rural areas due to the greater number of motor vehicles, pedestrians, and bicyclists on the road which leads to more casualties. However, an appreciable  number of casualties occured in rural areas

![download](https://user-images.githubusercontent.com/67028610/155323447-d0b74ea4-77d9-45ea-8766-5425bb5d3e3c.png)

On checking the effectiveness of the Police officers, it is seen that police officer visited the scene more. This denote an activeness to rescue by the police force in the UK

![download](https://user-images.githubusercontent.com/67028610/155324063-ba8578b0-938c-4ce5-ad95-872953c4c97a.png)

Putting into consideration the time and day each accident occur, this heatmap plot was generated. From the image it's obvious that more accidents occured on working days - MONDAYS - FRIDAYS, and this was during the rush hours 8am and 5pm, 6pm

## Summary:
The major key factor that caused majority of accidents on Uk, 2015 was as a result of single carriageway road type. Perhaps most the rate of this accident would have reduced if dual carriageway was provided.

Majority of the accideents occured without any physical crossing facilities within 50 meters and in day light, when there were no high winds and the roads were dry. So most natural factors weren't the causes of majority of this accidents but instead we can say that the single carriage ways had a huge part to play

