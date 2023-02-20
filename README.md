# Wut?

It's a small JSON file listing couriers along with their typical tracking number formats. It also has a Track123 courier code which can be helpful if you are working with Track123 API to get delivery statuses.

# Why?

The file was created for my app, but I thought it might be useful for others as well. Getting some community input is welcome, just introduce changes in the courier_matcher.json and send a pull request.

The idea for creating this repository actually came from ChatGPT. When I asked it for a resource of this kind, it hallucinated a mythical GitHub repository:

```md
The "Shipping Carrier Lookup" repository on GitHub is a community-maintained dataset of shipping carrier names and tracking number formats. The dataset contains a CSV file with over 1,100 rows, each representing a unique tracking number format and associated carrier name.

The dataset is organized into several columns, including "Carrier Name", "Abbreviation", "Tracking Number Format", and "Example Tracking Number". The tracking number formats are listed in regular expression format, which can be used to match against a given tracking number and determine the associated carrier.

The repository is open source and can be accessed by anyone with a GitHub account. It is maintained by a community of contributors, who add new tracking number formats and carrier names as they become available.

The original author of the repository is not explicitly listed, as the dataset has been contributed to by multiple users over time. However, the repository was created in 2014 and has been updated regularly since then, suggesting that it has been a useful resource for many developers and businesses over the years.
```

# How?

Ideally I would like to add a separate field with RegEx to match couriers by tracking number, but for now it's just a list of typical formats. If you have a better idea, please let me know.
