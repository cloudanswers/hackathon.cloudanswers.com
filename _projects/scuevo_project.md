---
title: Multi Line Input Tables with LWC
platform: Force.com
image_path: /images/project_logos/sean-headshot.jpg
repo: /seanpat09/dynamicFieldsLWC
blurb: A dynamic multi line input form using Salesforce's new Lightning Web Components
---

Something I have built over and over again is a multi-line input table for an arbitrary number of columns where you can add and remove rows. This is particularly tricky when your columns are not necessarily SObject fields and even more so when they are not statically defined. You can kind of do this in aura, but the lack of dynamic field binding forces you to build some hacky work arounds that I was never a fan of. With the release of Lightning Web Components, this is a good opportunity to try building this again to see if it can be done better and as a way of exploring the nuances of the new framework. When completed, you should be able to just reference `<c-multi-edit-table>` and never have to build this input again!
