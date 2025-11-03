---
title: "The myth of debt interest rates"
date: 2022-09-05
---

"Why would I pay off my 3% mortgage or my 6% student loan debt when I could be investing mutual funds yielding 8-10%?"

Let's talk about this.

### Risk-adjusted returns

Let's put on our nerd glasses for a second, and discuss [Risk-Adjusted Returns](https://www.investopedia.com/terms/r/riskadjustedreturn.asp).

Every investment has two main considerations: returns and risk (volatility). You could also collapse these into the idea that investment returns are best understood as a range: e.g., [the S&P 500 1-year returns are roughly -10-30%, but the 40-year returns are roughly 5-8% (adjusted for inflation)](https://dqydj.com/sp-500-historical-return-calculator/). So while the average or annualized returns over a long period of time might trend toward a nice number like 6% or 10% (depending on whether or not you adjust for inflation), that's not all there is to consider.

Note too that "average" and "annualized" returns aren't the same thing, coincidentally for exactly the reasons we'll discuss.

#### Annualizing Returns

Let's start with a simple example.

- You invest $100 today, year 0.

- By year 1, your investment is worth $50. Your return rate over the previous year was -50%.

- By year 2, your investment is worth $100. Your return rate over the previous year was 200%.

Your average return rate is just the average of each year's return rates: (-50% + 200%) / 2 = 75%. What a return rate!

But wait, that can't be right. You made no money at all, but you had a huge positive average return? [This is where annualized return comes in](https://www.investopedia.com/terms/a/annualized-total-return.asp).

_(Math note: the main issue here is that returns are multiplicative rather than additive. That means that the correct way to average things is the geometric mean, not the arithmetic mean. Annualized return is just the geometric mean of the returns.)_

Annualized return tells you what return you'd need per-year, if you had a constant annual return, to get you from the starting balance to the ending balance. In this case, we went from $100 in the beginning to $100 in the end, over two years. Clearly, that's just a 0% return. You can run [the equation here](https://www.investopedia.com/terms/a/annualized-total-return.asp) if you want.

#### Annualizing Returns With Withdrawals

This example gets more complicated when you have not just percentage returns, but also constant dollar-value withdrawals. Consider the following three scenarios.

In the first scenario, we'll have a no-risk 10% investment. Every year, we get our 10% paycheck without any variance. We'll withdraw some money mid-way and see what happens:

- We start with $100 invested.

- After the first year, our 10% return means we have $110 invested. We choose to withdraw $50 from that, leaving $60 invested.

- After the second year, our 10% return means we have $66 invested. We withdraw another $50, leaving $16 invested.

- After the third year, we have $17.60 invested, which we withdraw for a final amount of $117.60.

Let's just plug these values into [a relevant calculator](https://www.buyupside.com/calculators/annualizedreturn.htm) and find that our annualized return was 5.5%. The reduction in return was caused by our early withdrawals. Had we left the money alone, it would've yielded and annualized 10% return.

Alright, let's consider a high-risk 10% investment. This investment yields a consistent annualized rate of 10% long-term, but swings massive amounts each year along the way.

- We start with $100 invested.

- After the first year, we get a -25% return, leaving us at $75 invested. We choose to withdraw $50 from that, leaving $25.

- The next year, the investment returns 161%, leaving us with $40.25, which we withdraw for a final amount of $90.25.

Ouch. The fund we invested in has an annualized return rate of 10%--if we'd left the initial $100 alone, we would've had ~$121 after the two years--but our timing on that first withdrawal really hurt us. So even though the fund yielded 10% annualized over those two years, our personal return was -5%.

Note too that our behavior was exactly the same as in the first scenario. However, the way our behavior interacted with the volatility meant that we got -5% instead of 5.5%--a net difference of -10.5% worse annualized return just because we did the exact same thing in a volatile market instead of in a stable market, even with identical annualized returns on the funds we were investing in. That is, the returns for both investments were the same, but the risk-adjusted returns were different, and that translated into dramatically lower _real_ returns for us.

Finally, let's consider a third scenario with the same high-risk investment:

- We start with $50 invested, and save the other $50 for later.

- After the first year, we get a -25% return, leaving us $37.50 invested. We invest our second $50, for a total of $87.50.

- The next year, the investment returns 161%, leaving us with ~$141. We withdraw it all.

Again, the fund had an annualized yield of 10%, but our personal return was nearly 19%! We nearly doubled our returns by investing during the bad year instead of investing all up front. This is the same market as scenario B above with the same amount of money to invest, but we got even better yields than in scenario A above. The fund's annualized return was _identical_ in all three scenarios, but the differences in volatility _and_ how we interacted with that volatility resulted in three dramatically different returns on our particular investments.

#### Ok, but what if I'm not withdrawing?

"Ok", you say, "but let's just talk long-term yields. I pay 4% into my debt per year and expect an annualized return of 10% from my investments. Long-term, those yields are stable, so why pay off debt now instead of investing more earlier?"

Let's flip this equation. Let's say you're the lender instead of the borrower. You have $100,000 burning a hole in your pocket, and you want to invest it. Joe Schmoe comes and asks to borrow $100,000 to buy a house, and is willing to pay you 4% interest; Joe's a good bet and is very likely to pay his debt payments. Alternatively, you could take that $100,000 and invest it in a good mutual fund and get a 10% yield. Why on earth would you lend it to Joe instead of invest it in a mutual fund?

As a lender, there are two things going on here: 1) you're always withdrawing, because otherwise you're not making money by paying yourself or your staff; and 2) the reliability of the investment matters. We've already visited the effect of steady withdrawals, and noted that withdrawing in bad years is way worse than withdrawing in good years, and can even be worse than never having invested money in the first place. So people doing lots of investing need to consider not just the long-term yields, but what _stable_ yield they can derive from those investments.

Let's approach this two ways. First, as big-time investors, let's take a look at the most common risk-adjusted return metric, the Sharpe Ratio. This is mathy, I'm sorry, but it's important. After that, let's step back into the realm of normal humans and discuss the 4% rule.

##### The Sharpe Ratio

The most common metric for [risk-adjusted return](https://www.investopedia.com/terms/r/riskadjustedreturn.asp) is the [Sharpe Ratio](https://www.investopedia.com/terms/s/sharperatio.asp). This ratio tries to balance the expected return of an investment against its risk, with higher values representing better stable returns. Risk is measured relative to some "risk-free return", generally treasury bonds. That is, if you could make 1% with effectively no risk of losing your money, how good is 5±3%? or 10±30%? Sharpe ratios help investors look past the momentary, changing returns of various funds and look at what stable returns they could expect.

For example, in 2020 and 2021, the stock market had HUGE swings. Even though the returns were quite good by the end of those years, there were times when, had you withdrawn your money, your returns would have been quite bad. Alternatively, you could've invested in treasury bonds; the returns would have been mediocre, but at no point would you have lost your money. At some points, that might've seemed like a good idea in retrospect.

The point here is that even though the long-term yields for the S&P 500 may look very different from the interest rates on mortgages, that difference rapidly decreases, vanishes, or maybe even inverts when you instead consider the Sharpe Ratio of each investment and account for the dramatically different volatility in their returns.

##### The 4% Rule

Ok, but we still haven't found an intuitive argument for why _you_, an individual with some debt and some cash, should pay off the debt instead of investing. Or, at least, any answers are obscured by non-intuitive math. If I have $100,000 in 4% debt and $100,000 in 10% mutual funds, isn't that better than paying off my debt? After 30 years, I'll have $1.6M in my investments and, even if I only ever paid interest on my debt, I'd only have spent $120K in interest. That's like $1.5M of profit!

The most intuitive way to understand risk-adjusted returns at an individual level is to consider the [4% rule](https://www.investopedia.com/terms/f/four-percent-rule.asp). This rule states that, even with your money invested in the stock market, with annualized yields like 8-10%, when you want to convert your investment into income, you should only ever withdraw money at a rate of ~4% or else you'll collapse your investment and end up with nothing. (I'm aware that this might be more like 5% or 6%, but the significant drop from annualized long-term yield remains.)

That's interesting... 4-6% sure does sound similar to the interest rates we've seen in recent years for mortgages and student loans...

Let's take our original case again. We have $100,000 in 4% debt and $100,000 in cash that we're trying to figure out how best to spend it. Our time horizon is 30 years. If we invest that money in the stock market, we'd expect a final amount of $1.6M. Let's instead say we pay off our debt, then take the $4,000/yr money we were spending on interest and invest that instead. What happens now?

Let's start [by throwing this into a calculator](https://www.calculator.net/investment-calculator.html?ctype=endamount&ctargetamountv=1000000&cstartingprinciplev=0&cyearsv=30&cinterestratev=10&ccompound=monthly&ccontributeamountv=4000&cadditionat1=beginning&ciadditionat1=annually&printit=0&x=85&y=11), and we find that that $4K/yr is worth nearly $800K after 30 years, not the $120K we'd estimated earlier. Our earlier estimate didn't consider the opportunity cost of the money we were spending on interest. $800K is only half of the $1.6M we'd estimated from investing the money up front instead of paying off the debt, but things are starting to look a lot closer than before.

Recall, though, that as the flip side of constant withdrawals being disproportionately bad during down-years in the stock market, constant deposits during those same years are disproportionately good. So in reality, we'd actually expect our yield to rise over the long-term by depositing money regularly rather than investing it all up front. Thus the remaining difference can shrink altogether, or perhaps even begin to favor the slow, regular investing.

Of course all these values vary dramatically based on the interest rate of the debt, the nature of the repayment, the annualized return and volatility of the investments, and more. But when all's said and done, the difference between the two is completely different from merely the difference between their annualized returns. All those differences are difficult for an individual to keep track of, but that's exactly the kind of thing lenders account for when deciding their rates. You won't get a 2% mortgage if the lender knows they can get a better risk-adjusted return elsewhere.

One last thing, though. You're not going to find a calculator for this, but the reality is that debt causes stress and emotional pressure. Debt is a burden. It makes you a slave to your lender, as well as to whoever is paying your paycheck. If you pull your money out of the stock market for a year, nobody cares; if you stop making your debt payments for a year, you could lose your stuff, your car, your house, and a whole lot more.

Don't believe me? Go find someone hitting retirement age or older, and ask why they don't refinance all the equity out of their home to invest in the stock market. They could get the mortgage at 4-5% and could expect a "stable long-term yield" from the stock market of 8-10%. It's just free money, right? You might find one or two naive people who would consider it, but virtually everyone will look at you like you're a lunatic and ask why they should gamble on their hard-earned life savings to maybe make a buck. Even if they can't explain it with math, they feel the difference in risk in their gut... maybe their gut is right, maybe it's wrong, but the fear is a burden they won't bear if they keep their cash and eschew the debt.

### If the returns were really that good, they wouldn't be for long

There are billions and trillions of dollars invested across the whole market, including in personal loans and mortgages. If investing in the stock market were such a better option, don't you think big-time investors would do that instead of lending you cash for your house?

The reality is that prices (yield rates) in the investments market, include debt rates, are self-regulating. Obvious, easy ways to make money tend to get filled and begin to lose their profit margin. If a widget sells for $10 on one site and $20 on Ebay, people begin to buy widgets from that site and re-sell them on Ebay for a quick buck, until they begin to out-bid each other, account for the cost of inventory, adjust for demand, and cope with a whole host of other considerations. At the end of the day, either the prices will equalize on the two sites or practical considerations will be realized as a standing price difference. (E.g. maybe the first site only sells wholesale by the 10,000, so shipping and order handling is cheaper than selling individual items on Ebay.)

The same holds true for investments. If high yields are available in one market and low yields in another, money will transition between markets and traders will fill in the gap until the yields either equalize or have a good reason for remaining different. For two of the largest and oldest investment markets in the world--debt and capital--there's no good reason to think you can still make an easy buck by buying money in one market and selling it in the other. Even if the math seems complicated or muddled, even if you can't understand the reasons why the difference remains, that doesn't make the difference any less reasonable.

If mutual fund returns are so good at 8-10%, why would anyone loan you money at 4%? If you think you can beat that system, maybe you're the sucker that others are profiting from.
