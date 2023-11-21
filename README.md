Hey,

You can consider my team "PoeScience" as disqualified. I can see what I have to do, I can see how I can likely do it. But health issues prevent me from actually doing it.

What I would have done is:
1. Use the dependency table guides here to retrieve data for the relevant PsrTypes for each country. Get data from 1st of  January 2022 to 1st of January 2023, maybe get it as XML viles via Postman, since the range is realised/fixed already. or via the API directly. https://transparency.entsoe.eu/content/static_content/download?path=/Static%20content/web%20api/RestfulAPI_IG.pdf

For example the data could be retrieved using the link: https://web-api.tp.entsoe.eu/api?securityToken=fb81432a-3853-4c30-a105-117c86a433ca&documentType=A75&processType=A16&in_Domain=10YCZ-CEPS-----N&periodStart=202212312300&periodEnd=202301012300 or similar.

2. Standardize the data so each data type has 1 hour intervals. Where data is missing use the average between the two surrounding nearest dates or a similar mitigation strategy.

3. Use ML.NETs templates that among others allow forecasting based on series of data that is bound up on dates. ML.NET would then be able to give the right answer based on data put into SQL tables or data that had been put together in one common .CSV or .TXT file. And would be able to help forecast future hourly surplus levels of energy. ML.NET would also be able to suggest which model is likely the best one to use for prediction based on the data types. Alternatively, instead of ML.NET, use PyTorch.

I was hoping I would feel better this morning and perhaps be able to make an entry in time. But I dont think I will.

I wish you all great luck and continued fun with the hackathon.

Cheers.

# SE-Europe-Data_Challenge_Template
Template repository to work with for the NUWE - Schneider Electric European Data Science Challenge in November 2023.
