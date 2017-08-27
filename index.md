# Jeremy Mayeres

## About Me

I'm a software engineer living in Berlin. I'm currently the Data Pipeline squad
lead at Planet. I'm originally from Belgium, although I grew up in Florida. In
high school I did the International Baccalaureate and Computer Science programs.
I then studied Computer Science at the University of Central Florida in Orlando,
with a minor in Legal Studies. During that time, I was an intern at Lockheed
Martin in Cape Canaveral. I graduated in May 2012 with Honors. I then worked for
two years for Harris Corporation doing embedded software development before
moving to Berlin in 2014 to work for BlackBridge. In 2015, BlackBridge was
acquired by Planet. I've always been a huge space geek.

## Tech

My current primary programming language is Python.
I have previous experience in C, C++, and Java.
Additionally, I've done some smaller work with HTML/CSS, JavaScript, and Ruby.

In the Python world, I've used Django (mostly Django Rest Framework) and Flask.
For my job at Planet, I use GDAL and Numpy, and have made some minor contributions
to the GDAL project.

I've used Linux and Mac heavily for development, first learning Linux when I
was in middle school. I like using the Fish shell, though I still end up having
to write a lot of Bash scripts.

## Work Experience

### Planet Labs Germany (Sep 2014 - Present)

I started at BlackBridge in Berlin in September 2014 as a software developer for
the RapidEye data pipeline, mostly working with C++, with some Java and Python.
In 2015, Planet acquired BlackBridge. Since then, I've worked on getting the
RapidEye data uploaded to the cloud-based platform and processed alongside the
PlanetScope data. In early 2017 I was promoted to squad lead for the Berlin
Data Pipeline, leading a team of 6 developers to work on processing RapidEye,
Sentinel, Landsat, SkySat satellite data.

Some key tasks included:
* Port calibration tool from Matlab to C++ to be included in processing chain
* Introduced tools and processes into the team workflow:
  * Encouraged use of Wikis for documentation by creating the first Confluence pages
  * Introduced chat tools for better team communication
  * Advocated for more Agile processes (including Scrum and Kanban)
* Develop Python-based wrapper scripts that handle file-based XML messaging
* Design system to process and upload RapidEye data via legacy processing chain
* Support development of microservices in a Mule Java Enterprise Service Bus
* Port services and software to Python/Django as we shifted to a Python-centric team
* Develop tool to process and upload hundreds of terabytes of RapidEye archive data to the cloud
* Lead the development of the SkySat data processor to bring pre-processed high-resolution (<1m GSD) data to our customers for the first time

### Harris Corporation (May 2012 - July 2014)

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
