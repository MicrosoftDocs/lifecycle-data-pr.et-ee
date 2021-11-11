---
title: Elutsükli andmete eksportimise juhised
description: Toote elutsükli teabe eksportimise juhised
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: et-EE
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546795"
---
# <a name="lifecycle-data-export-guidance"></a>Elutsükli andmete eksportimise juhised
Selles dokumendis kirjeldatakse, kuidas kasutada toote ekspordifaili.

## <a name="query-information"></a>Päringuteave
Exceli dokumendis on väljad, mis aitavad tuvastada toote tabelisse asustatud andmeid.

### <a name="end-of-support"></a>Tootetoe lõpp
Tootetoe lõppväärtus filtreerib tooteid tootetoe lõppkuupäeva või väljalaske lõppkuupäeva järgi.

Võimalikud väärtused: Kõik (filtrit pole rakendatud), Aasta ja Vahemik.

### <a name="family"></a>Perekond
Pereväärtus filtreerib tooteid emataseme järgi hierarhias, mida nimetatakse pereks.

Võimalikud väärtused: Kõik (filtrit pole rakendatud), Perekonnanimi

### <a name="group"></a>Rühm
Rühma väärtus filtreerib oma emataseme (pere) tooted kindlasse rühma.

Võimalikud väärtused: Kõik (filtrit pole rakendatud), Rühma nimi

## <a name="table-columns"></a>Tabeli veerud
Toote tabel koosneb veergudest, mis määratlevad toote, väljaanded, väljalasked ja vastavad kasutajatoe kuupäevad.

> [!NOTE]
> Iga toote, väljaande ja väljalaske kombinatsiooni kohta on rida.

### <a name="product"></a>Toode
Toote nimi.

### <a name="edition"></a>Väljaanne
Väljaande veerg lisatakse siis, kui toode sisaldab väljaandeid. Kui toote väljaannet pole, on see väli tühi.

### <a name="release"></a>Väljaanne
Väljalaske veerg asustatakse siis, kui tootel on mitu väljalaset.
Kui tootel on ainult üks väljalase, on see väli tühi.

### <a name="support-policy"></a>Tugiteenuste poliitika
See väli määratleb toote tugiteenuste poliitika.

Võimalikud väärtused: [Fikseeritud](/lifecycle/policies/fixed), [Modernne](/lifecycle/policies/modern), Komponent

### <a name="start-date"></a>Alguskuupäev
Tootetoe alguskuupäev.

### <a name="mainstream-date"></a>Tavatoe kuupäev
Kui tugiteenuste poliitika väärtuseks on **Fikseeritud** või **Komponent**, on see toote tavatoe lõppkuupäev.
  
Kui tugiteenuste poliitika väärtuseks on **Modernne**, on see tühi.

### <a name="extended-end-date"></a>Pikendatud lõppkuupäev
Kui tugiteenuste poliitika väärtuseks on **Fikseeritud** või **Komponent**, on see toote pikendatud lõppkuupäev.

Kui tugiteenuste poliitika väärtuseks on **Modernne**, on see tühi.

### <a name="retirement-date"></a>Kasutuselt kõrvaldamise kuupäev
Kui tugiteenuste poliitika väärtuseks on **Fikseeritud** või **Komponent**, on see tühi.

Kui tugiteenuste poliitika väärtuseks on **Modernne**, on see toote kasutuselt kõrvaldamise kuupäev.

### <a name="release-start-date"></a>Väljalaske alguskuupäev
Väljalaske tugiteenuste alguskuupäev. Kui tootel on ainult üks väljalase, on see väli tühi.
 
### <a name="release-end-date"></a>Väljalaske lõppkuupäev
Väljalaske tugiteenuste lõppkuupäev.
Kui tootel on ainult üks väljalase, on see väli tühi.

### <a name="docs-url"></a>Docs Url
Laiendatud dokumentatsiooni URL.
