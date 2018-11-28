# CloudAnswers Hackathon

Open source hackathon based on the salesforce ecosystem (force.com + heroku).

This is our marketing site, rules, results, etc.

Marketing site template for the CloudAnswers Hackathon.

Based on this theme from cloudcannon:
https://github.com/CloudCannon/hydra-jekyll-template

## How do I participate?

- To register, add your project to the site via pull request
  - Fork the repo on github, add your project in the `./_projects` folder by copying the template and adding your information
  - Preview your work locally using jekyll serve to make sure it looks ok
  - Open a pull request to add your project (we'll merge within a day, as long as the content is complete and abides by the guidelines)
- Hack all December, following the rules: [hackathon.cloudanswers.com/rules](https://hackathon.cloudanswers.com/rules)
- Submit your usage stats and demo video before 2018-12-31T23:59:59.999Z
- Attend the judging webinar (not required)

## Setup

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics and Disqus keys to `_config.yml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Editing

Hydra is already optimised for adding, updating and removing pages, staff, advice, company details and footer elements in CloudCannon.

### Posts

- Add, update or remove a post in the _Posts_ collection.
- The **Staff Author** field links to members in the **Staff** collection.
- Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
- Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

- Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
- Sends email to the address listed in company details.

### Staff

- Reused around the site to save multiple editing locations.
- Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

- Exposed as a data file to give clients better access.
- Set in the _Data_ / _Navigation_ section.

### Footer

- Exposed as a data file to give clients better access.
- Set in the _Data_ / _Footer_ section.
