/////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////////////////////////////////////////////////////////////
////                                                                             ////
////                                  The Auror                                  ////
////                      Ranger Class Kit for BGII-ToB-EE                       ////
////                                Version 4.4.1                                ////
////                                by aeviannce24                               ////
////                                                                             ////
/////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////////////////////////////////////////////////////////////


TABLE OF CONTENTS////////////////////////////////////////////////////////////////////

1.  Changes by Version..........................................(au00)
2.  Why I made this Mod.........................................(au01)
3.  Lore on the Aurors..........................................(au02)
4.  The Auror Culture...........................................(au03)
5.  The Auror Ranger............................................(au04)
6.  Aurors and Bladur's Gate Lore...............................(au05)
7.  The Auror Ingame (Kit Description)..........................(au06)
8.  Freezing, Frozen, Stunning and Other Stuff..................(au07)
9.  Innate and Spell Progression Table..........................(au08)
	Innates:
		Cryogenesis....................................(au08a)
		Far sense......................................(au08b)
                Frost Blink....................................(au08c)
		Frostbite......................................(au08d)
	Spells:
		Glacial Aura...................................(au08e)
		Frost Wave.....................................(au08f)
		Aurora Borealis ...............................(au08g)
		Dire Frost.....................................(au08h)
		Hoarfrost......................................(au08i)
		Lament of Winter...............................(au08j)

10. Omitted Content.............................................(au09)
11. Rants and Ramblings.........................................(au10)
12. Thanks and Stuff............................................(au11)


CHANGES BY VERSION/////////////////////////////////////////////////////////////(au00)

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


WHY I MADE THIS MOD////////////////////////////////////////////////////////////(au01)

I love the archer kit. Unfortunately I felt that it kinda lacks the extra POW! other classes have. So I decided to look for a good archer-based kit mod but instead I stumbled onto some kit tutorials. I figured why not make one instead? I can mod one based on my preference. I remember the slayer change having a cone of cold effect while attacking, so I thought I could build a side story on that one and base my kit there. Thus, the Auror is born.


LORE ON THE AURORS/////////////////////////////////////////////////////////////(au02)

When a child (normally a female of magic-oriented race) is discovered to possess an ability to control frost or more formally known as Cryokinesis, an Auror might appear before the child. With the permission of the child's guardian in exchange for a dutiful life for their ward, she is drafted into the Auror ranks. Such is the way of the Aurors.

The Aurors are a unique group of warriors with the exceptional ability to control the elements of ice and the forces of winter. They are enigmatic, bordering on mythical, protectors of the northern realms. Often thought to be ice spirits or Aurillites, they are both feared and revered by northerners, and sometimes even worshipped as minor deities.

Perhaps they gained their legendary reputation from folks who tell tales of their rescue. One particular excerpt details an adventurer’s encounter with the fabled Auror: 

“…A dreaded mistake in reading the weather, with the consequence of getting caught in a violent storm of ice and hail. With all the might I could muster, I wade across the seemingly endless span of snow, battered by wind that screams of death and dismay. I fell to my knees… tired, cold and weary. I feel that death is upon me. I close my eyes and await it’s cold but relieving embrace. As I submit myself to the cold end that awaits me, the storm suddenly comes to a standstill; time seem to stop and everything falls silent. I opened my eyes and with a gust of cold wind, a figure appears in front of me. The creature, shining like a deva slowly but gently walks in a graceful manner towards me. With eyes blazing of blue and white hues of the northern lights, slowly dim and revealed eyes as beautiful as the northern sky then she greets me in a cold, but calming voice. She was pale, with hair glistening before the snow, and draped in no more than loose clothing unfit to stay the northern winds. Yet she shows no form of discomfort. She looks at me with a serene and compassionate look. I can’t help but feel relieved and felt my consciousness slowly fading... But I cannot! Not yet... I had yet to see with clarity the beautiful creature stands in front of me. I had yet to feel the cloth of her robe that gently caressed my frozen hand. I had yet to see if she was real. Try as I might, my consciousness cannot stay for too long. As the last of my consciousness fades I saw her hand glow brightly like that of the northern lights. It was the Aurora Borealis… the spirit of the north. I felt a warm embrace that overwhelmed my senses. My broken body fell silent. 

As I regained my senses, I realized that people were flocking over me. I stood up, stunned to find my body mangled by the bitter cold, undamaged. The townsfolk stood in awe and I would share their amazement though I sensed that the source of their wide-eyed stares were not of my condition. My memories were clouded. I did not know when and how I got there. All that’s left with me is the beautiful figure that appeared before me. The townsfolk after seeing that I was fine slowly dispersed. Muttering the words “another one…” or “what a lucky bastard”. Curious, I asked “what are you talking about?” An old woman turned back and said “The Auror... She saved you.”

Barbarians of the north sing hymns that depict of what might be Aurors in battle. In the song, the brave warriors stave off a rampaging demon that came from the mountains. But the beast proved its indomitable might, as they slowly loose foothold and fall back to the lands they were trying to protect. The demon continues its violent onslaught, picking off the noble warriors one by one. As all hope falls, a strong gust of icy wind swept across the battlefield, staving off the monster's assault. With it came forth women clad in nothing more than cloth and silk, with eyes filled with fiery blue light. The demon is suddenly bombarded with stars of ice and fire that came from the heavens. Two female warriors vanished in a gust of wind, only to appear near the demon, and attack it relentlessly with a barrage of arrows and ice. The demon furiously lashes back, but these women evade its attacks like it was nothing more than a child at play. Another star falls to the demon, the demon lurches, reeling in agony. As the demon sensed its inevitable doom, it makes a desperate attempt of an attack, only to be completely frozen before its claw could even touch the closest of the women that lead it to its imprisonment. She walks forth. In her hand formed a sword of pure ice and with one swing, breaks the frozen demon. At last, the monster was defeated. 

As the demon’s body dissipates, the heroic women tend to the wounded, easing their pain with light that reflect the northern sky. Then, as quick as they arrive, they vanished. Not a word or a sound of joy and gratitude was made. The enigmatic warriors were not seen again. Though their deeds had filled the songs of many, no one knew what they were. Only the beauty and the grace displayed by these noble women were forever etched in their memory.


THE AUROR CULTURE//////////////////////////////////////////////////////////////(au03)

The Aurors came from different backgrounds, different cities, and possibly different realms. The only thing that binds them is they all have the ability known as cryokinesis, or the innate ability to form and control ice at will. When a child is discovered to have this ability, a nearby Auror might sense this and would try to conscript the child, with the permission of the child's guardians. Most of them although hesitantly, would leave their child in the Auror's care, as the life of a child with an unusual ability (and quite possibly, even an unusual appearance) is normally a hard one. This is how Aurors normally increase their ranks, though it is not rare for an Auror to give birth to a child with a similar ability.

The Aurors comprised predominantly of female warriors and are thus, structured in a matriarchal but militaristic order. No one knows why but it is believed that this is due to the nature of their ability (as the element of ice and winter is under the portfolio of Auril, a primarily female god), though there have been instances of male Aurors, they are quite rare.

The Aurors are very reclusive, not because of anything but the fear for the safety of those around them, as the power of ice and winter is extremely unpredictable and highly destructive. A negative emotion such as fear, sadness, anxiety or anger might incite a sudden winter storm, or even worse, a dire frost. They do however, band in small communities deep within what would be considered as frozen wastes, living peacefully among their kin.

The Aurors are said to be lead by an unnamed silver dragon, who taught the first of the Aurors the ways of ice magic, lore and etiquette. These were passed down from generation to generation. As such, the very few Aurors who came in contact with the townsfolk were said to speak in kind and pleasing tones, if not a bit archaic.

An Auror spends a lifetime to acquire a better understanding and control of their ability, often going to the lengths of even sacrificing their physical wellbeing. As such, Aurors have relatively frail bodies. They do however excel in outmanoeuvring their foes, performing actions that seem to defy the grasp of the earth. They are a spectacle to behold; like graceful spirits dancing over the white covered land. Northern adventurers who get a glimpse of Aurors in play might mistake them for frost spirits; alluring them to an inevitable death. As such, they are normally left alone. Due to their weak physique, they are instead trained to be experts with the bow and arrow; using their psychic abilities to curve shots to hit marks that are otherwise impossible to make. To have a better control over their power, they are also trained to have a stronger mind and a steadfast will, thus are highly resistant to mental assaults and enchantments.

A young Auror is normally paired with a more experienced Auror, who serves as both teacher and a guardian. They value knowledge and wisdom and as such, give emphasis on education, among combat and magic training. They are also taught to present themselves elegantly and show proper etiquette to anyone they meet. One could even say that an Auror society is sort of ideal for women and consequently, even men.

Upon reaching a certain age, as a rite of passage to adulthood, a young Auror is tasked to enter a den of either a winter or a dire wolf in an effort to find an animal companion. These animals are notoriously known to adventurers to be quite aggressive and dangerous. Not for an Auror. When an Auror enters a den, she is seemingly greeted by the leader of the pack. The wolves are submissive and friendly, but only one wolf, normally a pup, would follow the Auror out of the den. When this happens, the Auror has found her animal companion.

When an Auror reaches her maturity, both in ability and in character, she is tasked to a certain part of an area, to serve as a protector of the land for a time. They are however, not allowed to make a strong contact with other creatures in order to preserve their untainted judgement. This is why Aurors are known to be the silent, enigmatic protectors of the wilds. 

An Auror who have served her duty is free to leave and live out her own life. Though the majority of Aurors tend to stay with their kin, some do leave and live a life of an adventurer or in service of a god. An Auror retain their good morals throughout her life, but she does not bend on the laws of men. At a certain point in their life, she would come back to her home, and share her experiences and if not with a life partner, would live the rest of her life with her fellow sisters.


THE AUROR RANGER///////////////////////////////////////////////////////////////(au04)

The Auror is known to possess the ability to control frost at will. This is primarily due to their psychic ability that is attuned to the element. With this, the Auror can also manifest abilities that are purely psychic such as psychokinesis, sensing presence of creatures, communicate telepathically and on higher mastery, assail a humanoid’s mind. With training, she learns how to meld this ability with her natural ice magic and as such, produce magic that are unique to her own.

The path of being an Auror is as cold and harsh as the rewards she might reap after. She is unprotected against the cold, though this is not really a discomfort for a creature who can command frost. At a young age, the Auror’s untamed magic leaves her constantly exposed, increasing her magic resistance at the cost of her physical wellbeing. She is trained day and night to hone her psychic abilities in conjunction to her marksmanship, agile movement and magic as the sheer psychic will is the most effective means to control her power. Her mind is constantly tested, to strengthen her will and make her less vulnerable to uncontrolled emotions that might spell disaster to those around her. Upon maturity, the Auror becomes a quasi-elemental and has gained almost complete control of her abilities, an agility that defies even the earth, a high resistance to magic and an indomitable will.

Other than combat and honing their magic and psionic abilities, they are also given education. Their culture, though being militaristic gives emphasis on intelligence and wisdom. Knowledge that is gathered from different realms relevant to their existence is taught and incorporated in their culture. With this, Aurors are known to be perceptive and quite intelligent. 

The Auror does not change much in physical appearance. The presence of cold magic in her body slows her aging, granting even human Aurors extended lifespan. Marks of aging or stress do not reflect on their bodies. Wounds do not leave traces of scars or any of the like. They retain much of their peak physical appearance throughout their lives. Due to this, they are normally described to be beautiful creatures, to the point of being mistaken for a frost dryad or something similar.


AURORS AND BALDUR'S GATE LORE//////////////////////////////////////////////////(au05)

So, how does the child of Bhaal fit in to the lore of an Auror?

Well... the Slayer had that ability to invoke a sort of cone of cold whenever it attacks. I thought it might be a good basis for a small story here.

Since the protagonist possesses a potent essence of Bhaal, she might have at one point in her young life; invoke something similar to the Slayer's cold ability. Gorion though being a powerful mage, admitted that he is not well versed in some aspects (as he does not also fully comprehend the whole bhaalspawn prophecy last time I checked), though he definitely knows someone who might.

So, he invites an Auror to Candlekeep (based on the storyline, he knew a lot of powerful people. So it's no suprise if he knew an Auror, or at the very least, their existence), and ask to assess the young child of Bhaal. Though she didn't fully understand the source of the child's power, the Auror did confirm that the power the child bears is somewhat similar to her own. Gorion, aware of the ways of the Auror, insisted to have the child taught within the safety of Candlekeep. The Auror questioned Gorion's motive, but was convinced by Gorion nonetheless. She hesitatingly agreed on Gorion's request and soon after, the child of Bhaal's training began.


THE AUROR INGAME///////////////////////////////////////////////////////////////(au06)

AUROR: A unique type of ranger; skilled with the bow and possessing an exceptional ability to control the elements of ice and the forces of winter. Though normally mistaken to be an Aurillian priest, she does not share the destructive whims of the goddess nor her followers but on the contrary, follows a strict, solitary edict of an unnamed silver dragon, known to be as her hegemon.

Trained to be agile, she is extremely quick and precise in every move but it proves to be a necessity rather than an advantage as the path of becoming an Auror renders her physically weak. This does not prevents her however, to aid those in need. She is an enigmatic protector of the good and a vicious, cold foe of evil.

ADVANTAGES:
-  +2 bonus to dexterity on character creation.
-  Immune to charm and confusion.
-  Grandmaster: bow-type weapons. The Auror may put 5 points in long bow and short bow.
-  +1 thac0 bonus with missile weapons every 4 levels.
-  +1 to damage with missile weapons every 6 levels.
-  +1 bonus to AC and save vs. breath weapons every 3 levels; caps at the 29th level.
-  +1 bonus to AC vs. missiles every 6 levels; caps at the 30th level.
-  +1 to save vs. spells every 2 levels till the 8th, then every 3 levels till the 17th, and finally every 4 levels till the 30th level of experience.
-  Starts with 7% cold resistance, gains +12% every 2 levels till the 10th, then on 13th and 16th, +9% on 20th and 24th, and finally +7% on the 29th level of experience.
-  +2% magic resistance every level; caps at the 30th level.
-  Gains additional priest spell slots starting at the 14th level of experience.
-  Sharpshooting: starts with critical hit chance on 1d19, and then gets better for every 6 levels of experience; caps at the 30th level with a chance of 1d14.
-  Foresight: at 4th level, the Auror gain an unnatural sense of her surroundings. This allows her to detect and attack hidden enemies (though they still remain invisible) and is impossible to surprise thus, making her immune to backstab attempts.
-  Frost Touch: at the 6th level, the Auror adds 2d4 cold damage on every attack and freezes the target for 4 rounds unless a successful save vs. spells is made. Missile attacks are charged with psionic force, knocking back targets if fails to save vs. breath.
-  Innate Abilities
   2nd Level: Cryogenesis - Ice Blade
   4th Level: Cryogenesis - Frost Arrow
   6th Level: Far Sense
   8th Level: Frost Blink
   10th Level: Frostbite
-  Beginning the 8th level of experience, the Auror learns new abilities upon reaching certain levels. They are as follows:
   8th Level: Glacial Aura
   10th Level: Frost Wave
   12th Level: Aurora Borealis
   15th Level: Dire Frost
   18th Level: Hoarfrost
   20th Level: Lament of Winter

DISADVANTAGES:
-  Available only to human, elves or half-elves of neutral or chaotic good alignment.
-  -6 to strength and -8 to constitution on character creation.
-  Hit Die: d4
-  Incurs -1 penalty to save vs. death every 4 levels of experience.
-  Has limited proficiency on selected melee and ranged weapons.
-  Cannot put any point to fighting style proficiency other than Two Weapon Style.
-  Cannot wear any armor.
-  Cannot dual class.
-  No Charm Animal ability.
-  No high level abilities.


FREEZING, FROZEN, STUNNING AND OTHER STUFF/////////////////////////////////////(au07)

This kit adds a couple of effects needs to be explained a bit:

FREEZE: The victim is slowed and gets a penalty to hit, AC and save vs. breath weapons by 2 for the duration of the effect.

DEEP FREEZE: twice the efficacy of freeze status.

FROZEN: The victim is unable to move, though is still aware of its surroundings. The frozen creature gets 100% resistance to cold damage and cannot be buffeted. However, it gets a 20 AC penalty for the duration of the effect.

Stunning damage: This is similar to crushing damage though when the target's hp is reduced to 1, it will fall unconscious and can only be killed by any damage other than stunning.


INNATE AND SPELL PROGRESSION TABLES////////////////////////////////////////////(au08)

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
Cryogenesis                                                                   (au08a)
-------------------------------------------------------------------------------------
The Auror gains the ability to create objects made out of pure ice.

Spell Power	: 0
Casting Time	: 4
Fatigue Value	: 0

Ice Blade
Level	Enchantment	Thac0	Damage
2	+0		+4	1d6 piercing
6	+1		+4	1d6 piercing
10	+2		+4	1d6 piercing
14	+3		+4	1d6 piercing

Frost Arrow
Level	Enchantment	Thac0	Damage
4	+0		0	1d6 missile
8	+1		0	1d6 missile
12	+2		0	1d6 missile
16	+3		0	1d6 missile
20	+4		0	1d6 missile

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