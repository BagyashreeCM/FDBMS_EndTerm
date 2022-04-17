# Amazon Co-purchase NetworkAnalysis
Network was collected by crawling the Amazon website. It is based on Customers Who Bought This Item Also Bought feature of the Amazon website. If a product i is frequently co-purchased with product j, the graph contains an undirected edge from i to j. Each product category provided by Amazon defines each ground-truth community.

![Filtered Graph](https://github.com/ArunitaYen/NetworkAnalysis/blob/main/Network%20Analysis%20Amazon%20Co-purchase/Filtered%20Graph.PNG)

The filtered graph suggests that the dataset has many items that are bought frequently, and the item bought along with those items, are random and are not strongly connected. There are 130 different communities and filtering them suggests the top six communities are also not bonded strongly enough

## Largest nodes in dataset
![largest dataset](https://github.com/ArunitaYen/NetworkAnalysis/blob/main/Network%20Analysis%20Amazon%20Co-purchase/Largest%20Node.PNG)

[Link to dataset](https://snap.stanford.edu/data/com-Amazon.html)
