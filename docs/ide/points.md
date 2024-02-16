---
sidebar_position: 11
---

# Points

At Bitquery we use points system to calculate the cost for a query. Each query will use different number of points, based on the complexity and size of the query requested.  For a comprehensive understanding of the points system, please refer to [our detailed post](https://community.bitquery.io/t/introducing-points/874).

Get started for free with the developer plan and use up to 100K points renewed every month.
For every query you run, you can check the points in real time.

![points](/img/ide/points.png)

Different plans have different limits for points available. You can always request a custom top-up of points by directly contacting us.

Check pricing [here](https://bitquery.io/pricing)


## How are points calculated?

The number of points can vary for various reasons. Even the same query can produce different results. These points are dynamically calculated based on the following factors:

- The quantity of records being queried, either through the count of records in limit or the date range.
- The level of complexity of the query.

For instance, if you include additional addresses, the points will be calculated considering the resources occupied by those addresses. To optimize this query, there are a few approaches you can consider. Firstly, narrowing down the date range can help to refine the results. Secondly, reducing the list of addresses may also be beneficial. However, the effectiveness of these strategies will depend on your specific goal.


## How do you check points for your account?

You can check points consumed under your [account](https://account.bitquery.io/user/statistics). 

![points_in_account](/img/ide/points_in_account.png)

