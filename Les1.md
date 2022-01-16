# Microsoft CLoud Adoption Framework for Azure

Door: Sam van Winsen & Daan Stam

- [Microsoft CLoud Adoption Framework for Azure](#microsoft-cloud-adoption-framework-for-azure)
  - [YouTube](#youtube)
  - [Image](#image)
  - [Type standaard/framework](#type-standaardframework)
    - [Doelgroep](#doelgroep)
  - [Governance bijdrage](#governance-bijdrage)
    - [Bedrijfsbeleid](#bedrijfsbeleid)
    - [Disciplines](#disciplines)
  - [Governance aspecten](#governance-aspecten)
  - [Sterke en zwakke punten](#sterke-en-zwakke-punten)
  - [Conformeren grote cloud providers zich hieraan](#conformeren-grote-cloud-providers-zich-hieraan)

----------------------------
## YouTube
[YouTube filmpje 1 min, 11 sec](https://www.youtube.com/watch?v=9ch1iuJJzgA)

## Image
<img src="https://docs.microsoft.com/nl-nl/azure/cloud-adoption-framework/_images/caf-overview-new.png">

-------------------------

## Type standaard/framework
"Het Microsoft Cloud Adoption Framework for Azure is een richtlijn die is ontworpen om u te helpen bij het maken van en implementeren van bedrijfs- en technologiestrategieën voor de cloud." ~ Microsoft 04-01-2022 

In dit framework worden de best practices voor cloud adoption samengebracht welke Microsoft in samenwerking met Microsoft-werknemers, -partners en -klanten heeft gedefinieerd. Het doel is om de cloud adoption voor nieuwe klanten te vergemakkelijken, door strategieën voor technologie, bedrijf en personen vorm te geven en zo de beste bedrijfsresultaten te krijgen bij de cloud adoptie. 

Enkele best practices binnen het Azure Well-Architected Framework, wat een onderdeel is van het Microsoft Cloud Adoption Framework, zijn; kostenbeheer, Operationele uitmuntendheid, efficiëntie van prestaties, betrouwbaarheid en beveiliging. 

### Doelgroep
Doordat de manier waarop gebruik wordt gemaakt van IT zaken zoals; servers, netwerk apparatuur, backup oplossingen verandert van On-premise naar de cloud, zullen ook de technische richtlijnen veranderen. Doordat de richtlijnen veranderen heeft dat ook invloed op de bedrijfsvoering en bedrijfscultuur. Volgens Microsoft zijn de volgende rollen hierbij betrokken. 
* Line-Of-Business-leiders
* Zakelijke beslisser
* IT-besluitvormers
* Finance
* Ondernemingsbeheerders
* IT-activiteiten
* IT-beveiliging en -naleving
* IT-governance
* Eigenaren van workloadontwikkeling
* Eigenaren van workloadbewerkingen

Elk van deze rollen zal op een andere manier beinvloed worden doordat de werkwijze is veranderd. Finance zal bijvoorbeeld zien dat de OPEX kosten van IT verhoogd zijn en dus dient er een groter OPEX budget voor IT gebudgetteerd te worden. Doordat de OPEX kosten veranderen zullen de CAPEX kosten ook veranderen. 

----------------------

## Governance bijdrage
<img src="https://docs.microsoft.com/nl-nl/azure/cloud-adoption-framework/_images/operational-transformation-govern-large.png">
Binnen het Microsoft Cloud Adoption Framework for Azure bestaat er een heel hoofdstuk welke over het onderwerp Governance gaat. Er worden hier ook handleidingen gegeven vanuit Microsoft over hoe Governance het beste ingericht kan worden volgens dit Framework. 

Zoals in bovenstaande afbeelding te zien is worden er drie punten van bedrijfsbeleid en vijf disciplines van Cloud Governance benoemd:

### Bedrijfsbeleid
1. Business Risks
2. Policy & Compliance
3. Process

### Disciplines
1. Cost management
2. Security Baseline
3. Resource Consistency
4. Identity Baseline
5. Deployment Acceleration

Door gebruik te maken van duidelijke mijlpalen en concrete zakelijke voordelen is de cloud-adoptie te vergemakelijken en op deze manier kan er ook zorg gedragen worden dat het project niet van het traject ontspoort en dus veel groter wordt als bedoelt. Op deze manier is het afronden van het project ook een stuk te vereenvoudigen, al is het invoeren van cloud-adoptie nooit echt klaar. Nu kan het natuurlijk wel zo zijn dat er telkens extra mijlpalen bij komen, maar je moet ervoor zorgen dat de eerder gezette mijlpalen wel afgesloten worden. 

------------------------
## Governance aspecten
Het Microsoft Cloud Adoption Framework for Azure behandeld de volgende governance aspecten: 
* Strategie
* Plannen
* Adopteren
* Beheren
* Beveiligen
* Organiseren

Bij het aspect Stategie wordt er gekeken hoe er het beste een cloudacceptatie strategie ontwikkeld kan worden, wat ook belangrijk is is dat de bedrijfsstrategie inzichtelijk gedocumenteerd is. Microsoft heeft enkele stappen gedefinieerd om de bedrijfsdocumentatie efficient te documenteren. Onderstaande zijn de stappen:
1. Uw motivaties definiëren en documenteren
   1. Hier dienen de redenen duidelijk gedocumenteerd worden, zodat er later op terug gekeken kan worden, mochten er vragen ontstaan waarom er gekozen werdt om naar de cloud te gaan. 
2. Bedrijfsresultaten documenteren
   1. Je documenteerd hier de volgende gegevens.
      1. Fiscale resultaten
      2. Resultaten van flexibiliteit 
      3. Reulstaten van bereik
      4. Resultaten van klantenbinding
      5. Resultaten van prestaties
      6. Duurzaamheidsdoelstellingen
3. Financiële overwegingen evalueren
   1. Hier documenteer je de verwachtingen over de verschuivingen van CAPEX naar OPEX. Dit doe je om de budgettoewijzingen aan te passen voor de nieuwe manier van werken. 
4. Technische overwegingen begrijpen
   1. Schaalbaarheid: Is er te schalen afhankelijk van gebruik en vraag. 
   2. Beschikbaarheid: Is het goedkoper op de beschikbare architectuur in de cloud te ontwerpen?
   3. Beveiliging en naleving: Microsoft bied hier toolsets voor aan om op de hoogte te blijven van de huidige staat van het netwerk. 
   4. Capaciteitsoptimalisatie: Hier kijk je naar het gebruik van de resources en dan specifiek naar het gebruik gedurende specifieke momenten. 
  
Microsoft heeft tevens een sjabloon ontwikkeld om de strategie voor cloud adoption in uit te bouwen: [Document](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2FCloudAdoptionFramework%2Fmaster%2Fplan%2Fcloud-adoption-framework-strategy-and-plan-template.docx&wdOrigin=BROWSELINK)

Bij het aspect Plannen dient er gekeken te worden naar hoe de migratie gepland wordt, denk hieraan aan het inhuren van extra personeel welke de kennis heeft welke gemist wordt binnen het team, een plan ontwikkelen voor ondersteuning aan de organisatie terwijl deze went aan de nieuwe werkomgeving. 

Bij het aspect Adopteren dient er gekeken te worden naar hoe wordt de migratie in de organisatie geadopteerd, dit is een aspect welke in het Microsoft Cloud Adoption Framework for azure apart wordt benoemd. Het aspect Adoptie gaat er ook op in dat er bedrijfsworkloads gaandeweg gemigreerd dienen te worden zodat mensen gewend raken aan de migratiemethodes van Azure. Dit kan ook tot verbeteringen in het migratieprocess leiden. 

Bij het aspect Beheren dient er gekeken te worden naar hoe wordt de nieuwe cloudomgeving beheerd, welke toezegingen kunnen er vanuit het bedrijf gegeven worden over de workloads. 

Bij het aspect Beveiliging dient er gekeken te worden naar wat de bedrijfsdisciplines zijn dus, wie heeft er toegang, wie heeft een wijziging uitgevoerd etc. Dit is een aspect welke zeer belangrijk is voor het veilig kunnen opereren van een cloud oplossing. 

Bij het aspect Organiseren dient de organisatiestructuur gedefinieerd te worden, dus de teams welke specifieke cloudfuncties aan bieden dienen bekend te zijn en dienen te passen bij het bedrijfsmodel. 

## Sterke en zwakke punten
Enkele sterke punten van het Microsoft Cloud Adoption Framework for Azure zijn de volgende:
1. Het framework is specifiek voor Microsoft Azure ontwikkeld
2. Het framework is in samenwerking met Microsoft-werknemers, -partners en -klanten ontwikkeld. 

Enkele zwakke punten van het Microsoft Cloud Adoption Framework for Azure zijn de volgende:
1. Het is heel erg op Microsoft Azure gecentreerd, andere cloud providers worden maar in een hoofdstuk benoemd. 

## Conformeren grote cloud providers zich hieraan

Het Microsoft Cloud Adoption Framework for Azure is een framework van Microsoft ontwikkeld voor Azure, dit is een framework waar Azure dus conform aan is. 

Als ik het Microsoft Cloud Adoption Framework for Azure vergelijk met het AWS Cloud Adoption Framework dan zijn er geen grote verschillen tussen de twee, behalve dat de eerste voor Azure is en de tweede voor Amazon Web Services. Natuurlijk zijn de bewoordingen niet gelijk, maar in grote lijnen zijn het vrijwel exact dezelfde frameworks. 

------------------------

Bronvermelding

[Wat is de Microsoft Cloud Adoption Framweork voor Azure](https://docs.microsoft.com/nl-nl/azure/cloud-adoption-framework/overview)

[AWS Cloud Adoption Framework(AWS CAF)](https://aws.amazon.com/professional-services/CAF/)

[Overview of Cloud Adoption Framework for Azure (YouTube 14 min)](https://www.youtube.com/watch?v=j2Vk-YNdSdQ)