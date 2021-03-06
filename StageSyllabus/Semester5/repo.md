#Github repository
Al je documenten en documentatie dien je in een eigen, private github repository te bewaren. Je dient daarvoor de structuur te gebruiken van de StudentRepo.
Je moet je aan de structuur van deze repo houden. Uiteraard mag je waar nodig in de mappen extra zaken toevoegen (ordelijk houden aub).

##Hoe ga je te werk
* Ga naar Blackboard en open daar in de cursus Bachelorproef en stage 6 de "cursusdocumenten" map.
* Volg de "invite"-link getitteld "Je private repo"
* Maak via de invite een nieuwe repo aan. **Let op de naamgeving:** deze moet AchternaamVoornaam_BAP1516 zijn. Heet je dus Jos Stoffels dan zal je repo als naam StoffelsJos_BAP1516 noemen.

Vervolgens, *mogelijkheid A*
* Download vervolgens de mappenstructuur van de voorbeeld repo [hier](https://github.com/AP-Elektronica-ICT/BAP_Stage_StudentRepo/archive/master.zip)
* Unzip deze zip en plaatst de content van de hoofdmap in je nieuwe repo. (dus de readme.md file en de overige mappen moeten in de root van je repo terecht komen)
* Commit al deze nieuw toegevoegde zaken aan je repo en je kan beginnen.

*Mogelijkheid B*

* Open een shell met Git en clone de BAP_Stage_StudentRepo met 
`git clone https://github.com/AP-Elektronica-ICT/BAP_Stage_StudentRepo.git`
* Ga naar de directory met de repo
`cd BAP_Stage_StudentRepo`
* Verander de remote origin van originele repo naar eigen repo
`git remote remove origin` en dan 
`git remote add origin (jouw repo giturl hier)`
* Push de locale repo naar GitHub 
`git push -u origin master`
* Commit al deze nieuw toegevoegde zaken aan je repo en je kan beginnen.

 
##Tijdens de stage
* Standaard ben je geen admin van de repo. Indien je andere mensen toegang wil geven tot je repo dan dien je admin-rechten via de stagecoordinator aan te vragen. *Het is aanbevolen dat ook je stagementor toegang heeft tot je repo.*
* Je repo hoeft niet als primaire repo gebruikt te worden voor je werk op het bedrijf. Indien het bedrijf bijvoorbeeld een eigen sourcecontrol-systeem heeft dan gebruik je deze voor al je code. 
* Je gebruikt deze repo minstens als primaire punt voor je **scriptie, log, presentaties en verslagen**.
