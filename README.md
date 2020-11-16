<!---

	Copyright (c) 2009, 2018 Robert Bosch GmbH and its subsidiaries.
	This program and the accompanying materials are made available under
	the terms of the Bosch Internal Open Source License v4
	which accompanies this distribution, and is available at
	http://bios.intranet.bosch.com/bioslv4.txt

-->

# PT-LOG LISA Scenario-Based Total Demand Forecasting  <!-- omit in toc -->

[![License: BIOSL v4](http://bios.intranet.bosch.com/bioslv4-badge.svg)](#license)

This repository contains documents and code about the product Scenario-Based Total Demand Forecasting within
the LISA program managed by the PT/LOI1. 

The LISA program brings Artificial Intelligence and Automation into the Supply 
Chain of Robert Bosch Power Tools.

Scenario-Based Total Demand Forecasting calculates full distribution forecasts of the total demand of all 
forecast-relevant base combinations for the next 18 months. It loads certain Percentiles into the PDP31 standard 
demand planning system of PT.

For mathematical details, please read the [technical report](documents/PT_LOG_LISA_ScenarioBasedTotalDemandForecasting.pdf) 
For business details, have a look at [PT-LOG LISA Docupedia](https://inside-docupedia.bosch.com/confluence/display/PTLOG/LISA).

## Table of Contents  <!-- omit in toc -->

- [Getting Started](#getting-started)
- [Building and Testing](#building-and-testing)
- [Contribution Guidelines](#contribution-guidelines)
- [Feedback](#feedback)
- [About](#about)
  - [Project Manager](#projectmanager)
  - [Agile Master](#agilemaster)
  - [Technical Lead](#technicallead)
  - [Contributors](#contributors)
  - [3rd Party Licenses](#3rd-party-licenses)
  - [Used Encryption](#used-encryption)
  - [License](#license)

## Getting Started

First, install the **Python programming language** via [IT Service Portal](
https://rb-servicecatalog.apps.intranet.bosch.com/RequestCenter/website/Grunt/application/offer.html?id=3843) 
'Anaconda Python 2019.07 (install)'.

Second, install the **version control system** via [IT Service Portal](
https://rb-servicecatalog.apps.intranet.bosch.com/RequestCenter/website/Grunt/application/offer.html?id=3843) 
'Source Tree + Git For Windows (install)'.


Third, if you do not like the default **integrated development environment** of Anaconda **Spyder** then organize 
[permanent admin rights](https://rb-servicecatalog.apps.intranet.bosch.com/RequestCenter/website/Grunt/application/offer.html?id=3845) 
and install: [PyCharm](https://www.jetbrains.com/de-de/pycharm/download/download-thanks.html?platform=windows&code=PCC). 


Fourth, **clone the repository** by opening a git bash in target directory of repository and execute 
following commands:
```
git clone https://sourcecode.socialcoding.bosch.com/scm/lisa/scenariobasedtotaldemandforecasting.git
cd scenariobasedtotaldemandforecasting
```

Fifth, create the **conda environment** by executing following commands:

```
source activate
conda env create -f environment.yml
source activate lisa
```

To automatically start the git bash with initial settings create a file .bashrc in your user directory 
(C:\Users\<NT User>) with following content

```
source activate lisa
alias python='winpty python.exe'
cd /<directory of source>/scenariobasedtotaldemandforecasting
python setup.py develop
```

From now on, whenever you open a git bash it automatically activated the correct conda environment and 
opens already in your repository directory.


Note: If you do not feel comfortable to use the git bash, then step 4 and 5 can also be executed in **SourceTree** 
and **Anaconda Navigator**.

## Building and Testing

If the repository contains SW, add instructions on how to build it from source
and test it in this section.

## Contribution Guidelines

The Contribution Guidelines can be found [here](CONTRIBUTING.md).

## Feedback

We are looking forward to your feedback. 

For business and use case questions please write an email to Daniel Stanek (PT/LOI1) Daniel.Stanek2@de.bosch.com

For technical questions please write an email to Oliver Hönig (PT/LOI1) Oliver.Hoenig@de.bosch.com.

## About

### Product Manager

Daniel Stanek (PT/LOI1) Daniel.Stanek2@de.bosch.com

### Agile Master 

Stefan Kujundzic (CI/DAD21.4) Stefan.Kujundzic@bosch.com

### Technical Lead

Oliver Hönig (PT/LOI1) Oliver.Hoenig@de.bosch.com

### Contributors

EXTERNAL Baumgartl Peter (Fa. foryouandyourcustomers, PT/BDO-BD) external.Peter.Baumgartl@de.bosch.com

Subramaniam Chandrakumar (RBEI/BSF1) Subramaniam.Chandrakumar@in.bosch.com

Kristina Kovacevic(CI/DAP41.7) Kristina.Kovacevic@bosch.com

Nikolaos Servos(PT/BDO-BD) Nikolaos.Servos@de.bosch.com

Daniel Stanek (PT/LOI1) Daniel.Stanek2@de.bosch.com

Najdan Vukovic (CI/DAP41.7) Najdan.Vukovic@bosch.com


You can also write to the whole team by PT-LOG-LISA PT-DLS-SQL@bcn.bosch.com

### 3rd Party Licenses

You must mention all 3rd party licenses (e.g. OSS) licenses used by your
project here. Example:

| Name | License | Type |
|------|---------|------|
| [Apache Felix](http://felix.apache.org/) | [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.txt) | Dependency

### Used Encryption

Declaration of the usage of any encryption (see BIOS Repository Policy §4.a).

### License

[![License: BIOSL v4](http://bios.intranet.bosch.com/bioslv4-badge.svg)](#license)

> Copyright (c) 2009, 2018 Robert Bosch GmbH and its subsidiaries.
> This program and the accompanying materials are made available under
> the terms of the Bosch Internal Open Source License v4
> which accompanies this distribution, and is available at
> http://bios.intranet.bosch.com/bioslv4.txt

<!---

	Copyright (c) 2009, 2018 Robert Bosch GmbH and its subsidiaries.
	This program and the accompanying materials are made available under
	the terms of the Bosch Internal Open Source License v4
	which accompanies this distribution, and is available at
	http://bios.intranet.bosch.com/bioslv4.txt

-->
