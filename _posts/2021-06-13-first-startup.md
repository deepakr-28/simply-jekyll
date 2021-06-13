---
title: How my First Start-up Failed Spectacularly.
tags: Product, Start-up, Lessons
comments: true
---

After you try and fail at building a profitable start-up multiple times, at one point you'd have learned enough from the failures that there'd be no way out but to do it right. I think that quote was by Edison or something, idk. In this essay, I'll be trying to touch upon my first attempt at building a start-up, how it miserably failed at being a start-up and the lessons I learned from it. These essential lessons I learned from my first failure was pivotal for everything that comes after.


The first problem was the motivation with which I wanted to start my first tech start-up. I was at the end of my third year of engineering at my university, it is 2019, you don't have to wear masks or social distance. Every day you're getting drunk, coding and talking shit. Life is unironically good. I just came back from Bangalore to Kochi after my data science internship and was processing all the information from the start-up where they raised Series A. The obvious next thing to do for me was to get into start-ups because I quite honestly didn't find placements or a job challenging enough. I programmer ego, and I had multiple cool internships under my belt. Obviously, the next obvious thing to do is to be worth $10 million so I can flex during the university reunions.


I also knew in my bones that it'd be a much more fulfilling thing to pursue next since I could find tech jobs pretty easily. The problem was that I was trying to get into deep-tech, or more specifically, I was trying to specialize in data science because I was aware that I had a lot of things left to learn if I needed to be credible on the global stage in my trade. The motivation with which I wanted to create a start-up was to upskill myself technically instead of building a product that solved a genuine problem of the user. So you can see the dilemma that I faced. I was more interested in becoming a "CTO" than taking responsibility for the users, PMF, vision and having skin in the "start-up" game because the tech was my comfort zone. The idea was that masters and PhD looked pretty drab, so if I could use my tech skills to found a B2B company that was valuable, I'd be credible on the global stage and I could work and tackle much bigger projects. This was my Plan-A.


I'm not an idiot, so I did plan for the possibility of my Plan-A failing. If my Plan-A failed, the Plan-B would be that I'd still have the tech skills from this venture to back my portfolio up. It's a gamble, but let's get this shit done. What would I have done differently? I should have started a Whatsapp newsletter. Just kidding. But yeah, I think if my motivations were in the right place, which was to create a start-up by bringing genuine value, that'd have yielded a better result than the strategy I took.


I wanted to build a start-up while specialising and gaining skills in Data Science. So what did I do? I went over to r/datascience and I offered my skills to the free market to see the response it yielded. The free market did respond. My post got removed and I almost got banned for spamming. I guess the free market wanted to preserve the value and integrity of the forum. One interesting thing happened though, before I got banned, a couple of folks commented on this post showing interest. 


One of the people who reached out was very enthusiastic, had a lot of great ideas for projects, had a great portfolio and industry knowledge and at that point, I was more interested in learning things to get this project done than to make money so we decided to team up. This was our initial idea, and boy was it exciting!


> Essentially I want to scrape news websites probably in African and Asian countries, get the stories, look for anything to do with certain topics, translate them and do entire extraction - names, roles, organisations etc and then flag them for certain use cases. Like I said things like wildlife trade but also money laundering all the way to terrorist financing. Basically, once you have a core platform to do this you can then filter on any specific case. Let's stick with wildlife for now.


Now to build the MVP out, I needed a team and I got three of my friends involved to help with this. A friend who was exceptionally good at ML, a friend for the frontend, backend and to do the general stuff. So we're a team of 5 and we're to kick ass.


This was a period of immense excitement since we brainstormed how to achieve this, build it out and take it to the market! I mean just thinking about the possibility of someone buying this was enough to keep us going for months. We registered our company in the UK, gave ourselves labels as co-founders and other C-positions to compensate for our lack of market knowledge and to create some momentum.


When you consider the start-up philosophy, we did things wrong from day one. If it's a profitable start-up that we wanted to build, we should've started with doing market research, looking at the competitors and similar products in the space and strategising about how we could differentiate ourselves in this market. We didn't think about the distribution neither. Who the fuck is going to buy this? Since our incentive was to "build an interesting project with real-world implications", we built something that we thought the market wanted instead of what the market actually wanted. I think this is the most common mistake that people who come from engineering background end up doing. We focus on the tech, and not enough on thinking about whatever the fuck we're building.


One of my friends did warn me in an email but we conveniently ignored that. Here's the email exchange between the both of us.


>ME - It's called http://alrt.ai/ and we stumbled upon this idea last December, our landing page is trash but a new one is coming in a couple more days. It's basically a way to monitor all the news sources across the world for news that are relevant to you and identify the news that'd be most useful for your industry. The idea is to start as a custom-tailored solution for corporates where the underlying infrastructure would stay the same but depending upon the use-case we'd carefully fine-tune our ML models to provide people with a story that might be immediately important to them via alerts, that's what is going to differentiate us. But I'm convinced there are even more use-cases on the consumer side which we could sell to people on. We have a Kaggle top 20 and an industry veteran who has all the contacts on our team.

> So I'll give you a few actual use-cases that we tailored this product around 

> Exploration of a particular news space: We call this the automatic mode. I've attached screenshots labelled "auto" for these dashboard pages, would make a bit more sense if you take a look at that. We had a few commodities based hedge funds that trade petroleum-based product show interest in this particular use-case. Suppose this hedge fund is interested in Diesel based news and wants to find events that surround diesel. So we give some keywords into the system like diesel refinery, diesel production, diesel storage, diesel capacity, diesel terminal, etc and pull all the news based on these keywords to our database and will keep monitoring the internet for this news. After pulling this news into our database, we do entity extraction and do sentiment analysis and apply our custom model scores. We render all this information into the dashboard so the user can see what Organisations, Products, and Countries are most relevant in the Diesel space. Suppose an explosion happens in South Korea in a Diesel plant, we'll have the trending entities related to the explosion on the page along with the news and if it is happening in real-time that model will alert you on what's happening. Another use-case is, if you want to see how the "Diesel" product was affected by COVID, we can automatically deploy a COVID detecting model onto the dashboard and it'd show all the entities and news that are most related to Diesel and COVID. Mind you, we can literally track anything and deploy a model for anything for eg, Technology, Medicine, Media etc. 

> Monitoring your Portfolio and setting up alerts if certain danger "metrics" are triggered: This mode is called the portfolio mode. I've attached the screenshots called "portfolio". This is quite straightforward. Suppose you're a Risk Manager and you have to keep an eye on the companies in your portfolio, while also making sure your clients are not involved in corruption or there's no data breach and stuff like that. You could also do due diligence and background check on your new potential clients and keep tabs on existing ones. For example, questions like were Deloitte ever involved in a data breach last year? What is the banking risk in Turkey? could be used to answer. In the portfolio-mode screenshot, at the top, the two buttons are the two custom trained models for detecting news that is related to financial crime or cybercrime for all the companies on the left. This mode helps you to monitor different companies in your portfolio for new and all the while making sure no news about a financial crime or cybercrime about your clients hit the mainstream news or go viral before you know it.

> On the consumer side, we were thinking of setting up a paid research platform for casual institutional investors to research and keep track of their portfolio but it's a very competitive space. We have a few interested clients and I was thinking while we pursue that, we could see to some of the applications on the Consumer side something which would help us create some income since B2B deals do take some time hahaha...


![page 1](https://i.imgur.com/eZYWjP7.png)


![page 2](https://i.imgur.com/SWtepnq.png)


![page 3](https://i.imgur.com/Dpr5wez.png)


![page 4](https://i.imgur.com/5vICnMJ.png)


![page 5](https://i.imgur.com/gQXxIqx.png)


> FRIEND -  "Mind you, we can literally track anything and deploy a model for anything for eg, Technology, Medicine, Media etc." This statement creates scepticism in me. I rarely see an all in one solution that works better than a solution designed for a specific niche or use case.

> For portfolio mode, how is this different than just setting up google news alerts or using a brand monitoring saas like mention.com? It doesn't have to be different. There are plenty of companies that do the exact same thing and co-exist, I'm just wondering how this might be better or different?


> ME - Yes definitely, if our core service is to make sure we get all this data to the users the fastest, we're screwed because we'll be competing with the big players like Bloomberg and Reuters who do this at such a fast rate that thinking about competing them would make you go bust hahaha... We're targeting clients who do medium frequency trading, which is basically they want it fast, but not that fast and for field research. So the differentiating factor would be how accurate can we identify relevant events from the constant stream of news, how good our custom build models are for alerting our users on relevant events, and how good the exploration thing is. Show me news where "<EVENT> happened in <REGION>".

> Yes, you're right about portfolio mode, I guess it's not that different from any other service out there, only our ML models would be the highlight. That's why we created the auto mode, which is more exciting.
 
> One of the use-cases we wanted to do was for institutional investors. If they wanted to diversify their portfolio or something and wanted to find Green energy investment in Australia or something. We could literally build a custom solution in 2 days for them to accomplish this and we could sell it based on that. You'll get weekly trending companies in green energy always on your portfolio and you could monitor that region or that industry quite nicely. So more of a research-oriented thing than a super speedy delivery of news.


> FRIEND - I'm a huge believer in selling something that you don't have. Can you talk to companies and tell them that you can do this, and just make a frontend product that you can show them, and get them to pay you before you build it. Tell them you will have this thing up and running in full force in three months, but if they sign up today, you'll give them 40% or something? If you have a few customers locked in, then that's super motivating.


Reading those emails, makes me cringe right now. Since we're a bunch of programmers, the thought of doing "business" didn't quite interest us. It's a bias that can end up with you building something for a hypothetical market that exists only in your head. We were quite shielded from the reality of things because the excitement within the bubble that we were living in gave us momentum.


All was not in vain, we gained a LOT OF SKILLS. I had to pivot from being a Data Scientist to being a Data Engineer since that's what the team required. Since we were building this thing out in Google Cloud, after some hustling and our previous experience with passing the YC Start-up School we qualified for $5000 credits on the platform to build out our infrastructure. Then I took the Cloud Engineer and Data Engineer Professional course, which had like 10 mini-courses in total and completed it. There was one point where I was obsessed with learning every. single. GCP. offering.


I definitely think if we were building a realistic start-up we wouldn't even have remotely tried even 10% of the tech we tried out. To give you a rough idea of our stack. We used and experimented with Postgres, MongoDB, python-Django, ReactJS, GraphQL, Neo4j, Cloud Scheduler, Cloud Functions, Airflow, Cloud Composer, Redis, Cloud Jupyter Notebooks, Cloud ML for hosting our algorithms, TensorFlow, Keras, Elasticsearch, Logstash, Kibana, Cloud Storage, Google-Pub-Sub, Entity Extraction, Sentiment Analysis, Pipelines for ETL, Deep Learning and a tonne of other things that I don't have the patience to list out here. If I was to tackle the problem again with my newfound wisdom, I would've just tried to prototype the whole thing in a Jupyter Notebook to see if it was possible to build and then just sell the algorithm for some money.


Since we had classes, we had to social engineer our way out of attending physical classes to sit and hack. I personally had to skip a lot of fun events in my final year of university to get this thing done but I have zero regrets because it was all compensated for by the things I learned. I do sometimes think I should've participated, but alas, no point in wishful thinking. 


Then BOOM COVID struck. University got cancelled, there was a lot of uncertainty regarding where things were going and not sure about what this meant. I knew that this was going to be a long event since I read an article on the Spanish Flu, but boy, were my expectations misplaced. We had one final drink with the boys and parted our ways hoping to see each other in two weeks. Fun fact: We didn't. We didn't see each other for months and we ended up graduating on a random Tuesday after two months.


Enough getting emotional, it turns out that COVID was another opportunity. Because now instead of not focusing on classes, we could work full-time on this. Halfway through building our project we had a hypothesis regarding who our target market was for. This was something we were supposed to do at the start. But we deluded ourselves by thinking it was hedge-funds and investment firms. LMFAO. We convinced ourselves that they'd buy it and kept the momentum going. We got on calls with hedge-fund managers, folks from investment firms, discussed what they wanted from this MVP, 5 months into building the MVP. We were suddenly struck with the realization that Bloomberg terminal was a competitor. Surprise surprise. 


That second epiphany was the lack of money coming in. It penetrated our bubble of delusions about the "start-up" we were building. By then, we had an MVP that we were proud of. Compared to our competitor, the BLOOMBERG TERMINAL, which literally brings in billions in revenue, our product was like a minor downgrade but hell, our UI had better colours.


It was a cool MVP which I was really really proud of. You could create a "scenario" like "Risk", "Climate Change", "Green Energy" and companies and entities that you want to track and they'd scrape and gather news articles regarding that. Did you want to know cool green energy company news in Australia? Boom, you got it! We kept on adding feature after feature. Graph database to map and connect entities? You got it. Predictive algorithm to score entity relationships? You got it.


Ultimately it was around May that the team started losing momentum. We couldn't find a paying customer, most of our peers had got full-time job offers and some started working while we were staying with our parents and trying to get this thing to take off and bring some revenue. Ultimately the truth dawned on us that we built a product in the void and that no one wanted it. This venture was a spectacular failure.


Since we couldn't sell this product to hedge-funds and investment firms, I tried to find consumer applications through newsletters and other channel but by that time I was running low on energy. I just wanted to get this thing over with. It was mentally taxing to work on something which yielded no returns. As one last-ditch effort to sell the tech that we built by posting it on r/startups and we had a lot of offers for $10,000 to $20,000 to buy this thing, but I and my team-mates were so burnt out from working 10 hour days for the last 7 months without weekend breaks that we just could not see it through since we were too exhausted to fix the bugs we needed for the demo. The realization that I wouldn't be a millionaire in 2020 hit me like a brick, on my face, when I'm driving 200 KM per hour. Yeah.


I ended up open-sourcing all the tech I wrote and put it on my Github. The last days of the company were filled with so much despair, realisations and harsh truths that I took a couple of days off just to process it. I was feeling bad for the team since we failed, and one of my peers had to cancel his masters for doing this. If you built a start-up, you know how hard it is to just let go of it. It's like a baby you're raising a baby and boom, one day the doctor tells you that it's not going to survive and you sit and ponder where you went wrong and how you can salvage something out of it. It was COVID, so you couldn't go out and have a drink to talk it out neither. The existential crisis of sitting in your room at 1 AM grappling with the reality of truth is a very humbling experience. Suddenly the expectations and hopes about being a millionaire come crashing down and the delusions that you convinced yourself of is out there clear as day. You had to let go and move on. With this, there was only one thing left to do, quit.


It was not all in vain, I was able to leverage the tech skills I gained here by learning all this and get a very well paying job, 2X more than I would've gotten from sitting in placements. The seven months that I spent doing this with my team were times of immense personal growth and sacrifice. I do not think the things I learned about myself through this journey could be recaptured by anything else. These would turn out to be fundamental lessons that fuel my journey forward. 


After this, I started freelancing for a friend's company in the US, which had a very interesting product. Since our user-facing backend was in Django with Postgres, I put out a proposal to my friend where I said "Hey, I'll solve any three issues that you give me in 10 days. You can hire me if I get it done". That gamble paid off since I knew the tech very well. Their tech stack was similar to what our start-up had and I was able to solve those three quite important issues in 7 days. I started freelancing for a comfortable $15 an hour as a normal programmer. 


Getting a day job was kind of weird since I was working with the customer service team to bring actual value to users through my tech skill. Quite a stark contrast from where I was just a month ago being the "CTO". You didn't need fancy databases, "ML" or "ENTITY FUCKING EXTRACTION WITH ETL" to create value. A CRUD app was all that was needed to comfortably solve the user's problems and bring them genuine value and make their life better. It was a humbling experience and a philosophy I started embodying for every project that followed.


Eventually, I was able to convert that into a job where I could work my own hours, I negotiated a better salary and I had plenty of time to work on my side-projects. The lessons I learned there were so valuable for me that I knew I had to build a start-up, but this time I knew how to do it right. Without writing a single line of code, just by myself, and after talking to users.


Why am I reflecting on this after a year? I don't know. If this helps one other person make a better decision, I guess that's enough but I don't think I'm that altruistic. I guess I just wrote this for myself and if you read my last essay, the launch success, getting a YC interview call is directly correlated to the lessons that I learned here. Just focusing on creating value and being of service to others. I still have a long way to go but yeah, this shit is fulfilling af.

<iframe width="560" height="315" src="https://www.youtube.com/embed/TD20bBR88o4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 

<iframe src="https://open.spotify.com/embed/track/5OLjhk2db14wAFMmWjrxGw" width="100%" height="380" frameBorder="0" allowtransparency="true" allow="encrypted-media"></iframe>
