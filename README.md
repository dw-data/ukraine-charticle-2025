#  Charting the human toll of Russia's war in Ukraine 
This repository contains the source code and data files used in [this](#) DW article.  

Each chart, except for the one about civil casualties, has corresponding files in the `code` directory, documenting all steps taken in data cleaning and analysis. The files used to create the interactive Datawrapper charts are in the `output` directory.  

Data for the civil casualties chart (a PDF file, which was manually transcribed) is available in the `data` directory.  

The `charts` directory contains PNG versions of the charts published in the article.  


---

# Details about sources and datapoints

## Area controlled by Russia

### Sources

The article refers to Brookings Institution calculations made with the [Institute for the Study of War (ISW)](https://www.understandingwar.org/) and [Critical Threats Project](https://www.criticalthreats.org/) mapping. 

Brookings Institution is a US-based think tank that hosts an interactive panel on the current developments of the war. It relies on other primary sources, such as the ISW and the Critical Threats Project. 
 
The ISW and the Critical Threats Project think tanks were created with participation of former US Army personnel in 2007 and 2009, respectively. Their stated goal is to provide information that can aid the United States in improving its military capabilities and assessment of global conflicts. 

### Methodology

The Brookings Institution computed the share of Ukrainian territory marked as controlled by Russia in maps made by the ISW and the Critical Threats Project. 

George Barros, head of the Russia and Geospatial Intelligence teams, said the ISW's maps are made by combining sources including Russian and Ukrainian official reports and maps, visual evidence such as combat footage, satellite imagery, and remote-sensor data such as heat anomalies and mobile location data. 

He gave a full overview of the methodology behind the maps at [this online meet-up](https://www.youtube.com/watch?v=1iTbT9VyVNo).

## Type of attacks conducted

### Sources

[Armed Conflict Location & Event Data (ACLED)](https://acleddata.com/ukraine-conflict-monitor/) is a US-based non-profit research organization led by Clionadh Raleigh, professor of Political Violence and Geography at the University of Sussex. ACLED monitors not only the war in Ukraine but also conflicts in Africa and the Middle East. 

### Methodology

ACLED collects and analyzes reports by the government of Ukraine, the government of Russia and pro-Russia militias, as well as NGOs, humanitarian organizations, and Ukrainian media that report the war events in near-real time. 

ACLED doesn’t rely on aggregate estimates by governments and other organizations, but rather compiles individual event fillings, which are further classified according to a detailed taxonomy (available [here](https://acleddata.com/knowledge-base/acled-methodology-and-coding-decisions-around-conflict-in-ukraine/). 

Those are later corroborated by longer, detailed, and delayed reports published by other organizations such as international news media, international organizations, Ukrainian and international nongovernmental organizations, and human rights groups. 

Each entry in the dataset — which refers to one specific event of violence — is tracked to at least one specific source. 

## Civilian deaths

### Source

The Office of the United Nations High Commissioner for Human Rights (OHCHR), through its [Human Rights Monitoring Mission in Ukraine (HRMMU) monthly reports](https://ukraine.ohchr.org/en/reports/periodic-reports-on-the-human-rights-situation-in-ukraine).

### Methodology

According to the OHCHR, reports are based on “interviews with victims, their relatives, and witnesses; open-source information, including photo and video material; forensic records and reports; criminal investigation materials; court documents; reports by international and national non-governmental organizations; public reports by law enforcement and military actors; data from medical facilities and local authorities.” 

Each report of harm to civilians is vetted individually and cross-checked with other sources until it reaches the threshold of the “reasonable grounds to believe” standard of proof — that is, when “based on a body of verified information, an ordinarily prudent observer would have reasonable grounds to believe that the harm took place as described.” 

They acknowledge the true extent of civilian harm is probably underestimated, especially immediately after the start of the full-scale invasion in February 2022, and in areas where direct access was harder, such as Mariupol (Donetsk region), Lysychansk, Popasna, and Sievierodonetsk (Luhansk region). 

## Civilian infrastructure damage

### Source

[Bellingcat](https://www.bellingcat.com/), an investigative journalism organization that specializes in using open-source intelligence (OSINT). 

### Methodology

Bellingcat maintains [a map with the location of civilian harm events](https://ukraine.bellingcat.com/) verified using video and images available online. Each entry is linked to open-source evidence, usually consisting of videos published on social media platforms. 

Bellingcat investigators check if the information is original, whether it was somehow manipulated, and verify where exactly it happened. Entries that couldn’t pass these verification stages are not displayed on the map. Each entry is also classified according to the main usage of the area where events took place.

They claim that their goal is to document how events in Ukraine are currently unfolding and to gather evidence for longer-term forensic research in the future. 

## Refugees and internally displaced people

### Source

The United Nations High Commissioner for Refugees (UNHCR) [most recent data on refugees and internally displaced people](https://www.unhcr.org/refugee-statistics).

### Methodology

The UNHCR gathers data published by governments, international organizations, and the UNHCR itself, depending on the country, the availability of data, and the target population. The compilation of data follows different protocols set up by the Expert Group on Refugee and IDP Statistics (EGRIS), part of the UN Statistical Commission.

A detailed description of the methodology and further documentation can be found [here](https://www.unhcr.org/refugee-statistics/methodology).

---  

**Reporting, writing, and graphics:** Rodrigo Menegat Schuinski  
**Editors:** Gianna Grün and Milan Gagnon
