# VCCV RUS
 All needed for VCCV RUS reclist.

## About the reclist

This reclist is ment for natural, smooth and adjustable Russian usage. It's much larger that CVC RUS, but gives more control and has more features. Also it has unstressed vowels, which allows Russian sounds natural.

The best usage is possible in OpenUtau by StAkira, since there are a lot little transtions, which are hard to adjust in UTAU itself. However, UTAU usage is also possible, and LyricInputHelper files are included (but LYH is not smart enough and processed them worse than OpenUtau phonemizer).

There are 3 options to record:
1. **VCCV v1** and **VCCV v2** are almost the same, the v2 just has consonants a bit recombined, so it may be a bit easier to record. However the usage is the same so you can pick any.
2. **CVC pitch for VCCV** is an experimental thing provided by Foggy Lea. The plan is that you record the medium pitch as full VCCV and **give no suffixes nor prefixes** for it, and other pitches are recorded as CVC pitch for VCCV. This way, CC's are taken all from the main pitch, and all other aliases are taken from the right pitches. But this is experimental and it's not guaranteed that the CC are actually okay to be transposed to any pitch.

All folders contain the reclist, the base oto, and WavConfigTool settings files.

## The content

The reclist contains the same kind of aliases like Arpasing, but with additional "-CV" and "VC-":
- -V: [- a]
- V-: [a -]
- -C: [- l]
- C-: [l -]
- CV: [ka]
- VC: [a k]
- VV: [a e]
- CC: [l k]
- -CV: [- la]
- VC-: [at -]

So the rules are basically the same like in Arpasing, but if there is only one consonant at the beginning, use [- CV] instead of [- C] [CV], and if there is only one consonant at the ending, use [VC -] instead of [V C] [C -].

The [- C] are not used for voiceless plosive & affricant consonant, since the [- C] would be a silence:
t,t',k,k',p,p',ch,ts

## Phonetic table
| VCCV RUS  | Word examples | Comment |
| ------------- | ------------- |------------- |
| **Vowels**     |
| a  | вод**а**, м**а**ть | Stressed "a" or "я". When it's "я" and there is no consonant before, the [j] phoneme also appears before this one. |
| e  | в**е**чер, прив**е**т | Stressed "е" or "э". When it's "е" and there is no consonant before, the [j] phoneme also appears before this one. |
| o  | в**о**ды, с**о**весть | Stressed "о" or "ё". When it's "ё" and there is no consonant before, the [j] phoneme also appears before this one.  |
| u  | п**у**ть, ск**у**чать  | Stressed and unstressed "у" or "ю". When it's "ю" and there is no consonant before, the [j] phoneme also appears before this one.   |
| i  | в**и**деть, с**и**ла | Stressed "и" |
| i  | т**ы**, б**ы**ть | Stressed "ы" |
| ax  | в**о**да, правд**а**  | Unstressed "а" |
| ex  | гор**ы**, **э**фир  | Unstressed "э" or "ы" |
| x  | пр**и**вет, веч**е**р, сов**е**сть, т**я**желый | Unstressed "е"/"ё"/"и"/"я" |
| **Consonants** | | Note that ['] symbol appears when the consonant is softened by being followed by any of: я, е, ё, ю, и, ь. Exceptions are: sh, j, zh, ts, ch. And sometimes when next consonant is also with ['] |
| **Special** |
| sh  | **ш**ёпот, ве**ш**ать  |
| sh'  | **щ**ит, про**щ**ать  |
| zh  | **ж**ара, кру**ж**ить  |
| j  | **й**од, тво**й**, **ё**лка [j o l k ax]  | When there is no consonant before я, е, ё, ю, the [j] phoneme appears before them |
| ts  | **ц**ена, **ц**апля, ви**тьс**я, спи**тс**я  | "тс" and "тьс" both becomes "ts" |
| ch  | **ч**аша, **ч**есть  |
| l  | **л**ожь  |
| l'  | зел**ё**ный  |
| m  | ду**м**ать  |
| m'  | **м**иска  |
| n  | го**н**ка  |
| n'  | ко**н**ь, ко**н**ец  |
| h  | **х**олод  |
| h'  | **х**илый  |
| **Voiced unvoicable** | | This consonants may be unvoiced if they are not followed by vowel, or are followed by unvoiced consonant. See "Unvoiced" category.
| b  | **б**оль  |
| b'  | **б**ерег  |
| v  | **в**ор  |
| v'  | **в**ечер  |
| g  | по**г**ода  |
| g'  | **г**итара  |
| d  | по**д**арок  |
| d'  | **д**ерево  |
| z  | **з**аря |
| z'  | **з**елёный  |
| **Unvoiced** | 
| p  | поку**п**ать, гро**б**  |
| p'  | ку**п**ить, дро**бь**  |
| r  | го**р**а, во**р**  |
| r'  | гореть, ве**рь**  |
| s  | ве**с**, вя**з**  |
| s'  | **с**ерый, ма**зь** |
| t  | бы**т**, го**д**  |
| t'  | бы**ть**, ве**дь**  |
| f  | **ф**орт, шар**ф**  |
| f'  | **ф**ерзь, кро**вь**  |
