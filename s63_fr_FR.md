---
layout: default_fr_FR
---
# Conditions de l'UserPermits S-63

- S-63 plugin n’est pas disponible pour Android ou iOS.

- Nous ne vendons pas de cartes de S-63, nous fournissons juste le S-63 *UserPermit* qui est un outil nécessaire à l'acquisition des licences des cartes S63 auprès de revendeurs comme[Chartworld](https://www.chartworld.com/shop/off_enc).

- Pour acheter un des cartes S-63 auprès de n’importe quel fournisseur, vous avez besoin d’un UserPermit. Les cartes sous licence avec le UserPermit pour OpenCPN S-63 sont utilisables uniquement en conjonction avec OpenCPN conformément à la norme S-63.

- Vous êtes autorisé à utiliser chaque carte, que vous avez acheté, sur 5 *systèmes d'exploitation* simultanément, ou vous pouvez conserver des utilisations disponibles pour le cas où votre système d'exploitation deviendrait hors d'usage. Nous génèrerons un *InstallPermit* pour OpenCPN pour chaque système individuel. Le InstallPermit associe un jeu de cartes S-63 pour OpenCPN à un seul système. Ne confondez pas l'InstallPermit pour OpenCPN avec les autorisations de cellule S-63.

- Un *Système"* est la conjugaison d'un matériel et de son système d'exploitation. Si le matériel ou le système d'exploitation change, votre installation sera considérée comme nouvelle et vous perdrez votre licence ce qui entrainera que vous devrez utiliser un autre "InstallPermit".

- Si vous avez consommé votre 5 droits d'installation, vous devrez acheter un nouveau UserPermit et donc la licence des cartes pour ce nouveau UserPermit. Comme il s’agit d’un nouveau cycle, vous aurez encore 5 possibilités d’installation (InstallPermits).

- Votre licence devrait rester active sur tous les systèmes, même si vous mettez à jour OpenCPN ou ses compléments. Mais si vous ré-installez votre système, vous perdrez votre licence.

- Une fois que vous avez acheté un UserPermit nous ne pouvons pas vous rembourser.

- Une fois que vous avez généré un InstallPermit pour un système, nous ne pouvons pas l'annuler ou le déplacer sur une installation différente (matériel ou système d'exploitation).

- Vérifier les conditions des fournisseurs de cartes S-63 en ce qui concerne les mises à jour et la date d’expiration.

# Installation UserPermits/InstallPermits et jeu de cartes S-63

![pas](./assets/images/s63.png)

1. Le *système* est l’ordinateur que vous utiliserez pour OpenCPN. Le jeu de cartes, que vous achetez chez un VAR pour un système, peut être exclusivement utilisé sur ce système. Allez sur la page [Complément oeSENC](https://opencpn.org/OpenCPN/plugins/s63.html) pour télécharger et installer le complément S-63 (uniquement pour la version 4.6 de OpenCPN ou plus récente).
    
2. Dans OpenCPN, allez dans *Options → Compléments → S63* et activez-le. Puis, allez dans OpenCPN, dans l'onglet *Options → Cartes/données → Cartes S63 → Clés/Permis* et créer un fichier d’identification du système (*FingerPrint</em) pour votre système en appuyant sur le bouton *Créer le fichier d'identification*.</p></li> 
        
3. Allez à [Boutique o-Charts](https://o-charts.org/shop) et achetez un UserPermit.
        
4. Allez sur la page [Mes UserPermit S-63](https://o-charts.org/shop/index.php?fc=module&module=ocpermits&controller=ocpermits), créer un InstallPermit en téléchargeant le fichier FingerPrint que vous avez généré avant et lier le à votre UserPermit S-63.
        
5. Visiter la boutique de votre VAR (fournisseur de S-63) et acheter autant de cartes S-63 que vous avez besoin, à l’aide de votre UserPermit pour S-63 avec OpenCPN. Parfois un VAR demandera un « HW-ID », ignorer la question.
        
6. Télécharger et décompresser vos fichiers de cartes S-63. Il contient un répertoire appelé ROOT_ENC (contenant les cellules des cartes) et vous trouverez également un fichier appelé "PERMIT.txt" avec les autorisations des cellules.
        
7. Aller dans les options d'OpenCPN, à l'onglet*Options → Cartes/données → cartes S63 → Clés/permis*. Entrez votre UserPermit et testez-le en appuyant sur la touche *Nouveau UserPermit*. Entrez votre InstallPermit et testez-le en appuyant sur la touche *nouveau InstallPermit*.
        
8. Aller dans les options d'OpenCPN, à l'onglet*Options → Cartes/données → cartes S63 → Cellules de carte*. Installer les permis de cellule en utilisant le bouton *Importer les permis des celleules* pour trouver le fichier PERMIT.txt à l’intérieur de vos jeux de cartes S-63. Importer vos jeux de cartes S-63 en appuyant sur *Importer cartes/mises à jour* en trouvant le dossier ENC_ROOT.
        
9. OpenCPN créera les fichiers eSENC nécessaires et ce sera fini !</ol></li> </ol> 
        
# Foire aux Questions
        
> **Pourquoi les cartes S-63 ?**
> 
> Officielles, elles sont, généralement, les cartes marines les plus à jour disponibles. Les traceurs de cartes vectorielles utilisés pour le marché des loisirs sont au mieux des dérivés (certains auront quelques fonctionnalités ajoutées).
> 
> **Pourquoi dois-je payer pour le UserPermit ?**
> 
> Il faut exécuter cette opération et de répondre au exigences de l’OHI sur une base permanente. La structure et les coûts sont réduits au minimum. Dans le cas où nous arriverons à un grand succès économique, les fonds iront à OpenCPN.
> 
> **Pour combien de systèmes un ordinateur dual-boot compte t il ?**
> 
> Chaque combinaison HW/SW est individuelle et nécessite son propre InstallPermit.
> 
> **Et si j’installe le logiciel sur une Machine virtuelle ?**
> 
> Il ne fonctionnera pas. Il faut empêcher le système d’être cloné.
> 
> **J’ai dû réinstaller mon OS. Maintenant, le InstallPermit n’est plus valide**
> 
> S’il vous plaît, générer une nouvelle InstallPermit.
> 
> **Mon PC est mort. Puis-je récupérer les cartes ?**
> 
> Oui et ceci vous "coûtera" un InstallPermit pour votre nouvelle machine.
> 
> **Puis-je avoir mon InstallPermit et les cartes sur une clé USB et les transporter d'un système à l'autre ?**
> 
> Ce serait une solution de dongle hardware. Nous pensons qu’il n’est pas viable pour nous d'envoyer des clés USB ou des DVD dans le monde entier. C’est pourquoi nous avons opté pour un dongle logiciel. Ainsi, la réponse aujourd'hui est "Non".
> 
> **Quel est le coût de cartes S-63 (et pourquoi sont-elles parfois si chère) ?**
> 
> Le prix de vente est fixé par chacun des offices hydrographiques (SHOM, UHKO, ...). Les clients proviennent de l’industrie du transport maritime et/ou des organismes officiels comme les gouvernements, pas le marché des loisirs. C’est un problème reconnu et c'est la raison pour laquelle il y a très peu d’utilisateurs de cartes S-63, pour l’instant. Nous aurons besoin de beaucoup de lobbying pour obtenir les meilleures solutions et les meilleurs prix. Aide ou soutien de ceux qui ont les bons interlocuteurs serait apprécié.
> 
> **Mon permis temporaire expire. Que va-t-il se passer ensuite?**
> 
> Les cartes ne disparaîtront pas, mais il y aura un avertissement affiché.
> 
> **OpenCPN est open source. Où est le code du complément ?**
> 
> Pour utiliser des cartes S-63, il faut s’assurer qu’aucune copie de cellule non chiffrée n’est accessible pendant l’exécution du logiciel. Par conséquent, le complément a une partie open-source et une partie close-source. Comme pour les compléments BSB4 et nv-charts.
