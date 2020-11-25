## Introduction
This topic is interesting for me since I have worked at a company who have put milions of dollars into AI and sees to be failing to get a ROI. What would I do better if I had the chance to change things?
Most of these notes are from different sources eg from podcasts I have listened to, conferences I have attended or books I have read.
- [Podcast interview of Henrik Landgren, founder of Spotify and EQT](https://www.pythonpodcast.com/henrik-landgren-artificial-intelligence-episode-287/)
- 

## When and how is AI useful? 
Digging in data is fund and you can learn so much. This is also a problem since it's really easy to put time and effor into things that does not drive the project forward and that is not useful. There are many companies who have not extracted any value, only isolated results where there is a missing link between data and the descissions that are needed.
And It's really easy to create dashboards presenting a lot of metrics. The key is to minimize the amount of data that is pressented, and only pressent the data that is used to take better descisions.
Present a hypothesis and extract only as many datapoints that is needed to take a descision. Should we continue or not?


## Which tecnique is most important, DL, ML, AI or statistics?
The most important thing is if it solves you problem or not, it's not that important which bucket you are using to solve your problem.

# How do you build a successful 
Start by finding a way of collecting both internal(within the company) and external data and store all the data on one place to make it easily accessable.
The create a pipeline unit for analyzing the collected data. It need to be in a logical fashon meaning that you first have one part with all the raw-data, and then use it to extract some features and continlue to build further on the data. It's really important to make clear from where the data is extracted and where the result is stored, it's easy to make a mess.
Then you need to make easy to store, test and deploy new models to fasten the itteration.

Use an machinelearning engineer to setup the tools and a data scientist to produce the models. Don't use your best engineers, but use the one who have both the technical and buisniss understanding.
Create clean dataset that can be used in the pipeline.
Make it easy and fast to try out different solutions.
There is actually nothing that is called AI, it's just a datadriven way of taking descissions.



Environment där data sicentist can access and expore models and place where they can put models into production
14.00
Or tooling for
Output for serving models

Bygga dashboards.
utmana: för enkelt att bygga dashboards. Tänk istället att vilken information de behöver för att kunna ta ett beslut och pressentera detta med så få dashboards som möjligt.

Vilket skillset är
i början:
2 roller: techincal roll- data engineer veta hur de olika komponenterna ser ut, tar architekt beslut. 
Perosnen som ställer frågorna: Data scientist som kan koda men som även kan affärsmodellen så att man både teck och buisnis. Om man bara har en developer finns risken att man inte svarar på de viktigaste frågorna.
hur man använder sig av de olika algorithmerna så att man kan vara kreativ och starta skapa de första modeller som finns. skapa prototyper av nya AI verktyg
man måste experimentera och itterera massor av gånger.
Detta är lätt om man ha all infrastruktur på plats.

Data engineer: mycket bättre på att bygga saker som går att skala upp. 
rensa data. skapa dataset som skall användas senare i pipelinen.
därefter bygga vidare.

finns egentligen inget som AI projekt. det handlar om att ständigt vara datadriven och använda sig av de bästa verktygen för att lyckas med sin verksamhet


-------------
Hur vet man om det är värt att starta ett projekt?
-
- Se till att man har tillräckligt med data
- Hur kan man göra en process där AI och människor arbetar tillsammans.
EQT- finns inte tillräckligt med datapunkter. Däremot Bygga en process med en modell som pressentera de mest intressanta punkterna därefter låter man människan slutföra uppgiften.
När människan gjort sitt beslut så ger man feedback tillbaka till systemet så att den får en ström av data att arbeta vidare med för att förbättra sig själv.
som ett självlärande process.
inte lösa allt på en gång.

26.45
2 syften med platformen. göra beslutsprocessen så effektiv som möjligt. bygga modellerna för att göra detta.
Om vi tar reda på vad som behövs för att göra beslutsprocessen effektivare och effektivare lär man sig vilken typ av data som behövs när den lyckas/misslyckas.
Varje evolution för varje månad

dashboards- som besluts verktyg, vad behöver de veta för att kunna ta ett bra beslut?

hur ai används:
gpt3 generara text med jälp av seed input.
generera information, deep-fake videos.
största misstag med AI. twitter agorithmen, väljer ett ansikte och väljer ansiktet och croppar till de.
om det är flera ansikten, algorighmen väljer vita killen ansiktet.

Man kommer förstärka BIAS in sin träningsloop. Hur kommer man bort från detta? Man indexerar på andra saker än vad algorighmen föreslår. t.ex att man kikar på diversiteten på sina teams.

psykologin i platfromen så att man faktiskt använder sig av verktyget. Om det inte är enkelt att använda verktygen 
Vad är personens arbetsbörda, är persoenen arbetsbörda, ge inte mer infromation om han inte är klar på andra sidan så att man får 


agila tänkandet, börja smått skala upp!


checkout data engineering podcast


anacondacon 2017:
https://www.youtube.com/watch?v=xrYMfbcv3-c&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=2

the dominion

Data sicence: 2017
https://www.youtube.com/watch?v=jx1zqddZM1k&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=17

book ultra learning
7:30: vanligaste felet, man anstället ett gäng data-scienteits, stänger in dem i ett rum och hoppas på att något magiskt skall hända.
för att lyckas:
1. team sport. uppgiften skall spegla företagets mål, vi hjälper varandra, insikter distrubueras över företaget så att man kan utveckla verksamheten
2. Processen kan vara viktigare än modellen: genom att man systematiskt utvecklas kan även en misslyckad modell vara grunden till en förbättrad verksamhet
3. Hastighet otroligt viktigt: När det gäller att testa en hyppotes och få ett svar är det viktigt att loopen är snabb. 

insight driven buisnezes

om man har en modell kan man 
1. hämta (mer)data
2. skaffa insikter
3. testa och implementera insikter i mjukvara
4. mäta resultatet och justera implementationen
5. identifiera utfall och följ metrics
gå tillbaka till nr 1

snabbheten i denna process är viktig.

trycker på att man inte skall köra "datadrivert" dvs vilken data har man, undersöka denna och därefter köra lite.
1. De som lyckas känner till marknaden.
2. De samlar ihop den data som de har och försöker skaffa kunskap som de tror har relevans
3. de implementerar insikterna och testar dessa vilket genererar mer data och oftast mer insikter (24.00)

31:30
data: insikter: actions decisions

https://www.youtube.com/watch?v=0XDqc5wTve0&list=PLGB9meziqbzqvly8Skj3qTieC-fSXeR8T&index=3&t=0s&app=desktop
