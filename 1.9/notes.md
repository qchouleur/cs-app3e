# Amdahl’s Law

Observation about the effectiveness of improving the performance of one part of
a system. When part of a system is sped up, the effect on the overall system
performance depends on both how significant this part was and how much it sped
up.

![equation](amdalhslaw.svg)

where:
- S = the seepd up of the execution of the whole system
- α = the proportion of execution time that the part benefiting from improved resources originally occupied
- k = the performance improvement factor


### Practice

**1.1.** Suppose you work as a truck driver, and you have been hired to carry a load of
potatoes from Boise, Idaho, to Minneapolis, Minnesota, a total distance of 2,500
kilometers. You estimate you can average 100 km/hr driving within the speed
limits, requiring a total of 25 hours for the trip.

**A.**  You hear on the news that Montana has just abolished its speed limit, which
constitutes 1,500 km of the trip. Your truck can travel at 150 km/hr. What
will be your speedup for the trip?

---
![equation](practice-1-1-A.svg)

_The speedup for the trip will be of 1.25×_

---

**B.** You can buy a new turbocharger for your truck at www.fasttrucks.com. They
stock a variety of models, but the faster you want to go, the more it will cost.
How fast must you travel through Montana to get an overall speedup for
your trip of 1.67×?

---

![equation](practice-1-1-B.svg)
_The truck must travel at 301.8 km/h to get an overall speedup for the trip of 1.67×._

---

**1.2.** A car manufacturing company has promised their customers that the next release of a new engine will show a 4× performance improvement. You have been as-signed the task of delivering on that promise. You have determined that only 90% of the engine can be improved. How much (i.e., what value of k) would you need to improve this part to meet the overall performance target of the engine?

![equation](practice-1-2.svg)

_You would need to improve this part by 6 to meet the overall performance target of the engine._ 

