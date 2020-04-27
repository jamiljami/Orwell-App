# RS Implementation

## Overview
We use LightFM to produce a RS for users (voters/MPs/people) and bills (items). 
By learning from this, we can find embedding matrices that should hopefully represent certain views (right/left/etc) or topics (economy/health/education/etc).

Development Phases:
1. Obtain Data
2. Data Wrangle (Visualise/Direction)
3. Model

## Obtaining Data

// where do we get data from? -> use fake data (but also check TheyVoteForYou API)

// how do we link voters to parliamentary voting procedures? -> Helper function mapping "voter input" to parliamentary voting (in essence the Virtual MP)

// what is the "voter input"? -> a questionnaire of some sort??

## Data Wrangling and Visualisation

Fake Data Creation and Visualisation
// cluster visualisation (good and shows we can have groupings)
// link to jupyter book in repo
Notes:
* abstention votes are hard to predict, perhaps having a range from -1 to 0 to 1

LightFM Phase 1
// lightfm implementation
// link to thing in repo
Notes:
* look at RS phase 1 notebook
* look at whiteboard


