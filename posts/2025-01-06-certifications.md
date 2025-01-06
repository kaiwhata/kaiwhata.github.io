---
layout: default
---

# Certifications
After jumping over from penetration testing to cloud blue team work in 2024, I was a little concerned that my pentest skills would atrophy. So I decided to do some of the certs and training that I had been putting off for years and now, 6 months later, I have a whole bunch of new certs. I've realised that online cybersecurity training is still very much the wild west, with MASSIVE disparities and price and quality between different providers - so I decided to write up my experiences so far, to serve as some guidance for anyone else in a similar position. This is gonna get pretty detailed - so if you're looking for a better general guide on how to get into pentesting in NZ, I would recommend instead reading [Bogan's excellent guide](https://www.linkedin.com/pulse/getting-started-penetration-tester-nz-2024-edition-simon-howard-ijntc/) which he keeps updated each year. 

## Purpose
The certs/coruse below are a mix of a bunch of stuff, cause I'm trying to achieve multiple different things with them:
1. Certs to get your foot in the door for an interview (The Microsoft and Offsec certs seem decent at this)
2. Certs/Courses that improve or refresh your knowledge and mastery of a topic (Burp, PWPP)
3. Certs/Courses that help you position my 'niche' in the market (AZ-500, CARTP, CARTE)
4. Certs/Courses that help build knowledge breadth, which improves maturity in risk assessments (PIPA, PMPA, AZ-500)

Here's the full list of certs/training that I have attempted or am attempting, their prices (as of time of writing in Jan 2025), and some comments about their quality and cost effectiveness. Note that I'm pretty heavily weighting cost here, as I'm self funding a lot of these so I just can't afford Offsec prices, and I'm comparing only prices for certifications that include training content. You might also note that there's no INE/eLearnSecurity on here - generally the INE certs are USD$400 for just the exam witout training material which is an additional USD$749 per year - I tried one of their Red Team courses in 2023, and the content was out of date and none of the labs worked - so, given my price sensitivity, it doesn't look like I'll be going back to those anytime soon (plus their eMAPT seems to be one of their few certs that's well known). 

| Certification | Provider | Cost | My Progress | Difficulty | Elf Recommends? | Comments |
| --- | --- | --- | --- | --- | --- | --- |
| Offensive Security Certified Professional (OSCP/PEN-200) | OffSec | USD$1,749 | Certification Obtained (2022) | Medium | | I did this because I had to. Failed twice before passing. |
| Azure Fundamentals (AZ-900) | Microsoft | USD$99 | Certification Obtained (2023)| Easy | :+1: | Quick and easy cert to show you have basic Azure knowledge |
| Azure Security Engineer Associate (AZ-500) | Microsoft | USD$165 | Certification Obtained (2023) | Medium | | Of all my certs, this one actually got me a job. |
| Certified Web Application Security Professional (CAWASP) | Altered Security | USD$299 | Certification Obtained (2024) | Easy | | Skip this, do CARTP instead |
| Burp Suite Certified Practitioner | PortSwigger | USD$99 | In Progress | Hard | :+1::+1: | Im treating this as a cheaper OSWE, with (probably) better content |
| Cybersecurity Architect Expert (SC-100) | Microsoft | USD$165 | Certification Obtained (2024) | Medium | | Rote learning of Microsoft documentation. |
| Certified Azure Red Team Professional (CARTP) | Altered Security | USD$449 | Certification Obtained (2024) | Easy | :+1::+1: | Solid intro to Azure security. Taught me more than AZ-500 and SC-100 combined. |
| Practical Mobile Pentest Associate (PMPA) | TCM Security | USD$249 | Certification Obtained (2024) | Easy | | The best, cheap mobile cert I could find. Course definintely needs an update. |
| Github Advanced Security (GHAS) | Github | USD$99 | Certification Obtained (2024) | Easy | | Rote learning of Microsoft documentation. I wouldnt have sat this if I didnt already have to learn teh material for work. |
| Beginners Guide to IoT and Hardware Hacking (PIPA) | TCM Security | USD$249 | Course Complete, Will not sit Cert | Easy | :+1::+1::+1: | Pretty much a perfect course :) |
| Practical Web Pentest Professional (PWPP) | TCM Security | USD$499 | In Progress, Will not sit Cert | Medium | :+1: | I'd consider doing this cert as a stepping stone to the Burp Certification, as they share content but Burp goes WAY deeper. TCMs exams seem decent, so there's a solid chance of passing on your first or second attempt. |
| Certified Azure Red Team Expert (CARTE) | Altered Security | USD$499 | Planned - Not Started | | | I'm really itching to do this, but no-one in NZ cares about teh different between Professional or Expert in Azure. So other than personal interest, there's little incentive for me to prioritise this. |

It's also worth noting that you can acess all the PortSwigger content for free, and you can access all the TCM content for USD$30/month.
If money wasn't a problem (or if someone else was footing the bill) then I'd personally do the following (in order):
1. Beginners Guide to IoT and Hardware Hacking (PIPA) - the course was that good
2. Certified Azure Red Team Expert (CARTE) - I'm just super interested to do this course given how good CARTP was
3. Practical Web Pentest Professional (PWPP) - prep for Burp
4. Burp Suite Certified Practitioner - prep for OSWE
5. OSWE & then OSEP - Offsec certs are still more recognised than others
 
The OSWE and OSEP are only on this list for that sweet OSCE3 (but they're both USD$1,749 each - so that's not happening) - and I dont think anyone in the NZ market cares except for top tier red-teamers (which is never goping to be me anyway).

### Best Overall Courses
 1. Beginners Guide to IoT and Hardware Hacking (PIPA) - TCM Security
 2. Certified Azure Red Team Professional (CARTP) - Altered Security

Anyone who knows me, knows that I am incredibly hard to please as a student on a course. Having written and delivered quite a few courses of my own in the past I'm really picky with both what content is delivered, and how it is delivered. So when I say that I had an absolute BLAST doing both of these courses, it means they're well worth your time and money. Andrew's PIPA course is a wicked intro to hardware hacking (which you can do without any hardware), is really well paced, taught and scoped. I'm genuinely saddened that I decided not to do the certitifcation exam for this one (simply because I don't think anyone in NZ appreciates hardware hacking certifications). The CARTP course has heaps of excellent content, is well delivered, and gives a lot of practical expertiese into penetration testing in Azure (which is something that very few trainings do well). Also, the support for both of these courses is excellent (usually responding to any queries within 24 hours).

### Most Cost-Effective Courses
 1. Burp Suite Certified Practitioner - PortSwigger

This one is a little deceptive, as the course content is free and each exam attempt is USD$99. However the content, for web application hacking, is absolutely top tier. In fact, the TCM Security Practical Web Hacking course is built around these free PortSigger labs (because they're that good). That said, I expect the actual costs of getting this certification to be more like USD$500 - as it appears that (like OffSec certifications), most people fail the exam the first few times. In contrast with OffSec content though, the tough Burp Suite exam seems designed to ensure that you have sufficient mastery to pass. They provide several free practice exams and challenges - but the tight timeframes involved means that you need decent mastery to get the cert. My estimate is that it will take me another 6 months to get the cert (if I ever do), but doing the course and labs has already impoved my skills much more than any other single course.  

### Best Pedagogy
 1. Beginners Guide to IoT and Hardware Hacking (PIPA) & Practical API Testing - TCM Security

I wanted to give a particular shout out to TCM here as, they seems to have the most consistently *decent* courses out of all of the providers that I have tried. And, in addition, their support is excellent. Whilst there are a couple of their courses that definitely have room for improvement (PMPA), their general course quality is solid (which is much more than I can say for other providers that I have tried in the past). The fact that they have a subscription which can be used to acess all course content, and that each cert includes two exam attempt - is really solid support for students (everyone has bad days, family emergencies and things outside of our control which can lead to a single failure. IMO a single poor attempt shouldn't force you to repay for a cert). 

[back](./)


