Next, we're going to talk a little bit about data warehousing. This is a field that's really been upended recently by the advent of Hadoop, and some big data techniques and cloud computing. So, a lot of big buzz words there, but concepts that are important for you to understand.

Let's dive in and explore these concepts! Let's talk about ELT and ETL, and data warehousing in general. This is more of a concept, as opposed to a specific practical technique, so we're going to talk about it conceptually. But, it is something that's likely to come up in the setting of a job interview. So, let's make sure you understand these concepts.

We'll start by talking about data warehousing in general. What is a data warehouse? Well, it's basically a giant database that contains information from many different sources and ties them together for you. For example, maybe you work at a big ecommerce company and they might have an ordering system that feeds information about the stuff people bought into your data warehouse.

You might also have information from web server logs that get ingested into the data warehouse. This would allow you to tie together browsing information on the website with what people ultimately ordered for example. Maybe you could also tie in information from your customer service systems, and measure if there's a relationship between browsing behavior and how happy the customers are at the end of the day.

A data warehouse has the challenge of taking data from many different sources, transforming them into some sort of schema that allows us to query these different data sources simultaneously, and it lets us make insights, through data analysis. So, large corporations and organizations have this sort of thing pretty commonly. We're going into the concept of big data here. You can have a giant Oracle database, for example, that contains all this stuff and maybe it's partitioned in some way, and replicated and it has all sorts of complexity. You can just query that through SQL, structured query language, or, through graphical tools, like Tableau which is a very popular one these days. That's what a data analyst does, they query large datasets using stuff like Tableau.

That's kind of the difference between a data analyst and a data scientist. You might be actually writing code to perform more advanced techniques on data that border on AI, as opposed to just using tools to extract graphs and relationships out of a data warehouse. It's a very complicated problem. At Amazon, we had an entire department for data warehousing that took care of this stuff full time, and they never had enough people, I can tell you that; it's a big job!

You know, there are a lot of challenges in doing data warehousing. One is data normalization: so, you have to figure out how do all the fields in these different data sources actually relate to each other? How do I actually make sure that a column in one data source is comparable to a column from another data source and has the same set of data, at the same scale, using the same terminology? How do I deal with missing data? How do I deal with corrupt data or data from outliers, or from robots and things like that? These are all very big challenges. Maintaining those data feeds is also a very big problem.

A lot can go wrong when you're importing all this information into your data warehouse, especially when you have a very large transformation that needs to happen to take the raw data, saved from web logs, into an actual structured database table that can be imported into your data warehouse. Scaling also can get tricky when you're dealing with a monolithic data warehouse. Eventually, your data will get so large that those transformations themselves start to become a problem. This starts to get into the whole topic of ELT versus ETL thing.

