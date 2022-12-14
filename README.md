# NLP for French Archaeological Reports - ARIADNEplus

<br>

This corpus was created within the Task 16.8 of the [ARIADNEplus project](https://ariadne-infrastructure.eu/)[^1]. It was annotated with [INCEpTION](https://inception-project.github.io/) (Ubiquitous Knowledge Processing Lab, TU Darmstadt) and consists so far of six French archaeological reports of the [Inrap](https://www.inrap.fr/) (circa 500 pages for 133,414 tokens and 5078 entities). 

<br>

Six types of entities were annotated and linked to the [Pactols](https://pactols.frantiq.fr/opentheso/) Knowledge Base for the moment: 

| **Name** | **Description** | **Number of occurrences** |
|----------|-----------------|---------------------------|
|     CHRONO     |      Used for temporal references ("Antiquity", "XIIth century", "200 BC", etc.).          |              1082             |
|     CONTEXTE     |        Used for archaeological features ("pit", "ditch", "wall", "hearth", etc.).         |              2399             |
|    INTERVALLE      |        Used for time spans ("from the Neolithic to the late Antiquity", "VIIth-IXth centuries", "between 50 and 70 AD", etc.). This entity type was not linked to Pactols.         |            225               |
|     MAT     |          Used for materials ("bronze", "dolerite", "ceramic", etc.).       |             123              |
|     MOB     |       Used for physical finds ("bones", "pottery shards", "roof tile", etc.).          |           1170                |
|    TECH_STYLE      |         Used for mentions of techniques and styles of fabrication or construction ("carved", "glazed", "polished", etc.).        |              79             |

<br>

Relations were also created between entities in an experimental way: hasForChronology (aPourChrono), hasForContext (aPourContexte), hasForTimespan (aPourIntervalle), hasForMaterial (aPourMat), hasForTechOrStyle (aPourTechOuStyle).

<br>

The data is available in two formats: **CoNLL 2002** and **WebAnnoTSV v.3.3**. 

The **annotation guidelines** (written in French) can also be found at the root of the repository.
 
<br>

**Terms of use : https://www.inrap.fr/catalogue-dolia-15609**

<br>

# Le TAL pour les rapports fran??ais d'op??ration arch??ologique - ARIADNEplus

<br>

Ce corpus a ??t?? cr???? au sein de la t??che 16.8 du [projet ARIADNEplus](https://ariadne-infrastructure.eu/)[^2]. Il fut annot?? avec [INCEpTION](https://inception-project.github.io/) (*Ubiquitous Knowledge Processing Lab*, TU Darmstadt) et se compose actuellement de six rapports d'op??ration arch??ologique de l'[Inrap](https://www.inrap.fr/) r??dig??s en fran??ais (environ 500 pages pour 133&nbsp;414 tokens et 5078 entit??s).

<br>

Six types d'entit??s ont ??t?? annot??es et reli??es ?? la base de connaissances [Pactols](https://pactols.frantiq.fr/opentheso/) pour le moment : 

| **Nom** | **Description** | **Nombre d'occurrences** |
|----------|-----------------|---------------------------|
|     CHRONO     |      Utilis?? pour les r??f??rences chronologiques ("Antiquit??", "XIIe si??cle", "200 av. J.-C.", etc.).          |              1082             |
|     CONTEXTE     |        Utilis?? pour les faits arch??ologiques ("fosse", "foss??", "mur", "foyer", etc.).         |              2399             |
|    INTERVALLE      |        Utilis?? pour les intervalles chronologiques ("du N??olithique ?? la fin de l'Antiquit??", "VIIe-IXe si??cles", "entre 50 et 70 de notre ??re", etc.). Ce type d'entit?? ne fut pas reli?? ?? Pactols.         |            225               |
|     MAT     |          Utilis?? pour les mat??riaux ("bronze", "dol??rite", "c??ramique", etc.).       |             123              |
|     MOB     |       Utilis?? pour le mobilier ("os", "tessons de c??ramique", "tuile", etc.).          |           1170                |
|    TECH_STYLE      |         Utilis?? pour les mentions de techniques et styles de fabrication ou construction ("taill??", "gla??ur??", "poli", etc.).        |              79             |

<br>

Des relations furent ??galement cr????es de mani??re exp??rimentale entre les entit??s : aPourChrono, aPourContexte, aPourIntervalle,  aPourMat, aPourTechOuStyle.

<br>

Les donn??es sont disponibles sous deux formats : **CoNLL 2002** et **WebAnnoTSV v.3.3**. 

Le **guide d'annotation** (??crit en fran??ais) peut ??galement ??tre trouv?? ?? la racine du d??p??t.

<br>

**Conditions d'utilisation : https://www.inrap.fr/catalogue-dolia-15609**

<br>

[^1]: ARIADNEplus is a Horizon 2020 project funded by the European Commission under Grant Agreement n.??823914. The views and opinions expressed in this publication are the sole responsibility of the author and do not necessarily reflect the views of the European Commission.
[^2]: ARIADNEplus est un projet Horizon 2020 financ?? par la Commission europ??enne dans le cadre de la convention de subvention n?? 823914. Les points de vue et opinions exprim??s dans cette publication rel??vent de la seule responsabilit?? de l'auteur et ne refl??tent pas n??cessairement ceux de la Commission europ??enne.
