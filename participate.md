---
title: Participate
heading: Join our open source hackathon!
description: 💻🍕💻🍕💻🍕💻🍕💻🍕💻
faq:
  - question: Are teams allowed?  Can I do it solo?
    answer: We are judging the *project* as the end product
  - question: What country do I need to reside in?
    answer: We are not limiting this to any specific countries
  - question: How will payment work?
    answer: We will use PayPal, wire transfer, or any other popular means of funds transfer
  - question: Who is sponsoring this?
    answer: a small consulting group named <a href="https://www.cloudanswers.com">CloudAnswers.com</a>
---

# Timeframe

- **Start** December 1, 2018

- **Finish** December 31, 2018

- **Judging Webinar** January 2, 2018

# Grading:

- **50%** number of beta customers (production orgs as active users)

- **50%** MVP judging panel

  - **16.5%** tech chops: are you a true hacker?

  - **16.5%** polish: no, not 🇵🇱, the other kind

  - **16.5%** business viability: is this a real product

# Open Source:

Projects must be **open source** on Github where we can validate that commits are happening throughout the project. _This does not mean you can't charge for it._ Your license can be a pervasive license or with an added an exception that no one can use your code for commercial purposes without your permission.

{% if page.faq %}

# Getting Started

1. Create an account on github

2. Fork this project site: https://github.com/cloudanswers/hackathon.cloudanswers.com

3. Add your project to the projects page and open a pull request. Copy the file `./_projects/example.md` to your own project name. Commit and open a pull request.

4. Hack and get users ~ we'll get in touch with how to share user counts in an honest way for judging.

# Participation FAQ

<dl class="faq">
  {% for item in page.faq %}
  <div>
    <dt>{{ item.question }}</dt>
    <dd>{{ item.answer }}</dd>
  </div>
  {% endfor %}
</dl>
{% endif %}

# Help, my question wasn't answered!

Submit an issue on our [GitHub issues page (click here)](https://github.com/cloudanswers/hackathon.cloudanswers.com/issues) or send an email to hackathon(at)cloudanswers.com
