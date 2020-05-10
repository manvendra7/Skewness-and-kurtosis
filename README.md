# Skewness-and-kurtosis## WHY DO WE CARE SO MUCH ABOUT NORAMLITY ?

---

Most of the paramteric machine learning models like LDA, Linear Regression and amy more assume that the data is normally distributed. If this assumption fails the model fails to give accurate predictions.

## WHAT IS NORMAL DISTRIBUTION ?
A probability distribution with the mean 0 and standard deviation of 1 is known as standard normal distribution or Gaussian distribution. A normal distibution is **symmetric** about the mean and follows a **bell shaped curve** . And almost 99.7% of the values lies within 3 standard deviation. The mean, median and mode of a normal distribution are equal.

---

## SKEWNESS

### WHAT IS SKEWNESS ?
Skewness of a distribution is defined as the lack of symmetry. In a symmetrical distribution, the Mean, Meadian and Mode are equal.The normal distribution has a skewness of 0.


Skewness tell us about distribution of our data.


<a href="https://imgur.com/6SH4wau.png"><img src="https://imgur.com/6SH4wau.png" title="source: imgur.com" /></a>

### Skewness is of two types:

* **Positive skewness:** When the tail on the right side of the distribution is longer or fatter, we say the data is positively skewed. For a positive skewness mean > median > mode.   

* **Negative skewness:** When the tail on the left side of the distribution is longer or fatter, we say that the distribution is negatively skewed. For a negative skewness mean < median < mode.
---

### What does skewness tells us?
To understand this better consider a example.

Consider house prices ranging from 100k to 1,000,000 with the average being 500,000. 

If the peak of the distribution is in left side that means our data is positively skewed and most of the houses are being sold at the price less than the average.  

If the peak of the distribution is in right side that means our data is negatively skewed and most of the houses are being sold at the price greater than the average.

Now, the question is when we can say our data is mderately skewed or heavily skewed?
  
  The thumb rule is:
  If the skewness is between -0.5 to +0.5 then we can say data is fairly symmetrical.
  If the skewness is between -1 to -0.5 or 0.5 to 1 then data is moderately skewed.
  And if the skewness is less than -1 and greater than +1 then our data is heavily skewed.


---



---

## KURTOSIS

You might have heard that kurtosis tells us about the shape or peakedness or flatness of the distribution but this is not correct. Kurtosis tell us about the tails behaviour. It is actually the measure of outliers present in the distribution. 

<a href="https://imgur.com/7FuwfAK.png"><img src="https://imgur.com/7FuwfAK.png" title="source: imgur.com" /></a>



### Kurtosis are of three types:

* **Mesokurtic:** When the tails of the distibution is similar to the normal distribution then it is mesokurtic. The kutosis for normal distibution is 3.

* **Leptokurtic:** If the kurtosis is greater than 3 then it is leptokurtic. In this case, the tails will be heaviour than the normal distribution which means lots of outliers are present in the data. It can be recognized as thin bell shaped distribution with peak higher than normal distribution.

* **Platykurtic:** Kurtosis will be less than 3 which implies thinner tail or lack of outliers than normal distribution.In case of platykurtic, bell shaped distribution will be broader and peak will be lower than the mesokurtic.


---



---

## HOW TO DEAL WITH SKEWNESS AND KURTOSIS ?

* Square root transformation.
* Cube root transformation.
* Log transformations.
* Box-cox transformations.

## LICENSE

Dataset : Ames Housing Datset

Licensed under gpl-2

Paper - http://jse.amstat.org/v19n3/decock.pdf

