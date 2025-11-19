---
title: "Mapping the Bins – How one person used FOI to fix a very ordinary, very real problem"
date: 2025-11-18
summary: "Request for a database of public litter bins and recycling bins in the local area"
type: "case"
authority: "North Warwickshire Borough Council"
jurisdiction: "England"
topics: ["Community", "bins", "local-government", "rpsi"]
foi_refs: ["litter"]
draft: false
---

Kamran Ali wants to build a free app so residents of North Warwickshire can find their nearest public bin. That's it. Not a commercial venture, not a data harvesting scheme—just a straightforward civic tech project to help people dispose of their rubbish responsibly.

Which sounds like exactly the kind of thing councils should be falling over themselves to support, right? Open data, community engagement, residents taking initiative to solve local problems. All the things we're supposed to want.

Except it's now mid-November, and Kamran's been navigating the council's FOI process since September to get permission to actually use the data they've already given him.

## What Kamran's Trying to Do

The concept is simple: take the council's bin location data, convert it to a format that works on mobile devices, and display it on a map. If you're out and about with a coffee cup or a dog waste bag, you can check the app and find the nearest bin rather than carrying it around for twenty minutes or (let's be honest) leaving it on a wall somewhere.

It's the sort of low-stakes, high-utility tool that proves useful not because it's revolutionary but because it solves a minor everyday annoyance. No different from apps that show you the nearest public toilet, EV charging point, or bus stop.

The data already exists, the council maintains a spreadsheet of all their public litter and dog waste bins with locations. Kamran requested it under the Environmental Information Regulations in early September, and the council provided it within six days. Perfectly straightforward.

But here's where most people would run into a problem they didn't know existed.

## The Bit Nobody Tells You About

Getting data under FOI or EIR doesn't actually give you permission to republish it. Disclosure laws require councils to show you information; they don't automatically grant you a license to put it on a website or in an app.

That's governed by a completely separate piece of legislation called the Re-use of Public Sector Information Regulations 2015 (RPSI). And Kamran, unlike most requesters, knew this.

Six days after receiving the bin data, he sent a second request, this time under RPSI, asking for explicit permission to reuse the dataset under the Open Government Licence v3.0. This is the standard open license that allows anyone (commercial or non-commercial) to copy, publish, and adapt public sector information as long as they attribute the source.

His request was thorough. He explained exactly what he planned to do with the data (convert coordinates to JSON for a map interface), confirmed he wouldn't republish the raw spreadsheet, asked about attribution requirements, and even preemptively addressed potential complications around Ordnance Survey-derived coordinates that might have licensing restrictions.

It's the kind of request that shows someone's done their homework.

Then he waited.

## Twenty Working Days Came and Went

RPSI has a statutory response deadline of 20 working days. By early November, nearly two months had passed with no reply.

Kamran followed up. Politely, professionally, asking the council to confirm either that reuse was granted under OGL or that they'd be issuing a formal refusal notice with reasons and appeal rights.

On 18 November, the council finally responded:

> "Yes you can re-use as long as all personal and sensitive data is redacted."

Which is... not really an answer.

## What's Actually Wrong Here

**The bin locations aren't personal data.**  
We're talking about geographic coordinates for public infrastructure, "outside the library on Market Street" or "junction of X Road and Y Avenue." There's no personal data in this dataset. Nothing to redact. The council appears to have applied a reflex data protection concern that doesn't apply.

**"Yes you can re-use" isn't a license.**  
RPSI requires councils to issue clear licensing terms. What's the attribution wording? Can the data be adapted? Can it be used commercially? Can derivatives be created? None of this is answered. Kamran still doesn't have the legal certainty he needs to publish his app without potential IP infringement concerns.

**They didn't address third-party licensing.**  
Kamran specifically asked about Ordnance Survey-derived content. If the council's bin coordinates were generated using OS products, there might be licensing restrictions. The council didn't engage with this question at all.

**They're two months late on a statutory deadline.**  
RPSI responses are supposed to take 20 working days. This took nearly twice that, and only after Kamran chased.

## Why This Matters More Than One Bin App

This isn't about one frustrated requester or one council getting RPSI wrong. It's a pattern.

Local authorities hold enormous amounts of geographic data that would be valuable to residents: bin locations, grit bins, dog waste bins, EV charging points, accessible parking bays, public toilets, dropped kerbs, street furniture. Most of this should be open by default—it's factual information about public infrastructure that everyone's already entitled to see.

But there's a persistent gap between:

- **Disclosed** (handed over in response to individual FOI requests)
- **Published** (proactively made available on the council website)
- **Licensed for reuse** (explicitly cleared for republication and adaptation)

Kamran's trying to bridge that gap. He wants to take public data about public infrastructure and make it useful to the public. This is civic technology in its purest form—not a startup looking for VC funding, just someone trying to solve a small problem in their community.

And he's being stalled because the council doesn't quite know how to handle RPSI requests, even though the regulations have been in force for nearly a decade.

## The Bigger Open Data Problem

The UK has committed to open government principles through multiple international partnerships. We have strong transparency laws (FOI/EIR), good reuse regulations (RPSI), and a solid open license ready to go (OGLv3). The legal framework exists.

What's missing is consistent implementation at the local authority level.

Most council FOI officers are excellent at processing disclosure requests. They understand FOI exemptions, they know when to apply EIR instead of FOIA, they handle sensitive requests with appropriate care.

But RPSI sits at the intersection of FOI law, copyright law, data protection law, and third-party licensing agreements. It's a completely different skill set. The result is often well-meaning but legally incomplete responses like North Warwickshire's, officers trying to be helpful but not quite sure what's being asked or what answer to give.

There's no malice here. Just under-resourced teams dealing with legislation they rarely encounter, trying to do their best without clear guidance.

## What Should Happen

**For this specific request:**  
The council should issue a proper RPSI decision. Something like: "We license this dataset under OGLv3. Attribution should be: '© North Warwickshire Borough Council 2025. Licensed under the Open Government Licence v3.0.' No charges apply. The coordinates are derived from [source], which we believe falls within permitted reuse under OS presumption to publish guidance."

That gives Kamran legal certainty and takes five minutes to write.

**For councils generally:**  
Someone needs to write template RPSI responses for common datasets. Bin locations, licensing registers, planning applications—anything routinely disclosed under FOI/EIR that has obvious reuse value. Templates would save officer time and give consistent answers.

The LGA or ICO could do this. It shouldn't fall to individual councils to reinvent the wheel every time.

**For requesters:**  
If you're planning to republish FOI/EIR data in any public-facing format—website, app, social media, research paper, send a separate RPSI request. Spell out exactly what license you need (usually OGLv3). Mention your intended use. Flag any potential third-party IP issues upfront.

And be prepared to wait longer than you should, then follow up politely when the deadline passes.

## Where This Leaves Kamran

As of publication, he's still waiting for proper licensing terms that would let him publish his bin-finding app without legal risk.

The council has given him de facto permission ("yes you can re-use") but hasn't provided the license terms that would make that permission legally meaningful. He's in limbo—he has the data, he has vague approval, but he doesn't have the paperwork that protects him if someone later claims IP infringement.

Which means a straightforward civic project that would take a weekend to build is now stalled in its third month over licensing bureaucracy.

Meanwhile, people in North Warwickshire are still wandering around looking for bins.

---

_Kamran's full request thread is available on [WhatDoTheyKnow](https://www.whatdotheyknow.com/request/environmental_information_regula_47)._