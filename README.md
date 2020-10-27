# Project Title

Stock_Direction_Prediction

## Summary

Support tool making the big shift in all available tickers in the stock exchange system, making predictions on some specific criteria like growth and reliablility. 


## Background

I'm am required to save for my own pension. I would like to build up a portfolio for my self to be able to control my own money. Which investments are like to help me reach my pension goals and which will threaten it.

It's near impossible for a private and small time invester to keep up with all the information needed to make sensible investments.
If it would only be possible for me to make some big shifts in all the possibilties to limit my pick to some requested category or categories.

some of the partial problems are.
* There are to many possibilties to keep track (to many options)
* Interpreting all the information for one option needs specific 'insider' knowledge but could be 'learned/detected' by an algorithme without acyually knowning the rules.
* Interpreting all the information for one option is very time-consuming.
* making predictions needs a lot of related and historical data


## How is it used?

I would like users to be able give themselves the opporunity to select potential investment opportunities within given boundaries.
This should give them a set to look into further based on the likelyhood of matching those criteria.

criteria could be something like 'risk', time till payout, etc.

This is how you create code examples: (i don't know how to do this)
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()

## Data sources and AI methods

Data can be collected from numerous sources:
- Yahoo finance
- Zacks.com
- Tipranks.com
