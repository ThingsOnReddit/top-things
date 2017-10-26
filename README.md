![ThingsOnReddit](https://thingsonreddit.com/static/logo_full.png)

## 📁 Methodology

This is a data dump of the top products (ordered by number of mentions) from every subreddit that has posted an amazon product. The data was extracted from [Google Bigquery's Reddit Comment database](https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_comments). It only extracts Amazon links, so it is certainly a subset of all products posted to Reddit.

The data is organized in a file structure that follows:

```
reddits/<first lowercase letter of subreddit>/<subreddit>.csv
```

An example of where to find the top products for /r/Watches would be:

```
reddits/w/Watches.csv
```

## 📚 Definitions
Below are the column definitions found in each `<subreddit>.csv` file.

#### name
The name of the product as found on Amazon.

#### category
The category of the product as found on Amazon.

#### amazon_link
The link to the product on Amazon.

#### total_mentions
The total number of times that product was found on Reddit.


#### subreddit_mentions
The total number of times that product was found on that subreddit.


## ❤️ Want more?

You can search and discover products more easily on [ThingsOnReddit](https://thingsonreddit.com/)

Feel free to reach out to: ben at thingsonreddit dot com
