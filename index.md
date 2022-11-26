---
layout: default
---
# Jeremy Mayeres

## About Me

I'm a software engineer living in Finland, currently working as a Python developer at Iceye.
I'm originally from Belgium, although I grew up in Florida.
I have dual United States and Belgian citizenships.
In high school I did the International Baccalaureate and Computer Science programs.
I then studied Computer Science at the University of Central Florida in Orlando,
with a minor in Legal Studies. During that time, I was an intern at Lockheed
Martin in Cape Canaveral, FL. I graduated in May 2012 with Honors. I then worked for
two years for Harris Corporation doing embedded software development before
moving to Berlin in 2014 to work for BlackBridge. In 2015, BlackBridge was
acquired by Planet. In November 2018, I started working for Architrave GmbH.
In October 2020, I started working remotely for Iceye before moving to Finland
in April 2021.

## Tech

My current primary programming language is **Python**.
I have previous experience in C, C++, and Java.
Additionally, I've done some smaller work with HTML/CSS, JavaScript, and Ruby.

In the Python world, I use **Django** (mostly with Django Rest Framework), Flask, and FastAPI for REST APIs, and **Celery** for distributed processing of tasks.
For my job at Planet, I used **GDAL** and **Numpy**, and have made some minor contributions
to the GDAL project.

In terms of DevOps and Site Reliability Engineering, I use **Docker** for building, testing, and production deployments, with **Kubernetes** handling the container orchestration.
Infrastructure is kept in code with **Terraform**, and Kubernetes applications are deployed using Helm. I am currently using mostly **AWS**, although I also have previous experience with **Google Cloud Platform** and other Infrastructure as a Service providers.
For CI, I primarily use GitHub Actions, and previously used Infrabox, GitLab CI, Jenkins, and Travis CI.

I've used Linux and Mac heavily for development, first learning Linux when I
was in middle school. I mainly use the Fish shell (though I still end up having
to write a lot of Bash scripts for servers).

## Projects

### [Is it Snowing in Berlin](https://github.com/jerr0328/isitsnowinginberlin)

I made [isitsnowinginberlin.de](http://isitsnowinginberlin.de) as a side project
to experiment with Node.js and play with deploying something to Heroku. It uses
Redis to cache the weather data, with the data coming from OpenWeatherMap. In
2017 I rewrote the app in Python using Flask. I also changed the API source to Dark Sky, and experimented with having the app run using serverless functions.

## Work Experience

### [Iceye](https://www.iceye.com/) - Senior Software Engineer (Oct 2020 - Present)

Working since October 2020 for Iceye, a Finnish SAR satellite company. I am working on the mission control software,
doing backend development as well as supporting the DevOps culture with improvements to our GitHub Actions,
Kubernetes deployment workflows (including setting up Helm charts for our various components), and improving
the logging and monitoring.

### [Architrave](https://www.architrave.de/en/) - Senior Software Engineer (Nov 2018 - Sep 2020)

In November 2018, I started at Architrave GmbH in Berlin as a Python Software Developer in a small team.
I mainly work with Python 3 using Celery, with deployments using Docker and Kubernetes.
One of my largest projects involved me designing and developing a system to OCR, classify, and extract data from PDFs. During this time I also helped colleagues improve their Python and Kubernetes skills.
I set up the CI system (Infrabox) on our Kubernetes infrastructure as an initial solution until Github Actions became available.
I am a member of the Site Reliability Chapter, responsible for maintaining reliability, availability, and delivery of our services.
My involvement includes designing a platform for engineering teams to use, as well as researching the right tools to help solve our problems.

In 2020, I was a founding member of a new team, where I have set up the projects using Terraform on AWS, including the setup of a Kubernetes cluster there, with automatic, continuous deployments for development and staging environments.
Working in a cross-functional team, I support not only the infrastructure but also doing development in our Python 3/Django application but also supporting QA testing infrastructure, defining coding standards for Python (relying on tooling), and also contributing changes to frontend code when necessary.

At Architrave, we have a concept of "XP Days" (Experience Days), where once a month everyone in the engineering team can pitch ideas and work on them in teams of their choice. I have been the lead for the Table Tennis Scoreboard project, which keeps track of our daily table tennis matches at the company and provides a leaderboard.
The project is in Python 3 and Django (with Django Rest Framework), and interacts with Slack using the Slack API and Slash commmands. The following Monday, the results are presented at the company all-hands in short, 5 minute presentation and demo.

### [Planet Labs Germany](https://www.planet.com) - Squad Lead, Senior Software Engineer (Sep 2014 - Oct 2018)

I started at BlackBridge in Berlin in September 2014 as a software developer for
the RapidEye data pipeline, mostly working with C++, with some Java and Python.
In 2015, Planet acquired BlackBridge. Since then, I've worked on getting the
RapidEye data uploaded to the cloud-based platform and processed alongside the
PlanetScope data. In early 2017 I was promoted to squad lead for the Berlin
Data Pipeline, leading a team of 5 other engineers to work on processing RapidEye,
SkySat, PlanetScope, and third party (including Sentinel and Landsat) satellite data.

Core technologies used include Python, GDAL, Numpy, and Docker.

Some key tasks included:
* Port calibration tool from Matlab to C++ to be included in processing chain
* Introduced tools and processes into the team workflow:
  * Encouraged use of Wikis for documentation by creating the first Confluence pages
  * Introduced chat tools for better team communication
  * Advocated for more Agile processes (including Scrum and Kanban)
* Develop Python-based wrapper scripts that handle file-based XML messaging
* Design and develop system to process and upload RapidEye data via legacy processing chain
* Support development of microservices in a Mule Java Enterprise Service Bus
* Port services and software to Python/Django as we shifted to a Python as a main language
* Develop tool to process and upload hundreds of terabytes of RapidEye archive data to the cloud
* Lead the development of the SkySat data processor to bring pre-processed high-resolution (\<1m GSD) data to our customers for the first time.
* Improve monitoring with DataDog, SignalFx, and Sentry
* Deliver high-quality products on schedule while maintaining existing systems

### [Harris Corporation](https://www.harris.com/) - Software Engineer Level 2 (May 2012 - July 2014)

I started at Harris in Palm Bay, Florida in May 2012 as an embedded software
engineer. My first project was in a mission avionics program working on
developing mission processors. The work involved integrating hardware, finding
firmware and software issues, and development of a built-in-test (BIT) system
to gather BIT data and report results via a custom web server. The code had to
run on VxWorks (6.x, MILS) and Linux. I received multiple internal awards for
this effort.

Some key tasks included:
* Developing Built-In-Test (BIT) aggregator and web server
* Integration of Commercial Off-The-Shelf (COTS) and internally-developed hardware
* Port IPv6 conformance suite to Linux to support critical milestone

I then moved to working on FliteScene, a digital moving map software product.
I was one of the main developers working on implementing new features, finding
and fixing bugs, supporting demos and traveling to customer locations when
needed. The software is written in C++ using the OpenGL ES 1.1 and OpenGL SC
(Safety Critical) 1.0 specs.

Some key tasks included:

* Porting software to new operating systems
* Updating code and projects to support 64-bit
* Refactor Android library/SDK with improved gesture code
* Find issues using static code analysis tools
* Support upcoming releases by preparing and updating documents, scheduling meetings, running tests and updating test scripts
* Suggested and implemented process-improvement ideas
* Update Linux projects to build shared-object and static libraries
* Demo hardware and software to customers
* Coordinate with different departments to get documents prepared for conference

### [Lockheed Martin](http://www.lockheedmartin.com/) - Software Intern (Jun 2010 - Aug 2010; May 2011 - Aug 2011)

Developed production code for an interactive electronic technical manual for a mission-critical program. Worked alongside full-time software engineers.
Technologies used: Java, JSP, Javascript, Oracle PL/SQL.
Also updated ActiveX interface to the RFID SDK and provided direction to resolving ID mismatch issue.

## Interests

* Technical Theatre - Lead theatre tech in high school, trained students in lighting, sound, rigging, and overall theatre upkeep and safety. Focused on stage lighting. Continued in college in working alongside professionals to set up and support concerts and live comedy.
* Amateur Radio - License amateur radio operator in US as General class. Became president of the Amateur Radio Club at UCF.
* Hardware - Worked in embedded development before, like to play with Arudino and Raspberry Pi.
* Avionics - Running ADS-B receiver to feed data into FlightAware.
* Spaceflight - Besides working for the largest private operator of satellites, I attended many launches in Florida and had semi-private tours of space launch facilities at Cape Canaveral/Kennedy Space Center.
* Digital Forensics - Took Master-level class in Digital Forensics at UCF, took Cybersecurity specialization on Coursera.
* Martial Arts - Practiced martial arts in middle and high school. From 2017-2018 I attended Taekwon-Do classes in Berlin.
* Mobility - I am interested in railways, aviation, and new forms of urban mobility with carsharing, scooter and bike sharing. I have my own bike and am interested in eBikes, cargo bikes, and how cities can adapt and change to improve the quality of life.


## Volunteering

* [OpenStreetMap](https://www.openstreetmap.org/) - Contribute to OSM, including Humanitarian OpenStreetMap mapping.
* [Berliner Tafel](https://www.berliner-tafel.de/berliner-tafel/) - Sorted unwanted food
* [Berliner Obdachlosenhilfe](http://www.berliner-obdachlosenhilfe.de/) - Prepared and distributed food for the homeless
* Habitat for Humanity - Helped build homes in Melbourne, FL
* Harris High School Design Challenge - Get students involved with Science, Technology, Engineering, and Math (STEM) in local high schools. The design challenge consists of teams of high school students creating a mobile application to solve certain challenges. My responsibilities included updating the Android framework, judging preliminary presentations by the students, and being a "dispatcher" during the actual competition.

## Education

### University of Central Florida
_August 2008 - May 2012 in Orlando, FL_

Graduated with Bachelor of Science in Computer Science, Magna Cum Laude with University Honors, from Burnett Honors College with Legal Studies minor. GPA: 3.9/4.0

### Suncoast Community High School
_August 2004 - May 2008 in Riviera Beach, FL_

Attended in Computer Science and International Baccalaureate programs. Took AP, IB, and college-level courses. Placed 1st in Palm Beach County Programming Competition Team.

## Languages

Language | Proficiency
---------|------------
English  | Fluent
French   | Fluent
German   | A2 Level
Finnish  | A1 Level

## Links

### Connect
* <a rel="me" href="https://mastodon.social/@jerr0328">Mastodon</a>
* [Twitter - Jerr](https://twitter.com/Jerr)
* [GitHub - jerr0328](https://github.com/jerr0328)
* [LinkedIn](https://www.linkedin.com/in/jmayeres/)
* [StackOverflow](https://stackoverflow.com/story/jeremy)
* [Dev.to - Jerr](https://dev.to/jerr)
* [Blogspot (outdated)](https://jeremymayeres.blogspot.de/)

### Talks
* [FOSDEM 2018 - GDAL Tips and Tricks](https://fosdem.org/2018/schedule/event/geo_gdal/) - GDAL installation, Python usage, and Cloud GeoTIFFs

### News
* [UCF News - Junior Works on Ballistic Missile Program](https://today.ucf.edu/junior-works-on-ballistic-missile-program/)
