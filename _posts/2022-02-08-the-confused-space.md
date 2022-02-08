---
toc: true
layout: post
description: A journal of my journey in the realms of the software industry.
categories: [testing, development, automation, movement, role-switch, personal]
title: The confused space
image: images/super_coder.jpg
---

Hello 👋🏼

So, continuing from where I left off last week. (Where did I leave off last week? 🤔 What is this story all about? Do you need to go back and read all previous chapters? 😟 - Don’t worry about these questions 🙃 I am just sharing my journey from a Tester to a Developer. Each post 📄 is like a summary of a string of events that led ➡️ the path)

And the regulars who have been with me from sometime now - do you have an answer? Any pattern in “what I did wrong?” 

> The answer is - I feared being judged as incapable. I yearned for too much acceptance from others - but forgot the simple trick - I need to accept myself first.

Now the second dangling topic from last post - what is an **Automation Maintenance Engineer**? Well, this was when I mentioned my role to be that of an Automation Tester, but all I ever did was fix “broken” tests. Oh no no - not fix broken scripts - fix broken **tests** (on excel sheet - changing test data, adding new keywords 😒) 

Please don’t assume that it was an easy task, because the quantity of test suites was huge. We had almost 8-10 applications which were candidates of automation. 😨 Out of those - few had regression[^1] suites of 700-800 test cases that had to be run every fortnight. I still remember - we had 5-6 spare desktops in our project - we called them “middle systems” - for running automation. And we literally used to run between them: to monitor, to trigger, to check results and what not. Even today I do not know if “Automated” tests could need so much of “Physical” effort 🏃🏻‍♀️😫

It was not a single technology- we had a hybrid framework with Selenium, 5 different frameworks with UFT, 1 with Sikuli plus multiple “scripts” to ease 😏 the effort. 

![]({{ site.baseurl }}/images/images.jpeg "Source credit: https://testsigma.com/testsigma-vs-other-tools")

In the burden of managing all of this, coding something new was never a priority. Yet, the worm 🐛 of coding made me do funny things. A senior once told - “I understand you love coding, but don’t write a new method on every opportunity.” 

So, yes - that is what I did for more than 2 years - maintained some automation suites, triggered them, reran the failed ones and scratched my head trying to figure out if the failed test is because of an actual bug or just a “sporadic” issue. This could have easily been a red flag - because I was not learning the technology - I was exhausted by the end of the day. 😮‍💨 I was stuck between knowing “I am not skilled enough for a job change” and “I don’t have time to work on self learning”. 

Meanwhile I planned to pursue higher studies. I appeared for “GATE” and “GRE” - but as you can easily guess - did not achieve the required score because “Not enough time”. I heard whispers of people - saying- oh Manual testing is end of career, you would not make far with it. So my only option out seemed via higher studies - and I failed there too. 😭 
> (P.S - My personal opinion - Manual testing is never going out of business - because it is not only testing the set of existing test suite - it is about the thought - how can the system break. It has its own importance.)

Now, looking back, I realize - higher studies was never for me. I have never been studious, so even if I had made it to an elite institution - I would still be a back-bench-er. Being focused is very important to make an optimized move. Also, if I was unable to learn or grow in the current position, I should have started applying elsewhere. While appearing for interviews, I could have understood the market requirements, prepared myself. 

In that “confused space” - I thought everyone else is doing better. Someone was switching to a different company with a hike, someone pursuing MBA/MTech, someone traveling to onsite location. I blamed myself for wanting to be a Developer 😡- because I started to believe that it won’t ever happen.


![]({{ site.baseurl }}/images/confused_me.jpeg "Source credit: https://www.npr.org/sections/13.7/2015/12/14/459651340/sometimes-confusion-is-a-good-thing")

▶️ The first rule of getting through this confusion is - listen to everything but don’t try to apply the same formula to your life. **Not every medicine is effective for everyone** - the prescription will be different. Once I started cutting out the unwanted information - I realized what I wanted. 

▶️ Secondly, people will tell you what they think is the best for you - but honestly - no one knows what is going to happen. So if you feel like, take risks. Do what you want to do. You are answerable to only yourself.

▶️ Finally - my stint as “Automation Maintenance Engineer” was not all waste. I learnt handling frequent context switches, I learnt “not breaking” under pressure. And I would definitely say - I had great seniors at work. So I was never reprimanded for mistakes. I was still given more responsibilities - which helped me build the confidence in myself. 

And special mention to my first manager - who has always been there to hear my childish blabbering, never being impatient. I still remember a very important thing he said - “Even if you do move to development, the testing will always be an additional skill. This, which is your bread and butter right now, will always give you that extra edge”. I learnt from him, how to be a leader - not a “boss”.

The next chapter will unfold my first “proper” automation task - and then a big change... So see you next Tuesday.. Okka, Bye 👩🏻‍💻

[^1]: regression - When any new feature/changes are introduced in an application (think app updates with new features) - the existing features should be tested - ‘coz no one likes “Oh why is this not working, it used to work!! 😠😩”. This is regression testing.