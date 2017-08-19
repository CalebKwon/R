## Generate two data sets
## First Normal, second from a t-distribution
words1 = rnorm(100); words2 = rt(100, df=3)

## Have a look at the densities
plot(density(words1));plot(density(words2))

## Perform the test
shapiro.test(words1); shapiro.test(words2)

## Plot using a qqplot
qqnorm(words1);qqline(words1, col = 2)
qqnorm(words2);qqline(words2, col = 2)
