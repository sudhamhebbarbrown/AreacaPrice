# AreacaPrice
A Data as a Service (DaaS) platform for Karnataka's areacnut prices


Features to be coded:
1. Backend
  1. Web scarping
     1. Scarpe https://www.krishimaratavahini.kar.nic.in/MainPage/ using beautifulsoup
     2. Add it to SQL database
     3. Cron job to do the same
     4. Expose it as an api
  2. GET call (fetch(Market, ToDate, FromDate))
     1. Fetch all data from db from ToDate, FromDate for the selected Market (select * from DB where db.market = "Market" WHERE db.date BETWEEN 'toDate' AND 'endDate';)
     2. Create json objects for the fetched data and send as response
2. Database
     1. Data dump for now (Optimize when polishing)
     2. Market, Date, Variety, Arrivals, Arrivals,Minimum Price,	Maximum Price,	Modal Price
     3. Query builder and queries to make graphs interactive
