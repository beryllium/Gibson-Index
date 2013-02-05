Gibson Index
============

* Version: 0.1
* Author: Kevin Boyd (aka Beryllium)

The Gibson Index is a ranking system for the relative severity of Cyber Attacks.

Media reports and political discussions surrounding computer security lack a simple structured context for communicating this information. This can result in simple concepts becoming muddled and intimidating.

There have also been cases where blame was not placed on the proper party. Often, the people discussing security events make analogies to "leaving the door open" and mistakenly portray certain types of events as common break-and-enter. This ranking system highlights that there can't be a break-and-enter when the house was built without walls. And, sometimes, your neighbour might come along and notice your door is open - they might poke their head in to see if anyone's home, and they might close the door behind them as they leave. They might even check again a few days later, to make sure you've been keeping on your toes. In this analogy, it's a favour - and an early warning to quickly harden your security to prevent more severe incidents.

The Gibson Index ranges from 0 to 7, with 7 being the most severe class of attack (resulting in multiple intentional deaths and/or egregious financial/economic damage).


Overview
=========

Gibson Level Zero
-----------------

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


Gibson Level One
----------------

A level one event is one that has some small real-world consequences, but can often have non-malicious explanations. Some groups have suggested that DDoS events are a form of protest, rather than a true attack. However, since bandwidth has a cost, some DDoS events are more attack-like than others.


**Example Level One Events:**

   * Distributed Denial of Service Attack (short-term, low relative throughput, but usually intentional)
   * Distributed/Mid-Throughput Vulnerability Probing
   * Accidental data leaks (if a vendor screws up and essentially leaves customer data world-readable, it is not the fault of the readers - but what the reader and the vendor do to exploit or fix things, respectively, can escalate the event to Level One or higher)
   * Certain intentional data leaks (PACER, JSTOR, Aaron Swartz)


Gibson Level Two
----------------

Level Two attacks have a clear malicious intent and can result in longer outages, more significant privacy issues, and generally more damage than Level One events.

If several Level One events are coordinated, they can be described as a Level Two attack under certain circumstances.


**Example Level Two Attacks:**

   * Large-Scale Distributed Denial of Service attacks with high throughput and resulting costs
   * Key logging, Man-in-the-Middle attacks, SQL Injection (these are often signs of a clear malicious intent)


Gibson Level Three
------------------

Minor financial damages and moderate privacy implications, generally stemming from a partial penetration of systems. 


**Example Level Three Attacks:**

   * Espionage. This can be anything from credit card skimming at a single business, to an internal corporate forum being hacked to gather business intelligence.
   * Site defacement. Associated downtime & rebuilding systems has a cost.
   * Botnet participation. A malware infection in a business can cause downtime (and attention should be paid to ensure it isn't part of a higher-level event)


Gibson Level Four
-----------------

Major financial damages or privacy implications. Well-defended systems breached by vulnerability. 


**Example Level Four Attacks:**

   * High-Value Espionage. 
   * Sabotage. 
   * New York Times, Washington Post, Twitter penetrations of Jan 2013. 
   * Operation Shady RAT. http://en.wikipedia.org/wiki/Operation_Shady_RAT


Gibson Level Five
-----------------

Systematic, coordinated, broad penetration of a multitude of networks, likely perpetrated by a large team or nation-state.  


**Example Level Five Attacks:**

   * Red October. http://arstechnica.com/security/2013/01/massive-espionage-malware-relied-on-java-exploit-to-infect-pcs/


Gibson Level Six
----------------

Level Six threats remain mostly theoretical. They consist of attacks that manifest themselves in real-world, targetted, intentional damage. 

The closest known example to such an attack is the Stuxnet virus, which was thought to be carefully built to target a very specific piece of lab equipment in an unknown lab (suspected to be used for enrichment of nuclear materials in Iran). Stuxnet cast a very wide net, with only a single small target in mind. Future Level Six attacks could have an array of targets in mind, but with localized effects.


Gibson Level Seven
------------------

A Level Seven attack would result in mass casualties from intentional, targeted efforts. This is mostly in the realm of SciFi at the moment, but if careful watch is not kept, a Level Seven attack could be unimaginably catastrophic.

One well-known SciFi example: Skynet.




Inspiration and Call to Action
==============================

This document is just a basic overview, a first draft. It needs improvement through better examples and a refinement of the categories. _If you find inconsistencies or have input, please submit an issue or fork and submit a PR._

The inspiration for this document is the desire to counteract perceived persecution and vilification of people who have done little or nothing wrong - they are being foisted to the level of Hacker-Pariahs, but they have done nothing to warrant such persecution. The firestorms surrounding Aaron Swartz, Ahmed Al-Khabaz, and Andrew "weev" Auernheimer are just a few examples of disproportionate responses to Gibson Level Zero or Level One events.

The media needs a guide to what constitutes a clear and present danger - this is that guide.








