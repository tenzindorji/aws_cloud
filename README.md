# AWS Cloud Interview Questions:
## EC2 options:
  * On demand
    - This is the instance we usually create
    - There is no time commitment
    - No Advance payment
    - Need to pay only hours which it is used
    - expensive option
    - Used for the applications with short-term, irregular workloads that cannot be interrupted.
  * Reserved
    - There is time commitment, like 1 or 3 years
    - Need to pay upfront
    - It gets applied to on demand instances immediately
    - billing discount applied to on demand instance
    - provides significant saving over on demand instance
  * spot
    - This type of instance are cheapest and are used for short duration
    - Need to put the bid for the instance and if the instance is available under bid prince,\
      instance is available for use. If the bid prince goes up, AWS will automatically pull down the EC2 instance.
    - Good for one who want to use high processing power at low price for small duration.
    - are a cost-effective choice if you can be flexible about when your applications run and if your applications can be     interrupted. For example, Spot Instances are well-suited for data analysis, batch jobs, background processing, and optional tasks

  * Dedicated
    - most costliest of all options
    - Give better performance as its resources are not shared.
    - 
