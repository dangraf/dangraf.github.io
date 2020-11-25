## Introduction
This topic is interesting for me since I have worked at a company who have put milions of dollars into AI and sees to be failing to get a ROI. What would I do better if I had the chance to change things?
Most of these notes are from different sources eg from podcasts I have listened to, conferences I have attended or books I have read.
- [Interview of Henrik Landgren, founder of Spotify and EQT](https://www.pythonpodcast.com/henrik-landgren-artificial-intelligence-episode-287/)

## Main pitfalls 
Digging in data is fund and you can learn so much. This is also a problem since it's really easy to put time and effor into things that does not drive the project forward.

How to startu a data science team. Mainly notes from the podcast podcast._init__ with an interview with Henrik Landgren, founder of spotify and EQT.
[https://www.pythonpodcast.com/henrik-landgren-artificial-intelligence-episode-287/](ref)

när, var och hur är AI användbart, 
Stor risk att man gräver ner sig i massor av dashboards, metrics etc. Man vill minimera mängden information, hur får vi ut värde så att man kan ta bättre beslut.
Om man inte är super diciplinerad kommer man lägga massor av tid på saker som i slutändan inte är användbart. Ta reda på vad som verkligen behövs, ta fram en hypotes och ta fram precis så många datapunkter som beövs för att kunna ta ett beslut.
ja eller nej för att fortsätta.
Många har inte fått ut något värde, bara ett isolerat resultat någon stans. man saknar länken mellan den data de har och de beslut som man vill ta. 
Om man lyckas konkretisera vad nycklarna är för sin verksamhet, vad man skall mäta för att se om man är på rätt väg, då kan AI göra underverk.

Motherbrain project? vad är det?

hur man avänder sig av uttrycker machine learning ai deep-learning etc.
Det viktigaste är utfallet och det finns massor av metoder att använda sig av. Om den är i statistik hinken, ML DL etc spelar mindre roll.

en metod att hämta all data, både internt och externt. En enhet där man spar all data så att den blir lätt tillgänglig.
Nästa enhet för att analysera datan och spara pipelines.
bygga en logisk sekvens och då kan man lätt bygga tillsammans på ett effektivt sätt.
Om man inte gör detta kommer man skapa massor av problem.

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
