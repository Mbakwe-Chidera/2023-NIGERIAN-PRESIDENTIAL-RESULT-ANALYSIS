2023 PRESIDENTIAL ELECTION RESULT ANALYSIS FOR TOP 4 PARTIES by MBAKWE CHIDERA (DATA ANALYST)


The Nigerian election is one of the largest most anticipated election in West_Africa. The 2023 Nigerian presidential election was held on 25 February 2023 to elect the president and vice president of Nigeria.
Nigeria’s Independent National Electoral Commission (INEC) has declared Bola Tinubu of the All Progressive Congress (APC) the winner of the 2023 presidential election. Tinubu polled a total of 8,794,726 votes to defeat his closest rival, Atiku Abubakar of the People’s Democratic Party (PDP), who scored 6,984,520 to emerge second, Peter Obi of Labor Party 
(LP) scored  and Kwankwaso of NNPP scored 1496671.

Data Sources
# The data was gathered from the Independent National Electoral Commission (INEC) official website and Vanguard for Presidential results.  

Data Analysis
The raw data obtained was in .pdf and .html formats, so I converted it into a more friendly format (.csv) to be analysed using python packages called pandas, geopandas, folium, and matplotlib.

The python environment i am using is call Jupyter notebook which can be view and downloaded from the links below:-
1) You can view it on GitHub here.

Source code
The completed source code is provided below, but I strongly recommend you view it on IPython notebook online here.


# # Nigerian Presidential Election Result Analysis - 2023
# 
# Author: Mbakwe Chidera


# ### Data Source
# The data was gathered from the Independent National Electoral Commission (INEC) official website.
# 
# The Data (in .csv format) used is available for 
# 
# Am going to use these three main python programming packages pandas with matplotlib embedded to analyse the 2023 Presidential Election Result.

INTRODUCTION
Nigeria has 36 states and 1 federal capital territory, 6 Geopolitical zones (SOUTH EAST, SOUTH WEST, SOUTH, NORTH EAST, NORTH WEST, NORTH CENTRAL). 
The 2023 presidential election was held in the 37 territories within the country.
Eighteen (18) political parties representing eighteen(18) candidates participated in the 2023 presidential elections. The parties are as follow: AA, AAC, ADC, ADP, APC, AP, APGA, APP, APM, BP, LP, NNPP,NRM, PDP, PRP, SDP, YPP and ZLP. See the names of candidates and there parties below:-


Candidate Names:
Party Name:
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

DATA ENTRY
The data entry was collected and entered by me combined statistics from INEC (iREV server wasn’t detail enough,it has mostly pictured result) and Vanguard(had detailed table for results of each candidate by state), I had to pull out some info and combined results and it will contain numeric values by states for;
1) Vote scored by each political party
2) No of registered voters
3) Population
4) Population rank.

I will attempt to answer the following questions through this analysis
1) Five top states with the highest number of registered voters
2) Which party got the highest vote among the top states with the states with highest no of registered vote?
3) Five top states with the HIGHEST population?
4) Which party got the highest vote among the top 5 states with the highest population
5) Five top states with the LOWEST population
6) Which party got the highest vote among the top 5 states with the lowest population
7) Group the data by 'Geopolitical Zones' and aggregate the sum of votes
8) COMPARING POPULATION AND NO OF REGISTERED VOTERS
9) Election Results by State and Party
10) TOTAL SUM OF VOTE FOR EACH PARTY
11) Nigerian map showing each states won by the four parties


RESULT
From the analysis and result called by inec Nigeria’s election umpire, here is the main summary from the 36 states and Abuja
Tinubu of APC scored the highest votes of 8,865,420 and won 12states( Rivers, Bornu, Jigawa, Zamfara, Benue, Kogi, Kwara, Niger, Ekiti, Ondo, Oyo, Ogun),
Atiki of People’s Democratic party (PDP) scored 6984290 votes and won 12 states (Kastina, Kebbi, Sokoto, Kaduna, Gombe, Yobe, Bauchi, Adamawa, Taraba, Osun, Akwa Ibom, Bayelsa),
Peter Obi also won 12 states got 6093962 votes from(Edo, Cross River, Delta, Lagos, FCT, Plateau, Imo, Ebonyi, Nasarawa, Anambra, Abia, Enugu),
Kwankwaso (NNPP) won with 1496671 votes and only won 1 state (Kano).

CONCLUSION
Based on the result Tinubu scored at least 25% of votes in 29 states, Atiki 21% and Obi 16%, one needs at least 24/25 states including FCT and Tinubu got the call making him to be pronounced the winner of the Presidential Election.Though there are still some controversies concerning the election, this analysis is based on what was declared by INEC as at this time.
Congratulations to the winning party (APC) and candidate (Bola Ahmed Tinubu).
