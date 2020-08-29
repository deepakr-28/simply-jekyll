---
title: Amazon Vs. Flipkart - Finding the Best Prices for Books!
tags: Data Analysis
comments: true
---


Amazon or Flipkart? The age old question for us lazy people who cannot be bothered to compare prices. You’re probably wondering why this even concerns you. On the surface, it seems like there probably won’t be much of a difference but it goes much deeper. In fact, on delving into the data the difference becomes pretty significant in our daily lives of online shopping.

## The data gathering hustle.

After creating two scrappers and bypassing all the hurdles to gather data on thousands of books on Amazon on Flipkart into a CSV, with the help of a few friends. We had enough information on rating, price, the author etc. We took the common books out joined the two Tables and we used the ISBN number of the particular book to join. We calculated the price difference relative to the Flipkart price and we calculated the price percentage difference from the Flipkart price. We ended up with a statistically acceptable sample of 800 books which looked like this:

![The cleaned CSV table.](https://cdn-images-1.medium.com/max/2056/1*brNWXz3A-_DiuWlotmnkVA.png)*The cleaned CSV table.*

### Some Boring Prerequisites

You wouldn’t be the first person to have a personal favourite e-commerce site when it comes to shopping. Be it due to your own preference, platform benefits, what your colleague recommended you to use or due to any conspiracy theory that you read on Reddit.

We see the distribution of the prices on the two websites in the given plot. We can see that there are some very distinct patterns starting with the spike at the price Rs. 100.

![Price distribution of the books on Amazon and Flipkart.](https://cdn-images-1.medium.com/max/2000/1*F71ndn5BQYSmIwxduBOUYA.png)*Price distribution of the books on Amazon and Flipkart.*

After doing some basic calculations, if you stuck to Flipkart for buying your books, it’d cost you around *Rs. 190490*. On the other hand, if you used only Amazon it’d cost you *Rs. 187355*.

You definitely won’t be able to afford a new BMW anytime soon by sticking to any one of the sites. So let’s proceed and do some cool analysis.

And like an untouched crime scene, I dived into the raw, mystery-ridden data to uncover some mysteries.

## Analysis

Let’s start out by looking at the best and worst case scenarios. If I only bought books from the cheaper option out of Amazon and Flipkart it would cost me *Rs 1,77,017*. In the worst case, where I only bought the more expensive option it would cost me a staggering *Rs 2,11,797*. That’s a difference of Rs 34,780 or 16%. Not a small amount! With that money, you could buy the whole Harry Potter set 16 times. Now that’s some BMW amount of money.

### Let’s compare the Prices.

![](https://cdn-images-1.medium.com/max/2000/1*p9mnqfOO1qKU_XKUNRhYnQ.png)

At a glance, we can see that about 25% of the books are priced almost the same.

By looking at the distribution of the prices we can see that the proportion of positive percentages increases to the right. Which means compared to Flipkart, about 20% of the books are priced cheaper at Amazon.

Let’s go ahead and take a quick glance at the data of books worth less than Rs 500 to see if the pattern holds up. It clearly reveals that for books that are cheaper, Amazon still holds the advantage.

![](https://cdn-images-1.medium.com/max/2000/1*clk_-hn2D0ix5qr2NcZrAw.png)

As the books get more expensive, that is more than Rs 500 the pattern still holds up and Amazon wins.

![](https://cdn-images-1.medium.com/max/2000/1*pB1rDKjuwc7ui1uAC34f5Q.png)

## Yo, your mind’s still not made up?

Let’s do one more analysis to make up your mind.

My friend, Dr Doe, only shops on Amazon whereas I prefer Flipkart for whatever reason. Let’s see how Dr Doe would fare if he bought all the 713 books in question from Amazon. Amazon has better pricing 45% of the time compared to Flipkart and Dr Doe would be overpaying compared to our best case cart by only 6%. On the other hand, I, after buying the whole cart from Flipkart would get better pricing only 30% of the time and I would end up overpaying by 8%.

Well you gotta agree, it’d be hard to beat Amazon pricing on books cause our favourite E-commerce marketplace started by selling books.

## Conclusion

Moving on (finally) to the actual point of all of this, deciding which site you should actually use. Well, here it seems Dr Doe has the advantage for books. That is Amazon. Overall the best idea is to check and compare both sites to get the best deal.

***But if you’re too lazy to compare and buy books, you could stick to Amazon all the time and they’ll provide the better or equally good deal 70% of the time compared to Flipkart.***

## **Project Details**

Talking about price comparison of books, I was inspired to do this analysis after seeing Chase’ wonderful and informative [post](https://unlooted.com/blog/amazon_v_ebay/) on comparing prices of Amazon Vs. eBay. But in that case you don’t have to do the manual comparison, his extension Unlooted does that for you, so definitely check it out if you’re from the US.

A huge shoutout to my juniors [Corruption13](https://github.com/Corruption13), [pranavmodx](https://github.com/pranavmodx), [Afnan-Navaz](https://github.com/Afnan-Navaz) and [voxetmohita](https://github.com/voxetmohita) for lending me a hand in this project! You guys rock!

You can find the [kernel](https://www.kaggle.com/mandan/who-is-ripping-you-off) and the [dataset](https://www.kaggle.com/mandan/amazon-vs-flipkart-book-prices) that I did the analysis on Kaggle. Feel free to go through and experiment on it.

The [scrapper](https://github.com/isht3/Book-Theifs) story probably needs a blog-post of its own. We gathered about 50,000 books but we couldn’t join them together due to some technical hitches due to the ISBN.

Please share if you have any cool ideas for data analysis, I’d love to hear your thoughts!
