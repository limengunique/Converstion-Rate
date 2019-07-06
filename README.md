# Converstion-Rate
## Goal
Increase website conversion rate (# conversions / total sessions) of registered users. To acheive that, I need to:
- build a model to predict user conversion rate
- Provide insights to product/market team to increase user conversion rate
## Backgroud
Dataset contains information about users who hit our site: whether they converted or not as well as some of their characteristics such as their country, the marketing channel, their age, whether they are repeat users and the number of pages visited during that session (as a proxy for site activity/time spent on site).
## Data
- country : user country based on the IP address
- age : user age. Self-reported at sign-in step
- new_user : whether the user created the account during this session or had already an account and simply came back to the site
- source : marketing channel source
           -          Ads: came to the site by clicking on an advertisement
           -          Seo: came to the site by clicking on search results
           -          Direct: came to the site by directly typing the URL on the browser
- total_pages_visited: number of total pages visited during the session. This is a proxy for time spent on site and engagement during the session.
- converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything. 

