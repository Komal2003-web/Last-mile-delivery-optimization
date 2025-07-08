# Last-mile-delivery-optimization
Optimizing Last Mile Delivery Route
Organizing routes to deliver parcels with a minimum number of drivers using python

How do you optimise your route for last mile delivery?

Walmart and Amazon are in a race to get your parcel to you fast.

One day shipping, a luxury 5 years ago, is a standard in online shopping.

Behind this modern day standard is a frenzy to keep costs down.

Last mile delivery, from distribution centre to a customer, is the most expensive part of a retailer’s supply chain.

In a nutshell, there are no cost savings from economies of scale of moving pallets on a vessel.

Costs typically include: fuel (59%) address location (39%), labor (36%) first delivery failure (34%) - it costs money to come back and redeliver

Managers at distribution centres organize your routes to deliver parcels with a minimum number of drivers.

Drivers take parcels from fulfilment centres to deliver them to final customers.

Here amazon and calmat have different strategies.

Amazon has and is building vast numbers of distribution centres
Walmart is using its existing network of retail stores as fulfilment centres.
The fulfilment centres are a key elements in the logistics network of the retailers.

They provide a large geographical coverage for last-mile delivery.

They have a competitive advantage of: Offering the best service level Reducing delivery lead time

I prepared a code to show a solution to optimize the last-mile delivery from these centres.

Based on:

Reducing costs
Uniform distribution of workload
Scenario: You are a manager in a local fulfilment centre:

4 drivers in your team
15 parcel capacity per vehicle
16 destinations to cover in the neighbourhood
1 route per driver
Demand at each location [0, 1, 1, 2, 4, 2, 4, 8, 8, 1, 2, 1, 2, 4, 4, 8, 8]
Objective

Deliver all parcels with a minimum number of drivers
Optimise the routing to minimise the distance covered per route
