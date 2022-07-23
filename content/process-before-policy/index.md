---
title: "Why I did InfoSec the wrong way around and you probably will too."
date: 2022-07-23T08:39:17+01:00
draft: false
tags: ["ISO 27001","Security Processes"]
categories:
  - InfoSec
cover:
  image: topsy-turvey-information-security.jpg
  relative: true
  hidden: false
---
# The Wrong Form

This is my second ISO 27001 transformation and they seem to fit a pattern. Company has little or no process but suddenly needs top be ISO compliant. The temptation there is to hire a consultant, knock up some policies, get the consultant to hand-hold you through just enough months to pass audit, learn nothing and fail audit a year later - but don't worry I'm sure the consultant would be keen to come back for a fee.

My interest in ISO 27001 came from just this need. I was CTO of a small internet startup in the days when all you needed was growth rather than a monetisation plan. When it came to monetising the product we discovered the people that valued what we were selling were mostly banks and government departments. What should have been less surprising was to discover that each of these organsiations had more InfoSec and compliance committees than we had staff.

In fairness most were surprisingly pragmatic on what they could expect from us but a regular pattern began to establish itself. In any given month at least one week was spent filliing-in huge questionaires on Information Security.

This came to a head when I spent - quite literally - 9 Monday morning through to 4.45 Friday afternoon filling a 700 page security questionnaire from a well-known high street bank. The fact they were expecting lengthy, detailed answers to be entererd into the cells of an old & very clunky Excel spreadsheet didn't help. I'd told the company not to expect any of my time that week so I was feeling a little smug at the accuracy of my prediction - I was still partly a softwaredeveloper at the time and we're notoriously bad at predicting how long things will take.

The following Wednesday I asked our Sales Director if he'd heard anything back from the bank. Five minutes later he was back "*You're not going to like this, they sent you the wrong form....*"

# ISO 27001

What could I do to avoid this endless repetition of security questionnaires ? The answer seemed to be to have our own pre-written security systems and "someone" (I foget who) told me the best one for that seemed to be [ISO 27001](https://www.iso.org/isoiec-27001-information-security.html).

This was my second career. For the first 15 years of my working life I'd been a Civil Engineer building [stations, shafts and tunnels](https://www.360virtualtour.co/portfolio/north-greenwich-tube-station-in-3d/) under London. Building & Safety Standards were nothing new to me though we called them British Standards back then. So picking up and reading ISO 27001 felt natural. Out of the box ISO 27001 is a little dry but we'd also purchased ISO 27002 which gives much more explanation around the controls in ISO 27001 - I've no idea why they have to be seperated and I suspect the mindset behind this is the root of why I'm writing this article now.

I gave myself the best part of a day sitting at the back of Caffe Nerro in Winchester and read through the 114 controls required by ISO 27001. 90% of these controls fell into one of two categories:

1. We were already doing it but in most cases hadn't formalised the process.
2. We weren't already doing it. Up until then I'd been pretty confident about our Information Security capabilities but I realised that we were only doing the obvious stuff like firewalls and private networks. Many of the less obvious things like secure coding, staying on top of known vulnerabilities in the systems we used or managing who has access to what was woefully inadequate.

In my time there we had three noteable InfoSec incidents and none of them were to do with hackers trying to get to our data.



 

 