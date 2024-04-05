---
title: Overzicht van Veva Vault-integratie
description: Overzicht van Veva Vault-integratie
exl-id: 52cc7290-b7e1-4476-877f-48934e6daf68
source-git-commit: 005c738818ab622a342ddc3a94e94638e344d058
workflow-type: tm+mt
source-wordcount: '692'
ht-degree: 0%

---

# Aan de slag met de integratie van Veeva Vault PromoMats en Adobe Experience Manager

Deze integratie zal uw inhoud beheren, rechten en naleving afdwingen terwijl ook het hefboomeffect eerst in de levering van de klassenervaring.

Voor deze integratie zijn minimaal de volgende softwareversies vereist:

* Adobe Experience Manager, 6.5.5+
* Veeva Vault PromoMats, 20R3.2+

>[!NOTE]
>
>De gebruikers van de dienst en de aangewezen toestemmingen worden vereist in beide systemen voor de integratie.
>

>[!IMPORTANT]
>
>Deze mogelijkheid is niet beschikbaar in de verpakking als onderdeel van het product. Voor de implementatie is een onderhoudscontract voor overleg met de Adobe vereist. Neem contact op met uw Adobe voor meer informatie.
>

## Beginselen en kenmerken

Deze integratie is ontworpen om twee hoofdgebruiksituaties te ondersteunen:

1. Goedkeuring van inhoud - Wanneer nieuwe inhoud is gemaakt of bestaande inhoud is bewerkt in AEM, moet de inhoud worden goedgekeurd voor gebruik in VVPM ter ondersteuning van het goedkeuringsproces voor medische, juridische en regelgevende (MLR) biowetenschappen.

2. Inhoudsbeheer - Voorzie de zichtbaarheid van het gebruik van middelen door in PromoMats relaties tot stand te brengen tussen digitale tactieken (bijvoorbeeld e-mail, presentaties, websites) en de elementen daarvan (bijvoorbeeld logo&#39;s, fotografie, afbeeldingen) die in AEM zijn gemaakt voor documenten die afkomstig zijn uit AEM.

De voordelen zijn onder meer:

* Eén bron van waarheid bewaren voor elementen en inhoud zonder duplicatie tussen digitale opslagplaatsen.
* Gebruik van zowel Veeva Vault voor beheer van rechten en naleving en AEM voor de beste prestaties op het gebied van klasse en middelen en het maken/leveren van inhoud.
* Hiermee kunt u het verplaatsen van inhoud en metagegevens tussen AEM en Veeva Vault automatiseren.
* Hiermee vermindert u handmatige inspanningen bij het verzenden van inhoud naar Veeva voor goedkeuringswerkstromen.
* Elk systeem wordt gebruikt voor zijn sterke punten en de schakelaar helpt in het verplaatsen van inhoud automatisch tussen de systemen om de tijd aan markt te helpen versnellen.

Wat doet de integratie?

* Ondersteunt het verzenden AEM Site Pages, Assets, Content Fragments en Experience Fragments naar VVPM. AEM Pagina&#39;s, inhoudsfragmenten en ervaringsfragmenten kunnen worden verzonden als PDF of afbeeldingen die zijn opgenomen in een schermafbeelding. AEM Assets-binaire bestanden worden ongewijzigd verzonden.
* Ondersteunt handmatige en geautomatiseerde synchronisatie van geselecteerde metagegevenselementen die kunnen worden geconfigureerd van AEM naar VVPM.
* Ondersteunt handmatige en geautomatiseerde synchronisatie van geselecteerde metagegevenselementen die kunnen worden geconfigureerd van VVPM naar AEM.
* Ondersteunt relaties tussen AEM sitepagina&#39;s, elementen, inhoudsfragmenten en ervaringsfragmenten in VVPM om inhoudsrelaties te automatiseren.
* Ondersteunt het genereren van vertoningen voor meerdere apparaattypen.

>[!NOTE]
>
>Raadpleeg de documentatie bij het integratiegebruik voor meer informatie over configuratieopties.
>

Wat doet de schakelaar NIET?

* Geeft geen replicatie van AEM processen en functionaliteit in Veeva of omgekeerd.
* Dit doet MLR op zich niet. Het helpt bij het automatisch verzenden van inhoud naar Veeva naar waar MLR plaatsvindt.
* Niet bedoeld om een identieke opstelling tussen AEM en Veeva te creëren. Niet alle inhoud hoeft tussen de twee platforms te worden verplaatst.


>[!IMPORTANT]
>
>Deze integratie beschouwt momenteel AEM als de bron van waarheid voor inhoudssynchronisatie.
>

## De integratie ophalen

Om deze integratie mogelijk te maken, moet u de onderstaande stappen volgen.

Volg hieronder het stroomschema en de stroomdiagramdetails om de integratie aan te vragen en te vormen.

![Toegang aanvragen](assets/integration-request.png)

Stroomdiagramdetails (afbeeldingen tot bovenstaande stappen):

* **Stap 1** - Er wordt aangenomen dat u al een licentie voor Veeva Vault PromoMats en voor Adobe Experience Manager hebt, of dat u dit aan het doen bent.
* **Stap 2** - Een nieuwe verkooporder (SO) die een onderhoudsovereenkomst met Adobe Consulting schetst, moet worden ondertekend om van de integratie te kunnen profiteren.
* **Stap 3** - Installeer, activeer en configureer het integratiepakket.

## Ondersteuning

Hieronder wordt beschreven hoe u contact opneemt met het ondersteuningsteam en een probleem aanmeldt.

### Integratie of Adobe Experience Manager-ondersteuning aanvragen

De kaartjes van de steun kunnen met de Zorg van de Klant van de Adobe worden geregistreerd. Uw Adobe Experience Cloud-beheerder moet zich aanmelden bij [Adobe Admin Console](https://adminconsole.adobe.com/)klikt u op het tabblad Ondersteuning en maakt u een hoofdlettergebruik. Voor alle problemen met integratie moet u de volgende informatie opnemen:

* **Procestitel**: `AEM - Veeva Vault Integration`
* **Proceseigenaar**: `Data Engineering`
* **Beschrijving**: `Description of the issue`
* **Contactpunt**: `The email address(es) for relavant AEM point of contacts for your organization.`
* **Instantie-URL AEM**: `Place the Adobe Experience Manager instance url here.`
* **Instantie-URL van Veeva**: `Place the Veeva Vault PromoMats instance url here.`

### Veeva Vault PromoMats-ondersteuning aanvragen

Het probleem dat zich voordoet, is soms een probleem met de werking van het Veeva Vault PromoMats-exemplaar. Als dat het geval is, kan de beheerder van uw Vève Vault PromoMats worden opgedragen een ondersteuningsticket te maken met [Veeva-ondersteuning](http://support.veeva.com/). De status van de instantie van Veva kan worden bekeken door naar [Veeva Trust](http://trust.veeva.com/).

