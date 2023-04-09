# 2023-NIGERIAN-PRESIDENTIAL-RESULT-ANALYSIS
2023 PRESIDENTIAL ELECTION RESULT ANALYSIS FOR TOP 4 PARTIES 
the nigerian election is one of the largest most anticipated election in West_Africa. The 2023 Nigerian presidential election was held on 25 February 2023 to elect the president and vice president of Nigeria.
Nigeria’s Independent National Electoral Commission (INEC) has declared Bola Tinubu of the All Progressive Congress (APC) the winner of the 2023 presidential election. Tinubu polled a total of 8,794,726 votes to defeat his closest rival, Atiku Abubakar of the People’s Democratic Party (PDP), who scored 6,984,520 to emerge second, Peter Obi of Labor Party 
(LP) scored  and Kwankwaso of NNPP scored 1496671

Data Sources
Obviously, the primary data source was the INEC official website, Vanguard 

Data Analysis
The raw data obtained was in .pdf and .html formats, so I converted it into a more friendly format (.csv) to be analysed using python packages called pandas, geopandas, folium, and matplotlib.

The python environment am using is call Jupyter notebook which can be view and downloaded from the links below:-
http://localhost:8888/notebooks/election_analysis.ipynb#

# coding: utf-8


# # Nigerian Presidential Election Result Analysis - 2023
# 
# Author: Mbakwe Chidera




# ### Data Source
# The data was gathered from the Independent National Electoral Commission (INEC) official website.
# 
# The Data (in .csv format) used is available for 
# 
# Am going to use these three main python programming packages pandas with matplotlib embedded to analyse the 2023 Presidential Election Result.











# # Introduction
# Nigeria has 36 states and 1 federal capital territory. The 2023 presidential election was held in the 37 territories within the country.
# 
# Fourteen (18) political parties representing fourteen (18) candidates participated in the 2015 presidential elections. The parties are as follow: AA, AAC, ADC, ADP, APC, AP, APGA, APP, APM, BP, LP, NNPP,NRM, PDP, PRP, SDP, YPP and ZLP. See the result table below:-


Candidate Names
Party Name
Bola Ahmed Tinubu
APC
Atiki Abubakar
PDP
Peter Obi
LP
Kola Abiola
PRP
Adebayo Adewole
SDP
Malik Ado-Ibrahim
YPP
Okwudili Anyajike
NRM
Ojei ChiChi
APM
Christopher Imumolen
AP
Dumebi Kachikwu
ADC
Rabiu Musa Kwankwaso 
NNPP
Hamza al-Mustapha
AA
Daniel Nwanyanwu
ZLP
Adenuga Oluwafemi
BP
Nandi Osita
APP
Omoyele Sowore
AAC
Peter Umeadi
APGA
Sabi Yusuf
ADC

This data analysis will explore more on 4 major parties (PDP, APC, LP, NNPP) 

Dataset
The data entry was collected and entered by me and it will contain numeric values by states for
Vote scored by each political party
No of registered voters
Population
Population rank

I will attempt to answer the following questions through this analysis
Five top states with the highest number of registered voters
which party got the highest vote among the top states with the states with highest no of registered vote?
Five top states with the highest population?
which party got the highest vote among the top 5 states with the highest population
Five top states with the LOWEST population
which party got the highest vote among the top 5 states with the lowest population
Group the data by 'Geopolitical Zones' and aggregate the sum of votes
COMPARING POPULATION AND NO OF REGISTERED VOTERS
Election Results by State and Party
TOTAL SUM OF VOTE FOR EACH PARTY
Nigerian map showing each states won by the four parties


Result from the analysis
From the analysis and result called by inec Nigeria's election umpire, here is the main summary from the 36 states and Abuja
Tinubu of APC scored the highest votes of 8,865,420 and won 12states( Rivers, Bornu, Jigawa, Zamfara, Benue, Kogi, Kwara, Niger, Ekiti, Ondo, Oyo, Ogun)
Atiki of People's Democratic party (PDP) scored 6984290 votes and won 12 states (Kastina, Kebbi, Sokoto, Kaduna, Gombe, Yobe, Bauchi, Adamawa, Taraba, Osun, Akwa Ibom, Bayelsa)
Peter Obi also won 12 states got 6093962 votes from(Edo, Cross River, Delta, Lagos, FCT, Plateau, Imo, Ebonyi, Nasarawa, Anambra, Abia, Enugu).
Kwankwaso (NNPP) won with 1496671 votes and only won 1 state (Kano).

CONCLUSION
Based on the result Tinubu scored at least 25% of votes in 29 states, Atiki 21% and Obi 16%, one needs at least 24/25 states including FCT and Tinubu got the call making him to be pronounced the winner of the Presidential Election

