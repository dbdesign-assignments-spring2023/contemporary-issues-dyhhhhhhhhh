# Different view points of centralized data
In this document, I discuss two opposing articles of centralized database by presenting two viewpoints in each of them. "Centralized" brings both pros and cons.

## article1
In Jenn Daugherty's [Why Centralize Data](https://mode.com/blog/why-centralize-data/), she presents advantages of centralized data.

First, centralizing data helps improve data culture. Providing a single source of truth for the data will both reduce costly errors and improve the integrity of the data, both literally and in the minds of team members. Businesses thrive when teams trust the data they use. Well-curated data sets and organized reports instill confidence in users less familiar with the data, providing them with a starting point for preliminary analysis that data team members can delve into.

Then, centralized data dramatically reduces the cost of running a business. Bad data can be expensive and may come from inaccurate reports, out-of-date analytics, poorly configured KPIs, or data that is not synchronized to the data warehouse. The impact of bad data can prevent a company from achieving very real or much-needed growth. There may be lost revenue, ineffective promotions, increased attrition rates, and reduced sales size - all from "bad" or scattered data. Modern data stacks built around a centralized data team can reduce costs. Having a platform simplifies your data stack while consolidating the entire ecosystem of applications used to run the business.

## article2
On the contrary, Lee Atchison shows different idea of centralized data in his article [3 reasons centralizing your data is a bad idea](https://www.infoworld.com/article/3622240/3-reasons-centralizing-your-data-is-a-bad-idea.html).

Centralized data is difficult to scale. When the data for the entire application resides in a centralized data store, as the application grows, the entire data store must be scaled to meet the needs of all the services in the application. If each service uses a separate data store, only the service with increased demand needs to be scaled, and the database being scaled is a smaller database. It is much easier to scale up a small database than it is to scale up a large database.

Another problem is that it is difficult to partition the centralized data later. It is often important to divide a data store into smaller data stores. However, it is much easier to do this when the application is first created than later in the application lifecycle. When an application has existed for a long time, and all parts of the application have access to all parts of the data, it can be difficult to determine which parts of the dataset can be split into Independent data storage.



