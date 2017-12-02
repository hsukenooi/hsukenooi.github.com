---
layout: post
title: "Investing in an Index Portfolio"
excerpt: "Something."
location: "Singapore"
---

# <a href="{{ page.url }}">{{ page.title }}</a>

## Summary

  * Mimic Betterment’s index portfolio (see below)
  * Split our allocation up into 20 parts chunks
  * Starting July 1st, 2017, buy a chunk every 6 months
  * If the market corrects 20% buy a chunk every 3 months
  * If the market corrects 30% buy a chunk every month

If you had done this at the absolute height of 2008, you’d still have returned 126.80% if held until today.

## Goal

Create a portfolio of indexes that we can invest a significant (35%) of our capital into and hold for the long term (10 years).

## What Others Do

Below are the indexes that Wealthfront, Betterment and the Vanguard Target fund invest in on behalf of their clients.

<img src="https://www.dropbox.com/s/auzgvgd0vwx0nga/Screenshot%202017-12-02%2012.23.47.png?raw=1" class="center">

The 3 portfolios have, on average, appreciated 6.96% this year, offer an additional 2.25% in dividends, and have an expense ratio of 0.12%.

Although the specific indexes are different, the allocation in broader categories is similar.

<img src="https://www.dropbox.com/s/gh5b1qvjf56kh44/Screenshot%202017-12-02%2012.31.07.png?raw=1" class="center">

I recommend we mimic Betterment's portfolio for 2 reasons:

1. **Granularity**. Unlike the Vanguard portfolio, that invests in a Total Stock Market index, I like the granularity of the Betterment portfolio. Although I don't have a preference for large or mid-cap stocks at the moment, I like having the option of being more specific with our allocations if need be.
2. **Lowest cost, highest return**. Even though past performance isn't an indicator of future performance, Betterment's portfolio has the highest YTD return (7.12%), highest yield (2.41%) and the lowest expense ratio (0.10%)

## Buying the Position

Obviously, we aren't going to buy our entire position at once. Certainly not with the market being on the expensive side. Instead we need a plan to buy into our position while minimizing the cost average.

To get a better understanding of how to do this, I looked at the prices of VTI (Vanguard Total Stock Market ETF) before and after the correction in 2008.

<img src="https://www.dropbox.com/s/n8cd94dprgugxwc/Screenshot%202017-12-02%2012.34.24.png?raw=1" class="center">

Important Dates

* High of $77.74 on 10/9/2007
* Low of $33.70 on 3/9/2009
* $126.27 on 6/19/2017 (Today)

If you had bought your entire position at the absolute bottom ($33.70), today you would be up 275%. Calling the bottom is impossible but the 275% is helpful in knowing that's the ceiling.

Correction and Rebound Velocity

* 0.25 years to drop 10% from High
* 0.76 years to drop 20% from High
* 0.99 years to drop 30% from High
* 1.42 years to go from High to Low
* 5.3 years to go from High to Low back to High

It took about 3.75x longer to recover from the correction (last bullet) than it did to go from the High to the Low. You see this if you look at other corrections, markets drop fast but recover slow.

### Backtesting

I backtested a few simple plans to see how they would have fared in 2008. I started by dividing the capital amount into 20 parts. To be conservative, I started the first buy at the High ($77.74) on 10/9/2007. From there, I tried different rules for speeding up or slowing down the frequency of buys.

<img src="https://www.dropbox.com/s/t0nzg3ehmdadq30/Screenshot%202017-12-02%2012.36.01.png?raw=1" class="center">

Plan 1. If you had simply bought every 3 months starting at the absolute peak and held until 10/3/2014 (7.23 years), you would have returned 74.85%. Still pretty good.

Plan 2 to 5. If you were trying to time the market a little bit, you might buy every 6 months and accelerate your buying to every 3 months after a 10%, 20% or 30% correction. That would have bumped up your return to about 86.33% (20% correction).

Plan 6. We can do a little bit better if we have a tiered accelerated plan where we start buying every 6 months, every 3 months if it corrects 20% and every month if it corrections 30%. That plan would have returned 98.44%.

Plan 7. The same purchase plan as Plan 6 but I changed the sell date to May of this year, an additional 2 years. That significantly bumped up the return to 126.80%. It pays to hold.

Plan 8. The same purchase plan as 6 but I started it a year before the peak so we're buying on the way up. Just like we can't time the bottom, we can't time the top. Turns out it's not too bad returning 103.13%.

## Recommendation 

Similar to the plans above, I recommend we split our allocation into 20 parts or $1.3125M chunks and do the following: 

1. Buy 1 chunk every 6 months starting July 1st, 2017
2. If the market corrects 10%, buy 1 chunk every 3 months
3. If the market corrects 20%, buy 1 chunk every 1 month

We want to hold this position for as long as 10 years, well into the next rally.

## Further Work

I’m planning on doing more work on the backtesting results. This was an initial investigation. Specifically I’m interested in doing the following.

* Backtesting the Betterment Portfolio. The backtesting I did was on VTI, a Total Stock Market ETF, not on the indexes in the Betterment portfolio. I might do the same analysis on the Betterment portfolio in the future but the outcome shouldn't be significantly different. Certainly on the risk side, the Betterment portfolio should be safer because of it's greater diversification.
* Backtesting through several corrections. I only looked at the 2008 correction but to be thorough I could look through all the corrections in the last 30 years.

I also haven’t done extensive research into how other people are tackling this, I’d like to do that.




