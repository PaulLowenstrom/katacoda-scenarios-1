Let's start with the t-statistic, also known as a t-test. It is basically a measure of the difference in behavior between these two sets, between your control and treatment group, expressed in units of standard error. It is based on standard error, which accounts for the variance inherent in the data itself, so by normalizing everything by that standard error, we get some measure of the change in behavior between these two groups that takes that variance into account.

The way to interpret a t-statistic is that a high t-value means there's probably a real difference between these two sets, whereas a low t-value means not so much difference. You have to decide what's a threshold that you're willing to accept? The sign of the t-statistic will tell you if it's a positive or negative change.

If you're comparing your control to your treatment group and you end up with a negative t-statistic, that implies that this is a bad change. You ultimate want the absolute value of that t-statistic to be large. How large a value of t-statistic is considered large? Well, that's debatable. We'll look at some examples shortly.

Now, this does assume that you have a normal distribution of behavior, and when we're talking about things like the amount people spend on a website, that's usually a decent assumption. There does tend to be a normal distribution of how much people spend.

However, there are more refined versions of t-statistics that you might want to look at for other specific situations. For example, there's something called Fisher's exact test for when you're talking about click through rates, the E-test when you're talking about transactions per user, like how many web pages do they see, and the chi-squared test, which is often relevant for when you're looking at order quantities. Sometimes you'll want to look at all of these statistics for a given experiment, and choose the one that actually fits what you're trying to do the best.