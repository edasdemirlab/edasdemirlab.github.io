---
title: EMU430- Data Analytics
permalink: /emu430-data-analytics/
layout: single
classes: wide
author_profile: false
toc: true
toc_label: "EMU430- Data Analytics"
toc_icon: "file-alt"
toc_sticky: "true"

gallery:
  - url: /assets/images/emu430photo/cem-talk.png
    image_path:  /assets/images/emu430photo/cem-talk.png
    alt: "emu430 foto 1"
  - url: /assets/images/emu430photo/mustafa-talk.png
    image_path:  /assets/images/emu430photo/mustafa-talk.png
    alt: "emu430 foto 2"
  - url: /assets/images/emu430photo/baykal-talk.png
    image_path:  /assets/images/emu430photo/baykal-talk.png
    alt: "emu430 foto 3"
  - url: /assets/images/emu430photo/sami-talk.png
    image_path:  /assets/images/emu430photo/sami-talk.png
---


# Course Overview
Data Analytics course is to provide basics and usefulness of data analytics, and to develop hands on skills for applying tools and techniques of data analytics in engineering problems, collecting and reshaping raw data having different formats, implementing advanced visualizations to extract usable conclusions, and using productivity tools to organize data analytic projects and generate reproducible reports.

The course content includes:
-	Fundamentals of data analytics
-	Programming basics for data analytics (basic syntax, data types, vectors and vector arithmetic, indexing, conditional expressions, loops and iteration, functions)
-	Principles and techniques of data visualization
-	Data wrangling: import, tidy and process data (importing spreadsheets, web scraping, reshaping data, combining tables, string processing)
-	Productivity tools for organized and reproducible data analytics projects (basic Unix, Git and GitHub, markup languages for reproducible reports)

I designed this course and continue to teach it to the [Industrial Engineering Department students at Hacettepe University](https://ie.hacettepe.edu.tr/index.php?lang=en) as part of my faculty responsibilities. You may visit the [department's website](https://ie.hacettepe.edu.tr/index.php?lang=en) for comprehensive information about IE Hacettepe and [course catalog](https://bilsis.hacettepe.edu.tr/oibs/bologna/index.aspx?lang=en&curOp=showPac&curUnit=310&curSunit=469#) to access the full curriculum, which includes details on EMU430 - Data Analytics too.

# Course Structure
The course is structured over 15 weeks, targeting both undergraduate and entry-level graduate students. Also, it is highly suitable for advanced individuals lacking a background in programming for data analytics. The course schedule includes one week each for the midterm exam, final exam, and project presentations, which leaves 12 weeks dedicated to instructional activities. For these 12 weeks, I utilize my lecture notes ([see Lectures](#lectures)). The content of these notes is primarily derived from Dr. Rafael's book, [Introduction to Data Science](https://rafalab.dfci.harvard.edu/dsbook-part-1/) ([see References](#references)).

The course currently utilizes the [R](https://www.r-project.org/) as the programing language and [Quarto](https://quarto.org/) for code-based reproducible reporting purposes. Additionally, the course incorporates [GitHub](https://github.com/), [GitHub Classroom](https://classroom.github.com/), and [DataCamp](https://www.datacamp.com/) as productivity platforms. The course can be taught using any programming language, but [R](https://www.r-project.org/) and [Python](https://www.python.org/) are the most compatible with the current design.

## GitHub
The course's progression is significantly influenced by the use of Git and [GitHub](https://github.com/). Specifically, the class is managed through [GitHub Classroom](https://classroom.github.com/). To put it simply, [GitHub Classroom](https://classroom.github.com/) allows us to use a shared account, [EMU Hacettepe Analytics](https://github.com/emu-hacettepe-analytics). I assign two types of assignments here. The first is an individual task requiring students to create their own repositories to host their personal websites. These websites, based on [Quarto](https://quarto.org/), must include a main menu labeled "EMU430 Coursework" during our 15-week course. Under this menu, they post their individual assignments and a link to their project repositories. This leads to the second assignment, a group task where students form teams for their term project. They are provided a repository to host their project website, which should feature team details, data insights, exploratory data analysis, and in-depth analytical work.

This approach is similar to the one employed by [Dr. Berk Orbay](https://www.linkedin.com/in/berkorbay/) in his [BDA 503 - Essentials of Data Analytics course at MEF University](https://mef-bda503.github.io/). He has experience with this framework and confirmed its efficacy to me during the planning stage of my course.

## Quarto
[Quarto](https://quarto.org/) is a versatile documentation tool that allows for the integration of code, data, and narrative in a single document. It works both with [R](https://www.r-project.org/) and [Python](https://www.python.org/). [Quarto](https://quarto.org/) and [GitHub](https://github.com/) are compatible, enabling students to render their code-based [Quarto](https://quarto.org/) documents (e.g., websites) on their local computers and then commit and push them to [GitHub](https://github.com/). Simply setting the repository's pages settings to deploy from the /docs branch is sufficient for [GitHub](https://github.com/) to automatically publish their webpages. This process is both easy and efficient.

## DataCamp
I utilize [Datacamp Classroom](https://www.datacamp.com/universities) for my students, providing them with complimentary access to [Datacamp's paid content](https://www.datacamp.com/). Here, I assign tasks that contribute as bonus points towards their grades. I highly recommend this approach to my colleagues who teach analytical courses involving programming languages. There's a straightforward application and verification process. Once your faculty status is confirmed, all that's required is to send invitations to your students' email addresses. Upon their acceptance, they are added to your classroom, allowing you to assign them courses and tasks. As they complete each piece of content, they earn XP points. You can monitor their progress, and there's even a leaderboard that my students enjoy checking at the beginning of each lecture to see the weekly leaders.


## Invited Speakers
I designed this course to include four weeks of guest lectures from Data Science experts. These speakers share their knowledge and real-world experiences, giving students a comprehensive view of practical applications. In the Fall term of 2023-2024, we welcomed four invited speakers.
{% include gallery layout="half" class=". erdi_width_50 .align-right" %}

- [Cem Vardar (Ph.D.)](https://www.linkedin.com/in/cem-vardar-70119514/), Data Scientist, Former data scientist at Intel (2002-2010), Revionics (2010-2015) and Carvana (2015-2021), Founder of Decision Science Lab [decisionsciencelab.com](https://decisionsciencelab.com)
- [Mustafa Baydoğan (Ph.D.)](https://www.linkedin.com/in/mustafa-baydogan-36127a2/), Data Scientist, Associate Professor of IE Bogazici, Founder of Algopoy, [www.mustafabaydogan.com/](http://www.mustafabaydogan.com/)
- [Baykal Hafızoğlu (Ph.D.)](https://www.linkedin.com/in/baykal-hafizoglu-7244a84b/), Data Scientist, Platform Management Director, FICO, Atlanta, USA
- [Sami Serkan Özarık (Ph.D.)](https://www.linkedin.com/in/cem-vardar-70119514/), Data Scientist, Operations Research Scientist, Amazon, Luxembourg



The first three talks were conducted remotely, and I recorded them and uploaded the videos to my [YouTube channel](https://www.youtube.com/@ErdiDasdemir/videos). I highly recommend them to those interested. Please note that the talks are in Turkish.

<div class="video-container">
  <div class="video-column">
    {% include video id="Fi8-phj1X1A" provider="youtube" %}
  </div>
  <div class="video-column">
    {% include video id="1Mvkn71dhaA" provider="youtube" %}
  </div>
  <div class="video-column">
    {% include video id="tV_0pHSdLAM" provider="youtube" %}
  </div>
</div>

# References {#references}
My course content draws upon the excellent references listed below. Specifically, my slides are derived from [Dr. Rafael Irizarry's](https://rafalab.dfci.harvard.edu/pages/about.html) exceptional book. He has recently refreshed his material, resulting in two outstanding parts:

- Irizarry, Rafael A. [Introduction to Data Science](https://rafalab.dfci.harvard.edu/dsbook-part-1/)
- Irizarry, Rafael A. [Advanced Data Science](https://rafalab.dfci.harvard.edu/dsbook-part-2/)

My other references are:
- Charles Russel Severance. [Python for Everybody](https://www.py4e.com/)
-	Peng, R. D., & Matsui, E. (2016). [The art of data science](https://bookdown.org/rdpeng/artofdatascience/). A Guide for Anyone Who Works with Data. Skybrude Consulting, LLC, ISBN-978-1365061462
-	Zamora Saiz, A., Quesada González, C., Hurtado Gil, L., & Mondéjar Ruiz, D. (2020). [An Introduction to Data Analysis in R](https://link.springer.com/book/10.1007/978-3-030-48997-7). Springer, Cham, Switzerland, ISBN- 978-3-030-48996-0

My [GitHub Classroom](https://classroom.github.com/) approach is inspired by the strategy used by [Dr. Berk Orbay](https://www.linkedin.com/in/berkorbay/) in his [BDA 503 - Essentials of Data Analytics course at MEF University](https://mef-bda503.github.io/). Additionally, I have drawn inspiration from his assignment and project guidelines.

Of course, the content goes beyond these references and incorporates both my insights and the students' experiences. Specifically, the individual and project websites created by IE Hacettepe students significantly enrich our content. These students have developed excellent projects from which we can learn a great deal.

# Syllabus
The syllabus I used for EMU430-Data Analytics during the Fall Semester of 2023-2024 at IE Hacettepe is outlined below:

[EMU430 - Data Analytics, 2023-2024 Fall Semester Syllabus](/assets/docs/emu430/emu430-data-analytics-syllabus-2023.pdf){: .btn  .btn--large .btn--success}


# Lectures {#lectures}
The lecture notes I used for EMU430-Data Analytics during the Fall Semester of 2023-2024 at IE Hacettepe is outlined below. I mainly derived my slides from [Dr. Rafael Irizarry's](https://rafalab.dfci.harvard.edu/pages/about.html) [Introduction to Data Science](https://rafalab.dfci.harvard.edu/dsbook-part-1/). While they may not be flawless, I've invested considerable time into shaping them, and I anticipate they will continue to develop and mature over the next few years.

- [Week 1](/assets/docs/emu430/emu430-2023-fall-week-1.pdf)
- [Week 2](/assets/docs/emu430/emu430-2023-fall-week-2.pdf)
- [Week 3](/assets/docs/emu430/emu430-2023-fall-week-3.pdf)
- [Week 4](/assets/docs/emu430/emu430-2023-fall-week-4.pdf)
- [Week 5](/assets/docs/emu430/emu430-2023-fall-week-5.pdf)
- [Week 6](/assets/docs/emu430/emu430-2023-fall-week-6.pdf)
- [Week 7](/assets/docs/emu430/emu430-2023-fall-week-7.pdf)
- [Week 8](/assets/docs/emu430/emu430-2023-fall-week-8.pdf)
- Week9- Midterm
- [Week 10](/assets/docs/emu430/emu430-2023-fall-week-10.pdf)
- [Week 11](/assets/docs/emu430/emu430-2023-fall-week-11.pdf)
- [Week 12](/assets/docs/emu430/emu430-2023-fall-week-12.pdf)
- [Week 13](/assets/docs/emu430/emu430-2023-fall-week-13.pdf)
- [Week 14- Project Presentations](#projects)
- Final Exam

# 2023-2024 Fall Term
This term ended with very fuitful outcomes. Studentds did a great job in both individual and project team levels. Our [GitHub Classroom](https://classroom.github.com/) domain [EMU Hacettepe Analytics](https://github.com/emu-hacettepe-analytics/) includes individual student repositories and project repositories for fall 2023-2024 term.

## Individual Pages
Among 73 students, some students did an amazing job in personalizing their websites both in terms of design and content. Some great examples are below.

- [Aykut Şimşek - www.aykutsimsek.net](https://aykutsimsek.net/) (Aykut went more forward and obtained a domain name for his webpage.)
- [Mert Kaplan's Analytics Lab - https://emu-hacettepe-analytics.github.io/emu430-fall2023-mer7kaplan/](https://emu-hacettepe-analytics.github.io/emu430-fall2023-mer7kaplan/)
- [Sena Nur Enşici's Analytics Lab - https://emu-hacettepe-analytics.github.io/emu430-fall2023-ensici/](https://emu-hacettepe-analytics.github.io/emu430-fall2023-ensici/)

## Project Topics and Pages {#projects}
The first four were my favorites, but most of them are worth exploring.

- [Team Safe İstanbul](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-team_safe_istanbul)
This project aims to analyze three datasets from the Istanbul Metropolitan Municipality to identify districts at high risk of earthquakes. Using data on building numbers, construction years, floors, and population, the team will create a risk map and prioritize neighborhoods for earthquake preparedness.

- [synergy](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-synergy/)
Focusing on the cultural sector, this project examines statistics on libraries and museums across Turkish cities. By analyzing visitor numbers, registered users, and book counts, the team intends to assess cultural institution utilization and highlight areas for development.

- [CTRL-S](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-ctrl_s/)
This project explores the competitive landscape of mobile communication technologies and market shares of mobile vendors globally, with a focus on how country-specific dynamics influence market positions.

- [Data Ciphers](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-data_ciphers/)
Through the Türkiye Health Survey, this project analyzes health indicators, disease prevalence, alcohol use, and body mass indices to provide insights into national health trends and facilitate international health comparisons.

- [data_vizards](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-data_vizards/)
Analyzing 2021 internal migration data in Turkey, this project explores migration trends, demographic factors, and economic indicators to understand regional migration patterns and their implications.

- [EMUTrend Explorers](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-emutrend_explorers/)
This project examines student preferences for Industrial Engineering departments in Ankara universities, focusing on demand and placement trends using the YOK ATLAS dataset. The analysis includes data cleaning to focus on preferences of students with full scholarships and aims to understand trends in department selection.

- [icaRdi](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-icardi/)
The aim of this project is to examine the relationship between team performance metrics and identify the metrics that significantly influence team ratings.

- [semicolon](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-semicolon/)
Focused on developing strategies for suicide prevention across different age groups and genders, aiming to identify effective approaches to reduce suicide rates.

- [4k1e_rda](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-4k1e_rda/)
Examines crime data from 2011 to 2020 with a focus on the gender and educational status of criminals, using data from the Turkish Statistical Institute to analyze crime trends.

- [mission prediction](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-mission_prediction/)
Analyzes the potential impact of a 7.5 magnitude earthquake in Istanbul, focusing on infrastructure and population risks. The study aims to guide local authorities and emergency responders in enhancing the city's resilience and preparedness.

- [red_flag](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-red_flag/)
Analyzing and comparing Consumer Price Index (CPI) data from Turkey and the US to understand inflation trends and the economic and sociological factors influencing these trends.

- [Altı Üstü Data](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-alti_ustu_data/)
Investigating the relationship between air pollution and forestation, this study uses data on PM10 levels and forest area per square kilometer to analyze and understand the impact of forestation on air quality.

- [data_criminals](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-data_criminals/)
A straightforward project aimed at understanding the correlation between educational levels and crime rates.

- [Germen Obasi](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-germen_obasi/)
Investigating the relationship between education and happiness using TUIK data on happiness rates and literacy rates from 2003 to 2022. The study aims to explore if educational status correlates with happiness levels and seeks to demonstrate the potential independence of these factors.

- [Quant Flare](https://emu-hacettepe-analytics.github.io/emu430-fall2023-team-quant_flare/)
This study analyzes Turkey's population growth rate and the number of foreign babies, relying on TURKSTAT data to understand demographic changes and their implications for Turkey's future.
