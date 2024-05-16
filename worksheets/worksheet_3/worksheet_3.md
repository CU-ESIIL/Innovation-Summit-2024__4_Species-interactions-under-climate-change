# TEAM ACTIVITY 2: Innovate as a Team

Welcome back! We hope today is a productive day getting to know your team and coding.

## Day 2 summary: 
Please complete the warm-up with your team, briefly review today’s objectives, and carefully read the Day 2 and Day 3 report out items to guide your efforts.  

## Objectives for Day 2
1. Work together to decide on the data sets you will use. Reminder: Use a decision-making technique discussed during Day 1. Kaner’s Gradient of Agreement is below for reference.
2. Practice joining your datasets together. 
3. Discuss and try creating interesting graphics.
4. Report back on your results at the end of the day. Today’s report back is short and focused on your team process. The Day 3 report back is more detailed. 


## Morning Warm-up
Please share the following informaton with your team. (No need to write down your responses this time)
- Name
- Pronouns
- Reflecting on Day 1, what is something that surprised you?

## Decision-Making
Use the gradient of agreement (Kaner 20214) to make decisions as a team.

We will use the gradients of agreement to make big decisions, but expect to reach consensus on any permanent/written products.

![Gradients of agreement](../worksheets/love_gradient-of-agreement.png)

## Day 2 Morning Notes - Colleen

**Group Decision Making**
- We will make most decisions using the decision gradient tool, but final *written* decisions (e.g., final research question and strategy) will be decided via consensus

**Identified tension**
- Are we methods/data drive OR are we system/hypothesis driven (e.g. type of species interaction?) (Maybe more methods/data driven, with bias towards systems we know well)
- Are we climate change response driven or mechanistically drive? (Probably more response/change driven)

**Research Questions**
 - General focus: How does climate change affect specie sinteractions
   - Explanatory variables: change in climate or some climate change-connected extreme event of some frequency/severity, and habitat/geographic variables
   - Response variables: number of interactions, functional diversity, phylogenetic diversity
- [Pablo's general research ideas] https://docs.google.com/presentation/d/1pUqs0mrHxMR-FMcc_acRCcLccBqBfMEz/edit?usp=sharing&ouid=105655421727470960440&rtpof=true&sd=true

**Methodologies**
- Pull lots of data into cyverse and explore
- Scrape EDI repository and upload to cyverse
- build rtool to pull relevant data from EDI revelant to question
- merge LTER and NEON data
- Need to think about the spatial scale of the data: are we working at the regional scale or ecotone level?
  - Our questions will probably require longitudinal data (20-30 year timespan) to more explicitly test influence of climate change over time (need deep data)
  - Location of data: NEON or other network sites vs. custom sites vs. dispersed data (e.g., community science data)
- Functional traits of a given site (PCA to represent diversity, distance matrix)
- Phylogenetic traits: use phylogenies (narrows down the types taxa we work with). 

**Datasets/Databases**
Some options
- IWDB
- TRY
- GIFT
- Plant for a future
- Web of life (binary species interaction data) combined with some richer, deeper, data source
- NEON (good habitat/landscape data!)
- Tamburini agricultural insect trait dataset
- EltonTraits Bird/Mammal trait dataset
- NEED: timestamped, local exteme/climate event data (e.g., drought, hurricane)

**Goals**

- We should plan to work with Pablo's general idea and framework and adapt our various broader ideas to this framework
- We will spend the afternoon solidifying the datasets we want to use (and therefore the specific interactions that we will focus on)
  - We will start with looking into using iNaturalist image data to do some image ID via Miguel

## Day 2 Morning Notes - Miguel


**Your CyVerse account:**
Miguel Leon: miguelcleon
Colleen: ccm246
YJ: yjsu1028
Grant: grant5500
Pablo: pmoreno92 

CyVerse share location: /iplant/home/miguelcleon/group4b
/iplant/home/shared/iplant_esiil_summit/2024/group_04b

**ESIIL - 5-15-2024**
**Possible outcomes from groups**
- When are we meeting next?
- One pager? 
- Conceptual Framework
- A figure that describes your project
- List of data sources
  - Later
    - Lets put together a conference abstract 

**Team 4b**
- Tension between broadness and narrowing in 

**Datasets**
- LUQ LTER 
  - Phenology of Forest Dynamics Plot - ~160 species of flowering, fruiting and seeding; ~30 years 
    - I have some specific functional trait data for some species 
    - Leaf area; max height, etc 
- Bird surveys - 1989 -2021 annual population survey
- Gastropods
- Phasmids (Walking sticks)
- Shrimp; aquatic insects 
- Met, precip min max temp
- LTER Network; We can try to pull data similar data




**Ideas**
- We can try to pull the data into CyVerse - having a bunch of data in a shared space in CyVerse could be a product we can pull together  
- I can scrape the entire EDI Data repository - I have code to do this 
  - We could then work on categorizing it - what are potentially relevant data to species interactions; morphology; functional traits 
    - Are methods comparable? 
  - I can scrape metadata to find keywords - I already have code to do this  
    - This assumes metadata are sufficient to find what we are looking for. 
- Build an R tool for pulling functional trait data for LTER
  - Potentially add the ability to merge it with NEON data 
    - Pitfalls
      - Divergent methods might make data incongruous 
- Make a specific example of merging some LTER data with some NEON data for species interactions and climate change 
  - Extreme  events - 
    - I have drought periods and hurricane events defined - 
    - frequency and severity of drought
  - Similar data from the same site or same ecotone - 

**YJ** - 
- Web of life - 
  - Species interactions from several different species 
  - Some of these have interaction strength 
  - Paired data 0,1 species interact or not 
  - Bees - comparable with inaturalist data 
- Resilience 
  - Recovery rate 
- Resistance 
- How do we choose the reference point? 


**Grant**
- Decide first the location, NEON sites 
- Customized location list - any location in the world? 
- Response variables - should be about resilience - 
  - Quantify the resilience, changes in the number of interactions to quantify resilience 
  - Functional trait diversity
    - Collect multiple traits - reduce multiple traits into a single composite index, distance matrix  
  - Philogenetic diversity 
    - Philongeny 
  - Community level or species level
    - One value about resilience, one about location, 
  - Explantory variables - climate, temp or precip changes 
    - NEON data - soils- sand, silt, clay
    - Geographical variables 
  - Make a proposal first -   
  - Seed disposal database - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10354656/ 
**Pablo** 
- Pollination change - powerpoint 	
- Plantnet 
**Phylogenetic trees - rtrees**
- Connects to Rgbif API  
  - Search inaturalist - for pollinator 
**Ruby throated hummingbird**
  




## Day 2 Report Back
Day 2 report-back questions are about the team *process*. We are interested in your team’s unique experience. Below are some prompts you might consider. You don't need to address all of them - choose which ones you want to present. Please limit your reflection to 2-3 mins.  

1. **What worked well for your team?**
- Each able to contribute some ideas about directions to move in
- Then considered a variety of ideas
- Then reached a conclusion about ways to move forward
- Found a good way to agree on how to balance data-driven questions and system based paths 
- Everyone has been very proactive/productive and has naturally found roles

3. **What’s one thing you would change?**
- Could have been more structured, but may be inherent to the process
- Could have talked about communication styles earlier in the process, but we got around to later
- Maybe could have created a central hub earlier (maybe more quickly facilitated)
- We need a parking lot before we leave

5. **Did your group ever have an “ah-ha” moment?  What led up to that moment?**
- We captured the decision gradient mindset to move forward
- Applying the cloud of ideas to the plant-pollinator

7. **Did your group experience the groan zone?  What is one tip you want to share with future groups at the Summit about getting through the groan zone?**
- Yes, definitely. 
  - Getting project management structure earlier might be helpful. 
  - Hard to generalize
  - Definitely a necessary step


**************************************************************

### Looking Ahead: Day 3 Report Back
*These are the prompts for the final Report Back **tomorrow (Day 3)** - start thinking about these questions as you work today. Each group will share their Day 3 GitHub page on the screen and give a 4 minute presentation.*

- **Project Title:**
- **Research Question:**
- **One interesting graphic/finding:**
- **What are you thinking about doing next with your team? Long-term, short-term?**
- **What’s missing: what resources, people, data sets, etc. does your team need?**
      
### Reminder
There is the opportunity for groups to continue working on their projects as an ESIIL Working Group. If you love your team and want to continue working together, considering submitting a Working Group Application this fall. See the ESIIL website for more information: <https://esiil.org/working-groups>.
     

