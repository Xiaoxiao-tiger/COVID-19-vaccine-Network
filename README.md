# Twitter-Network

## Description

The repository contains 3 databases -- userids of the seeded users, lists of the seeded users' friends, and a built Twitter social network. We use **twint** (a wrapper library for the Twitter API) to crawl tweets containing "COVID-19 vaccine" from 2020-02-11 to 2021-08-01([Tweets](https://github.com/chengluoji/COVID-19-vaccine-Tweets/tree/main)). Then 106,564 seed users are selected from the users who sent tweets, and **twarc** is used to crawl the list of friends of these users. Finally, 17,196 users are randomly selected from the seed users to form Twitter social network.

## Data Organization

The data in the file is as follows:

- Seeduser-ids file contains the userids of 106,564 seed users.
- Friends_list file contains lists of friends of 106,564 seed users.
- Twitter_network file contains the Twitter social network of 17,196 users randomly selected from seed users.


