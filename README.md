**Introduction**

pm4py is a python library that supports (state-of-the-art) process mining algorithms in python. It is open source (licensed under GPL) and intended to be used in both academia and industry projects. pm4py is a product of the Fraunhofer Institute for Applied Information Technology.

This repo contains links to process mining training, links to supporting documentation to support with installing libraries & how to use the library, and an example python notebook that you can run with the artifical healthcare data provided.

**Presentation**

I presented on process mining in the East of England at a few different communities, presentation below:

[Presentation](https://github.com/RubyNixx/Process_Mining_Python_Healthcare/blob/main/Process_Mining.pdf)

**Recommended training in process mining**

[Coursera Process Mining](https://www.coursera.org/learn/process-mining)

**Process Mining in Python - Youtube Videos**

[pm4py tutorials - tutorial #1: What is Process Mining?](https://www.youtube.com/watch?v=XLHtvt36g6U)
This video covers what is process mining; examples, definition of process mining, event log, main tasks of process mining, process discovery, conformance checking, process enhancement

[pm4py tutorials - tutorial #2: Importing CSV Files](https://www.youtube.com/watch?v=bWOKVx0PO6g)
This video covers example process; how to read graphical representation of processes, example data in CSV format #(can be downloaded [here](https://processintelligence.solutions/static/data/getting_started/running-example.csv), importing CSV data in Python using pandas library, importing CSV data, reformatting the data into event log using format_dataframe function and obtaining start and end activities using get_start_activities and get_end_activities functions from pm4py library.

[pm4py tutorials - tutorial #3: Importing XES Files](https://youtu.be/pmpN3A_h2sQ)
This video covers case level attributes, XES format; tools supporting XES format, how XES looks, example XES file, XES - extensions, standard extensions of XES (website), extensions on log level, trace level and event level, XES public datasets, globals (default values) in XES files, classifiers; meta information in XES files, reading XES files using read_xes function from pm4py library and getting start and end activities.

[pm4py tutorials - tutorial #4: Playing with Event Data; Lambda Functions](https://www.youtube.com/watch?v=48p_LP0c3g8&list=PLkWuoFn9UEb5l41T4CMKPYHyRcL5ojI9Z&index=4)

[pm4py tutorials - tutorial #5: Playing with Event Data; Shipped Filters](https://www.youtube.com/watch?v=alkZkhK2mAo&list=PLkWuoFn9UEb5l41T4CMKPYHyRcL5ojI9Z&index=5)

[pm4py tutorials - tutorial #6 exporting event data](https://www.youtube.com/watch?v=gVnfG6xLIxI&list=PLkWuoFn9UEb5l41T4CMKPYHyRcL5ojI9Z&index=6)

[pm4py tutorials - tutorial #7 process discovery](https://www.youtube.com/watch?v=BJMp763Ye_o&list=PLkWuoFn9UEb5l41T4CMKPYHyRcL5ojI9Z&index=7)

[pm4py tutorials - tutorial #8 conformance checking](https://www.youtube.com/watch?v=0YNvijqX3FY&list=PLkWuoFn9UEb5l41T4CMKPYHyRcL5ojI9Z&index=8)

**Resources Available:**

***Official pm4py***

[pm4py official documentation](https://processintelligence.solutions/static/api/2.7.11/index.html)

[Process Intelligence website](https://processintelligence.solutions/pm4py)

[pm4py installation support](https://processintelligence.solutions/static/api/2.7.11/install.html)

[YouTube Videos](https://www.youtube.com/embed/XLHtvt36g6U)

[Process Mining - Data Science in Action Book](https://link.springer.com/book/10.1007/978-3-662-49851-4)

***dcr4py - supporting documentation***

[dcr4pydocs - extension of pm4py documentation](https://paul-cvp.github.io/dcr4pydocs/api.html#overall-list-of-methods)


[pm4py-dcr](https://github.com/paul-cvp/pm4py-dcr)

**Example Publications using pm4py**

https://processintelligence.solutions/pm4py/publications

**Structure of this repo**

Python Notebook - open in google colab
Example artificial healthcare data

**Additional example datasets for healthcare & process mining**

[Ambulance Data](https://github.com/nhsengland/ProcessMining/tree/main/Data)

Real life log of a Dutch academic hospital, originally intended for use in the first Business Process Intelligence Contest (BPIC 2011) 
Uploaded to this repo.

[Data.XML](https://github.com/RubyNixx/Process_Mining_Python_Healthcare/blob/main/DATA(1).xml)
[Hospital_log.xes.gz](https://github.com/RubyNixx/Process_Mining_Python_Healthcare/blob/main/Hospital_log.xes.gz)

**Requirements**

pm4py depends on some other Python packages, with different levels of importance:

Essential requirements: numpy, pandas, deprecation, networkx

Normal requirements (installed by default with the pm4py package, important for mainstream usage): graphviz, intervaltree, lxml, matplotlib, pydotplus, pytz, scipy, stringdist, tqdm

Optional requirements (not installed by default): scikit-learn, pyemd, pyvis, jsonschema, polars, openai, pywin32, python-dateutil, requests, workalendar

Source: https://github.com/paul-cvp/pm4py-dcr
