# The Addison County Community Table

This is the development guide for the Addison County Community Table, an online ordering platform that supports local businesses in Addison County, Vermont. This README file contains the most up-to-date guidance on the current status of the project and how you can contribute to its development.

**Current state: ALPHA TESTING**

_Last updated: August 19, 2020_

## Contributing

We would love for you to contribute to the project—in fact, we need your help! The platform's interface is inconsistent (we cooked up the visual design in a weekend!), it has bugs, and we are generally lacking readable language and user uidance for various parts of the app. Our main developers are spending their time implementing core features, so we have been struggling to find the time to think through what would look nice to users and all the little details that make an application pleasant to use. So in addition to helping us find and eliminate bugs, we welcome your **completely original ideas and work**. We would love for you to draw a sketch of what you think a particular interface should look like so that we can work with you to turn it into reality. You can find all of the specific things we need help with in the issue tracker labeled with the "help wanted" tag. While we can't pay you for your contributions at this point (we don't get paid ourselves), we will deeply appreciate it.

If you have experience developing sofware in Typescript, React, Rails, and/or GraphQL and would like to contribute code please contact Justin Doran at jmdoran@communitytable.market.

## Using the issue tracker

To keep track of your contributions, we use an issue tracker hosted in a GitHub repository. In that repository, you can find the [most recent version of this file](https://github.com/community-table-market/addison-county/blob/master/README.md), which will be updated along with the project. To contribute, you will need to first [create an account on GitHub](https://github.com/join). Once your account is created, confirmed, and you've logged in, you should visit the project's [issue tracker](https://github.com/community-table-market/addison-county/issues). We have set up several [templates](https://github.com/community-table-market/addison-county/issues/new/choose) to help you write your request, but you should also feel free to create an issue from scratch. 

Our goal is to respond to your idea or problem within one working day, but since we're an all-volunteer development shop, please be patient if it takes us a little bit longer to give you feedback. Once you've submitted your question, feature idea, bug report, or other issue, we'll communicate updates with you through the issue's page. GitHub can be set up so that you [receive email notifications](https://docs.github.com/en/github/managing-subscriptions-and-notifications-on-github/configuring-notifications) in addition to their on-site notification system.

This is the preferred way to communicate with the project's developers because it ensures we don't lose track of something.

## The Testing Environment

Our current testing environment can always be accessed at the following URL:

[http://testing.communitytable.market](http://testing.communitytable.market)

The URL forwards directly to a (secure) Heroku instance to avoid conflicts with production, so seeing the URL change is normal. We will periodically transition to new testing servers when there are major structural changes to the app, or if the testing environment's database has been filled up or broken for some reason. **Crucially**, this means that you should not expect anything you input into the testing environment to be permanent. We will try to keep the information you enter into the testing environment as consistent as possible, but it is fundamentally for testing, and so data will be lost periodically.

To make changes to the testing environment, such as creating a mock business or placing an order, you will need to register an account on the platform. We will soon allow you to use your GitHub account to log in to the testing environment, but right now we're still testing our email service, so we'd like you to go through the normal email sign up process. The account you register in the testing environment is relatively secure, but you should **not** re-use a password that you use for other accounts, as we are not regularly auditing the security of the test data. 

The platform requires that you confirm your account via email, so you **must** use a real email address that you have access to. Your account on the testing platform is completely independent from the (eventual) production version of the platform. That means you can use the same email address for both this environment and the (eventually) running website. So feel free to use your primary email address. We won't send you any emails except to manage your account. Note that if the testing environments are cycled, you will have to recreate your account and reconfirm your email. We are currently getting reports that our emails are successfully and immediately delivered on Gmail/G-suites, but Outlook/Office365 accounts are marking them as junk, so please do check that folder after creating an account.

## What we'd like you to focus on

We genuinely appreciate any and all suggestions you have. Currently, we're in the alpha stage of testing. This means we'd like you to test the complete features and give us notes about bugs you experience and how those core features can be improved. You should also feel free to add any and all feature ideas that you can imagine to the issue tracker, as we we will be quickly circling back to them. Once we introduce new, specific features, we'll update this section of the guide to direct your attention to what we're actively focusing on. Just to let you know what's currently happening in this stage implementation, as of _August 19, 2020_ we are currently testing and debugging (so please look at these!) the following (working) features:

- Ordering items from an existing restaurant business
- Processing orders from the restaurant's perspective
- Monitoring an order's status from a customer's perspective
- Updating an order's status from a restaurant manager's perspective
- Accepting credit card transactions

We are actively implementing the following (not quite working) features:
- Dynamic addresses for businesses
- General open hours for restaurants and specific availability hours for menus
- Better order histories for businesses and users
- Adding third-party delivery to the ordering process
- Adding third-party distribution points to the ordering process

## Thank you

We absolutely could not do this without support from the community. We appreciate any time, effort, thoughts, or experiences you share with us.
