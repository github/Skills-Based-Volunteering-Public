![image](https://user-images.githubusercontent.com/70599317/110247783-e95e4700-7f3b-11eb-877b-b0f1884ed13c.png)

# About DHIS2
DHIS2 stands for the district health information software and is the world's largest health management information system (HMIS) platform, in use by 72 low and middle-income countries. 2.3 billion people (30% of the world's population) live in countries where DHIS2 is used. DHIS2 is an open source software and is a digital public good supporting SDG 3: Ensure healthy lives and promote well-being for all at all ages.

## How DHIS2 uses GitHub

- DHIS2 is fully open source and is hosted on GitHub
- DHIS2 maintains a number of libraries
- GitHub Actions for deployment and publications to npm
- Repo pulls into .war files 
- Most CI/CD is in Actions now

## Skills Needed
- JavaScript
- Java

## Experience Needed
- Actions set up and configuration
- Experience with [GitHub Classroom](https://classroom.github.com/), instructional design, online learning
- Experience and/or interest in public health
- Experience and/or interest in tech tools for sub-Saharan Africa

# About the Projects/Products including in Skills-based Volunteering

_To see descriptions and examples of project maturity levels, [(right) click to read this deck in a new tab](https://docs.google.com/presentation/d/1fVOChiPK4xJKT5s9W2M_MXqz0VcLwh3jx31c1HBqgPM/edit?usp=sharing)._

## 1. Product documentation - Established maturity level project
DHIS2 needs volunteers to build out [4 quadrants of documentation](https://documentation.divio.com/) for a suite of tools targeted at 3rd party web application (and Android app) developers on [https://developers.dhis2.org](https://developers.dhis2.org). These are the types of documentation they are envisioning:
- Getting Started tutorials (minimal amount exists already)
- How-to guides (minimal amount exists already)
- Technical documentation (already exists to some extent, could be improved)
- Concepts (need more, but likely a task for the DHIS2 core team)
  
### Project Board Link - coming

## 2. Self-paced Training Materials Project - Established maturity level project
DHIS2 has hosted several live online trainings and webinars, but would like to consolidate and formalize standalone, self-paced materials. These are ideas they are considering:
- This could also include helping to develop a self-paced course for developers (we have used [OpenEDx](https://open.edx.org/))
- Possible synergy with [GitHub Classroom](https://classroom.github.com/)!
- There are also some formal and semi-formal education programs (university level) teaching DHIS2 app development in Norway, South Africa, Mozambique, and others - could be collaboration opportunities

### Project Board Link - coming

## 3. GitHub Actions End-to-End Testing - Concept maturity level project
DHIS2 is looking for volunteers to help them create end-to-end testing on their applications using GitHub Actions against multiple versions of the server, versions of the database, etc.

- DHIS2 is composed of 30+ core web applications and 1 Java server
- DHIS2 supports 3 versions of the Java server (18-24 months of support)
- DHIS2 is moving our applications to be independently released
  - This will significantly improve our application development velocity
  - Avoids costly application backports
  - Requires testing all application changes against multiple DHIS2 backend versions
- DHIS2 currently does most testing manually but are increasingly implementing Cypress test
- DHIS2 would like to support end-to-end testing with live backend instances and databases
- This (natively) requires seeding and spinning up GitHub Actions services for multiple backend versions before running a testing matrix
- We would like to build an infrastructure for these multiplexed end-to-end tests on GitHub Actions that is efficient (minimal test scaffolding overhead) and easy to use (easy to write new tests)

### Project Board Link - coming

## 4. Multi-Calendar Library - Concept/Pilot muturity level project
DHIS2 is looking for volunteers to help them build a new javascript non-standard calendar. DHIS2 is used in 70+ countries, several of which use calendars that newer versions of DHIS2 does not support. These countries are thus blocked from upgrading to a newer version of DHIS2. Example countries are:
- [Ethiopia](https://en.wikipedia.org/wiki/Ethiopian_calendar) - DHIS2 has an engineer in Ethiopia who has put a fair amount of thought into this)
- [Nepal](https://en.wikipedia.org/wiki/Vikram_Samvat) - stuck on old DHIS2 versions, but DHIS2 has some support for this calendar
- [Solar Hijri](https://en.wikipedia.org/wiki/Solar_Hijri_calendar) - Afghanistan & others (stuck on old DHIS2 versions)

There are a few existing open-source projects, but most have stagnated or are based on outdated technologies like jQuery.  DHIS2 thinks there’s potential that this could become a standalone general-interest OS project. There would be three layers to multi-calendar support in DHIS2
- Browser UI elements (in the DHIS2 design-system)
- Javascript date conversion engine (could be based on existing libraries)
- Database and analytics multi-calendar support (difficult and tightly coupled with core functionality)

### Project Board Link - coming

# Social Impact Tracking
Parameter | Value for Partner Org
--------- | ---------------------
SDG Goal(s) | 3
SDG Target(s) | 3.4, 3.5, 3.7, 3.8, 3.9
Partner Org is in Benevity? | Yes/No
Ovio Collection | Public Health / COVID-19
Required webinars | General tech for social good + public health/COVID-19
