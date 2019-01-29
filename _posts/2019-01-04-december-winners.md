---
date: 2019-01-04
title: December Hackathon Winners!
categories:
  - announcements
author_staff_member: paul_fox
---

The December hackathon was our first month long hackathon. Given the business of the end of the year, we thought people could use some extra time to create some amazing applications. And although many people were still scrambling to finish up their apps before the demo round, we saw many amazing demos. Without further ado, here are the winners:

# First Place: James Sullivan, Org Health Check

James took first place with a comprehensive and super simple way to monitor changes to a Salesforce org. Using Amazon and JSforce, James created an app that anyone can sign up for in just a few seconds.

<img src="/images/winners/dec-2018-db-saver-website.png" style="max-width:100%; height:auto;">

After they’ve given permission the app to login to their Salesforce org, the app will login on a daily basis, run a variety of tests, and email the admin with important information about the security of their org.

Some of the various things that it monitors:

Where people are logging in from (to detect unexpected locations)
Newly installed apps (to monitor for unexpected installs)
Unit test failures (in case configuration changes broke your code)

# Second Place: Avinava Maiti, Smart Alerts

In a very close second, Avinava created a system for admins to create record alerts for their users. Some times, a validation rule is just too much, and you want to allow people to save the record but still get a warning of sorts. Well, with Smart Alerts you can setup formulas that display warnings to the users, like when they don’t have a Next Step on an Opportunity or don’t have a phone number for a Contact.

<img src="/images/winners/dec-2018-smart-alerts.png" style="max-width:100%; height:auto;">

Using a custom object and a lightning component, Avinava built a system that will use lightning data service to evaluate formulas and display alerts to the user. The system is fully customizable and works on any object with a little bit of setup.
