---

layout: col-sidebar
title: OWASP Riyadh
site_side: true
tags: riyadh
level: 3
region: Asia
currency: Asia
meetup-group: owasp-riyadh-meetup-group
country: Kingdom of Saudi Arabia
postal-code: 

---
<!-- rebuild -->

OWASP Riyadh
-------------
Welcome to the OWASP Riyadh chapter homepage. OWASP (The Open Web Application Security Project) is a worldwide not-for-profit organisation focused on improving the security of software. With over 200 local Chapters worldwide and 45,000+ volunteers OWASP's open community is dedicated to enabling organisations and individuals to develop and maintain applications that can be trusted. OWASP's meet-ups, tools, standards, guidelines, documents and forums are free and open to anyone interested in improving application security. The chapter leaders are Aatif Khan and Rayed Almutiry. <br />
Follow chapter news on [LinkedIn](https://www.linkedin.com/company/owasp-riyadh/) | [Twitter](https://twitter.com/owaspriyadh) | <a href="https://t.me/owaspriyadh">Telegram</a> 
## Upcoming Meetings: 

{% include chapter_events.html group=page.meetup-group %}


<br />December 2021 Event Details
----------------
Date - 23rd Dec 2021 <br />
Time - 8:00 PM <br />

<b>What are we missing in Web Applications?</b> <br/>

In today's world, we have a modern and stable web application framework to develop on. That is already so much secured from the attacks, regardless of the OS. If you design the system properly, attacker cannot injection the system. Or attacker cannot attack the website with common attacks like XSS, CSRF, SSRF, SSTI, etc. On the other hand, we have sophisticated scanners which scan the website dynamically with the interactive logins as well, it scans the website along with the internal pages. And we have secure coding practices as well along with the scanners which can scan the source code regardless of the programming language. They are necessary tools while developing a secure application.

But what all these are missing is "Business Logic Flaws", which are the reason for the highest-paid bounties on Hackerone, bugcrowd, etc. Business Logic Flaws are the attacks, which neither the source-code analysis tool nor dynamic web application scanner can detect.

The presentation/talk will discuss vulnerabilities that can arise from business logic flaws which can affect confidentiality, integrity & availability of customers' information as well as the product that is connected with the application. We will discuss CVE-2019-2823 - Oracle Financial Services along with other 2FA bypasses in Financial Mobile Applications. Where I was able to do vertical privilege escalation in regards to roles, checker, maker, etc. modules. These were critical findings that were used in financial information systems. On which APTs are attacking day and night.

The majority of the banks use this Oracle service in the world. There are a lot of similar bugs in the world right now as well, in regards to Business Logic Flaws. We have to enhance the testing skills rather than depending on the scanners, manual testing approach to test the use cases will be a good approach.

Briefing Outline:  <br />
~ What are current/critical Web Application Flaws?  <br />
~ What are Business Logic Flaws (BLF)?  <br />
~ Common Vulnerabilities in with BLF.  <br />
~ Security Design Flaws.  <br />
~ Me against the Odds – Scavenging the application.  <br />
~ Bottlenecks, Solution.  <br />
~ Pwning the financial application.  <br />
~ 2FA bypass with BLF.  <br />
~ Test Cases for your application.  <br />
~ Closing Remarks / Q&As  <br />

Takeaways:  <br />
~ Test Business Logic in Web Application.  <br />
~ Different methodologies to test against this issue.  <br />
~ What to look for in source code to mitigate it.  
 <br/>


<b>Speaker - Mirza Burhan Baig</b><br/>
Mirza Burhan Baig is an Information Security Threat Analyst at Riyadh Bank – KSA. Mr. Baig is OSCP Certified professional with over 8 years of experience in Penetration Testing, Threat Hunting & Vulnerability assessments which include Core banking solutions, Banking applications, Network assessment, Mobile penetration testing. Mostly served financial industry.

Mr. Baig is also a certified professional and holds an OSCP, eWPTX, eCPPTv2, eNDP, etc. He is involved in bug bounty programs as well, where he helped many companies to fix vulnerabilities at a different level. Companies include Google, Microsoft, Facebook, Amazon, PayPal, Apple, IBM, CISCO, etc. Mr. Baig is also involved in many physical security projects to bypass networks and systems.

Mr. Baig has conducted many seminars and workshops at different levels of corporate, NGOs, Universities, specifically for students to create awareness & guide them to a career path in information security. Some of them include Dubai Electric Water Authority (DEWA), etc. <br/> 

## Past Meetings: 

<br />August 2021 Event Details
----------------
Date - 30th August 2021 <br />
Time - 7:30 PM <br />

<b>Introduction to SSL/TLS & Their Attacks</b> <br/>
The presentation will talk about the history of the SSL/TLS protocols, and the old and new vulnerabilities in the protocols as well as the ciphersuites. Moreover, it will briefly talk about the encryption issues and the applications of the TLS that went bad in the recent years. Finally, the discovery of the issues and the exploitation of some of them will be explained.<br/>

<b>Speaker - Rian Saaty</b><br/> 

Rian Saaty is a senior cybersecurity consultant focused on penetration testing, vulnerability assessment, and Red Teaming. Rian has a M.S. degree in Cybersecurity from Johns Hopkins University Whiting School of Engineering. He was previously a lecturer at KAU and an advisor for multiple entities. Furthermore, he holds a number of top-notch industry certificates such as OSEP, OSCE, OSCP, GPEN, CRTE, CRTO, etc.<br/>

July 2021 Event Details
----------------
Date - 28th July 2021 <br />
Time - 8:00 PM <br />

<b>Extending Security to IoTs Using Low-Overhead Public-Key Cryptosystem</b> <br/>


<b>Speaker - Dr. Fatemah Alharbi, PhD</b><br/>
A consultant at the Communication and Information Technology Commission (CITC). An Assistant Professor in the Computer Science Department at Taibah University, Yanbu. Has a Ph.D. degree in computer science from University of California, Riverside (UCR), which is ranked #17 in security based in CSRankings. Interested in, but not limited to, cybersecurity, cyberattacks, Internet of Things (IoT), applied crypto, system and network measurements and analysis. Has been involved in many research projects that were published in prestigious conferences (e.g., USENIX, CCS, and INFOCOM) and journals (e.g., IEEE TDSC). Received public attention after presenting a cyberattack on the DNS infrastructure targeting Apple macOS, Linux Ubuntu, and Microsoft Windows. Passionate about building systems and tools that will result in long-lasting real-world impact. A strong believer in the power of feedback and teamwork.<br/> 


June 2021 Event Details
----------------
Date - 5th June 2021 <br />
Time - 7:00 PM <br />

<b>The Challenges and Opportunities in TLS1.3 Monitoring</b> <br/>
 

Ensuring users' privacy while protecting your network is becoming a hard tasks with the adoption of new features in TLS1.3 such as the encrypted TLS server name indication (ESNI) in addition to other protocols such as the encrypted DNS such as DNS over HTTPS (DoH). TLS 1.3 is a great development in the secure transmission of data. But there’s a few security challenges that we need to be ready for. In this talk, I will present the current threat landscape and possible mitigation to some of the known malicious usages of the new privacy features implemented in TLS1.3. We will discuss the impact of TLS 1.3 on Network-based security solutions used by enterprises and public sector given that the several changes introduced in TLS 1.3 have a good goal to improve the overall security and privacy provided. However, some of these changes have a negative impact on network-based security solutions <br/>


<b>Speaker - Khalid Alsuwaiyel</b><br/>
Khalid Alsuwaiyel is a Senior Incident Response Consultant in IBM X-Force IR team. He is responsible for the successful execution of incident response and proactive services to the X-Force IR customers in EMEA and globally. He has more than 6 years of professional experience, most of which are on the Digital Forensics team of the Saudi National Cyber Security Center. Khalid worked as a DFIR team leader for key critical National Infrastructures for more than 3 years. He holds the SANS GIAC Defending Advanced Threats (GDAT), GIAC Certified Incident Handler (GCIH) and Certified Threat Hunting Professional certifications along with others. He is a fierce forensicator who understands how the adversary thinks and what they might do. He is a known speaker on the topic of DFIR /Security, spoke in conferences  such as RSA Abu Dhabi and the International Cyber Security Conference in Riyadh. <br/>


February 2021 Event Details
----------------
Date - 25th February 2021 <br />
Time - 4:00 PM <br />

<b>Unveiling BugHound: a static code analysis tool based on ElasticSearch</b> <br/>
Bughound is an open-source static code analysis tool that analyzes your code and sends the results to Elasticsearch and Kibana instances to get useful insights about the potential vulnerabilities in your code.Bughound has its own Elasticsearch and Kibana Docker image that is preconfigured with dashboards to give you a strong visualization for the findings.You can easily pull and run the docker image and start the bughound python client which will analyze the code and then send it to the docker container which will visualize all the potential vulnerabilities for you.Bughound will search for any keywords “which is the unsafe functions” based on a JSON file contains these functions and the core code will make sure that these functions exist in the code, then it will ship them to the Bughound docker container.Bughound will map the results found in the code and store them in Elasticsearch which will help you to search manually for any potentially vulnerable code schema based on the unsafe functions found. Also, Bughound has a preconfigured Kibanna dashboards that will give you insights about the potential vulnerabilities that were found. <br/>


<b>Speaker - Mohammad Askar</b><br/>
Mohammad Askar is a penetration tester, OSCP and OSCE certified, working in information security field with over 6 years of practical experience. He has worked with some private and government entities and has spent his time with them performing penetration testing for their infrastructures. Over the past few years, he has been contributing and building open source projects that are related to offensive security in general; Also, He has been focusing on discovering and developing exploits for 0-days that he found in various solutions. He spends his time breaking things or learning how to break things. <br/>


October 2020 Event Details
----------------
Date - 24th October 2020 <br />
Time - 4:00 PM <br />

<b>The Road Towards 365 Bugs in Microsoft Office 365</b> <br/>
Microsoft 365 is used by over a million of companies and billions of users worldwide. According to Microsoft, Office 365 i.e., the world's productivity cloud is a security-hardened service and follows the Microsoft Security Development Life-cycle. In this presentation, I will share the stories of my journey towards 365 valid bugs in Microsoft Office 365 umbrella applications. The talk will highlight the lessons learned during Office 365 bug hunting.  <br/>
The bounty award winning bugs that will be discussed during the presentation are:<br/>
1) Cross-tenant privacy leak in Office 365  <br/>
2) All your Power Apps Portals belong to us<br/>
3) SQLi, CSRF(s) and SSRF in Dynamics 365<br/>
4) Privilege Escalation issues in SharePoint Online<br/>
5) Dozens of XSS(es) in Outlook- Some rate limiting issues<br/><br/>

Further, the talk reveals XSS issues in Microsoft 365 Admin Centre, OneDrive, Word, Excel, PowerPoint, OneNote, Yammer, Microsoft Forms, Kaizala, Dynamics 365, SharePoint Online, Stream, Video 365, Azure, Security & Compliance services of Office 365. Last but not the least, we will share tips and tricks as far as how one can stay at the top to test the new and upcoming features of Office 365.<br/><br/>

<b>Speaker - Ashar Javed</b><br/>
Ashar Javed is a security engineer at Hyundai AutoEver Europe GmbH with over 5 years of experience. Before that he has spent three years as a security researcher for Ruhr-Universität Bochum, Germany. Ashar holds a PhD degree from Ruhr-Universität Bochum and MSc from Technische Universität Hamburg-Harburg, Germany. His research interests include web application vulnerabilities and in particular Cross-Site Scripting.<br/>
Ashar delivered talks at main security events like Black Hat Europe 2014, HITB KL 2013, OWASP Spain (2014, 2015 & 2016), SAP Product Security Conference 2015, International PHP Conference 2015, ISACA Ireland 2014, RSA Europe (OWASP Seminar) 2013, DeepSec, Austria (2013, 2014, 2015 and 2018), and GISEC, Dubai 2016. In his free time, he likes to participate in bug bounty programs. <b>Microsoft has recognised Ashar as No. 1 security researcher in Microsoft’s Security Response Center (#MSRC) Top 100 security researchers list of 2018 and at No. 4 spot in the 2019 and 2020 Most Valuable Security Researcher list. </b>He blogs at <a href="https://respectxss.blogspot.com">“Respect XSS”</a> and tweets at <a href="https://twitter.com/soaj1664ashar">@soaj1664ashar</a><br/>


Past Meeting/Event(s)
----------------------------------------------------

September 2020 Event Details
----------------
<b>Talk #1</b> <br />
Date - 26th September 2020 <br />
Time - 4:15 PM <br />

<b>DevSecOps:Separating Myth from reality</b> <br />
When you think about DevSecOps or DevOps, you probably think of tooling. A tool in every stage of secure SDLC, scanning on each commit. A few hundred to few thousand scans to gather all the issues for a project or maybe vulnerability management.Yet DevSecOps has completely changed the way we think of security. New ways of scaling information security mean that traditional security mechanisms like pentesting are no longer holy grails to secure organizations.More and more, organizations are working towards building security inside out rather than bolting it at the end, and security engineers are starting to see the benefits of this new type of security.But as more companies begin to embrace DevSecOps, both organizations and security managers have discovered that DevSecOps has its own complexities. These days there's more folklore than the science behind DevSecOps in organizations, more myths than reality.Yet with the right attitude and a few simple ground rules, companies can benefit significantly from DevSecOps.<br/>
In this talk, you'll also learn:<br/>
1. How organizations can bust DevSecOps myths and concentrate on reality.<br/>
2. Why it's a good idea to think DevSecOps program from the organization's point of view.<br/>
3. Why organizations need to streamline DevSecOps by concentrating on People, Process, and Technology.<br/><br/>

<b>Speaker - Mohammed A. Imran </b><br/>
Mohammed A. “secfigo” Imran is the Founder and CEO of Practical DevSecOps and seasoned security professional with over a decade of experience in helping organizations in their Information Security Programs. 
He has a diverse background in R&D, consulting, and product-based companies with a passion for solving complex security programs. He was the winner of DevSecOps Leadership award in United Kingdom for his contribution to the DevSecOps community globally. He was also nominated as a community star for being the go-to person in the community whose contributions and knowledge sharing has helped many professionals in the security industry. He is usually seen speaking and giving training in conferences like Blackhat, BruCon, DevSecCon, AppSec, All Day DevOps, Nullcon, and many other international conferences. He is the founder of Null Singapore, the most significant information security community in Singapore, where he has organized more than 60 events & workshops to spread security awareness.<br/>
His courses are avaiable at - <a href="https://www.practical-devsecops.com">Practical DevSecOps</a> 

<b>Talk #2 </b><br />
Date - 26th September 2020 <br />
Time - 5:00 PM <br />

<b>Fundamentals of Malware Analysis & Reverse Engineering</b> <br />

This talk will take you through the fundamentals of malware analysis with the live demonstration and you'll able to learn the following:<br/>
1. Why Malware Analysis ?<br/>
2. Malware Analysis Techniques<br/>
3. Malware Analysis Stages<br/><br/>

<b>Speaker - MOHAMMED SALAMI </b><br/>
Mohammed Salami is a Cyber Security Consultant with SITE  and  holds some of the prestigious certifications such as OSCE, GREM, OSCP, GPEN, GWAPT, EWPTX. His passion for Cyber Security started in early days of his schooling that led him to UK to pursue Bachelors in Computer Forensics & Ethical Hacking. Later, he completed his Masters in Cyber Security from UK as well. His area of expertise includes red teaming, malware analysis, penetration testing. He has been involved with the cyber security community from many years and was also nominated in the Top 10 UK university’s CTF, published cybercrime research for Saudi Arabia’s IT Security & Anti-Forensics techniques. He believes that sharing knowledge is one of the key to learn and grow. <br/>



<b>August 2020 Event Details</b> <br/>

Date - 29th August 2020 <br />
Time - 4:00 PM <br />

<b>Zero Trusting Your Enterprise - A Deep Dive Technical Implementation Guide.</b> <br />
Traditional IT network security is based on the castle concept. In castle security, it is hard to obtain access from outside the network, but everyone inside the network is trusted by default.
Zero trust security is an IT security model that requires strict identity verification for every user and device trying to access resources on a network, regardless of whether they are sitting within or outside of the network perimeter.
Zero trust s a holistic approach to network security that incorporates several different principles and implementations. We will discuss the best recommended ways to start implementing the zero trust concept in your enterprise.

<b>Speaker - Abdulrahman Al-Nimari </b><br/>
A self-motivated renowned cyber security expert and a frequent conference speaker with more than 25 years of IT and cybersecurity experience. Al-Nimari played different roles, in government and private sectors, in different IT and cyber
security fields: Network/System Administration, IT Management, Cybersecurity Advisory and Architecting. Always working to advance cyber security and contribute to community. Al-Nimari was awarded the Arab Social Media Cyber Security Influencer Award for year 2019. He holds industry standard cyber security and project management certifications:
CISSP, CISM, CCISO, PMP, GSEC, GCIA, GCIH, GCUX, GREM, BCVRE

March 2020 Event Details
----------------
<b>Date</b> - 14th March 2020 <br /> 
<b>Location</b> - Al Masaa Cafe, 2239 Al Urubah Rd, Al Wurud, Riyadh 12214 <br /><br />
<b>Schedule:</b> <br />
20:00 - Introduction to OWASP Riyadh and the annual plan <br />
20:30 - Brief Talk on "OWASP API Security Top 10" followed by Group Discussion<br />
21:00 - Coffee and Networking <br />

<b>Attending the event:</b> Kindly send us an email with your name and contact number to block your seat. 


Meeting Supporters
----------------

OWASP Riyadh conducts meetings/talks at various locations across Riyadh. Currently, we are organizing events virtually. We organize quarterly talks on various topics covering application security. Moreover, there are also CTFs and workshops planned frequently. 



Speaking at OWASP Riyadh Chapter Events
---------------------------------------

#### Call For Speakers

Call For Speakers is open - if you would like to present a talk on Application Security at future OWASP Riyadh Chapter events - please review and agree with the [OWASP Speaker Agreement](https://owasp.org/www-policy/legal/speaker-agreement) and send the proposed talk title, abstract and speaker bio to us via e-mail:

`aatif.khan (at) owasp.org`  OR <br> 
rayed.almutiry (at) owasp.org


 
