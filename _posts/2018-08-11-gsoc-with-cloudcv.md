---
title: gsoc 2018 with cloudcv
tags: Internship
comments: true
---


On April 23rd, 2018 I received the wonderful news that I was selected as a Google Summer of Code intern at the organization CloudCV. I wasn’t actually surprised that I got in. Probably because I already got so much value out of the preparations, I was satisfied with the things I’ve achieved (Honestly, mentally I was prepared for the worst just in case I wasn’t selected lol).

From June of 2017, I was fascinated by the projects at CloudCV and I just wanted to contribute. I started actively solving and contributing the projects in small ways from July onward. I didn’t think I’d get selected, but I guess I underestimated myself very much (I like to do this, it makes me work better).

The last three months were a blast. I learned more things in the last three months than the past year combined. I wrote the proposal over a period of 3 months because I knew that this was going to be an extremely amazing experience. I was also aware of the inside outs of EvalAI, from the submission worker to the angular front-end, which I learned just to contribute to this project (Man, I hated working on the front-end). I was committed to seizing this opportunity because

1. I was building a project from scratch and releasing it, which is exciting on its own.

1. I would have to set up all the other utilities like Travis-CI, PyPI and all the tests on my own.

1. I had to push myself to stick deadlines and make things happen from the comfort of my home.

## **EvalAI-CLI**

This was the main part of my project. It enabled a user to use the wide range of EvalAI features through the terminal. From making submissions to view the leader-boards. After 5,000 lines of Python code, we finally published the package on PyPI on 22nd July. [EvalAI-CLI](https://github.com/Cloud-CV/evalai-cli/commits?author=isht3) Official Command Line utility to use EvalAI in your terminal.

## EvalAI

Along with my contributions to EvalAI-CLI, I’ve also done some significant contributions to [EvalAI](https://github.com/Cloud-CV/evalai/commits?author=isht3) like, token authentication and rewriting the architecture of the Submission worker inside Docker.

### Project Dissection

1. [Token retrieval from the EvalAI web app](https://github.com/Cloud-CV/EvalAI/pull/1683).

1. [Setting up the initial directory structure.](https://github.com/Cloud-CV/evalai-cli/pull/1)

1. [Token authentication, storage, and retrieval.](https://github.com/Cloud-CV/evalai-cli/pull/9)

1. [Implementing EvalAI Challenges features on the CLI.](https://github.com/Cloud-CV/evalai-cli/pull/9)

1. [Implementing EvalAI Teams features on the CLI.](https://github.com/Cloud-CV/evalai-cli/pull/52)

1. [Implementing EvalAI Submission features on the CLI.](https://github.com/Cloud-CV/evalai-cli/pull/56)

1. [Host URL configuration on the CLI.](https://github.com/Cloud-CV/evalai-cli/pull/37)

1. [50 other PR’s I can’t fit into this blog](https://github.com/Cloud-CV/evalai-cli/pulls?q=is%3Apr+is%3Aclosed) :P

1. [Docker fix on EvalAI.](https://github.com/Cloud-CV/EvalAI/pull/1692)

### What I Learned

* Collaboration on big projects: This might be one of the most significant skills I gained. I believe that writing the feature is just 60% of the work. 20% is on testing (OMG, so exhausting!), 10% is documenting and 20% is making changes on the PR, iteration after iteration.

* Utilities while coding: Travis CI, PEP 8 conventions and all the other cool integrations. God bless programmers. It was absolute fun to work and set up these. But there was instance I regretted having these since they were always pointing out my mistakes.

* Amazon SQS: In the 21st century, we’re living on the cloud. I was absolutely thrilled to work on Amazon SQS because this is the first cloud-based tool that I seriously committed to.

* Docker: Another amazing tool to work with. I was so used to setting up the *virtualenv* and all the dependencies, manually, by getting hands my hands dirty and solving all the errors that popped up, that when I used docker for the first time, I was absolutely blown away by how easy it was to set the whole project up with just one click.

### Ending notes

I’m extremely grateful that I was selected to work on this project. This opportunity empowered me to work on fore-front technology and improved my communications and collaboration skills within an organization. I’m very much looking forward to the future of the projects within Cloud-CV and will be sticking around to work on and help with the projects for the foreseeable future. This wouldn’t have been possible without the mentors, I know I was quite dumb sometimes but thanks for guiding me through the tough part.

* [Rishabh Jain](https://github.com/RishabhJain2018)

* [Deshraj Yadav](https://github.com/deshraj)

* [Varun Agrawal](https://github.com/varunagrawal)

## Ciao.
