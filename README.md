# Aerial Intelligence Software Exercise

## The project

Staying up to date on weather is crucial to the agricultural community. For this project, we want to know how much it's raining in areas that grow soybean.

Your mission:

**Create a service that shows today's total rainfall for counties that produce a lot of soybeans. The user can choose a state to filter the results.**

The user interface is completely up to you! Be as creative as you like.

## Working on the project

### Data sources

You can get soybean production statistics from the USDA QuickStats service. For convenience, here's a URL that will return a JSON dump of all soybean production for 2015 by county. You can change `agg_level_desc=COUNTY` to `agg_level_desc=STATE` to get state level data.

[http://quickstats.nass.usda.gov/api/api_GET/?key=657A7402-DF3A-3C12-A7D6-FFCC1DDE180D&format=json&year=2015&commodity_desc=SOYBEANS&statisticcat_desc=PRODUCTION&agg_level_desc=COUNTY&unit_desc=BU&prodn_practice_desc=ALL PRODUCTION PRACTICES&reference_period_desc=YEAR](http://quickstats.nass.usda.gov/api/api_GET/?key=657A7402-DF3A-3C12-A7D6-FFCC1DDE180D&format=json&year=2015&commodity_desc=SOYBEANS&statisticcat_desc=PRODUCTION&agg_level_desc=COUNTY&unit_desc=BU&prodn_practice_desc=ALL PRODUCTION PRACTICES&reference_period_desc=YEAR)

You can get real-time weather data from several weather providers. For example, Forecast.io ([https://developer.forecast.io/]()) provides a JSON API and a free trial.

### Focus

You can choose to focus on the front-end, back-end, or build the entire stack. Depending on your focus, here's what we're looking for.

- **Front-end**: A polished front-end with minimal back-end (e.g. static JSON data file or using the data services directly).

- **Back-end**: A well-documented API server with a minimal front-end (e.g. static documentation or README)

- **Full stack**: A front-end UI that pulls data from a backend API server.

Please let us know in your `README.md` what you chose to focus on.

### Stack

You're free to choose whatever technology stack and boilerplate template you want for this project. Please mention this decision in your `README.md`, and let us know how comfortable you are with the stack you chose. If you used boilerplate, please point out what you wrote versus what came with the boilerplate.

## What we're looking for

We want to learn how you approach problems, how you prioritize engineering tasks, how you make tradeoffs, and how you communicate that thought process to others.

We want to know what you consider *minimally shippable* code. *Minimally shippable* does not necessarily mean throwing something together as quickly as possible, or creating a shining example of programming perfection. Instead, we'd like you to decide what tradeoffs you need to make in order to build something quickly while keeping future iteration in mind.

It's okay to leave things out if they don't meet your standards - just let us know in your `README.md`.

### Readme

Please include a README detailing:

- A brief description of the problem and how you chose to solve it.
- Your focus for this project (front-end, back-end, full stack)
- Technical choices you made during the project
- What challenges, tradeoffs, or compromises did you face during the project?
- What did you learn along the way?
- If you had more time, what would you improve? What would you tackle first?

We care about your thought process and your engineering prowess. The better we can understand how you approached the problem, the better we can review your project. Here are a few questions we'll consider:

- **Can we understand your thought process?** Does your `README.md` clearly and concisely describe the problem, your solution, and what you did to achieve it? Does your project do what the `README.md` says it does?

- **Can we understand your priorities and tradeoffs?** If your tradeoffs aren't intuitive, do you explain your rationale?

- **Can we understand your code?** Is your code clean, consistent, and concise? Does it follow good practices? Is it easy to build and host locally?

- **Can we understand your technical choices?** If your choices aren't intuitive, do you explain your rationale?

- **Is your project intuitive to use?** If you built a front-end, is it easy to understand and use? If you built a back-end, is the API intuitive? If not, why?

Here are some questions that will get you bonus points:

- **How would you address scalability?**

- **Is your project robust?** What's the test coverage like? Does it include good error handling?

### Submitting

Please create a Git repository somewhere (e.g. GitHub, BitBucket, Gitlab) and send us the link. If you'd like, host your finished project somewhere we can take a look at it (e.g. Azure, AWS, Heroku).
