# README

A party entry looks like this - stances are ranked from 1-5 or unknown.
```
      {
          "id": "party-1",
          "name": "Party Name"
          "country": "Country",
          "eu_affiliation": "EU Party",
          "stances": {
              "Reduce Regulatory Burden": "3",
              "European Inc": "unknown",
              "Tax Discounts": "unknown",
              "Embrace AI": "unknown",
              "Reform Bankruptcy Laws": "unknown",
              "Teach AI": "unknown"
          },
          "metadata": {
              "description": "Description of the Party",
              "website": "Weblink to the party homepage"
          },
          "sources": {
            "Reduce Regulatory Burden": [
                {
                    "source_title": "Short title of the source",
                    "url": "Link to the source"
                }
            ]
          }
      },
```

If you'd like to use this data in your app, you can query http://backend.euaccel.xyz/data

