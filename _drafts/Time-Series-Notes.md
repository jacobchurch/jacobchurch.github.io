---
layout: page
title:  "Time Series Notes"
date:   2018-03-07 07:13:06 -0800
categories: Time-Series Notes UWF
---
# Stuff to note on blog about Time Series

## Plotting

### How to plot a random walk

{% highlight R %}
# create a random variable
w = rnorm(200,0,1)

# create random walk as sum of random variable
x = cumsum(w)

# plot our handiwork
plot.ts(x, main="Random Walk!")
{% endhighlight %}