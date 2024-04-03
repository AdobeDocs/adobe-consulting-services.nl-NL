---
product: adobe experience manager
solution: Experience Manager
description: Raadpleeg documentatie van Experience Managers
type: Documentation
git-repo: https://github.com/AdobeDocs/adobe-consulting-services.nl-NL
index: y
source-git-commit: e2dac4b36fb94d72b72ef6f73a77e3f566539444
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 0%

---


# Metagegevens voor intern gebruik

De meta-gegevens in het GitHub auteurssysteem zijn hiërarchisch en worden bepaald de volgende stijgende niveaus van precedent.

1. metadata.md
1. ToC
1. Artikel

De metagegevens die zijn gedefinieerd in het bestand metadata.md, worden toegepast op de volledige repo, maar kunnen worden overschreven op de ToC- en artikelniveaus. Als de metagegevens worden genegeerd, moet dat op het laagst mogelijke niveau gebeuren.

metadata.md

* `product`
* `git-repo`
* `index: y`

ToCs

* `sub-product`
* `user-guide-title`

Artikel

* `title`
* `description`

Aanvullende informatie over de metagegevens vindt u in het gedeelte [interne ontwerphandleiding](https://experienceleague.adobe.com/docs/authoring-guide-exl/using/authoring/metadata.html).
