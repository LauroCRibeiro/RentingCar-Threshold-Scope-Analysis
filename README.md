# Introduction

When using our services, drivers book cars for a specific time period, from an hour to a few days
long. They are supposed to bring back the car on time, but it happens from time to time that drivers are late for the checkout.

Late returns at checkout can generate high friction for the next driver if the car was supposed to be rented again on the same day : Customer service often reports users unsatisfied because they had to wait for the car to come back from the previous rental or users that even had to cancel their rental because the car wasn’t returned on time.

In order to mitigate those issues the task is to implement a minimum delay between two rentals. A car won’t be displayed in the search resultsif the requested checkin or checkout times are too close from an already booked rental.

## The Product Manager still needs to decide:

- the threshold: how long should the minimum delay be?
= the scope: should we enable the feature for all cars?, only Connect cars?
