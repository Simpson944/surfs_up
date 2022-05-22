# Surfs up!!
## This analysis was created to assist in the decision to invest in a new business serving beach goers and surf enthusiasts. We will take a look at weather patterns and determine what risk exsists in terms of weather impact.


--------------------------------------------
### June analysis:
- 1700 temperature measurments taken 
- Average t\Temp of 75 deg
- Lowest Temp recorded 64 deg
- Highest Temp recorded 85 deg
-----
### December analysis:
- 1517 temperature measurments taken 
- Average Temp of 71 deg
- Lowest Temp recorded 56 deg
- Highest Temp recorded 83 deg
----
## Conclusions:
The average temps and high temps do not vary greatly from this summer month to winter month. There is more of a story to be told in the standard diviation, 3.25 for June and 3.75 for December, indicating larger swings in temp in the winter months. Overall, the temp data would indicate this would be a viable climate to invest in a business dependent on good weather for beach-goers. a few additional queries that could be written include:

 "session.query(Measurement.date, Measurement.percp).filter(func.strftime('%m', Measurement.date) == '06').all()"

 &

"session.query(Measurement.date, Measurement.percp).filter(func.strftime('%m', Measurement.date) == '12').all()"

These queires, converted to a database, would help us uncover percipitation patterns, which may tell more of a story than simply Temp. 