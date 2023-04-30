---
title: Home
layout: home
---

> __Today we’re launching Clinic. It’s a free hosted practice builder for doctors with a “choose your own price” subscription model. Now any doctor in the US can create their own online clinic in minutes, for any kind of medical care, and start accepting subscribers immediately. Check it out at https://clinic.dev/__

# Features
* No code clinic builder which is free to use
* Built-in eRx with ECPS
* Custom formulary, intake forms & patient eligibility
* Admin tools to accept, reject or kick any subscriber you want
* Custom clinic page with dedicated URL
* Support up to ~2k/subscribers per clinic

# Why we built this

Despite there being a ton of online options in digital health these days, existing platforms tend to either:
 
* Limit their offerings to a few narrow indications (https://clinic.amazon.com/)
* Restrict providers to simple refills & one off video calls (https://www.teladoc.com/prescription-policy/)
* Position doctors to “work the platform” instead of building their own practices (https://www.wheel.com/clinicians)

There are some online marketplaces like <a href="https://sesamecare.com/" target="_blank">Sesame</a> & <a href="https://www.pushhealth.com/" target="_blank">Push</a> that give providers more independence, but these sites are bloated, don’t provide doctors their own practice page, and have convoluted pricing models. 

We think Clinic is really powerful because __it gives doctors free tools to create any kind of care experience they want__, and easily scale it online through paid subscribers. 

Some of the things you can easily do on Clinic:
* Create a 50 state insulin refill service
* Make a concierge clinic for fewer than 10 patients
* Make your clinic free ($0 subscription) 
* Build a members-only space for your sports team or school
* Tons of other cool stuff we haven’t thought of yet

We also spent time on customization so your clinic can be more than just a virtual doctor’s office. Give your clinic a name, upload your own favicon, share your link on Reddit or TikTok, and make announcements to the group (coming soon). When we built Clinic, we were inspired by other creator platforms like Discord and Twitch which taught us the power of online communities & private virtual spaces. We wanted to take this same idea and extend it into the realm of digital health. 

# Payments

Today there’s lots of different billing models in healthcare with no one size-fits-all solution. But if you had to choose one, we think it would be subscriptions. They are customer friendly, easy to implement, easy to cancel/refund, and set expectations for both parties that this is ongoing care based on a relationship vs “one & done” prescribing. 

Our subscription model also means doctors on Clinic have __zero upfront costs__ when building their clinics, and only pay once they’re earning.
When making your clinic, doctors are able to select their own subscription price, from $0/month* to $250/month, similar to a Substack or OnlyFans page. Your subscriber base is then calculated at the end of each month, and we remit your earnings via ACH, minus our marketplace fee. Currently, our fee is 20% of patient subscriptions, exclusive of credit card processing (2.9% + 30¢). *Up to 25 subscribers

# Technology
Clinic features an out-of-the-box virtual clinic that’s competitive with professional async operations like Hims, Roman, Nurx, & Thirty Madison.
With a Clinic account, doctors can easily build their own online clinic, customize it to any specialty or treatment type, and list it on the platform for free. 

_Example Clinic page_

To support your subscriber base, Clinic has a built-in workflow to manage patient requests & messages, an eRx pad with ECPS, and the ability to reject & kick any subscriber you deem unfit. 

_Example provider dashboard_

Future enhancements include community announcements, member group chat, native lab support, user invites, and an automated refill protocol.

# Who’s eligible
Clinic is eligible to all US licensed providers in the US (MDs, DOs, & APRNs) with prescribing authority. 
We currently approve provider accounts based on the following input:
* NPDB self-query within the last 60 days
* Proof of active malpractice insurance
* Successful verification using ID.me

# What’s restricted/what can’t I do
We generally allow everything, as long as it follows these simple rules & guidelines:
* We currently support ECPS, but don’t allow Schedule II prescribing of any kind
* All clinics should follow established standards of care in their domain of specialty 
* Doctors should not be recommending any unapproved therapies, devices or nutraceuticals 
* Patients should be notified in advance of drugs prescribed off-label
* Providers should not make lewd, sexual, racist or overtly discriminatory statements at any kind 
* We monitor prescribing habits for diversion and will alert authorities if any user attempts to abuse/circumvent our platform
* Anyone caught violating these terms will be summarily banned

# Getting started for doctors
At this early stage, we ask any provider interested in creating their own clinic to work with us directly. We can show you the ropes and get you up and running rather quickly. This is beta software though so bugs should be expected.

Those interested please send us a short message at __admin at mps.health__

# Architecture
Clinic is a monolith built on Ruby with a React front-end. Providers build clinics & manage patient flow through our subdomain <a href="https://run.clinic.dev/" target="_blank">run.clinic.dev</a> and patients access their care through the root domain, <a href="https://clinic.dev/" target="_blank">clinic.dev</a>

We don’t currently offer any apps in the app store.

Clinic is hosted on Google Cloud and is encrypted using AES 256K. 

# Data privacy
Clinic takes data privacy seriously. It is not our intention to collect, share or sell patient data to third parties. 

# Team
Clinic was built by me, __Mark Arthur Drew__, healthcare designer & autoimmune patient, __Theodore Yemc__, fellow RISD graduate & entrepreneur, and __Paul Damer__, full stack Ruby developer.

Additional technical support from __Besar Pllana__ & __Steven Gettys__. 

Legal support from <a href="https://www.buchalter.com/attorneys/andrea-r-musker/#bio" target="_blank">Andrea Musker</a> & <a href="https://www.wiggin.com/person/len-gray/" target="_blank">Len Grey</a>

# Get in touch
During our beta, customer service inquiries will be conducted exclusively over our Discord server. Please access it here: <https://discord.gg/RkK77ajn24>

For providers, business partners & pharmacies, the best way to get in touch is to direct message Mark on Twitter @mrkdrew . Alternatively, we can be emailed at __admin at mps.health__. Please keep email inquiries short.
