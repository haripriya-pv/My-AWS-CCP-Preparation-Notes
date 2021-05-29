# Pricing Models

## On-Demand

No long-term commitment

Low cost and flexible

Only pay per hour or minute

No upfront payment

For short term, spiky,unpredictable workload applications

Can not be interrupted

For first time applications

When you launch an application it is by default using On-Demand pricing model

 

## Spot

Request spare computing capacity

Flexible start and end times

Can handle interruptions(Server randomly stopping and starting)

For non critical background jobs

For applications that are only feasible at very low compute cost

AWS Batch is an easy way to use spot pricing

Spot instances can be terminated by AWS at any time

If instance is terminated by AWS ,wont get charged

If we terminated then it will be charged for any hour that it run.

## Reserved

Best for long term

For steady state or predictable usage or require reserved capacity applications

Commit to EC2 over a 1 or 3 year term

We can resell unused reserved instances

Longer the term greater the savings

- Standard: Up to 75% reduced pricing compared to On-Demand, can not change RI attributes
- Convertible: Up to 54% reduced pricing,allows to change RI attributes if greater or equal in value
- Scheduled: Reserve instances for specific time periods,example : once a week for few hours

        Payment options: All Upfront, Partial Upfront,No Upfront

        The greater the upfront the greater the savings

Reserved instances can be shared between multiple accounts within an organization. 

## Dedicated Host

Most expensive

Dedicated servers

Can be On-demand or Reserved

Designed to meet regulatory requirments

Enterprises and large organizations needs