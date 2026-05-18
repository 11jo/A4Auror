/////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////////////////////////////////////////////////////////////
////                                                                             ////
////                                  L'Auror                                  ////
////                      Kit de Rôdeur pour BGII-ToB-EE                       ////
////                                Version 4.4.1                                ////
////                                by aeviannce24                               ////
////                                                                             ////
/////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////////////////////////////////////////////////////////////


SOMMAIRE////////////////////////////////////////////////////////////////////

1.  Versions..........................................(au00)
2.  Pourquoi j'ai créé ce mod.........................................(au01)
3.  Renseignements sur les Aurors..........................................(au02)
4.  La culture des Aurors...........................................(au03)
5.  L'Auror, un rôdeuse............................................(au04)
6.  Les Aurors dans les jeux Baldur's Gate...............................(au05)
7.  L'Auror (Description du kit)..........................(au06)
8.  Gel, glace, étourdissement et bien d'autres..................(au07)
9.  Tableau de progression des sorts innés et standard..........................(au08)

	Innés :
		Zéro absolu....................................(au08a)
		Projection des sens......................................(au08b)
            Le clin d'œil de l'hiver....................................(au08c)
		FLa morsure de l'hiver......................................(au08d)
	Sorts :
		Aura glaciale...................................(au08e)
		Déferlante de glace.....................................(au08f)
		Aurore boréale...............................(au08g)
		Terrible hiver.....................................(au08h)
		Désolation glacée......................................(au08i)
		Les lamentations de l'hiver...............................(au08j)

10. Contenu absent.............................................(au09)
11. Délires et divagations.........................................(au10)
12. Remerciements et autres............................................(au11)


Versions/////////////////////////////////////////////////////////////(au00)

Version 4.4.1
- Uprade fl#add_kit_ee 2016 edition to 2017 edition for better EET compatibility
- Add French translation.
- Correct items proficiency.
- Handle Charset.

Version 4.4.1
- Compatibility with BGII-EE and BGII-TOB
- Fixed typo errors and added proper descriptions on kit, items and spells.

Version 4.04
- Thac0 bonus for missile weapons changed from +1 every 2 levels to +1 every 4 levels.
- Damage bonus for missile weapons changed from +1 every 4 levels to +1 every 6 levels.
- AC bonus vs. Missles changed from +1 every 5 levels to +1 every 6 levels, caps at the 30th level.
- Changed save vs. spell bonuses from +1 every 2 levels to increments of +1 every 2 levels till the 8th level, then every 3 levels till the 17th level, and finally every 4 levels till the 29th level of experience.
- Frostbite progression table rebalanced. See table for details.
- Removed AC bonuses from Glacial Aura
- Removed leftover effects during testing from spells
- Decreased hp gained per level to 1d4 (EE only).

Version 4.03
- Thac0 bonus for missile weapons changed from +2 every 4 levels to +1 every 2 levels.
- Increased save vs. spells bonus to +1 every 2 levels.
- Added Foresight ability. She can now detect invisible creatures, though they are still invisible (invisible detection by script) and is immune to backstab.
- Removed Frost Touch ability to instantly kill fire elementals.
- Removed low level versions of Frostbite and reworked freezing effects. See progression table for details.
- Reworked Cryogenesis ability, ice blade and arrows. The Cryogenesis ability can now be learned every 2 levels of the caster. The blade and arrow produced by this spell is limited to usable only by human/elf/half-elf rangers with a charisma score of 16 and up (minimum cha requirement for Auror kit) in an attempt to limit its use to other npc. Ice blade now deals 1d6 piercing damage and is now a shortsword. Ice blade can be removed through its equipment ability.
- Standardized Freezing and Frozen abilities. All freezing abilities will have a save vs. breath and all frozen abilities will have a save vs. death.
- Glacial Aura now behaves more like an aura and hopefully less cheesy. Its effects have been reworked; see spell progression table for details.
- Removed frozen effect from Frost Wave.
- Increased Aurora Borealis HP bonus. See Spell progression table for details.
- Dire Frost's level 30 instant freezing death now allows a save vs. death, no bonus.
- Reworked damage curve of Hoarfrost. Increased max level damage to a total of 20d10. See spell progression table for details.
- Changed Lament of Winter's kill 60HP, no save, to instant freezing death, no save, with effect dependent on hit dice values of enemies within range of its effect. See spell progression table for details.
- Reduced Lament of Winter's casting time to 2 seconds.
- Lament of Winter's side effect now prevents the caster from getting healed for 1 turn.

Version 4.02
- Improved Ice Arrow ability. It will now function similar to a quiver of plenty though the duration is lessen to 8 hours.
- Decreased Ice Blade duration to 8 hours.
- Correction on the mod version. Sorry, I forgot the extra zero. :S

Version 4.01
- Fixed some typos and improved some descriptions.
- Improved buffet distance curve per level for Frost Wave.
- Aurora Borealis now increases in regeneration and hp bonus depending on the level of its caster.
- Decreased Direfrost chance to instant freezing death by 5%.
- Reworked Hoarfrost to deal more damage by level of caster and harm party members.
- Added Far Sense innate ability. Effects are the same as Farsight albeit shorter duration.

Version 4.0
- Too many to put into detail.

Version 3.0
- Not released.

Version 2.0
- Not released.

Version 1.0
- First release.


Pourquoi j'ai créé ce mod////////////////////////////////////////////////////////////(au01)

J'adore le kit Archer. Malheureusement, j'ai trouvé qu'il manquait un peu du POW ! supplémentaire des autres classes. J'ai donc décidé de chercher un bon mod de kit d'archer, et je suis tombé sur des tutoriels. Alors pourquoi ne pas en faire un à la place ? Et en modifier un en fonction de mes préférences. Je me souviens que l'Echorcheur avait une capacité cône de froid en attaquant, j'ai donc pensé que je pourrais construire une histoire secondaire et construire mon kit sur celle-ci. Ainsi, l'Auror est né.


Renseignements sur les Aurors/////////////////////////////////////////////////////////////(au02)

Lorsqu'on découvre qu'un enfant (normalement une fille douée de magie) possède la capacité de contrôler le gel ou plus officiellement la Cryokinésie, un Auror peut alors se manifester. Avec la permission de son tuteur et en échange d'une vie dévouée à sa pupille, l'enfant est enrôlé dans les rangs des Aurors. C'est ainsi que fonctionne cette congrégation.

Les Aurors sont un groupe unique de guerrières ayant la capacité exceptionnelle de contrôler les éléments de glace et les forces de l'hiver. Ce sont des protectrices énigmatiques, à la limite du mythique, des royaumes du nord. Souvent considérés comme des esprits de glace ou des Aurillites, elles sont à la fois craintes et vénérées par les habitants du Nord, et parfois même considérés comme des divinités mineures.

Elles ont peut-être acquis leur réputation légendaire grâce aux récit des personnes qu'elles ont secourues. Un extrait particulier décrit la rencontre d'un aventurier avec une légendaire Auror : 

"...Une redoutable erreur de pronostique, avec pour conséquence d'être pris dans une violente tempête de glace et de grêle. Avec toute la force dont j'étais capable, j'ai avancé dans cette étendue de neige apparemment sans fin, battu par un vent qui hurle la mort et la consternation. Je suis tombé à genoux... fatigué, gelé et las. Je sens la mort arriver. Je ferme les yeux et attends son étreinte glacée mais apaisante. Alors que je me soumets la tempête s'arrête soudainement ; le temps semble se figer et tout devient silencieux. J'ouvre les yeux et, dans une bourrasque, une silhouette apparaît devant moi. Une créature, rayonnante telle une deva, s'avance lentement, doucement avec grace. Ses yeux d'abord flamboyants avec des teintes bleues et blanches similaires aux aurores boréales se révèlent être aussi beaux que le ciel nordique, elle me salue d'une voix froide, mais réconfortante Elle était pâle, avec des cheveux scintillants sous la neige, et ne portait que des vêtements légers, impropres à résister aux vents du nord. Pourtant, elle ne semble souffrir d'aucun inconfort. Elle me regarde d'un air serein et compatissant. Je ne peux m'empêcher de me sentir soulagé et sens mon esprit défaillir lentement... Mais je ne peux pas ! Pas encore... Je dois encore observer cette magnifique créature qui se tient devant moi. Je dois sentir l'étoffe de sa robe qui caresse délicatement ma main gelée. Je dois savoir si elle est réelle. J'ai beau essayer, mais ma conscience ne résiste pas rester très longtemps. Alors que je m’évanouis, sa main se met à briller telle une aurore boréale. C'était... l'esprit du nord. Une étreinte chaleureuse qui submergea mes sens. Mon corps brisé devint alors silencieux. 

En reprenant mes esprits, j'ai constaté que les gens se précipitaient sur moi. Je me suis mis debout, stupéfait de constater que mon corps meurtri par le froid glacial était indemne. Les habitants de la ville étaient stupéfaits et je partageais leur étonnement, mais je sentais que la source de leurs regards écarquillés ne venait pas de mon état. Mes souvenirs étaient brouillés. Je ne savais pas quand et comment j'étais arrivé là. Mon seul souvenir est la belle silhouette qui est apparue devant moi. Après avoir vu que j'allais bien, les habitants de la ville se sont lentement dispersés. En murmurant les mots "encore un..." ou "quel veinard". Curieux, j'ai demandé "De quoi parlez-vous ?" Une vieille femme s'est retournée et a répondu : "L'Auror... Elle vous a sauvé."

Les barbares du nord chantent des hymnes qui dépeignent ce que pourraient être les exploits des Aurors au combat. Dans ce chant, les braves guerriers repoussent un démon déchaîné venu des montagnes. Mais la bête est puissante, indomptable, alors qu'ils perdent lentement du terrain et se replient dans les terres qu'ils essayaient de protéger. Le démon continue son attaque violente, éliminant les nobles guerriers un par un. Alors que tout espoir semble perdu, une violente rafale de vent glaciale balaie le champ de bataille, repoussant l'assaut du monstre. Des femmes vêtues de simple tissu et de soie apparurent, les yeux remplis d'une lueur d'un bleu ardent. Le démon est soudain bombardé de comète de glace et de feu venues des cieux. Deux des guerrières disparaissent alors dans une bourrasque, pour réapparaître près du démon et l'attaquer sans relâche avec un déluge de flèches et de glace. Le démon riposte furieusement, mais ces femmes esquivent ses attaques comme s'il n'était rien de plus qu'un enfant en train de jouer. Une autre comète s'abat sur le démon, qui vacille, agonisant. Sentant son destin inéluctable, il tente désespérément une dernière attaque, mais ralenti par le froid et la glace, avant que ses griffes n'aient pu toucher la plus proche de ces femmes qui ont mené à sa perte. L'une d'entre elles s'avance, dans sa main une épée faite de la glace la plus pure et d'un seul coup, elle brise le démon figé dans la glace. Enfin, le monstre est vaincu. 

Alors que le corps du démon se désagrège, ces héroïnes s'occupent des blessés, soulageant leur douleur avec des lumières reflétant le ciel du nord. Puis, aussi vite qu'elles sont arrivées, elles disparurent en un clignement de paupières. Pas un mot, pas de sourires, aucune gratitude ne put être prononcée. Les énigmatiques guerrières n'ont jamais été revues. Bien que leurs exploits aient alimenté de nombreuses chansons, personne ne savait ce qu'elles étaient. Seules la beauté et la grâce manifestées par ces généreuses femmes étaient à jamais gravées dans leur mémoire.


La culture des Aurors//////////////////////////////////////////////////////////////(au03)

The Aurors came from different backgrounds, different cities, and possibly different realms. The only thing that binds them is they all have the ability known as cryokinesis, or the innate ability to form and control ice at will. When a child is discovered to have this ability, a nearby Auror might sense this and would try to conscript the child, with the permission of the child's guardians. Most of them although hesitantly, would leave their child in the Auror's care, as the life of a child with an unusual ability (and quite possibly, even an unusual appearance) is normally a hard one. This is how Aurors normally increase their ranks, though it is not rare for an Auror to give birth to a child with a similar ability.

The Aurors comprised predominantly of female warriors and are thus, structured in a matriarchal but militaristic order. No one knows why but it is believed that this is due to the nature of their ability (as the element of ice and winter is under the portfolio of Auril, a primarily female god), though there have been instances of male Aurors, they are quite rare.

The Aurors are very reclusive, not because of anything but the fear for the safety of those around them, as the power of ice and winter is extremely unpredictable and highly destructive. A negative emotion such as fear, sadness, anxiety or anger might incite a sudden winter storm, or even worse, a dire frost. They do however, band in small communities deep within what would be considered as frozen wastes, living peacefully among their kin.

The Aurors are said to be lead by an unnamed silver dragon, who taught the first of the Aurors the ways of ice magic, lore and etiquette. These were passed down from generation to generation. As such, the very few Aurors who came in contact with the townsfolk were said to speak in kind and pleasing tones, if not a bit archaic.

An Auror spends a lifetime to acquire a better understanding and control of their ability, often going to the lengths of even sacrificing their physical wellbeing. As such, Aurors have relatively frail bodies. They do however excel in outmanoeuvring their foes, performing actions that seem to defy the grasp of the earth. They are a spectacle to behold; like graceful spirits dancing over the white covered land. Northern adventurers who get a glimpse of Aurors in play might mistake them for frost spirits; alluring them to an inevitable death. As such, they are normally left alone. Due to their weak physique, they are instead trained to be experts with the bow and arrow; using their psychic abilities to curve shots to hit marks that are otherwise impossible to make. To have a better control over their power, they are also trained to have a stronger mind and a steadfast will, thus are highly resistant to mental assaults and enchantments.

A young Auror is normally paired with a more experienced Auror, who serves as both teacher and a guardian. They value knowledge and wisdom and as such, give emphasis on education, among combat and magic training. They are also taught to present themselves elegantly and show proper etiquette to anyone they meet. One could even say that an Auror society is sort of ideal for women and consequently, even men.

Upon reaching a certain age, as a rite of passage to adulthood, a young Auror is tasked to enter a den of either a winter or a dire wolf in an effort to find an animal companion. These animals are notoriously known to adventurers to be quite aggressive and dangerous. Not for an Auror. When an Auror enters a den, she is seemingly greeted by the leader of the pack. The wolves are submissive and friendly, but only one wolf, normally a pup, would follow the Auror out of the den. When this happens, the Auror has found her animal companion.

When an Auror reaches her maturity, both in ability and in character, she is tasked to a certain part of an area, to serve as a protector of the land for a time. They are however, not allowed to make a strong contact with other creatures in order to preserve their untainted judgement. This is why Aurors are known to be the silent, enigmatic protectors of the wilds. 

An Auror who have served her duty is free to leave and live out her own life. Though the majority of Aurors tend to stay with their kin, some do leave and live a life of an adventurer or in service of a god. An Auror retain their good morals throughout her life, but she does not bend on the laws of men. At a certain point in their life, she would come back to her home, and share her experiences and if not with a life partner, would live the rest of her life with her fellow sisters.


L'Auror, une rôdeuse///////////////////////////////////////////////////////////////(au04)

L'Auror est réputé pour sa capacité à contrôler le givre avec sa seule volonté. Grâce à leur capacité psychique, l'Auror peut également bénéficier d'autres compétences comme la psychokinésie, la détection de créatures, la télépathie et, à un niveau de maîtrise supérieur, les attaques psioniques. Avec de l'entraînement, elle apprend à combiner ces capacités avec sa magie glacée naturelle et ainsi à produire une magie qui lui est propre.

The path of being an Auror is as cold and harsh as the rewards she might reap after. She is unprotected against the cold, though this is not really a discomfort for a creature who can command frost. At a young age, the Auror’s untamed magic leaves her constantly exposed, increasing her magic resistance at the cost of her physical wellbeing. She is trained day and night to hone her psychic abilities in conjunction to her marksmanship, agile movement and magic as the sheer psychic will is the most effective means to control her power. Her mind is constantly tested, to strengthen her will and make her less vulnerable to uncontrolled emotions that might spell disaster to those around her. Upon maturity, the Auror becomes a quasi-elemental and has gained almost complete control of her abilities, an agility that defies even the earth, a high resistance to magic and an indomitable will.

Other than combat and honing their magic and psionic abilities, they are also given education. Their culture, though being militaristic gives emphasis on intelligence and wisdom. Knowledge that is gathered from different realms relevant to their existence is taught and incorporated in their culture. With this, Aurors are known to be perceptive and quite intelligent. 

The Auror does not change much in physical appearance. The presence of cold magic in her body slows her aging, granting even human Aurors extended lifespan. Marks of aging or stress do not reflect on their bodies. Wounds do not leave traces of scars or any of the like. They retain much of their peak physical appearance throughout their lives. Due to this, they are normally described to be beautiful creatures, to the point of being mistaken for a frost dryad or something similar.


Les Aurors dans les jeux Baldur's Gate//////////////////////////////////////////////////(au05)

Comment l'enfant de Bhaal s'inscrit-elle dans la tradition des Aurors ?

L’écorcheur a la capacité d'invoquer une sorte de cône de froid quand il attaque. J'ai pensé que ça pourrait être une bonne base pour une petite histoire ici.

Comme la protagoniste possède une importante parcelle de l'essence de Bhaal, elle a pu, dans sa jeunesse, provoquer quelque chose de similaire à cette capacité cône de froid de l’écorcheur. Gorion, bien qu'étant un puissant mage, reconnaît qu'il n'est pas très familier avec certains aspects de la prophétie d'Alaundo, mais il connaît certainement quelqu'un qui en saurait assez.

Il invite donc une Auror à Château-Suif (d'après le scénario, il connaissait beaucoup de gens puissants. Il n'est donc pas surprenant qu'il connaisse une Auror, ou au moins leurs existences), et lui demande de se pencher sur la jeune enfant de Bhaal. Bien qu'elle ne puisse pas comprendre parfaitement la source du pouvoir de l'enfant, l'Auror confirme que son pouvoir est similaire à ceux des Auror. Gorion, qui connaissait la voie de l'Auror, insista pour que l'enfant soit formé en sécurité derrière les murailles de Château-Suif. L'Auror a questionné les motivations de Gorion, mais fut néanmoins convaincue. Elle accepta alors avec appréhension la demande de Gorion et ainsi, la formation de l'enfant de Bhaal commença.


L'Auror (Description du kit)///////////////////////////////////////////////////////////////(au06)

AUROR : Une rôdeuse plutôt singulière, compétente à l'arc et dotée d'une faculté remarquable pour contrôler les éléments associer à la glace et aux forces de l'hiver. Bien qu'on la prenne généralement pour une prêtresse d'Auril, l'Auror ne partage pas les tendances destructrices de la Fille du Gel et ses adeptes, au contraire elle applique rigoureusement la voie solitaire d'un dragon d'argent inconnue, connu pour être son hégémon.

Entraîné à développer son agilité, l'Auror est particulièrement rapide et précise dans ses mouvements, mais cette caractéristique tient davantage de la nécessité que du privilège, car le long chemin à parcourir pour devenir Auror est éprouvant et affaiblit le corps. Mais cela ne l'empêche pas d'aider ceux qui sont dans le besoin. C'est une protectrice énigmatique de tout ce qui est bon en ce monde, mais aussi une glaciale et impitoyable ennemie de ceux qui empruntent la voie du mal.

Avantages :

- Immunité aux charmes et à la confusion.
- Bonus de 2 à la dextérité à la création du personnage.
- Bonus de 1 au THAC0 pour les Armes de trait tous les 4 niveaux.
- Bonus de 1 au dégâts avec les armes de trait tous les 6 niveaux.
- Peut lancer de sorts de prêtre supplémentaires à partir du niveau 14.
- Gagne de 2 % de résistance à la magie à chaque monté de niveau; jusqu'au niveau 30.
- Bonus de 1 à la classe d'armure contre les projectiles tous les 6 niveaux; jusqu'au niveau 30.
- Peut atteindre la grande maîtrise avec les armes de trait : 5 points de compétence en Arc long et Arc court.
- Bonus de 1 à la classe d'armure et aux jets de sauvegarde contre les souffles, tous les 3 niveaux; jusqu'au niveau 29.
- Bonus de 1 aux jets de sauvegarde contre les sorts tous les 2 niveaux jusqu'au niveau 8, puis tous les 3 niveaux jusqu'au niveau 17, et enfin tous les 4 niveaux jusqu'au niveau 30.
- Démarre avec 7 % de résistance au froid, et gagne 12 % de résistance supplémentaire tous les 2 niveaux jusqu'au niveau 10, ainsi qu'aux niveaux 13 et 16, puis 9 % au niveau 20 et 24, et enfin 7 % supplémentaire au niveau 29.

- Tireuse d'élite : Démarre avec 1d19 chance de coup critique, et s'améliore tous les 6 niveaux ; jusqu'à atteindre 1d14 chance de coup critique au niveau 30.

- Boule de cristal : à partir du niveau 4, l'Auror appréhende le monde qui l'entoure de manière surnaturelle. Ce qui lui permet de détecter et d'attaquer les ennemis dissimulés (sans pour autant les rendre visibles). Étant impossible à surprendre, elle devient immunisée aux attaques sournoises.

- Caresse glacée : au niveau 6, à chaque attaque réussie, l'Auror inflige 2d4 points de dégâts de froid supplémentaires et gèle sa cible pendant 4 rounds (jet de sauvegarde contre les sorts pour éviter). Ses projectiles sont désormais chargés en énergie psionique qui renverse la cible si elle échoue à son jet de sauvegarde contre les souffles.

-  Dons innés :

   Niveau 2 : Zéro absolu - Lame de glace
   Niveau 4 : Zéro absolu - Flèches givrées
   Niveau 6 : Projection des sens
   Niveau 8 : Le clin d'œil de l'hiver
   Niveau 10 : La morsure de l'hiver
   
-  À partir du niveau 8, l'Auror développe de nouvelles aptitudes :

   Niveau 8 : Aura glaciale
   Niveau 10 : Déferlante de glace
   Niveau 12 : Aurore boréale
   Niveau 15 : Terrible hiver
   Niveau 18 : Désolation glacée
   Niveau 20 : Les lamentations de l'hiver

Inconvénients :

- Classe accessible uniquement aux humain, elfes et demi-elfes d'alignement neutre bon ou Chaotique bon.
- Ne peut pas attribuer de point de compétence dans d'autres styles de combat que celui à deux armes.
- Subit une pénalité de 1 à ses jets de sauvegarde contre la mort tous les 4 niveaux.
- Est peu compétente avec un certain nombre d'armes de jet et de mêlée.
- Malus de 6 à la constitution à la création du personnage.
- Malus de 8 à la force à la création du personnage.
- N’acquiert pas la capacité de charmer les animaux.
- N’acquiert pas de capacité de haut niveau.
- Ne peut pas porter d'armure.
- Ne peut pas se jumeler.
- Dés de vie : d4~


Gel, glace, étourdissement et bien d'autre/////////////////////////////////////(au07)

This kit adds a couple of effects needs to be explained a bit:

FREEZE: The victim is slowed and gets a penalty to hit, AC and save vs. breath weapons by 2 for the duration of the effect.

DEEP FREEZE: twice the efficacy of freeze status.

FROZEN: The victim is unable to move, though is still aware of its surroundings. The frozen creature gets 100% resistance to cold damage and cannot be buffeted. However, it gets a 20 AC penalty for the duration of the effect.

Stunning damage: This is similar to crushing damage though when the target's hp is reduced to 1, it will fall unconscious and can only be killed by any damage other than stunning.


Tableau de progression des sorts innés et standard////////////////////////////////////////////(au08)

Level	: Level requirement of the spell ability
SP	: Spell power. The level equivalent of the spell
CT	: Casting time
Fatigue	: The physical toll of the spell to the caster
PhyRES	: Physical resistance
FireREs : Fire resistance
Immu	: Immunity to enchanted weapons


////////////////
//            //
//  Innates:  //
//            //
////////////////

-------------------------------------------------------------------------------------
Zéro absolu                                                                   (au08a)
-------------------------------------------------------------------------------------
L'Auror gagne la capacité de créer des objets naturellement constitués de glace.

Spell Power	: 0
Casting Time	: 4
Fatigue Value	: 0

Lame de glace
Level	Enchantment	Thac0	Damage
2	+0		+4	1d3+3 points de dégâts perforant
6	+1		+4	1d3+3 points de dégâts perforant
10	+2		+4	1d3+3 points de dégâts perforant
14	+3		+4	1d3+3 points de dégâts perforant

Flèches givrées
Level	Enchantment	Thac0	Damage
4	+0		0	1d6 points de dégâts projectiles
8	+1		0	1d6 points de dégâts projectiles
12	+2		0	1d6 points de dégâts projectiles
16	+3		0	1d6 points de dégâts projectiles
20	+4		0	1d6 points de dégâts projectiles

-------------------------------------------------------------------------------------
Far Sense                                                                     (au08b)
-------------------------------------------------------------------------------------
At the 6th level, the Auror learns to extend her psychic sense over long distances to reveal areas that are otherwise impossible through the use of the naked eye. She gains this ability every 3 levels of experience.

Spell Power	: 0
Casting Time	: Instantaneous
Fatigue Value	: 0

Level	Duration in Rounds
3		3
6		4
9		5
12		6
15		7
18		8
21		9
24		10
27		11
30		12

-------------------------------------------------------------------------------------
Frost Blink                                                                   (au08c)
-------------------------------------------------------------------------------------
Beginning at the 8th level, the Auror can disappear in a gust of ice, and reappear anywhere in an area. She gains this ability every level.

Spell Power	: 0
Casting Time	: Instantaneous
Fatigue Value	: 0
No Progression

-------------------------------------------------------------------------------------
Frostbite                                                                     (au08d)
-------------------------------------------------------------------------------------
At the 10th level, the Auror can supercharge her missile attacks with psionic force. For 4 rounds, all her ranged attacks will explode upon impact, dealing 1d4 stunning and 2d4 cold damage +1 for every 3 levels of experience. Her attack speed incurs a penalty of -2 for the duration of the ability. She gains this ability every 2 levels of experience.

Casting Time	: 0
Fatigue Value	: 0

Level	SP	Damage			Effects
1	3	1d4+1 stunning		Freezing for 4 rounds
		2d4+1 cold		Save vs. breath, no bonus
		(Save vs. breath
		for half)

12	4	1d4+2 stunning		Freezing for 4 rounds
		2d4+2 cold		Save vs. breath, no bonus
		(Save vs. breath
		for half)

15	5	1d4+3 stunning		Freezing for 4 rounds
		2d4+3 cold		Save vs. breath -1
		(Save vs. breath
		for half)

18	6	1d4+4 stunning		Freezing for 4 rounds
		2d4+4 cold		Save vs. breath -1
		(Save vs. breath
		for half)

21	7	1d4+5 stunning		Freezing for 4 rounds
		2d4+5 cold		Save vs. breath -2
		(Save vs. breath
		for half)

24	8	1d4+6 stunning		Freezing for 4 rounds
		2d4+6 cold		Save vs. breath -2
		(Save vs. breath
		for half)

27	9	1d4+7 stunning		Freezing for 4 rounds
		2d4+7 cold		Save vs. breath -3
		(Save vs. breath
		for half)

30	10	1d4+8 stunning		Freezing for 4 rounds
		2d4+8 cold		Save vs. breath -3
		Save vs. breath
		for half)

-------------------------------------------------------------------------------------
_____________________________________________________________________________________


///////////////
//           //
//  Spells:  //
//           //
///////////////

-------------------------------------------------------------------------------------
Glacial Aura                                                                  (au08e)
-------------------------------------------------------------------------------------
Area of Effect: 15' radius around the caster

Level	SP	CT	Fatigue	  PhyRES	Immu
8	4	6	1	  7		normal weapons
10	5	5	1	  10		normal weapons
12	6	4	1	  13		+1
14	7	3	2	  16		+1
16	8	2	2	  19		+2
18	9	1	2	  22		+2
20	10	0	3	  25		+3

Level     Damage per round     Freezing per round
8         1d8                  Save vs. breath +2
10        1d8+1                Save vs. breath +1
12        1d8+2                Save vs. breath, no bonus
14        1d8+3                Save vs. breath -1
16        1d8+4                Save vs. breath -2
18        1d8+5                Save vs. breath -3
20        1d8+6                Save vs. breath -4


-------------------------------------------------------------------------------------
Frost Wave                                                                    (au08f)
-------------------------------------------------------------------------------------
Casting Time	: 0
Fatigue Value	: 0

Level	SP	Damage			Wing Buffet
10	5	1d6 stunning		Distance 5
		2d8 cold		Save vs. breath -4

13	5	1d6+1 stunning		Distance 8
		2d8+1 cold		Save vs. breath -5

16	6	1d6+2 stunning		Distance 10
		2d8+2 cold		Save vs. breath -6

19	6	1d6+3 stunning		Distance 13
		2d8+3 cold		Save vs. breath -7

22	7	1d6+4 stunning		Distance 15
		2d8+4 cold		Save vs. breath -8

26	7	1d6+5 stunning		Distance 18
		2d8+5 cold		Save vs. breath -9

30	8	1d6+6 stunning		Distance 20
		2d8+6 cold		Save vs. breath -10

Level	Freezing
10	4 rounds; save vs. breath, no bonus
13	4 rounds; save vs. breath -1
16	4 rounds; save vs. breath -2
19	4 rounds; save vs. breath -3
22	4 rounds; save vs. breath -4
26	4 rounds; save vs. breath -5
30	4 rounds; save vs. breath -6

-------------------------------------------------------------------------------------
Aurora Borealis                                                               (au08g)
-------------------------------------------------------------------------------------
Spell Power	: 6
Casting Time	: 2
Fatigue Value	: 1

Cures		: Fear(Horror, Morale Break), Intoxication, Poison, Blindness,
		  Deafness, Silence (Vocalize), Disease, Feeblemindedness,
		  Confusion, Rigid Thinking, Berserking, Hold, Stun, Sleep

Saves		: +2 bonus
Duration	: 4 rounds

Level	Regen Rate	HP bonus
12	1hp/12 sec	10
14	1hp/11 sec	13
16	1hp/10 sec	16
18	1hp/9 sec	19
20	1hp/8 sec	22
22	1hp/7 sec	25
24	1hp/6 sec	27
26	1hp/5 sec	29
28	1hp/4 sec	32
30	1hp/3 sec	35		

-------------------------------------------------------------------------------------
Dire Frost                                                                    (au08h)
-------------------------------------------------------------------------------------
Casting Time	: 6
Fatigue Value	: 1

Level	SP     Freezing Death			Slays Fire Elementals
15	6      5% chance; Save vs. death +4	Save vs. death -8
17	6      5% chance; Save vs. death +4	Save vs. death -8
19	7      5% chance; Save vs. death +3	Save vs. death -9
21	7      5% chance; Save vs. death +3	Save vs. death -9
24	8      5% chance; Save vs. death +2	Save vs. death -10
27	8      5% chance; Save vs. death +2	Save vs. death -10
30	9      5% chance; Save vs. death +0	No save

Level	Freezing			Frozen
15	1 turn; Save vs. breath -4	1 hour; Save vs. death -2
17	1 turn; Save vs. breath -5	1 hour; Save vs. death -3
19	1 turn; Save vs. breath -6	1 hour; Save vs. death -4
21	1 turn; Save vs. breath -7	1 hour; Save vs. death -5
24	1 turn; Save vs. breath -8	1 hour; Save vs. death -6
27	1 turn; Save vs. breath -9	1 hour; Save vs. death -7
30	1 turn; Save vs. breath -10	1 hour; Save vs. death -8

-------------------------------------------------------------------------------------
Hoarfrost                                                                     (au08i)
-------------------------------------------------------------------------------------
Spell Power	: 10
Casting Time	: 4
Fatigue Value	: 0

Level	Crushing Dmg	Cold Dmg	
18	8d6		2d4
21	9d6		4d4
24	10d6		6d4
27	11d6		7d4
30	12d6		8d4

Level	Wing Buffet
18	Distance 10; Save vs. breath -4; Unconscious for 1 round; save vs. death -8
21	Distance 10; Save vs. breath -5; Unconscious for 1 1/2 rounds; save vs. death -9
24	Distance 10; Save vs. breath -6; Unconscious for 2 rounds; save vs. death -10
27	Distance 10; Save vs. breath -7; Unconscious for 2 1/2 rounds; save vs. death -11
30	Distance 10; Save vs. breath -8; Unconscious for 3 rounds; save vs. death -12

-------------------------------------------------------------------------------------
Lament of Winter                                                              (au08j)
-------------------------------------------------------------------------------------
Spell Power	: 9
Casting Time	: 2
Fatigue Value	: 7

Constant Effects:
Deep freeze, 1 turn, no save
Deafness and/or Silence, 60% chance, 10% chance for both, 1 turn, no save

Level    Instant Freezing Death (no save)
20       Creatures with hit dice 12d
25       Creatures with hit dice 15d
30       Creatures with hit dice 18d

Level 	Freezing Death		Fear or Confusion
20	Save vs. death -2	33% chance, 6 rounds; save vs. spell -4 negates
25	Save vs. death -3	33% chance, 6 rounds; save vs. spell -5 negates
30	Save vs. death -4	33% chance, 6 rounds; save vs. spell -6 negates

-------------------------------------------------------------------------------------
_____________________________________________________________________________________


OMITTED CONTENT////////////////////////////////////////////////////////////////(au09)

While making this kit, I decided to omit some abilties that would make this kit a little too unbalanced or would be in conflict with other mods I want to try out. If you think they are still good to be added, tell me why and if you convinced me, I would gladly add them to this kit.

Summon Wolf Guardian
As the name suggests, at a certain level, the Auror is able to summon her wolf guardian. The wolf gets more powerful as the Auror gains in level.

WHY IT WAS OMITTED: I wanted to try Animal Companions by Ulb (http://www.shsforums.net/files/file/1064-animal-companions/). Having this ability is kinda redundant with that mod.

Mind Shatter
The the 10th level, the Auror is now able to assail the mind of a humanoid foe. If she wins, the victim is rendered either stunned for 2 rounds, unconscious for 6 rounds or addled and forgets three wizard spells. If she fails however, the Auror is hit with a psychic backlash recieving 1d12 stunning damage and is slowed due to mental pain for 4 rounds. Assailing a creature's mind is a difficult feat even for the Auror and continued use would render her mentally exhausted. Gains an ability ever 2 levels of experience.

WHY IT WAS OMMITED: At first, I opt to not include this ability since it might be overpowered. Trying to make this ability work only on humanoids and giant humanoids as well to invisible creatures is quite tedious to do so I didn't include it in this version.

Summoning from the previous versions
WHY IT WAS OMITTED: Auror summoning creatures was not inline with the lore I made for the Auror. It also proved to be too overpowered. So, I replaced them with abilities that I think are more suitable for her.


RANTS AND RAMBLINGS////////////////////////////////////////////////////////////(au10)

I really, really, REALLY... wanted to recreated the Comet animation for Hoarfrost. I had a basic idea on how to recreate it but I don't know how to make it work. It involves making use of split bam sequences (about 6 to 9 of them) and make the game engine it play simultaneously, just like the original Comet animation. However up till now, I have no idea how to code splitted bam sequences. As a result, I had to make due with what I know and made the Hoarfrost animation similar to a fireball. It's kinda disappointing really but it'll have to do for the meantime.

I also had a hard time finding a good animation for the Frost Wave spell. I wanted... well, a wave, around 15' radius or so, that animates similar to the animation I got for Lament of Winter albeit bigger... So, I end up not putting any animation for that spell. I guess its okay, though it might have been better if it did have one.

This might be the last time I would be doing a major overhaul of this kit, unless I get another eureka moment. For the suceeding release, it would likely be just minor improvements,rebalancing or error corrections.


THANKS AND STUFF///////////////////////////////////////////////////////////////(au11)

First of all, I would like to thank CamDawg for his awesome kit tutorial. I would also like to thank Daulmakan, The Imp, Wisp and Kwiat_W of SHS Forums for entertaining my questions, no matter how annoying they were. Lastly, I would also like to thank you, yes you! for trying out my mod. I hope you'd like it as much as I enjoy remaking it.

This kit had only been tested briefly since I don't want to play BGII ToB without BWP installed. So it might have some issues with balancing, some glitches or errors. If you have any comments, suggestions and whatnots, feel free to contact me through my email: (aeviannce24@gmail.com) or my profile over SHS forums: (http://www.shsforums.net/user/7088-aeviannce/)

I do not claim ownership over the BAMS used in this mod. Most of them came from IWDII and from BGII itself. All I did was just a little bit of colour tweaking, some cut and paste, and some recompiling.

Anyway, thank you again and I hope you enjoy playing as an Auror. cheers! :D


END OF DOCUMENT//////////////////////////////////////////////////////////////////////