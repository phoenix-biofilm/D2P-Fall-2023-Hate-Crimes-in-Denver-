# D2P-Fall-2023-Hate-Crimes-in-Denver
Code for D2P Project Fall 2023: How Can We Improve the Response to Hate Crimes in Denver With Spatial Analysis?

Project Abstract: 

Despite the ongoing efforts of Civil Rights, Women’s Rights, Queer Liberation, and Black Lives Matter movements
(among many others) to create a more just and equitable world where diversity is celebrated, people across our world
and even within our city remain intolerant towards diversity, to the point of violence. From 2010 to 2022, nearly
600 Hate Crimes occurred in the City of Denver. In this project, we will examine patterns of spatial clustering
within this dataset of Hate Crimes with cases (in our case-control point pattern analysis) delineated by the type of
target group (the case status and the crime type).

To acknowledge the complexity of the issue of Hate Crimes, let us frame our analysis with the legal definition
of a hate crime. Colorado law distinguishes Hate Crimes from other criminal activity with three criteria:

    1. The accused person knowingly committed the crime.
    2. The accused person intended to intimidate or harass the victim.
    3. The accused person committed the criminal activity because of the victim’s perceived or actual protected
        class or identity (i.e.: race, ethnicitiy, gender, sexual orientation, religion, disability, etc.).

How does one show the accused had the intention to intimidate or harass the victim? How do one tell if the
victim was chosen randomly or specifically for their race? The complexity of proving a crime was a hate crime (in
the legal sense at least) can be difficult, but understanding the requirements can help us understand the value and
limits of our analysis.

The Denver City Open Data Catalog provided the dataset for this project, which consists of the following
information about 567 distinct and relevant hate crimes that occurred from 2010 to 2022:
    
    • Case Numbers
    • Dates
    • Deidentified location information
    • Case Status
    • Crime Type
    • Target Groups
