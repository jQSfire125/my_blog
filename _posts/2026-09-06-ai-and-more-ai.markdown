---
layout: post
title: "AI and more AI"
date: 2026-09-06 18:34:58 -0500
categories: update
---

In April, I wrote about how much AI was changing my work. Reading that post now, it is incredible how much has happened since. We went all in on Claude, then moved to Codex, and now we are exploring how to work with different models through [OpenRouter]. There is a lot to keep up with.

One of the projects we built was a plugin to give Claude context about our data. The idea is that someone can ask a question in plain English, and Claude can find the right tables in BigQuery or use the semantic layer we have already built in Looker, drawing on the definitions we have documented in Atlan.

That last part matters a lot. Being able to write SQL is one thing. Knowing which table to use, what a metric means, and how we define it at DataCamp takes a different kind of knowledge. We have spent years building and documenting that understanding. Now we are making it available to AI so that it can work with the same definitions we use.

I find that very cool. All those metrics tables, definitions, and documentation have another use now. They help connect someone's question to the data that can actually answer it.

Then there is the question of which model to use. After Claude and Codex, we started exploring OpenRouter and a world where we choose the right model for each task. Spending tens of thousands of dollars per engineer per year on frontier models is hard to sustain. We have to figure out where that extra capability makes a difference and where a less expensive model can do the job well. Making this sustainable is part of the work too.

On a different note, over the past few weeks I have been working on an agentic app for our social media workflows, hosted on [Claude Managed Agents][managed-agents]. I have learned so much building it. But the biggest lesson so far has been how much time I should spend planning before asking these tools to start coding.

How will the app work as usage grows? What absolutely has to be there in the first version? What would be nice to have, but can wait? Those questions deserve a lot more attention than I initially gave them.

These tools are so powerful that they can quickly create hundreds of tests and enough transaction machinery to make you wonder whether you are building a social media app or a bank. ;)

It is impressive, but then you have to understand, review, and maintain all of it. Every extra feature brings decisions with it, and it is very easy to let the implementation get ahead of your understanding of what you actually need.

I am learning to spend more time describing the problem, reviewing the design, and deciding what belongs in version one. There is plenty of time to add more once we know the first version does its job. The temptation to start building is strong when you can see results so quickly. I have to remind myself to slow down and think it through.

Six years ago, I was trying to get Jekyll installed so I could put this blog online. Now I can ask an agent to help build an entire application. It is hard to believe how much has changed. And here I am, learning that one of the most useful things I can do is spend more time thinking before I start.

#### Still so much to learn. Including when to slow down.

[OpenRouter]: https://openrouter.ai/docs/guides/overview/models
[managed-agents]: https://www.anthropic.com/engineering/managed-agents
