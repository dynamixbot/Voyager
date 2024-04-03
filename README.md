# Voyager

Hello! Welcome to Voyager, A better alternative to ScratchDB. Voyager is being currently developed by @NotFenixio and me, @dynamixbot. We are developing Voyager to work as an open-source and faster alternative to ScratchDB, which faces frequent downtimes and has caused havoc to ScratchDB-reliant services.

## Devlopment of Voyager

Voyager is split into two parts, Pioneer, the scraper and Horizons, the database. Both will be gone into great development details. This system allows for more efficiency, faster data updation and lower downtimes in comparison to ScratchDB. Voyager and its subdivisons will be completely open-source, and code modification requests to fix bugs and vulnerabilities will be greatly apprecciated.

### Pioneer (scraper)

Pioneer is the scraper for Voyager, which scrapes the Scratch Forums (since there is no API for the forums). Pioneer works by going to forum pages in the 4 major categories, Welcome to Scratch, Making Scratch Projects, About Scratch and Intrests Beyond Scratch. Currently, we are not adding support for Scratch Around the World, but will be added in a future version after a first stable release and implement.

Each major category has its subcategories like Advanced Topics in About Scratch. Bots (which respect the 10 requests at an instance rule) scrape the subcategories. Each bots have microbots (macros) which scrape individual topics. There are 25 macros in a bot. The macros have even smaller bots called nanobots (nanos) which scrape each page of a topic. All of these subdivisons run in parallel and every aspect of each topic. This bot also records post counts by checking the username and adding to a count for every forum post. Pioneer is designed to record every aspect of the Scratch Forums.

The current expected programming language for Pioneer is GO (Golang) due to its speed and efficiency with adavnced features built-into the standard library. Ports of Pioneer into different programming languages or transitions to different programming languages are not planned, but transition notifications will be given and old versions would still have support until 1 year after new release.

### Horizons (database)

Horizons is the database system for Voyager. It takes data from Pioneer and stores it in its database. Horizons has a file storing system called x

To be updated, do not merge, I REPEAT DO NOT MERGE
