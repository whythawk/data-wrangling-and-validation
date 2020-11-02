[🇫🇷 Français](README.fr.md)

# Data Wrangling and Validation for Open Data

[![DOI](https://zenodo.org/badge/253458856.svg)](https://zenodo.org/badge/latestdoi/253458856)

The term _Open Data_ is generally understood to be data that are made available to the public free of charge, without registration or restrictive licenses, for any purpose whatsoever (including commercial purposes), in electronic, machine-readable formats that ensure data are easy to find, download and use. 
 
Open data initiatives by public institutions, such as governments and intergovernmental organisations, recognise that such data is produced with public funds and so, with few exceptions, should be treated as public goods.
 
Data reuse, both by data experts and the public at large, is key to creating new opportunities and benefits from government data. Open data reuse requires two basic criteria:
 
1. Data must be legally open, meaning that it is placed in the public domain or under liberal terms of use with minimal restrictions. This ensures that government policies do not create barriers or ambiguities concerning how the data may be used.
2. Data must be technically open, meaning that it is published in electronic formats that are machine-readable and non-proprietary. This ensures that ordinary citizens can access and use the data with little or no cost using common software tools.

The purpose of this syllabus in _Data Wrangling and Validation for Open Data_ is to guide learners to confidence in delivering technically open data: well-structured, machine-readable data, validated to a defined and standard metadata schema.

## Lesson 1: Data wrangling messy data

_Learning outcomes_:

- Understand, and have practical experience with, the structure and design of machine-readable data files.
- Use Excel to investigate and manipulate source data to learn its metadata, shape and robustness, and employ these methods to develop a structural metadata schema.
- Learn and apply a basic set of methods to restructure messy source data into machine-readable CSV files using Microsoft Excel.
- Learn, and have practical experience with writing, the basic syntax and approach to coding in Python.
- Integrate and apply methods from the core data analysis libraries of Numpy, Pandas and Matplotlib to investigate and manipulate source data.
- Perform techniques in analysis and coding, using the Whyqd data wrangling package, to create a structured, JSON-formatted method, for restructuring data into a standard schema.

_Project_:

Each participant will be assigned a spreadsheet from [training data](https://drive.google.com/open?id=0B8eZRkdFGaEHfnlwU25vdVRUOFNOdnNfWnMwb3IwYXJ3QU9BeTU0ZmlTNlpaRmZFZE5iM28) and expected to restructure it both in Excel and using Python/Whyqd.

## Lesson 2: Validating restructured data against a schema

_Learning outcomes_:

- Understand, and employ, standard definitions to write a JSON schema for data validation.
- Perform data validation using Microsoft Excel.
- Learn how to validate machine-readable data in online applications against a defined schema.
- Write and use modular functions to automatically validate data files using Python.
- Apply techniques in open data publication to prepare data, schemas and validation outputs for publication.

_Project_:

Using the machine-readable spreadsheet created in Lesson 1, develop a JSON schema, and validate the data using this schema on [CSV Lint](https://csvlint.io/). Then import [whyqd](https://whyqd.readthedocs.io/) and perform the same task in Python.

## Lesson 3: Anonymising personal data prior to publication

_Learning outcomes_:

- Acknowledge the privacy and confidentiality issues in data storage and security of personal data.
- Recognise responsibilities and mechanisms for securing data-at-rest and data-in-motion.
- Employ methods for anonymising data, including geospatial jitter, address and name redaction, and field obfuscation.
- Investigate and apply appropriate aggregation techniques to anonymise personal data that is otherwise immune to field redaction approaches.

_Project_:

Use a manufactured sample data file containing personal information and redact these data to prevent de-anonymisation.

## Project: COVID-19 data preparation for release

As a topical subject, a general discussion of likely data sources for release, and wrangling. We may need manufactured patient records for aggregation, wrangling and release.

---

## Whois

My name is [Gavin Chait](https://gavinchait.com), and I am an independent data scientist specialising in economic development and data curation. I spent more than a decade in economic and development initiatives in South Africa. I was the commercial lead of open data projects at the Open Knowledge Foundation, leading the open source CKAN development team, and led the implementation of numerous open data technical and research projects around the world. Recently, I have developed [Sqwyre.com](https://sqwyre.com), an initiative to develop a comprehensive business intelligence search engine for entrepreneurs. Data are based on open data and Freedom of Information requests.

I've worked with [SBC4D](http://www.sbc4d.com) since 2016 on a range of projects spanning from Ghana to Morocco, Tunisia and Ethiopia, to Tanzania and Mauritius. This syllabus was developed for the [Des Chiffres et des Jeunes](https://www.dcdj.ci/) project in Cote d'Ivoire.

I have extensive experience in leading research projects, implementing open source software initiatives, and developing and leading seminars and workshops. I have taught for 25 years, including for undergraduates, adult education, and technical and analytical teaching at all levels.

## Licensing and release

Course content, materials and approach are copyright Gavin Chait, and released under both the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) and the [MIT](https://opensource.org/licenses/MIT) licences.

The objective is to ensure reuse, and I recommend - but do not require - that any modifications or adaptations of the source material should be released under an equivalent licence.