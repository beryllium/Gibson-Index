Gibson Index
============

* Version: 0.1.1
* Author: Kevin Boyd (aka Beryllium)
* Homepage: [www.gibsonindex.org](http://www.gibsonindex.org)
* Email: **admin at gibsonindex.org**

The Gibson Index is [a ranking system for the relative severity of Cyber Attacks](http://www.gibsonindex.org).

Media reports and political discussions surrounding computer security lack a simple structured context for communicating this information. This can result in simple concepts becoming muddled and intimidating.

There have also been cases where blame was not placed on the proper party. Often, the people discussing security events make analogies to "leaving the door open" and mistakenly portray certain types of events as common break-and-enter. This ranking system highlights that there can't be a break-and-enter when the house was built without walls. And, sometimes, your neighbour might come along and notice your door is open - they might poke their head in to see if anyone's home, and they might close the door behind them as they leave. They might even check again a few days later, to make sure you've been keeping on your toes. In this analogy, it's a favour - and an early warning to quickly harden your security to prevent more severe incidents.

The Gibson Index ranges from 0 to 7, with 7 being the most severe class of attack (resulting in multiple intentional deaths and/or egregious financial/economic damage).


### Overview

#### Gibson Level Zero

A level zero event is one that causes little or no disruption/damage, or is the result of a mitigating circumstance.

It is important to note that Gibson Level Zero events are not true cyber attacks. Advanced networking/testing tools may be the source of the events, but often the controller behind the tools is just an average person who has a curious mind - and no malicious intent.

In fact, Level Zero events are a great learning experience for system administrators. If a level zero event causes an issue on a network, it shows that the design of the network may need to be improved.


**Example Level Zero events:**

   * Port scanning
   * Pinging (including flood mode)
   * Limited probing of available ports, especially within protocol specification (e.g., weev and At&t, incrementing a variable in a GET/POST)
   * Some types of vulnerability scanning (e.g., Dawson College/Ahmed Al-Khabaz incident, highlighting security concerns and re-checking to see if they have been fixed promptly)
   * Inadvertently triggering a failure condition due to a bug in the code
   * Random person plugging both ends of a network cable into the wall (if you do this more than once, you're a jerk)
   * Observing and reporting Misconfiguration/Default Passwords on vendor systems (it is the responsibility of the vendor to secure their systems, and if they have made an oversight, it is important to notify them)


---
#### Gibson Level One

A level one event is one that has some small real-world consequences, but can often have non-malicious explanations. Typically, such an event would only target one website or computer network.

A distributed denial of service could be seen as a Level One event, if it is small in nature and only targets one server or network. Certain data leaks can be seen as Level One events, especially if the data being leaked is something that should be publicly available to begin with (see: [PACER](http://en.wikipedia.org/wiki/Aaron_Swartz#Investigations_and_prosecution)).

**Example Level One Events:**

   * Distributed Denial of Service Attack (short-term, low relative throughput, but usually intentional)
   * Distributed/Mid-Throughput Vulnerability Probing
   * Observing a default password or misconfiguration (Level Zero), and [taking small advantage to pull a prank](http://www.gibsonindex.org/blog/2013/02/12/zombie-alert/).
   * Data leak via accidental exposure. If a vendor leaves customer data world-readable, the fault lies with them and not with the person reporting the issue. However, depending on the nature of the data, disrespectful handling of the incident could elevate it to a Level Two Attack.
   * Certain intentional data leaks (PACER, JSTOR, Aaron Swartz) - as explained with regard to PACER, sometimes this does not constitute an attack.


---
#### Gibson Level Two

Level Two attacks have a clear malicious intent and can result in longer outages, more significant privacy issues, and generally more damage than Level One events.

If several Level One events are coordinated, they can be described as a Level Two attack under certain circumstances.


**Example Level Two Attacks:**

   * Large-Scale Distributed Denial of Service attacks with high throughput, extended downtime, and resulting costs
   * Corporate espionage tactics such as Key logging, Man-in-the-Middle attacks, SQL Injection (these are often signs of a clear malicious intent)
   * Site defacement of a small-to-medium-traffic property. This does not typically include social media accounts.


---
#### Gibson Level Three

Minor financial damages and moderate privacy implications, generally stemming from a partial penetration of systems. 

An example of this is the coordinated "watering hole" attack that saw machines from Apple, Twitter, and Facebook get infected with spyware/malware. By using a Level Two Attack to inject a malware payload onto a forum frequently accessed by developers of mobile software, the attackers were able to gain access to notable corporate networks - turning it into a Level Three Attack.

**Example Level Three Attacks:**

   * Coordinated multi-target large-scale Distributed Denial of Service (DDoS) attack
   * Cyberheist featuring minimal financial damage
   * Organized campaigns of Corporate Espionage against a single target over a short period of time
   * Site defacement of a high-traffic property. Associated downtime & rebuilding systems has a cost.
   * Botnet participation. A malware infection in a business can cause downtime (and attention should be paid to ensure it isn't part of a higher-level event)
   * Watering Hole malware infection, such as what led to the Twitter/Facebook/Apple breaches of early 2013.

---
#### Gibson Level Four

Major financial damages or privacy implications. Well-defended systems breached by vulnerability, with a clear intention of theft or destruction. 

An example of this is the Christmas Eve 2012 cyberheist against San Francisco's "Bank of the West". A DDoS attack was used to cover up an alleged $900,000 cyberheist.

Another example is the penetration of the New York Times and Washington Post over an extended period of time, reported in early 2013. The two targets were high-value for political spying. Theoretically, the attack could have led to the discovery of whistleblower names - which could have led to real-world consequences such as imprisonment.

**Example Level Four Attacks:**

   * Cyberheist. Substantial financial damages.
   * High-Value Espionage. New York Times and Washington Post penetrations of Jan 2013. 
   * Sabotage. Stuxnet was reportedly built to cause physical damage to equipment in a targetted lab, but there are many kinds of sabotage that could be carried out.


---
#### Gibson Level Five

Systematic, coordinated, broad penetration of a multitude of networks, likely perpetrated by a well-funded large team or nation-state.  

Several such attacks have been reported, both on a small scale (New York Times/Washington Post incident, Apple/Twitter/Facebook incident, covered above), and on a large scale (Shady RAT, Red October).

The large-scale attacks tend to be international, difficult to detect, and very highly targetted to individuals - indicating quite an investment in research, development, and planning. This strongly suggests that such attacks are generally carried out by national-states.


**Example Level Five Attacks:**

   * [Operation Shady RAT](http://en.wikipedia.org/wiki/Operation_Shady_RAT), remote access intrusions against high value targets of a political nature
   * [Red October](http://arstechnica.com/security/2013/01/massive-espionage-malware-relied-on-java-exploit-to-infect-pcs/) malware network, undetected for several years and targetted at high-value individuals


---
#### Gibson Level Six

Level Six threats remain mostly theoretical. They consist of attacks that manifest themselves in real-world, targetted, intentional damage. 

The closest known example to such an attack is the Stuxnet virus, which was thought to be carefully built to target a very specific piece of lab equipment in an unknown lab (suspected to be used for enrichment of nuclear materials in Iran). Stuxnet cast a very wide net, with only a single small target in mind. 

Future Level Six attacks could have an array of targets in mind, but with localized effects - such as commandeering a few drones at one base and using them in nearby attacks, or using lower-level attacks together with strategic and tactical information to distrupt a military operation.

What separates a Level Six attack from lower levels is that a Level Six attack will likely have a small number of casualties.


---
#### Gibson Level Seven

A Level Seven attack would result in mass casualties from intentional, targeted efforts. This is mostly in the realm of SciFi at the moment, but if careful watch is not kept, a Level Seven attack could have a profoundly negative effect on the world.

A US-based federal agency recently claimed that hackers had worked their way into Air Traffic Control systems. If that access were abused, perhaps by terrorists, it could theoretically result in multiple plane crashes.

The film Fight Club contained another example of a possible Level Seven attack (albeit, carried out by explosives - not exactly "cyber" in nature). The destruction of credit records on a mass scale would cause severe economic damage, and if the attack were carried out in the way it was depicted on film, the physical damage and casualties would be extensive as well.


---

## Inspiration and Call to Action

This document is just a basic overview, an early draft. It needs improvement through better examples and a refinement of the categories. 

_If you find inconsistencies or have input, please [submit an issue or fork and submit a PR](https://github.com/beryllium/Gibson-Index/issues)._ 

You can also reach out to **admin at gibsonindex.org** by email.

The inspiration for this document is the desire to counteract perceived persecution and vilification of people who have done little or nothing wrong - they are being elevated to the level of Hacker-Pariahs, but they have done nothing to warrant such persecution. The firestorms surrounding [Aaron Swartz](http://en.wikipedia.org/wiki/Aaron_Swartz#Investigations_and_prosecution), [Ahmed Al-Khabaz](http://en.wikipedia.org/wiki/Dawson_College#Student_Records_Security_Controversy), and [Andrew "weev" Auernheimer](http://en.wikipedia.org/wiki/Weev) are just a few examples of disproportionate responses to Gibson Level Zero or Level One events.

We need a guide to what constitutes a clear and present danger - [this is that guide](http://www.gibsonindex.org).
