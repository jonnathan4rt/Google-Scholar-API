# Google-Scholar-API


Our Google Scholar API allows you to scrape SERP results from a Google Scholar search query. The API is accessed through the following endpoint: /search?engine=google_scholar.

A user may query the following: https://serpapi.com/search?engine=google_scholar utilizing a GET request. Head to the playground for a live and interactive demo.

Advanced Google Scholar Parameters
cites

Optional

Parameter defines unique ID for an article to trigger Cited By searches. Usage of cites will bring up a list of citing documents in Google Scholar. Example value: cites=1275980731835430123. Usage of cites and q parameters triggers search within citing articles.

as_ylo

Optional

Parameter defines the year from which you want the results to be included. (e.g. if you set as_ylo parameter to the year 2018, the results before that year will be omitted.). This parameter can be combined with the as_yhi parameter.

as_yhi

Optional

Parameter defines the year until which you want the results to be included. (e.g. if you set as_yhi parameter to the year 2018, the results after that year will be omitted.). This parameter can be combined with the as_ylo parameter.

scisbd

Optional

Parameter defines articles added in the last year, sorted by date. It can be set to 1 to include only abstracts, or 2 to include everything. The default value is 0 which means that the articles are sorted by relevance.

cluster

Optional

Parameter defines unique ID for an article to trigger All Versions searches. Example value: cluster=1275980731835430123. Usage of cluster together with q and cites parameters is prohibited. Use cluster parameter only.
