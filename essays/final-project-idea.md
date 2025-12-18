---
layout: essay
type: essay
title: "Final Project Idea"
date: 2025-11-04
labels:
  - Software Engineering
  - Nextjs
---
<img class="img-fluid" src="../img/fish.png">

# Project: CatchMap Hawaii

## Overview

**The problem:**  
UH Manoa students and local anglers do not have a simple, trustworthy way to learn which nearshore areas tend to produce certain species, when conditions are good, and what bait or gear works. Forum posts and social media are scattered, and they often reveal too much location detail or contain unreliable information.

**The solution:**  
CatchMap Hawaii is a UH focused fishing web app where users log catches by general area and species, with optional photo, bait, and notes. The app compares two datasets for insight. First, a baseline of species that are commonly expected in each area. Second, the actual community reported catches. Each user gets a personalized dashboard that suggests target species, times, and baits based on their own history and current reports. Location privacy is built in by using broad study areas rather than exact GPS points.

---

## Approach

After logging in, a user can record a catch with species, area, optional bait and gear, length or weight, and a short note. The map shows generalized areas like Magic Island Lagoon or Heeia Pier with privacy radius blur. Each area displays two views side by side. Known likelihood from a curated baseline. Recent reports from community logs. The system highlights agreement or surprise patterns such as expected but not seen recently or unexpected but reported.

There are three roles. Regular users log catches and browse areas. Verified contributors can propose new areas and species entries. Admins review flagged posts, approve new areas, and maintain the baseline dataset.

The special sauce is personalization. The app learns a user’s study areas, baits, and successful times and recommends what to try next. For example, it might surface omilu at Ala Moana Reef in early morning with grub lure based on the user profile and recent reports.

---

## Some mockup pages include

- **Landing page:** Project overview, example map tiles, login and register links.  
- **User dashboard:** Recent catches, suggested targets this week, streaks, and badges.  
- **Catch log page:** Simple form to add species, area, photo, bait, release status.  
- **Area page:** Two panels showing known species vs reported species with agreement badges and recent photos.  
- **Species page:** Top known areas and top reported areas, seasonality notes, size and bag info.  
- **Admin page:** Review queue for flagged posts, approve new areas, manage baseline entries.

---

## Use case ideas

- New user visits the landing page, logs in, and adds a papio catch from Magic Island Lagoon with cut squid. The dashboard updates and shows a suggestion to try early morning at the same area later this week.  
- Returning user opens the Area page for Heeia Pier. The page shows that oio is expected but there have been no recent reports. The user decides to try another recommended area where oio has been reported in the past 30 days.  
- A verified contributor proposes a new shoreline area with a short description and centroid. An admin reviews and approves it.  
- Admin logs in to remove a post that shared exact GPS or sensitive details and reminds users about the area level privacy policy.

---

## Beyond the basics

- Add tide, moon, and weather overlays to improve recommendations.  
- Offer a simple bait effectiveness view per user and per area.  
- Provide optional photo assisted species suggestions to reduce mislabels.  
- Introduce community events such as catch and release week and friendly challenges.  
- Publish privacy first heatmaps that require a minimum number of distinct reporters before public display.  
- Partner with UH clubs or local groups for citizen science summaries and education on size limits and sustainable practices.

---

**Authors:**  
Noah Oya and [add your team members here]

*This essay was collaboratively written by all listed authors.*

