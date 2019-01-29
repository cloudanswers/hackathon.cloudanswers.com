---
title: Participate
heading: Join our open source hackathon!
description: 💻🍕💻🍕💻🍕💻🍕💻🍕💻
faq:
  - question: Are teams allowed?  Can I do it solo?
    answer: You are welcome to work in teams, although most of us compete solo.
  - question: What country do I need to reside in?
    answer: We are not limiting this to any specific countries
  - question: How will payment work?
    answer: We will use PayPal, wire transfer, or any other popular means of funds transfer
  - question: Who is sponsoring this?
    answer: A small consulting group named <a href="https://www.cloudanswers.com">CloudAnswers.com</a>
---

<strong>TLDR: Open source, online (participate anywhere) hackathon focused on making salesforce.com apps.</strong>

# Rules

- Projects must be related to the Salesforce ecosystem, but do not have to be built entirely on Salesforce technology. During your demos, make sure to explain the Salesforce technologies used in your app.
- Participants must demo their finished solution during the Judging Webinar. You will have 4-6 minutes to share your screen and demo your app.
- Projects must be **open source** on Github where we can validate that commits are happening throughout the project. _This does not mean you can't charge for it._ Your license can be a pervasive license or with an added an exception that no one can use your code for commercial purposes without your permission.
- All code related to the app must be written between the Start and End times, unless you are using code that is open source and publicly available prior to the hackathon. 

# Next Hackathon

- **Start** February 7, 2018 10:00 AM EST

- **Finish** February 8, 2018 10:00 AM EST

- **Judging Webinar** February 8, 2018 10:00 AM EST - 12:00 PM EST (At least one team member _must_ be present to demo your app!)

# Judging

Judging will be done by a panel that has extensive experience in the salesforce.com community. Scores will be based on the weighted average of the judges scores in the following areas:

  - **25%** originality: please don't make a slightly better de-dupe tool. Lets see some creativity.

  - **25%** tech chops: are you a true hacker? 

  - **25%** polish: is it easy to understand and use, or does it have errors everywhere?

  - **25%** business viability: would people use this app? Would they pay for it?

At the end of the judging webinar, the judges will submit their scores, take a brief moment to deliberate and discuss adherence to rules, and then the winners will be announced live!

# How to Join

1. Create an account on github.com if you don't have one already

2. Fork this project site: [https://github.com/cloudanswers/hackathon.cloudanswers.com](https://github.com/cloudanswers/hackathon.cloudanswers.com)

3. Add your project to the projects page by copying the file `./_projects/example.md` to your own project name (eg `my_cool_proj.md`). Commit and open a pull request. 

4. Start planning your app. At the official start time, begin coding.

If you're not familiar with Github we recorded this brief video of the whole process: <Br/>
[https://drive.google.com/file/d/12q6vO5khv2eFSGeWZcDqvKhLR7s5oZoQ/view](https://drive.google.com/file/d/12q6vO5khv2eFSGeWZcDqvKhLR7s5oZoQ/view)

{% if page.faq %}

# FAQ

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
