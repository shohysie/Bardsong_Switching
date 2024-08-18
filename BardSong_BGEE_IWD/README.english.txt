@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@                                                           @
@   Bard Song Switching (Icewind Mode) for BGEE Series V4.5   @
@   By Shohy                                                @
@                                                           @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

With this pack you can freely switch your bard song in several songs, just like in Icewind Dale. 
Jester and Skald song effects are modified and improved to make up for them not being able to switch between songs like Standard Bard and Blade. 
Characters of all bard kits can learn Enhanced song and Lingering Song (which allows all bard songs last for 2 extra rounds) after 3,000,000 exp. 
Different battle songs can work at the same time. The same bard song has no accumulation effect, except when The Chorus component is installed, with which a battle song can be enhanced by multiple bards performing at the same time. A leader of chorus should be designated first.


***** Compatibility *****

	Only BG EE series are supported.
	Compatible with any other MODs that modifies the original bard kits. Requied to be installed after such MODs, then all modifications of them as well as HLA revisions are remained.
	In component of The Chorus and The Custom AI, creature states of BACKSTABDAMAGEMULTIPLIER, SHAMANIC_DANCE and BERSERKER_RAGE_FATIGUE are used to help checking bard songs. There may be some compatibility issues with other MODs, but since these states are only used on bards, they generally do not cause obvious conflicts.

***** Main Effects *****

[Kit Adjustment & Custom AI for Bards enhanced by this MOD]

	[Kit Adjustment]

	Bard will learn different songs on different level. You can switch to the song you need by clicking new buttons in Special Abilities.
	LV1: The Ballad of Three Heroes, which has the effect of +1 to hit, +1 to damage and +1 to all saving throws.
	LV4: The Tale of Curran Strongheart, which gives the immunity to Fear and Morale Break.
	LV8: Tymora's Melody, which has the effect of +1 luck, +3 to all saving throws, +10 to lore and thief's skills.
	LV12: The Song of Kaudies, which gives the immunity to all sound effects like silence, deafness and spells that use sound as a medium, e.g. Power Words.
	LV16: The Siren's Yearning, which enthrals enemies in the visual range unless they make save vs. spell. Does NOT affect mindless enemies e.g. golems.
	LV20: The WarChant of Sith, which has the effect of AC-2, +10% physical damage resistance, and regenerate 3 HP per round.
	Enhanced Bard Song: Gives all allies +4 to hit, +4 to damage, -4 to AC, +5% magic resistance, and grants them immunity to Fear, Morale Break, Confusion and normal weapons. While singing the Enhanced Bard Song, the Bard himself gains an extra bonus of -6 to AC and +5% magic resistance.

	Blade starts with +1 to hit and damage, get maximum proficiency (3 points) in two weapon fighting style, and then +1 to hit and damage per 10 levels. He can learn different songs on different level, but less than normal Bard. He can learn skill of Whirlwind after 3,000,000 exp. 
	LV1: The Ballad of Three Heroes, which has the effect of +1 to hit, +1 to damage and +1 to all saving throws.
	LV6: The Tale of Curran Strongheart, which gives the immunity to Fear and Morale Break.
	LV12: Tymora's Melody, which has the effect of +1 luck, +3 to all saving throws, +10 to lore and thief's skills.
	LV18: The Song of Kaudies, which gives the immunity to all sound effects like silence, deafness and spells that use sound as a medium, e.g. Power Words.
	Enhanced Blade Song: Gives all allies +4 to hit, +4 to damage, -4 to AC, +5% magic resistance, and grants them immunity to Fear, Morale Break and normal weapons. While singing the Enhanced Blade Song, the Blade himself gains an extra bonus of +2 to hit, +2 to damage, -2 to AC and +5% magic resistance.

	Jester starts with +1 luck, +5% stealing, immunity to charm and confusion. Effect of his battle song improves with level, but he can't perform other songs, and the Enhanced Jester Song will merely replace the original song.
	LV1: Opponents in 30 feet must save vs. spells once per round or be confused (+4 save penalty).
	LV5: Opponents in 30 feet must save vs. spells once per round or be charmed (+2 save penalty).
	LV10: Opponents in 30 feet must save vs. spells once per round or be slowed (no penalty) or confused (+2 save penalty).
	LV15: Opponents in 30 feet must save vs. spells once per round or be slowed (-2 save penalty) or confused (no penalty).
	LV20: Opponents in 30 feet must save vs. spells once per round or be slowed (-2 save penalty) confused (-2 save penalty), and must save vs. poly or be unconscious (+2 save penalty).
	Enhanced Jester Song: Affects every opponent within 30 feet, they must save vs. spells once per round or be slowed (-4 save penalty) confused (-2 save penalty), and must save vs. poly or be unconscious (no penalty). They may also fail in casting spells and innates by 10% chance.  While singing the Enhanced Bard Song, the Jester himself gains an extra bonus of -6 to AC and +5% magic resistance.
	Note: mindless creatures e.g. golems are immune to Jester' songs.

	Skald starts with +1 to hit and damage. Effect of his battle song improves with level, but he can't perform other songs. And the Enhanced Skald Song will merely replace the original song.
	LV1: +2 to hit, +2 to damage, -2 to AC.
	LV5: +2 to hit, +2 to damage, -2 to AC, offers the immunity to Fear and Morale Break.
	LV10: +3 to hit, +3 to damage, -3 to AC, offers the immunity to Fear and Morale Break.
	LV15: +4 to hit, +4 to damage, -4 to AC, offers the immunity to Fear and Morale Break.
	LV20: +4 to hit, +4 to damage, -4 to AC, offers the immunity to Fear, Morale Break, Stun and Confusion.
	Enhanced Skald Song: Gives all allies +4 to hit, +4 to damage, -4 to AC, +2 to all saving throws, +5% magic resistance, and grants them immunity to Fear, Stun, Confusion and normal weapons. While singing the Enhanced Skald Song, the Skald himself gains an extra bonus of -6 to AC and +5% magic resistance.

	Lingering Song (Enhanced Song pre-requested): Effects of all Blade songs last for 2 extra rounds. Can be learned by all bard kits.

	Note:
	This component also modifies the problem that Enhanced songs (except the Jester) only works for the 6 teammates. Enhanced songs (except the Jester) now work for all friendly creatures within twice of the visual range, while the effective range of normal songs is also increased to the visual range (50').
	Most of the different battle songs can be effective at the same time, but when a Bard, Blade and Skald play Enhanced songs at the same time, only one of them will play a role, with the priority of Skald > Bard > Blade. 
	According to the original settings of bards in EE games, Battle Songs do not work on deaf creatures (except The Song of Kaudies, which relieves teammates' deafness); and the bards are forced to be visible while singing, but extra bonuses of Improved Invisibility can be retained.

	[Custom AI]

	The Custom AI provides the ability to make brief attacks between playing intervals and maintain the presence of battle songs, but only for bards fixed by this MOD. 
	Select Customize > Script > BI#BARD in the character's Record interface. 

	Press "V" to switch in three Attackive Modes: Sing songs without attack actions / More singing than attack actions, try to keep songs effective / More attack actions than singing, with songs occasionnally expire. 

	Press "Z" to toggle whether or not to prompt the effective moment of bard songs: prompt with animation/ prompt with game pause / not prompt. At this time you can control the bard to cast a spell manually, then the poet will automatically continue to sing and keep effect of songs uninterrupted. Such prompts only exist in battle.

	Press "F" to force a bard to sing and attack when invisible. As a bards will be visible when he starts singing, this AI tells him to do nothing when invisible, unless "F" is pressed to give a command.
	This command ends with your invisibility, and "F" should be pressed again next time.

	Press "B" to cast a memorized protective spell, in the order of Stone Skin, Strength, Protection from Magic Energy, Spirit Armor / Ghost Armor / Armor, Shield, Protection from Normal Missiles, Resist Fear, Blur, Protection from Evil, Improved Invisibility (remember to press "F" to active an invisible bard), Mirror Image, Spell Shield, Spell Immunity: Abjuration, Improved Haste, Protection from the Elements, True Sight, Spell Turning (or Minor), Spell Deflection (or Minor), Globe of Invulnerability.
	You can press it multiple times to add all BUFFs. Existing spells will not be repeated.

	Press "S" to switch Lingering Mode and Normal Mode. The character will greatly increase the attack chance and reduce time of singing in the Lingering Mode. 
	If your bard has acquired an High-Level Ability of Lingering Song, he will automatically enter the Lingering Mode and will not switch back. 
	If your bard gets the ability of Lingering Song by means other than High-Level Ability (such as the Bard Hat in Siege Of Dragonspear), you need to switch to Lingering Mode manually because the game engine does not provide a way to check those means.
	Please remember to switch back to Normal Mode manually if your bard lose ability of Lingering Song (such as taking off the Bard Hat).


[The Chorus]

	With this component installed, all songs can be played by multiple bards (or their magical illusions) at the same time to gain extra bonus. 
	You need to click the "Lead a chorus" skill button of one of the bards to specify the leader of chorus. 
	When the other bards join the chorus and play the same song with the designated leader, they will get extra bonus. 
	If the other bards join the chorus but play different songs with the designated leader, their songs will temporarily become the same with the designated leader and get extra bonus in the next round. They're not necessary to have learned the song that the leader is singing.
	If there is no designated leader of chorus, there will be no chorus effect. 
	Each time you assign a new leader of chorus, the other bards stop leading chorus. 
	In addition, the lead singer must be one of the 6 team members. Clicking the "Lead a chorus" skill button of other creatures (such as magic illusions) takes not work. In this case, effects of his song can coexist with others but without a chorus bonus. 
	All bards agree to join the chorus by default. Clicking the "Drop out of the chorus" skill button ensures that a bard's song does not change with the leader of chorus. Effects of his song will coexist with other songs, but will not contribute to a chorus bonus. By clicking "Join the chorus" he can join the chorus again.
	The bonus effect of the chorus lasts only one round, and the duration cannot be increased even by Lingering Song.
	Bards with Kits from other MODs also join the chorus probably, but they can't lead or drop out of the chorus.

	The more bards in the chorus, the stronger the effects of the battle song. When the amount of chorists reaches 2/ 3/ 4~5/ 6/ 7~9/ 10, the extra effects are improved to different levels, which can be identified by red / yellow / green / green / blue / purple glow on chorists.
	The details are as follows：

		The Tale of Curran Strongheart, which gains immunities to Charm/ Confusion/ Hold and Slow/ Feeblemindedness and Unconscious/ Berserk, Fatigue and Stun/ Maze and Imprisonment at the 6 levels. 
		The Song of Kaudies, which forces enemies around to make save vs. breath with a penalty of -1/ -2/ -3/ -4/ -5/ -6, to avoid deafness and bleeding (1 damage per second) for 1 round.
		The Siren's Yearning and the Jester songs, gain an entra chance each round to take effect, which forces enemies to save with a penalty of -1/ -2/ -3/ -4/ -5/ -6.
		For all other battle songs that provide bonus values, the bonus values are improved to 1.5/ 2/ 2.5/ 3/ 3.5/ 4 times as the original songs. (To avoid touching the lower limit of AC, Chorus of Enhanced Songs afford bonus AC vs. crushing, missile, piercing and slashing instead of normal AC)
		Extra bounses of Enhanced Songs for bards themselves, e.g. -6 to AC and +5% magic resistance, are not improved in the chorus.


[Allow Image Projections to Perform Bard Songs]

	In the enhanced edition games, image projections made by Mislead can no longer perform bard songs. This component changes it back to the old settings so that the image projections can sing and join the chorus.


***** History *****

	V4.5	Fixed a serious problem that Lingering Songs do not work.
	Fixed the problem that the Custom AI prompts too frequently and inaccurately.
	Adjusted the Custom AI to cast more buff spells, and further optimized the AI to make characters more active in fighting.

	V4.4	Fixed the problem that in BGEET there were some unmodified Kit descriptions.
	Fixed the problem that description of Custom AI were prone to text misplacement with many MODs installed.

	V4.3	Added detailed description for the Custom AI.

	V4.2	Fixed the problem that bards often stop singing on 'More attack actions than singing' mode of the Custom AI.
	A new ability in Custom AI: Press "Z" to toggle whether or not to prompt the effective moment of bard songs. At this time you can control the bard to cast a spell manually, then the poet will automatically continue to sing and keep effect of songs uninterrupted.

	V4.1	Kit descriptions of all bards will also be modified to show all of the adjustments (including instructions for the Chorus and Custom AI).
	The Custom AI and the Kit Adjustment are combined into one component.

	V4.0	No longer supports no-EE games.
	New component of The Chorus, with which a battle song can be enhanced by multiple bards performing at the same time. A leader of chorus should be designated first.
	According to the original settings of bards in EE games, Battle Songs do not work on deaf creatures (except The Song of Kaudies); and the bards are forced to be visible while singing.
	Tymora's Melody can be learned before The Song of Kaudies, the same as Icewind Dale.
	Changed the settings that Enhanced Bard Songs only work on 6 teammates, they work on all friendly creatures around now.
	For lingering Enhanced Songs, extra bounses for bards themselves alse last for 2 extra rounds now.
	A custom AI for bards in this MOD only.
	Better compatibility. 

	V3.1	Better compatibility. All Bard HLA revisions of other MODs will remain only if this MOD is installed after all of them. And no more error messages will appear no matter how names of HLA tabs are altered by such MODs.

	V3.0	Supports BG EE series.
	If Rogue ReBalancing Pack is already installed, its Bard HLA revisions will remain.
	Jester gain the same extra bonus as others while singing Enhanced Bard Song.
	Enhanced Blade Song is weakened.

	V2.2	Fixed the icon of the Song of Kaudies.
	Fixed the problem that Ctrl+R invalids fixed Bard Songs.
	Fixed the bug that leaving team (and then join again) makes Lingering Songs nolonger take effect.

	V2.1	The bug that lingering Songs lose their effects if a bard sings when Cromwell forges an item, is fixed.

	V2.0	Bard Songs can be switched without an extra action, therefore an extra round is no longer required. You'll feel much freely in making choice from songs during the battle.

	V1.5	Extended to level 50.
	Different icons appear when different songs take effect: Blessed - The Ballad of Three Heroes; Resist Fear - The Tale of Curran Strongheart; Vocalize - The Song of Kaudies; Good luck - Tymora's Melody; Mental Combat - The Siren's Yearning; Regenerating - The WarChant of Sith.
	Lingering Songs now take effect with a new method, by which they can really last for 2 extra rounds after the bard stops his song.

	V1.4	Some adjustments for BGT: New songs added, now bards may learn all songs from IWD, and their skill learning processes are changed. No longer supports single SOA.
	Jesters are forced to be VISIBLE when singing. The Song of Kaudies no longer gives immunity to stun, but gains immunity to all power words.
	The high-level-skill lingering SONG is added. And a little adjustments of Enhanced songs are made. New skill icons are added.

	v1.3	Added an Traditional Chinese Version, and fixed the disappearance of The Ballad of Three Heroes.

	V1.2	An English Version was added.
	The Song of Kaudies now gives immunity to Commands of clerics and War Cry of fighters.
	Some literal bugs were fixed.
	Kit descriptions of bards were changed, but you can restore them by choosing Component 4 (when uninstalling).

	V1.1	The Song of Kaudies now gives immunity to Wail of Banshees and Wail of Demilich.

	V1.0	All kits were changed. No more Lingering Songs. Effect of same songs can't be added.

	V0.2	The bug of selecting Enhanced song is fixed.
	Choices of Lingering Songs and adding up of the same song were available.

	V0.1	A first attempt.