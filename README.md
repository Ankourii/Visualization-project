# Visualization-project

## This project consists in creating visuals for a database. In my case I chose to work with Power Bi.

For the purposes of this project I will be using a database I created as a part of a different project. You can find it [here](https://github.com/Ankourii/ETL)

This is a database with the total number of recorded births, per day, in the U.S for the years 1994-2003. I added the moon phases of each day to the dataset to examine how many children are born under each moon phase. 


![phases](https://as2.ftcdn.net/v2/jpg/05/34/41/87/1000_F_534418784_MChGg8kmiZLueqUptFJOoACKupKcWi1e.jpg)

There are eight moon phases in each month. The first one is the New Moon. That is when the moon is dark , then it starts to fill itself throught the Waxing Cresent, First Quarter and Waxing Gibbous phases until it reaches the Full Moon phase where it is completely full. After that it starts to loose brigthness again starting with the Waning Gibbous phase, then Last Quarter, Waning Crescent and goes back to the New Moon phase once again. And the cycle repeats itself.


The duration of the moon phases is as per below:


**New Moon**: lasts about 1 day

**Waxing Crescent**: lasts about 6 days

**First Quarter**: lasts about 1 day

**Waxing Gibbous**: lasts about 6 days

**Full Moon**: lasts about 1 day

**Waning Gibbous**: lasts about 6 days

**Last Quarter**: lasts about 1 day

**Waning Crescent**: lasts about 6 days 

In addition to the above there are:

2 to 5 solar eclipses 

![solar eclipse](https://www.australiangeographic.com.au/wp-content/uploads/2023/04/Untitled-1-1000x667.jpg)

and 0 to 3 lunar eclipses each year

![lunar eclipse](https://media.ktoo.org/wp-content/uploads/2022/11/ap22136148474266_custom-319e4a0f55b40d2c3e0483497c32e2663b68dd30-830x553.jpg)

![eclipses explanation](https://cdn1.byjus.com/wp-content/uploads/2018/12/difference-between-solar-eclipse-and-lunar-eclipse.png)

You can find the power bi dashboard in folder power bi. 

I will talk about the clustered column graph first. As it was expected, the moon phases with the most births are waning gibbous, waning crescent, waxing crescent and waxing gibbous (which are the ones that last the longest).
Last quarter, first quarter full moon and new moon have far less births since each of them normally only lasts 1 day per month. The rarest phases are Solar and Lunar eclipses, which also consecuently have the least amount of births.

Moving on to the stacked bar chart for the days of the month, obviously the day with the least amount of births is the 31st since not all months have 31 days. It is followed by the 30th and 29th which we could blame February for.
We can see that the day with the most births is the 18th of each month but the difference is insignificant. 

When it comes to the days of the week babies are born on, as per the donut chart, it looks like the day with the most births is Tuesday, followed by Friday and Wednesday, and the days with the least amounts of births are Sundays and Saturdays.

I would say that the most interesting graph is the line graph of the evolution of birth numbers throughout the years. In 1994 there are almost 4 million births, but it seems that for some reason they are descending until they hit an all time low in 1997 and start increasing again.
The number of births reaches a peak in 2000, starts lowering again until 2002 when it starts increasing once more. 
 



