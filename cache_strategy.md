
## Read-Through Cache

> Read-through cache sits in-line with the database. When there is a cache miss, it loads missing data from database, populates the cache and returns it to the application.


## Write-Through Cache
> In this write strategy, data is first written to the cache and then to the database. The cache sits in-line with the database and writes always go through the cache to the main database.


## Write-Around
> Here, data is written directly to the database and only the data that is read makes it way into the cache.
