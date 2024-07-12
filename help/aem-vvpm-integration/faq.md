---
title: Veelgestelde vragen over de integratie van Veeva Vault
description: Veelgestelde vragen over de integratie van Veeva Vault
exl-id: c308ebb3-7881-4094-9f35-c67a96fb5ab1
source-git-commit: e4a5e55ac9b79a8de7dfa8ddd3d0ad99560917b8
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 0%

---

# Veelgestelde vragen

**Welke meta-gegevens aan Veeva zouden moeten worden gesynchroniseerd?**

Het is belangrijk dat u de metagegevens begrijpt op basis van het inhoudstype (bijv. promoties) in de portal van Veeva. Nadat u het Veeva-portaal hebt bekeken, stelt u het metagegevensschema voor de inhoud in AEM om alle relevante metagegevens voor elk element/elke pagina te bevatten en configureert u de integratie om de metagegevens tussen de twee systemen in kaart te brengen.

**steunt de integratie de aan Veeva verbonden documenten? Zo niet, welke relatietypen worden ondersteund?**

Nee. Zie [ document van Veva ](https://vaulthelp2.vod309.com/wordpress/admin-user-help/documents-admin-user-help/about-document-relationships/). Het gekoppelde document (type referentierelatie) is een van de standaardrelatietypen die niet via de API kunnen worden gemaakt of verwijderd, omdat ze een speciaal vaultgedrag hebben. Component, ondersteunende documenten en andere documenten die niet in deze lijst staan, moeten kunnen worden geconfigureerd via AEM configuratie van Veeva Cloud.

**steunt de integratie de AEM modulaire inhoud?**

Ja, de integratie ondersteunt AEM Content Fragments en Experience Fragments.

**steunt de integratie de modulaire inhoud Veeva?**

Nee, op dit moment niet.

**synchroniseert de integratie visuele aantekeningen van Vève aan AEM?**

Nee, op dit moment niet. Visuele annotaties zijn alleen toegankelijk via API als PDF.

**hoe plaatsen wij toestemmingen op VVPM documenten die door de integratie worden gesynchroniseerd?**

De integratie gebruikt een de dienstgebruiker om documenten door API te uploaden.  De het in gebreke blijven en met voeten treden van documenten regels (het in gebreke blijven rollen op documenten) worden gesteund slechts in het VVPM gebruikersinterface, en niet toegepast wanneer het gebruiken van API. De aanbeveling is om DAC (Dynamic Access Control) te gebruiken voor roltoewijzingen. DAC wordt afgedwongen via alle aanraakpunten, inclusief de API. [ zie hier documentatie.](http://vaulthelp2.vod309.com/wordpress/admin-user-help/ah-user-permissions-access-control/about-dynamic-access-control-for-documents/)

**steunt de integratie veelvoudige instanties VVPM?**

De integratie gebruikt een benadering van de wolkenconfiguratie die veelvoudige eindpunten van Veeva om van één AEM instantie toestaat worden gevormd.

**steunt de integratie AEM publiceren?**

Nee, deze integratie werkt alleen met AEM auteur. Het is bedoeld om MLR-beoordelingscycli te vergemakkelijken voordat de inhoud wordt gepubliceerd.
