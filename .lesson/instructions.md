# Instructions  

For this assignment, you will design a set of classes that work together to simulate a car’s fuel gauge and odometer. The classes you will design are the following:


The FuelGauge Class: This class will simulate a fuel gauge. Its responsibilities are as follows:

To know the car’s current amount of fuel, in gallons.
To report the car’s current amount of fuel, in gallons.
To be able to increment the amount of fuel by 1 gallon. This simulates putting fuel in the car. (The car can hold a maximum of 15 gallons.)
To be able to decrement the amount of fuel by 1 gallon, if the amount of fuel is greater than 0 gallons. This simulates burning fuel as the car runs.

The Odometer Class: This class will simulate the car’s odometer. Its responsibilities are as follows:

To know the car’s current mileage.
To report the car’s current mileage.
To be able to increment the current mileage by 1 mile. The maximum mileage the odometer can store is 999,999 miles. When this amount is exceeded, the odometer resets the current mileage to 0.
To be able to work with a FuelGauge object. It should decrease the FuelGauge object’s current amount of fuel by 1 gallon for every 24 miles traveled. (The car’s fuel economy is 24 miles per gallon.)


Demonstrate the classes by creating instances of each. Simulate filling the car up with fuel, and then run a loop that increments the odometer until the car runs out of fuel. During each loop iteration, print the car’s current mileage and amount of fuel.