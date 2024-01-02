---
layout: post
title:  "Data warehouse migration"
date:   2022-10-22 19:11:06 -0500
categories: big data
---

The dbt course with [CoRise] is coming to a close, I learned a lot and feel more confident with dbt. I enjoyed the hands-on approach. Thank you, Jake Hannan, for all your help.

After the great news about my contract, I am happy to share that I have started transitioning to the analytics team. I will be helping as a data analyst, officially beginning in January.

Between now and then, I will continue to work on competitions as they move to a different department. 

It is super exciting and scary. Everyone is so good at what they do. 

The first project I will be helping between now and my official start is a transition from AWS Redshift to GCP [BigQuery]. We have to adapt about 1,200 queries to the SQL dialect that BQ uses, which is mostly the same but slightly different from what RS uses. 

There are some crucial differences, for example, how they handle JSON fields and arrays, date functions, etc. BQ has some cool new things like Qualify, but there are also some annoying things, like how it handles aliases. 

Overall, it is a step forward for the company; BigQuery will give us better performance at a lower cost. And I am so excited to be part of this. Now, I have to level up in SQL to be a productive analytics team member.

#### It is very humbling to be the worst member of the team. But you have to start somewhere...

[CoRise]: https://corise.com/course/analytics-engineering-with-dbt
[BigQuery]: https://cloud.google.com/bigquery