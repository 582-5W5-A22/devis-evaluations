[*Ce travail sera évalué directement sur GitHub et votre serveur Web d'hébergement du site Web **par votre enseignant** (aucune remise requise, mais assurez-vous que les éléments de remise sont complets sur GitHub et le serveur d'hébergement à la date limite de remise).*]

## Intégration de l'interface utilisateur du site Web (6 points)

---
### Objectif général
---

À l'issue de ce sprint, la mise en page de l'interface utilisateur du site Web doit être en grande partie complétée et le site Web doit être déployé sur la plateforme d'hébergement approuvée (*SiteGround*) : 
* Les modèles du thème WP (ou encore les composants *React* consommant l'API WP) sont développés suffisamment pour représenter fidèlement la structure de votre site Web (*gabarits* WP tels que `front-page.php`, `header.php`, `footer.php`, `functions.php`, `page.php`, etc. ou composants adéquats dans le cas d'une IU développée avec *React*) ;
* Le formatage de l'interface utilisateur est complété à l'aide des feuilles de style (CSS/Sass) et le résultat est conforme au design du site Web spécifié dans les maquettes graphiques ;
* Le site Web est déployé sur *SiteGround*.

---
### Éléments de remise et barème
---

#### **A) Intégration Web des écrans du site** (2 points)
   1) Niveau d'avancement ;
   2) Respect des maquettes ; 
   3) Navigation fonctionnelle. 

#### **B) Codification CSS/Sass** (2 points)
   1) Les fichiers de code source sont adéquatement commentés ;
   2) Originalité de la structure *Sass* ;
   3) La structure de dossiers permet de retrouver facilement les règles de styles des éléments de base, des composants et des écrans du site en général ;
   4) Les sélecteurs sont efficaces : général pour les éléments de base et spécifique pour les composants ;
   5) Vous utilisez les propriétés CSS de façon optimale ;
   6) Les stratégies de positionnement que vous utilisez permettent l'adaptabilité de vos pages aux différentes largeurs d'écran. Vous utilisez notamment le mode d'affichage *flex* et/ou *grid* pour atteindre cet objectif.

#### **C) Codification HTML/PHP/React** (2 points)
   1) Les fichiers de code source sont adéquatement commentés ;
   2) Les médias sont intégrés avec la fonctionnalité *media* de WordPress et non pas manuellement dans un dossier non standard ;
   3) Vos modèles WP (ou composants *React*) sont bien structurés ;
   4) L'extraction des données se fait de façon optimale notamment dans le fichier `functions.php` avec le *hook* : `pre_get_posts`.